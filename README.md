# AIMERS Link Studio（第一版）

簡潔、適合手機與 iPad 的追星首頁，可自行修改首頁文字、背景圖網址、配色、字體、成員資料、分類與連結按鈕。

## 部署到 GitHub Pages
1. 將 `index.html`、`style.css`、`app.js` 放在 repository 根目錄。
2. GitHub 專案 → Settings → Pages。
3. Source 選 `Deploy from a branch`，Branch 選 `main`，資料夾選 `/ (root)`，按 Save。

## 編輯方式
在頁面右上角點「編輯網站」，可編輯外觀、成員、分類和按鈕，最後按「儲存變更」。可在備份頁下載 JSON，或匯入先前備份。

## 重要限制
這是第一版前端原型。儲存內容只留在當前瀏覽器的 localStorage，不會自動更新 GitHub Pages 公開網站，也不會同步到其他裝置。若要從 iPad 後台修改後讓公開站自動更新，需再加登入與資料庫/安全後端（不能把 GitHub Token 放進前端）。圖片目前使用公開圖片網址，直接選取 iPad 相簿上傳需另接圖片儲存服務。字幕功能刻意不包含在本版。
