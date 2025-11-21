# 111 全國技藝競賽 — 網頁作品

本專案為參加 **111 年全國技藝競賽** 的網站作品，採用 **Bootstrap、Vue.js、jQuery** 等技術開發，並結合 PHP 實作登入與註冊功能。整體架構清晰，包含前端版面、互動效果與基本會員系統。

## 專案特色

- 使用 **Bootstrap** 建立完整 RWD 響應式版面  
- 使用 **Vue.js** 進行前端資料綁定與互動  
- 使用 **jQuery** 處理 DOM、事件與 AJAX  
- 具備 **登入 / 註冊** 的基本會員系統  
- 前後端分離度高，結構清晰易維護  

## 專案結構

```
├── _notes/ # 編輯器產生的設定資料，可忽略
├── css/ # 樣式（包含 Bootstrap 與自訂 CSS）
├── images/ # 頁面用圖片（banner、海報等）
├── img/ # icon、小圖示
├── js/ # JavaScript / Vue / jQuery 程式碼
│
├── index.html # 主首頁，整合 Bootstrap + Vue + jQuery
├── login.php # 會員登入功能
├── register.php # 會員註冊功能
├── content.txt # 文字或簡易資料來源
└── README.md # 說明文件
```

## 使用技術

### Front-End
- HTML5 / CSS3 / JavaScript
- **Bootstrap**（排版、元件、RWD）
- **Vue.js**（資料綁定、互動邏輯）
- **jQuery**（DOM、事件、AJAX）

### Back-End
- **PHP**（處理登入與註冊）
- 簡易檔案儲存（TXT）

### Tools
- GitHub
- VS Code / Dreamweaver

## 功能說明

### 首頁（index.html）
- RWD 版面
- 圖片展示區塊
- JS / Vue 整合互動效果

### 註冊（register.php）
- 表單格式驗證  
- 輸入後寫入資料（TXT 或其他方式）

### 登入（login.php）
- 讀取資料驗證帳密  
- 可搭配 PHP Session（若有實作）

### 結構模組化
- css / js / images 分類完整  
- 前端與後端檔案清晰分工  

## 部署方式

1. 將整個專案放入伺服器或本機環境（如 XAMPP）。




