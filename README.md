# Saw Blade App

這是一個可離線、可分享、單一檔案的鋸片診療系統，提供鋸片基本資料、症狀勾選與診斷建議，適合現場維修或快速分享給同事。

## 內容物

- `saw-blade-app.html` — 單一檔案版本（HTML/CSS/JS 全部打包在一起）。
- `index.html` — GitHub Pages 預設入口檔案（內容與單檔版本相同）。

## 快速開始

1. 用瀏覽器開啟 `saw-blade-app.html`。
2. 填寫鋸片資料、勾選現場症狀，系統會產生診斷建議並保存在瀏覽器本機。
3. 把檔案分享給其他人（AirDrop、Email、聊天軟體皆可）。

## 手機使用方式

- 把檔案存到手機後，從「檔案」或「下載」開啟。
- iOS Safari 或 Android Chrome 可使用「加入主畫面」取得類 App 的操作體驗。

## GitHub Pages 部署

1. 進入 GitHub 專案的 **Settings** → **Pages**。
2. 將 **Build and deployment** 的 **Source** 設為 **GitHub Actions**。
3. 推送到 `work` 分支後，GitHub Actions 會自動部署。
4. 部署完成後，網址會顯示在 GitHub Actions 與 Pages 設定頁。

## 客製化

直接編輯 `saw-blade-app.html`，即可修改欄位、症狀與建議規則；保持單一檔案可讓分享更簡單。

## 專案目標

- 單一檔案、離線可用。
- 方便分享給非技術使用者。
- 以手機優先的版面設計。
