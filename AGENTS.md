## 通用 AI Agent PROMPT 範本（中英對照）

下面是一個可以直接丟給「前端生成型 AI（例如：寫 HTML/CSS/JS 的 Agent）」的 Prompt，你可以依技術棧再精調：

***

**PROMPT 開始：**

你是一名資深前端工程師 Senior Frontend Engineer，請幫我生成一個產品型 Landing Page，仿造以下結構與資訊架構（Information Architecture），但使用全新的文案與設計（不能抄襲原網站文案，只保留功能邏輯與版型概念）。

### 一、開發技術要求 Tech Stack

- 使用技術（擇一或多選，若未指定則用純 HTML + Tailwind CSS）：  
  - HTML5 + Tailwind CSS    
  - 或 Vue 3 + Composition API + Tailwind CSS  
- 網站需具備：  
  - 響應式設計 Responsive Design（桌機 / 平板 / 手機）。  
  - 清楚的結構化語義標籤（`<header> <main> <section> <footer>`）。  
  - 可讀性良好的 class 命名與適度註解。  

### 二、產品定位 Product Positioning

- 產品類型：廟宇數位化管理系統 Temple Digital Management System（AI 廟祝 AI Temple Assistant）。  
- 主要客群：廟宇 / 宮廟管理者、主委、董事會。  
- 主要賣點：  
  - AI 智能解籤 AI-powered Divination Explanation。  
  - 線上祈福 Online Blessing Service。  
  - 會員與活動管理 Member & Event Management。  
  - LINE 活動卡片推播 LINE Rich Message Promotion。  
  - 數據營運儀表板 Data Analytics Dashboard。  

請用全新的中文文案（可穿插少量中英對照專有名詞），避免與既有網站字句重複。

### 三、頁面結構 Page Structure

請依照以下區塊順序建立版面：

1. Hero 區塊 Hero Section  
   - 元素：  
     - 左側：  
       - 產品 Logo/產品名稱（文字版即可）。  
       - 主標題：強調「AI + 廟宇管理」的價值。  
       - 副標題：說明這是專為宮廟設計的數位化解決方案。  
       - 兩個主要按鈕：  
         - 「立即預約諮詢」(Primary CTA) → 捲動到聯絡表單。  
         - 「體驗線上解籤 Demo」(Secondary CTA) → 捲動到功能展示區。  
     - 右側：  
       - 一個代表系統介面的假圖（可用漸層色塊 + 卡片組合模擬 Dashboard）。  
   - 背景風格：簡潔現代，可融入微量東方廟宇元素（例如：雲紋、線條），但不要太花。

2. 系統特色區 Features Section  
   - 區塊標題：例如「一站式廟宇數位管理中心」。  
   - 四個主要功能卡片，對應：  
     - 會員管理 Member Management：會員資料、活動紀錄、消費紀錄、個人化服務。  
     - 活動管理 Event Management：活動建立、報名、通知推播、數據統計。  
     - 線上服務 Online Services：AI 解籤、線上祈福、線上購物、電子支付。  
     - LINE 活動卡片推播 LINE Promotion：活動卡片、一鍵報名、群組通知、狀態即時更新。  
   - 每張卡片包含：圖示 icon、標題、2–3 句說明文字、簡短 bullet list。  

3. 系統介面展示區 UI Showcase Section  
   將此區分成多個子段落，每個子段落一個標題 + 說明 + 圖片占位。  
   - 子段一：AI 智能解籤 AI Divination  
     - 說明「信眾可以線上抽籤、系統用 AI 解釋籤詩、提供現代語言建議」。  
     - 右側用一個卡片風格區塊模擬聊天 / 解籤結果。  
   - 子段二：LINE 智能推播 LINE Integration  
     - 說明「透過官方 LINE 帳號推播活動卡片、一鍵報名」。  
     - 模擬 LINE 對話框樣式卡片。  
   - 子段三：活動報名服務 Event Registration  
     - 說明「快速建立進香團 / 法會 / 祈福燈活動，民眾線上填表報名」。  
     - 左右排版：左文字右假表單。  
   - 子段四：數據營運中心 Data Analytics Center  
     - 說明「視覺化圖表呈現會員數、活動參與、收入等指標」。  
     - 使用幾個虛構的長條圖 / 圓餅圖卡片作為 UI placeholder。  
   - 子段五：會員服務整合 Member Service Integration  
     - 說明「個人會員頁面，整合歷史祈福、活動紀錄。」  

4. 體驗引導區 Experience Call-to-Action  
   - 區塊標題：例如「加入官方 LINE，立即體驗」。  
   - 說明文字：鼓勵掃描 QR code 或點擊按鈕加入 LINE。  
   - 元素：  
     - 一個 LINE 風格按鈕（文字「加入 LINE 官方帳號」即可）。  
     - 一個 QR code 占位方框（用邊框 + 文案「QR Code 位置」代替）。  

5. 聯絡表單區 Contact Form Section  
   - 區塊標題：例如「預約專人導入諮詢」。  
   - 簡短說明文字 1–2 句。  
   - 表單欄位（請用語義化 `label` 對應 input）：  
     - 廟宇名稱（必填）Temple Name (required)  
     - 聯絡人姓名（必填）Contact Person Name (required)  
     - 聯絡電話（必填）Phone (required)  
     - 電子郵件 Email  
     - 需求說明 Requirement Description（`textarea`）  
   - 表單提交按鈕：「送出表單」。  
   - 前端層級的必填欄位驗證（HTML5 `required` 或簡單 JS 驗證）。  

6. 底部資訊區 Footer Section  
   - 四個小欄位：  
     - 關於我們 About Us：1–2 句介紹「連結傳統與科技的團隊」。  
     - 功能特色 Features：列出主要功能名稱列表，使用簡單文字連結（不需實作跳轉功能，但可加 `href="#features"` 類似結構）。  
     - 技術支援 Technical Support：列出導入輔導、問題排除、功能更新、教育訓練。  
     - 版權宣告 Copyright：年份 + 產品名稱 + 簡短 slogan。  

### 四、設計風格 Design Style

- 整體風格：  
  - 現代 SaaS 風格，乾淨、留白充足。  
  - 色彩：主色可選擇深紅 / 靛藍 / 金色點綴，代表廟宇莊嚴感，但搭配淺底。  
- 字體：  
  - 網頁字體用系統字體堆疊即可（例如 Noto Sans TC / system-ui）。  
- Icon：  
  - 可使用 Tailwind + Heroicons 風格（用簡單 SVG 或 Unicode 符號模擬）。  

### 五、輸出格式 Output Format

- 若使用純 HTML + Tailwind：  
  - 請輸出完整 HTML 文件，包含 `<!DOCTYPE html>`、`<html> <head> <body>` 結構，並引入 Tailwind CDN。  
- 若使用 React 或 Vue：  
  - 請輸出單頁主組件程式碼（例如 `App.jsx` 或 `App.vue`），保持結構清晰，並在註解中標明各區塊用途。  

請直接輸出程式碼，不要加額外的解說文字。

**PROMPT 結束。**


