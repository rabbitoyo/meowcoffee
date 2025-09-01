## MeowCoffe 喵行旅
熱愛貓咪，過去造訪過許多貓咪咖啡廳，也觀察到超過八成店家沒有線上預約系統，導致貓奴們難以方便規劃行程。因此，我希望打造一個整合式的平台，彙整全台（初期聚焦台北）各地的貓咪咖啡館，讓使用者能夠輕鬆預約造訪、踩點集章，並透過探索與互動，解鎖每家店獨有的貓咪角色與故事。
就像旅人般穿梭於城市角落，記錄下每一段與貓咪的溫柔邂逅。透過虛實整合的任務與收藏系統，使用者可以累積足跡、完成挑戰，查看自己是否是資深貓奴，蒐集專屬的喵咪地圖與回憶，展開一場療癒的城市冒險之旅。

- [GitHub Page Demo](https://rabbitoyo.github.io/meowcoffee/)

### 🛠 使用技術

- Bootstrap 5 
- SCSS (變數、mixin、迴圈)
- Vite (ejs 模板管理)

### 💻 安裝執行

- 將專案 clone 到本地端

```bash
git clone https://github.com/rabbitoyo/meowcoffee.git
```

- 安裝執行

```bash
npm install				// 安裝
npm run dev				// 執行
```

- 瀏覽器訪問

```bash
http://localhost:5173/
```

### 🗂 專案設置

```
assets					# 靜態資源
├── images
└── scss
	├── base
	├── components
	├── layout
	├── pages
	├── untils
	└── vendors
layout					# ejs 模板管理
pages					# 頁面
```

### 🌟 未來規劃

- 導入 framework
- API 開發 & 第三方驗證機制