# 3D 雕刻指令速查（適用 ZBrush）

非官方的中文 ZBrush 指令速查網頁。與 Maxon 無關，ZBrush 為 Maxon 的商標。

## 上傳到 GitHub Pages（全程在網頁上操作，不用寫程式）

1. 到 https://github.com 註冊並登入。
2. 右上角「+」→ New repository。名稱自訂（例如 `sculpt-ref`），選 Public，按 Create repository。
3. 在新 repository 頁面點「uploading an existing file」，把這個資料夾裡的所有檔案拖進去（index.html、manifest.webmanifest、sw.js、三個 icon PNG、README.md），按 Commit changes。
4. 進入 Settings → Pages。Source 選「Deploy from a branch」，Branch 選 `main`、資料夾選 `/ (root)`，按 Save。
5. 等 1～2 分鐘，頁面上方會出現網址，格式是 `https://你的帳號.github.io/sculpt-ref/`。

## 之後要更新內容

在 repository 點 index.html → 右上角鉛筆圖示編輯，或重新上傳覆蓋檔案，Commit 後約 1 分鐘生效。
大改版時，把 sw.js 第 2 行的 `v1` 改成 `v2`，讓手機確實換成新版。

## 加到手機主畫面

- iPhone：用 Safari 開網址 → 分享按鈕 → 「加入主畫面」。
- Android：用 Chrome 開網址 → 右上角選單 → 「加到主畫面」或「安裝應用程式」。

第一次開啟後，沒有網路也能使用。
