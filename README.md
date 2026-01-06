# 花蓮慈濟醫院環境巡檢管理系統

> 專業的醫院環境巡檢數位化管理工具

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Version](https://img.shields.io/badge/version-1.0.0-green.svg)](https://github.com/yourusername/hospital-inspection-system)
[![Status](https://img.shields.io/badge/status-active-success.svg)](https://github.com/yourusername/hospital-inspection-system)

---

## 📋 系統簡介

花蓮慈濟醫院環境巡檢管理系統是一套專為醫院環境巡檢作業設計的數位化管理工具，支援：

- ✅ 公共區域巡檢記錄
- ✅ 病房 ATP 16項檢測
- ✅ 完整複查追蹤機制
- ✅ Google Sheets 雲端同步
- ✅ 多裝置資料共享
- ✅ 資料匯出功能

---

## 🚀 快速開始

### 線上使用（推薦）

直接開啟網址即可使用：
```
https://[您的GitHub帳號].github.io/hospital-inspection-system/
```

### 本地使用

1. 下載 `index.html` 檔案
2. 雙擊開啟
3. 開始使用

---

## ✨ 主要功能

### 🏥 公共區域巡檢
- 多項目管理
- 照片上傳
- 複查機制

### 🛏️ 病房巡檢
- 病房名稱記錄
- ATP 16項檢測
- 視覺化檢測結果

### ☁️ 雲端同步
- 自動同步到 Google Sheets
- 多裝置資料共享
- 即時更新

### 📊 資料管理
- 記錄查詢
- 複查追蹤
- 多格式匯出（Excel/CSV/JSON）

---

## 📚 文件

- [快速上手指南](docs/快速上手指南.md) - 5分鐘快速入門
- [使用說明手冊](docs/使用說明手冊.md) - 完整操作說明
- [Google Sheets 設定指南](docs/Google%20Sheets%20設定指南.md) - 雲端同步設定
- [系統部署指南](docs/系統部署指南.md) - 部署與維護

---

## 🔧 技術規格

- **前端技術**：HTML5, CSS3, JavaScript (ES6)
- **儲存方式**：localStorage + Google Sheets
- **雲端服務**：Google Apps Script
- **瀏覽器支援**：Chrome 90+, Edge 90+, Firefox 88+
- **響應式設計**：支援桌面、平板、手機

---

## 📦 安裝與部署

### 方案 A：GitHub Pages 部署

1. Fork 此 Repository
2. 到 Settings → Pages
3. 啟用 GitHub Pages
4. 開啟網址即可使用

### 方案 B：本地部署

```bash
# 下載專案
git clone https://github.com/yourusername/hospital-inspection-system.git

# 進入資料夾
cd hospital-inspection-system

# 開啟 index.html
# Windows: start index.html
# Mac: open index.html
# Linux: xdg-open index.html
```

### 方案 C：Google Sheets 整合

參考 [Google Sheets 設定指南](docs/Google%20Sheets%20設定指南.md)

---

## 🎯 使用情境

### 情境一：公共區域日常巡檢
```
環境同仁 → 選擇棟別/區域 → 填寫巡檢項目 → 拍照記錄 → 提交
→ 自動上傳雲端 → 複查人員進行複查 → 完成
```

### 情境二：病房 ATP 檢測
```
環境同仁 → 選擇病房 → 填寫病房名稱 → 進行 16 項 ATP 檢測
→ 點選合格/不合格 → 拍照記錄 → 提交 → 自動同步
```

---

## 📊 ATP 檢測項目

### 床位區域（1-8項）
1. 叫人鈴
2. 床欄
3. 床頭燈座
4. 床腳板
5. 床尾按鈕
6. 窗台
7. 陪病床
8. 電腦開關

### 環境區域（9-16項）
9. 門把
10. 床頭洗手台
11. 紅漏斗
12. 馬桶及扶手
13. 浴室水槽
14. PUMP
15. 床旁桌
16. 垃圾桶

---

## 🔐 資料安全

- **本地儲存**：資料儲存在瀏覽器 localStorage
- **雲端備份**：可選擇性上傳到 Google Sheets
- **權限控制**：Google Sheets 可設定共享權限
- **資料隱私**：不會上傳到第三方伺服器

---

## 🤝 貢獻指南

歡迎提交 Issue 和 Pull Request！

### 提交 Issue
- Bug 回報
- 功能建議
- 文件改善

### Pull Request 流程
1. Fork 專案
2. 建立分支 (`git checkout -b feature/AmazingFeature`)
3. 提交變更 (`git commit -m 'Add some AmazingFeature'`)
4. 推送分支 (`git push origin feature/AmazingFeature`)
5. 開啟 Pull Request

---

## 📝 更新記錄

### v1.0.0 (2025-10-16)
- ✨ 首次發布
- ✅ 公共區域巡檢功能
- ✅ 病房 ATP 檢測功能
- ✅ 複查追蹤機制
- ✅ Google Sheets 雲端同步
- ✅ 資料匯出功能（Excel/CSV/JSON）
- ✅ 響應式設計

---

## 📄 授權

本專案採用 MIT 授權 - 詳見 [LICENSE](LICENSE) 檔案

---

## 📞 聯絡資訊

**花蓮慈濟醫院 資訊部門**

- 📧 Email: it@hospital.org.tw
- 📱 電話: (03) xxxx-xxxx
- 🏥 地址: 花蓮市中央路三段707號

---

## 🙏 致謝

感謝所有使用本系統的醫療同仁，您們的回饋讓系統不斷進步！

---

## 🔗 相關連結

- [GitHub Pages](https://pages.github.com/)
- [Google Apps Script](https://developers.google.com/apps-script)
- [MDN Web Docs](https://developer.mozilla.org/)

---

**開發完成，立即體驗！** 🎉
