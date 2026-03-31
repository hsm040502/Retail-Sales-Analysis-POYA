# 寶雅門市皮帶銷售分析 (Retail Sales Analysis: POYA Belt Category)

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=flat&logo=r&logoColor=white)
![Statistics](https://img.shields.io/badge/Statistics-ANOVA_%26_Nested_Model-blue)

## 📌 專案背景與目標
本專案針對「寶雅門市」皮帶品類銷售進行深入研究。透過統計檢定驗證銷售差異，為品牌商與通路商（寶雅）提供具財務可行性的營運策略。

## 🛠 關鍵技術：統計建模與分析流程
本分析不僅停留在敘述統計，更深入應用進階統計推論技術：
- **分層隨機抽樣 (Stratified Sampling)**：平衡直轄市與一般縣市樣本，確保檢定力。
- **對比分析 (Contrast Analysis)**：針對特定款式（如：針棒款）進行對比，驗證其與市場其他產品之顯著差異。

## 📂 檔案結構說明
- `變異數資料處理.ipynb`: 實作分層抽樣與資料維度轉換。
- `寶雅皮帶銷售分析.html`: 包含 Contrast、Tukey HSD 事後檢定與 Mixed Model、Fixed Model 和 Nested Model 的統計實作。
- `POYA_Final_Report.pdf`: 完整分析報告，涵蓋商業洞察與對象別策略建議。

## 📊 核心洞察與策略建議 (Business Insights)

### 1. 產品端：強化「針棒款」與「中性定位」
* **統計發現**：「針棒款」皮帶在各類地區銷售表現皆具備顯著優勢 ($p < 0.05$)。
* **廠商建議**：建議調整生產比例，將資源集中於針棒款以**規模經濟降低成本**。針對直轄市大宗市場，開發更多「中性定位」產品，以同時覆蓋特定性別與跨性別需求。

### 2. 通路端：地區化進貨策略
* **統計發現**：直轄市在「針棒」與「中性」品項表現優異，且縣市的產業分佈具顯著影響。
* **寶雅建議**：考量到目前系統「售出才補貨」的自動化限制，建議針對直轄市特定門市手動調高「針棒款」的安全庫存水位，以優化迴轉率並減少缺貨損失。

---
*備註：本專案所使用之數據已進行去識別化處理，分析結果僅供學術與專業能力展示之用。*
