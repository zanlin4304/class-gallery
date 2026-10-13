# 班級作品牆

學員透過 LINE 官方帳號傳 `.html` 檔，由發布機器人自動存到這個 repo 並公開成網頁。

- `index.html`：作品牆首頁，讀取 `works.json` 顯示作品卡片
- `works.json`：作品清單，由機器人自動維護（不要手動編輯）
- `students/<學員代號>/<作品名>/index.html`：學員的作品，每次發布都是一筆 commit，commit 訊息記錄發布者與自動掃描標記，方便事後檢查與下架

網址：https://zanlin4304.github.io/class-gallery/
