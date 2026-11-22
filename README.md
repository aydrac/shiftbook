# 接案收入

排班月曆、收入統計與入帳記錄。資料只存在使用者自己的瀏覽器（localStorage），不上傳。

## 檔案
- `index.html`：App 本體（單檔）
- `manifest.webmanifest`、`icon-*.png`、`apple-touch-icon.png`：加到主畫面用
- `img/`：首頁圖（`art-light.png`、`art-dark.png`），詳見 `img/README.md`

## 更新
在 GitHub 覆蓋 `index.html` 即可。使用者端可能因快取需要重新整理。

## 圖示
- `apple-touch-icon.png`、`icon-192.png`、`icon-512.png`：米白底、茜色日式零錢包，金色口金，中間米白小愛心（淺色深色共用同一組）


## 教學與聯繫（第十一輪）
- 第一次開啟會自動跳出使用教學；之後在「更多 → 使用教學」重看。網址加 `#guide` 可直接開教學、`#contact` 直接開聯繫表單。
- `guide.html`：網頁版教學（可列印）；`shiftbook-guide.pdf`：同內容 PDF（由 guide.html 列印產生）。
- 「與開發者聯繫」：收信設定寫在 `config.js`（`web3formsKey`、`email`）。更新 index.html 時不必動這個檔案。
