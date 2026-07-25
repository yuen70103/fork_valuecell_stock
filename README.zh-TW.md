[English](README.md) | 繁體中文

<p align="center">
  <img src="assets/valuecell.png" style="width: 100%; height: auto;">
</p>

<div align="center" style="line-height: 2;">
    <a href="https://www.python.org/downloads" target="_blank">
<img src="https://img.shields.io/badge/python-3.12+-blue.svg"
            alt="Python version"></a>
    <a href="LICENSE" target="_blank">
<img src="https://img.shields.io/badge/license-Apache2.0-red.svg"
            alt="License: Apache2.0"></a>  
    <br>
    <a href="https://discord.com/invite/84Kex3GGAh" target="_blank">
<img src="https://img.shields.io/discord/1399603591471435907?logo=discord&labelColor=%20%235462eb&logoColor=%20%23f5f5f5&color=%20%235462eb"
            alt="chat on Discord"></a>
    <a href="https://twitter.com/intent/follow?screen_name=valuecell" target="_blank">
<img src="https://img.shields.io/twitter/follow/valuecell?logo=X&color=%20%23f5f5f5"
            alt="follow on X(Twitter)"></a>
    <a href="https://www.linkedin.com/company/valuecell/" target="_blank">
<img src="https://custom-icon-badges.demolab.com/badge/LinkedIn-0A66C2?logo=linkedin-white&logoColor=fff"
            alt="follow on LinkedIn"></a>
    <a href="https://www.facebook.com/people/ValueCell/61581410516790/" target="_blank">
<img src="https://custom-icon-badges.demolab.com/badge/Facebook-1877F2?logo=facebook-white&logoColor=fff"
            alt="follow on Facebook"></a>
    <a href="https://www.youtube.com/watch?v=C3tfHyGY9YE" target="_blank">
<img src="https://img.shields.io/badge/Watch%20on-YouTube-red?logo=youtube"
            alt="Watch on YouTube"></a>
</div>

<div align="center">
  <a href="README.md" style="color: gray;">English</a>
  <a href="README.zh.md" style="color: auto;">中文（简体）</a>
  <a href="README.zh_Hant.md" style="color: auto;">中文（繁體）</a>
  <a href="README.ja.md" style="color: auto;">日本語</a>
</div>


# 值單元

## 我們的產品推出了🔥🔥🔥

