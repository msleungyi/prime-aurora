---
title: 閱讀障礙亞型地圖（MAP-DyS）
date: 2026-03-06
draft: false
summary: 一個視覺化發展性閱讀障礙亞型研究分析方法多樣性的Shiny 應用程式。
links:
  - icon: 🟢
    icon_pack: fas
    name: Shiny App
    url: https://dyslexiaproject.shinyapps.io/dyslexia_subtypes/
  - type: preprint
    url: https://www.medrxiv.org/content/10.1101/2025.07.23.25332032v1
  - type: dataset
    url: https://github.com/kristantodan12/Dyslexia_subtyping
  - type: code
    url: https://github.com/kristantodan12/Dyslexia_subtyping
tags:
  - 發展性閱讀障礙
  - 閱讀發展
  - 亞型研究
  - 開放科學
  - 研究綜述方法

---

## 為什麼要研究閱讀障礙的亞型？

心理學或生物醫學的研究人員嘗試根據不同的認知特徵，將發展性閱讀障礙（developmental dyslexia）的個體劃分為不同的亞型。例如，有些研究將亞型區分為語音處理困難或視覺處理困難等不同類型。

辨識亞型的目的，是希望更深入理解閱讀困難背後的機制，同時為不同類型的學習者設計更個人化的介入方法。

然而，在實際研究中，不同研究往往採用不同的分析決策來界定亞型。例如：

- 研究所依據的理論框架  
- 數據處理或標準化方法  
- 納入分析的認知測量指標  
- 所使用的統計方法（例如分群分析或分類規則）

由於辨識閱讀障礙亞型的方法上的差異，即使研究使用相似的數據，也可能得出不同的亞型結果。

這便引出一個重要的方法學問題：

> 讀寫障礙亞型研究中的差異，到底有多少是來自個體本身的差異，又有多少是來自研究方法與分析決策的不同？

---

## 我們的研究計劃：“MAP-DyS”

本研究項目，Mapping Dyslexia Subtypes（MAP-DyS） 計劃的目標，是希望把閱讀障礙亞型研究的方法及結果多樣性，以視覺化的形式呈現出來。

在這個研究中，我們對現有的閱讀障礙亞型研究進行了系統性文獻回顧，並整理出文獻中常見的分析決策，包括：

- 研究採用的讀寫障礙理論模型  
- 數據處理與標準化方法  
- 表現指標（例如正確率或反應時間）  
- 統計分類方法  
- 各類亞型的報告比例

根據這些資訊，我們構建了一個展示不同分析路徑的「方法多元宇宙（multiverse）」。

為了方便研究員及臨床工作者探索這個「方法多元宇宙（multiverse）」，我們開發了一個互動式的 **Shiny 應用程式**[**（MAP-DyS）**](https://dyslexiaproject.shinyapps.io/dyslexia_subtypes/)。使用者可以在這程式上瀏覽及比較不同的亞型分類方法及結果。

---

## MAP-DyS 應用程式的作用

MAP-DyS 應用程式可以讓使用者：

- 探索不同研究中讀寫障礙亞型方法的差異  
- 視覺化文獻中使用的分析決策路徑  
- 比較不同的亞類研究方法  
- 反思研究設計如何影響研究結論

我們希望 MAP-DyS 能夠幫助研究者及臨床工作者更清楚地理解閱讀障礙亞型研究中的方法差異。

---

## 給研究員及臨床工作者的啟示

亞型研究在心理學與生物醫學中非常常見。然而，如果研究方法本身會顯著影響結果，那麼不同研究之間的比較就會變得困難。

而像 MAP-DyS 這樣的視覺化工具，可有助我們：

- 以批判的角度理解及分析既有文獻  
- 設計更透明的研究方法及成果匯報  
- 理解科研方法步驟的多樣性如何影響科學結論

雖然本研究以發展性閱讀障礙為案例，但理論上，本分析框架亦可應用於其他心理學與生物醫學領域中的亞型研究。

---

## 了解更多

若欲了解完整的研究方法與結果，歡迎閱讀我們的Preprint：

[**Leung, A. Y., Kristanto, D., Gießing, C., Ioannidis, J. P. A., Hildebrandt, A., & Schmalz, X. (2025).**  
*The multiverse of developmental dyslexia subtyping: The “Mapping Dyslexia Subtypes” (MAP-DyS) app for analytical decision-making.*](https://www.medrxiv.org/content/10.1101/2025.07.23.25332032v1)

---

### 鳴謝

本計劃由我與 Dr. Daniel Kristanto 共同主導，並獲得 META-REP Priority Programme（Phase 1）「Treasure Box for Early-Career Researchers (ECR)」的資助。我們亦感謝以下合作研究者在理論與方法上的建議與支持： Prof. John Ioannidis、Prof. Andrea Hildebrandt、Dr. Xenia Schmalz、Dr. Carsten Gießing，同時感謝研究助理 Mr. Peter Roßmeier 協助資料整理與整合。