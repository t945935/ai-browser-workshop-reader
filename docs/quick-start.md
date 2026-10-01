# 快速開始

1. 從 README 下載 chapters.zip，解壓至自己的資料夾。
2. 找到當章 chapter-XX-start，另複製為練習目錄。chapter-XX-done 是對照版。
3. 使用 Windows x64、Node.js 24 以上及文字編輯器。在練習目錄開啟 PowerShell，核對 node --version 與 npm.cmd --version。
4. 第 1 章是需求文件；第 2 章 start 尚無程式入口，依正文建立檔案。其他章節依正文及附件 README 操作。有 package-lock.json 的程式階段使用 npm.cmd ci。
5. 只有 package.json 有對應 script 時才執行 npm.cmd start、npm.cmd test、npm.cmd run check 或 npm.cmd run smoke。不同章節提供的命令不同。
6. 記錄環境與實際結果，閱讀本章結果表，再保存自己的 Git 版本。

## 使用 bundle

從下載檔案所在目錄執行：

```powershell
git clone -b chapter-snapshots chapter-history.bundle my-chapter-history
Set-Location my-chapter-history
git switch --detach chapter-09-done
```

標籤檢出後為 detached HEAD。要保存修改，可執行 git switch -c my-chapter09。不要把未安裝依賴或尚未完成的 start 當成程式故障。

AI 實際請求需自己的金鑰與額度，可能產生費用；不要在 Issues、截圖或 Git 保存金鑰。本機表單練習僅針對附件提供的示範網站，不代表支援任意網站。
