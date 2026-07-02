# Toolshelf 收藏櫃（唯讀分享版）

Yen 的個人設計工具／網站收藏櫃。單檔 HTML、無框架、無後端、純靜態。

## 檔案

- `index.html` — 網站本體（唯讀版，只能瀏覽／搜尋／篩選，不能編輯）
- `collection.json` — 收藏資料（42 筆）。網站啟動時讀這支；**更新內容只要換這個檔**

## 運作方式

`index.html` 開啟時 `fetch('collection.json')` 讀外部資料。讀不到（本機 file:// 直接雙擊會被瀏覽器擋）就退回內嵌的備份資料，畫面不會空白。

## 更新內容

在本機編輯版（`web-collection.html`）增修 → 匯出 JSON → 改名成 `collection.json` → 覆蓋這裡的同名檔。檔名必須全小寫 `collection.json`。

---
編輯與維護版本不放這裡，這個 repo 只放對外唯讀站。
