# Zhen Huang's Academic CV 

[![Deployment: Cloudflare Pages](https://img.shields.io/badge/Deployment-Cloudflare_Pages-f38020?style=flat&logo=cloudflare&logoColor=white)](https://pages.cloudflare.com/)
[![Analytics: Cloudflare Web Analytics](https://img.shields.io/badge/Analytics-Cloudflare_Web_Analytics-f38020?style=flat&logo=cloudflare&logoColor=white)](https://www.cloudflare.com/web-analytics/)

這是我的個人學術履歷網站，主要作為個人入口網站首頁，展示學術著作與其他個人基本資訊。

## 網站資訊
- **主站網址**: [https://zhenhuang.tw](https://zhenhuang.tw)
- **部署**: Cloudflare Pages
- **流量統計**: Cloudflare Web Analytics

## 技術
- **Frontend**: HTML5, Tailwind CSS (via CDN)
- **Interactivity**: Vanilla JavaScript (Dark Mode detection & toggle)
- Responsive Web Design (RWD)

## 網頁架構與內容
本網頁遵循通用的學術履歷格式，包含以下區塊：
- 學歷 (Education)
- 研究興趣 (Research Interests)
- 計畫 (Research Projects)
- 著作 (Publications)
- 研討活動 (Conferences)

## 部署與維護
### 1. 部署方式
本專案透過 GitHub 儲存庫與 Cloudflare Pages 進行連動。每當執行 `git push` 後，Cloudflare 會自動進行部署。

### 2. 網域與重新導向設定
- **Apex Domain**: `zhenhuang.tw` (主要存取點)
- **WWW Subdomain**: 透過 Cloudflare Redirect Rules 自動重新導向至根網域。

### 3. 本地開發
由於本專案採 Single-page 結構且透過 CDN 引入 CSS，無須安裝 Node.js 依賴。直接開啟 `index.html` 即可預覽：

```bash
# 若有安裝 VS Code Live Server，點擊 "Go Live" 即可
```

## 授權
本專案內容由 Zhen Huang 所有，原始碼部分歡迎參考。