**ValueCell現提供A股深度研究、市場分析，無需部署，直接存取[valuecell.ai](https://valuecell.ai)。 **

## 描述

ValueCell 是一個社區驅動的多代理金融應用平台。我們的使命是打造全球最大的去中心化金融代理社群。

它提供了一個頂尖的投資代理團隊來幫助您選股、研究、追蹤、甚至交易。

系統將您所有的敏感資訊保存在您的裝置本地，確保核心資料安全。

歡迎加入我們的 Discord 社區，分享您遇到的回饋和問題，並邀請更多開發者貢獻🔥🔥🔥

>注意：ValueCell团队成员绝不会主动联系社区参与者。本項目僅供技術交流。投資涉及風險。 ⚠️

# 螢幕截圖

[![Watch the video](https://img.youtube.com/vi/C3tfHyGY9YE/maxresdefault.jpg)](https://www.youtube.com/watch?v=C3tfHyGY9YE)


<p align="center">
  <img src="assets/product/AutoTradingAgent.png" style="width: 100%; height: auto;">
</p>

<p align="center">
  <img src="assets/product/Model_Configuration.png" style="width: 100%; height: auto;">
</p>


# 主要特點

<p align="center">
  <img src="assets/architecture.png" style="width: 100%; height: auto;">
</p>


## 多Agent系統
- **DeepResearch Agent**：自動檢索和分析基礎文檔，以產生準確的資料見解和可解釋的摘要
- **策略代理**：支援多種加密資產、多策略智能交易，自動執行您的策略
- **新聞檢索代理**：支援個人化定時新聞投遞，即時追蹤關鍵訊息
- **其他**：更多代理商正在計劃中...

## 靈活的集成
- **多個LLM提供者**：支援OpenRouter、SiliconFlow、Azure、Openai相容、Google、OpenAI和DeepSeek
- **熱門市場數據**：涵蓋美國市場、加密貨幣市場、香港市場、中國市場等
- **相容多Agent框架**：支援Langchain、Agno by A2A協定進行研發集成
- **交易所連線**：即時路由至 OKX 和 Binance，內建護欄

# 快速入門

## 新用戶

要快速開始，請從 GitHub 上的 [Releases page](https://github.com/ValueCell-ai/valuecell/releases) 下載適用於 MacOS 或 Windows 的最新 ValueCell 應用程式。

安裝後，請在首次使用 ValueCell 之前配置您的首選模型提供者。根據需要請參閱應用程式或文件中的說明。

### 即時交易

- 設定 AI 模型：透過 Web 介面新增您的 AI 模型 API 金鑰。
- 設定交易所：設定 Binance/HyperLiquid/OKX/Coinbase... API 憑證
- 創建策略：將 AI 模型與交易所結合，創建自訂策略
- 監控與控制：啟動/停止交易者並即時監控表現
- 附註：目前僅支援合約交易（現貨以1X合約實現），請確保您的合約帳戶有足夠的餘額

#### 支援的交易所

|交流 |筆記|狀態 |
| --- | --- | --- |
| **幣安** |僅支援國際站點[binance.com](binance.com)，不支援美國站點。使用USDT-M期貨（USDT保證金合約）。確保您的合約帳戶有足夠的USDT餘額。交易對格式：`BTC/USDT`。注意：保證永續合約帳戶餘額不為0。申請API時，透過搜尋引擎搜尋`My IP`新增IP白名單| ✅ 已測試 |
| **超液體** |僅支援USDC作為保證金貨幣。使用您的主錢包地址+API錢包私鑰認證（使用[API tab](https://app.hyperliquid.xyz/API)申請）。市價單自動轉換為 IoC 限價單。交易對格式必須手動調整為`SYMBOL/USDC`（例如`WIF/USDC`）。配置主錢包位址+API錢包私鑰。每筆交易最低 10U | ✅ 已測試 |
| **確定** |需要 API Key、Secret 和 Passphrase（OKX 帳戶密碼）進行身份驗證。支持USDT保證金合約。交易對格式：`BTC/USDT` | ✅ 已測試 |
|幣庫 |支援USDT保證金合約。目前尚未支援Coinbase International | 🟡 部分測試 |
| Gate.io |支援USDT保證金合約。需要 API 金鑰和秘密 | 🟡 部分測試 |
|墨西哥 |支持USDT保證金合約。需要 API 金鑰和秘密 | 🟡 部分測試 |
|區塊鏈|支援USDT保證金合約。需要 API 金鑰、秘密 | 🟡 部分測試 |

**傳奇**：
- ✅ **經過測試**：在生產環境中經過全面測試和驗證
- 🟡 **部分測試**：程式碼實作已完成，但尚未完全測試，可能需要偵錯
- **推薦**：優先使用經過充分測試的交易所（Binance、Hyperliquid、OKX）

### 注意
- 目前僅支援槓桿交易，因此您需要確保您的Perps帳戶有足夠的餘額。
- 您必須確保 API 機密的安全，以避免資金損失。該應用程式將秘密儲存在您的裝置本地，並且不會透過網路將其發送給任何第三方。
- 為確保您的帳戶安全，您需要定期重置您的API金鑰。

---

**注意**：在運行應用程式之前，請確保安裝了所有先決條件並正確配置了環境變數。如果距離上次更新已經很長時間了，您可以刪除本地資料儲存並重新開始：
- LanceDB目錄（儲存在您的系統應用程式目錄中，與`.env`相同路徑）：
  - 蘋果系統：`~/Library/Application Support/ValueCell/lancedb`
  - Linux：`~/.config/valuecell/lancedb`
  - 視窗：`%APPDATA%\\ValueCell\\lancedb`
- 知識目錄（存放在您的系統應用程式目錄中，與`.env`相同路徑）：
  - 蘋果系統：`~/Library/Application Support/ValueCell/.knowledge`
  - Linux：`~/.config/valuecell/.knowledge`
  - 視窗：`%APPDATA%\\ValueCell\\.knowledge`
- SQLite資料庫檔案（儲存在您的系統應用程式目錄中，與`.env`相同的路徑）：
  - 蘋果系統：`~/Library/Application Support/ValueCell/valuecell.db`
  - Linux：`~/.config/valuecell/valuecell.db`
  - 視窗：`%APPDATA%\\ValueCell\\valuecell.db`


## 開發商

我們真誠地邀請所有開發者加入我們的 Discord 討論小組，我們定期在其中分享社區路線圖和即將推出的貢獻者福利計劃。

有關開發流程和標準的詳細資訊如下：[CONTRIBUTING.md](.github/CONTRIBUTING.md)

ValueCell是一個基於Python的應用程序，具有全面的Web介面，支援多平台部署。依照下面的配置即可快速上手。

## 克隆儲存庫

   ```bash
   git clone https://github.com/ValueCell-ai/valuecell.git
   cd valuecell
   ```

## 運行應用程式

啟動完整的應用程式（前端、後端和代理）：

### Linux/蘋果系統
```bash
bash start.sh
```

### Windows（PowerShell）
```powershell
.\start.ps1
```

### 存取介面

- **Web UI**：在瀏覽器中導航至[http://localhost:1420](http://localhost:1420)
- **日誌**：直接在終端機中查看應用程式日誌，以了解後端服務和各個代理程式的詳細運行時信息

### 下一步

應用程式運行後，您可以探索 Web 介面以與 ValueCell 的特性和功能進行互動。

### 配置

更詳細的配置資訊可以在[CONFIGURATION_GUIDE](./docs/CONFIGURATION_GUIDE.md)找到

# 路線圖

## 🤖 增強的代理能力
### 交易能力
- **加密貨幣**：支援OKX、Binance和Hyperliquid交易所，規劃整合更多交易所...
- **證券**：逐步支持AI證券交易

### 市場拓展
- **歐洲市場**：增加對 FTSE、DAX、CAC 40 和其他歐洲交易所的支持
- **亞洲市場**：將覆蓋範圍擴大到日經指數和亞洲新興市場
- **商品市場**：石油、黃金、白銀、農產品分析
- **外匯市場**：主要貨幣對和交叉貨幣分析

### 資產多角化
- **固定收益**：政府公債、公司債與殖利率分析代理
- **衍生性商品**：選擇權、期貨與複雜的金融工具
- **另類投資**：私募股權、對沖基金與創投分析

### 進階通知和推播類型
- **即時警報**：價格變動、交易量高峰與技術突破
- **定期報告**：每日/每週/每月作品集摘要
- **事件驅動的通知**：收益發布、股利公告、監理變化
- **自訂觸發器**：使用者定義的條件和閾值
- **多通路交付**：Discord 和 webhook 集成

## ⚙️ 產品配置與個人化
### 多平台產品
- **桌面支援**：逐步支援桌面與用戶端功能
- **資料庫熱更新**：逐步支援相容性升級

### 國際化（i18n）
- **多語言支援**：英語、中文（簡體/繁體）、日語、韓語、西班牙語、法語
- **在地化市場資料**：特定地區的金融術語和格式
- **文化適應**：時區、日期格式與金錢偏好
- **座席個人化在地化**：適合文化的溝通方式

### 令牌和身份驗證管理
- **API 金鑰管理**：第三方 API 金鑰的安全儲存和輪換
- **OAuth 整合**：支援主要金融數據提供商

### 用戶偏好和自訂
- **投資概況**：風險承受能力、投資期間與策略偏好
- **UI/UX 客製化**：暗/亮模式、儀表板佈局和小部件首選項
- **座席行為**：溝通頻率、分析深度與報告風格
- **投資組合管理**：自訂基準、績效指標與分配目標

### 記憶和學習系統
- **對話歷史記錄**：跨會話的持久聊天歷史記錄
- **使用者學習**：基於使用者行為的自適應推薦
- **市場記憶**：歷史背景與模式識別
- **偏好演變**：隨著時間的推移動態調整推薦

## 🔧 ValueCell SDK 開發
### 核心SDK功能
- **Python SDK**：用於代理整合和客製化的綜合庫
- **WebSocket 支援**：即時資料流和雙向通信

### 代理整合框架
- **外掛架構**：輕鬆整合第三方代理與工具
- **代理註冊中心**：社區貢獻代理的市場

### 開發者工具和文檔
- **互動式 API Explorer**：具有即時測試的 Swagger/OpenAPI 文檔
- **程式碼範例**：多種程式語言的範例實現
- **測試框架**：單元測試、整合測試和模擬資料提供程序

# 執照

該項目根據 **Apache License 2.0** 獲得許可 - 有關詳細信息，請參閱[LICENSE](./LICENSE) 文件。

> 📌 注意：Apache 2.0 **僅適用於 ValueCell 團隊和貢獻者所寫的原始程式碼**。第三方元件（例如 API、小部件、庫）受其自己的許可證和條款的約束 - 請參閱下文。

## 第三方組件和許可

ValueCell 整合外部服務並嵌入第三方小部件。它們的使用**不包含在 Apache 2.0** 中，作為使用者/開發人員，您有責任遵守它們的條款。

|組件|類型 |授權/條款|
|---------|------|-----------------|
| **TradingView 進階圖表** |嵌入式 iframe 小工具 | [Free Advanced Charts Agreement](https://www.tradingview.com/chart-embedding/)（專有）|
| **交易所 API**（Binance、OKX、Hyperliquid 等）| REST/WebSocket 端點 |每個交易所的服務條款（例如[Binance API Terms](https://www.binance.com/en/terms)）|
| **LLM 提供者**（OpenAI、Azure、Google、DeepSeek 等）|推理 API |特定於提供者的服務條款（例如[OpenAI ToS](https://openai.com/policies/terms-of-use)）|

# 明星歷史

<div align="center">
<a href="https://www.star-history.com/#ValueCell-ai/valuecell&Date">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=ValueCell-ai/valuecell&type=Date&theme=dark" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=ValueCell-ai/valuecell&type=Date" />
   <img alt="TradingAgents Star History" src="https://api.star-history.com/svg?repos=ValueCell-ai/valuecell&type=Date" style="width: 80%; height: auto;" />
 </picture>
</a>
</div>

<div align="center">
