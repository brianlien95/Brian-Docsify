# docsify 教學

> 2025/4/3 第一次進行 docsify 的練習

## 快速部署

```bash
npm i docsify-cli -g
docsify init ./docs
docsify serve docs
```
- `npm i docsify-cli -g` -> 全局安裝 docsify-cli，僅需執行一次
- `docsify init./docs` -> 在你要的資料夾下執行，會自動生成 _sidebar.md 與 index.html
- `docsify serve docs` -> 本地預覽你的網頁，會自動更新

## 目錄
目錄一律在 `_sidebar.md` 中設定
記得先在 index.html `window.$docsify = {` 中加入 `loadSidebar: true,`

## 首頁
首頁在 `_coverpage.md` 中設定
與目錄一樣，記得先在 index.html `window.$docsify = {` 中加入 `coverpage: true,`
