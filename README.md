# 協調島｜生物的協調作用

可部署到 GitHub Pages 的靜態互動課程網站。入口為 `index.html`，內容資料集中在 `data/content.json`。

## 本機預覽

請從 `site/` 啟動靜態伺服器，例如：

```powershell
npx serve .
```

不要直接以 `file://` 開啟，因為瀏覽器會阻擋 `content.json` 的 fetch。

## 教學功能

- 4 座主題不同的生物協調島嶼與 3D 地圖
- 教材、學習單、隨堂測驗分頁
- 自編會考素養練習
- localStorage 保存島嶼、學習單、答題、星星與主題設定
- 完成所有島嶼與任務後解鎖證書
