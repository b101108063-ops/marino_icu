# Marino ICU 翻譯模板

## 檔案抬頭（Front Matter）

```markdown
---
source: "Marino's ICU Book (4th Edition)"
specialty: "Critical Care Medicine"
weight: 1
chapter: "CH##"
title: "標題（英文）"
---
```

## 標準結構

### 1. 開場引言（可選）

```markdown
> 引言內容
> — 引言來源
```

### 2. Introduction（敘述性導言）

用一段流暢的中文敘述，介紹本章主題的歷史背景或重要概念。

### 3. 導讀摘要（Chapter Summary）

```markdown
## 導讀摘要

- **重點一**：說明
- **重點二**：說明
- **重點三**：說明
- **重點四**：說明
- **重點五**（可選）：說明
```

### 4. 主要內容章節

```markdown
## 第一章（H2）

敘述性文字...

### 1.1 小節（H3）

內容...

### 1.2 小節

內容...

#### 子小節（H4，適當時使用）

內容...
```

### 5. 常用藥物（適用時）

```markdown
## 常用藥物

| 藥物 | 機轉 | 適應症 | 副作用 |
|------|------|--------|--------|
| 藥物名稱 | 機轉 | 適應症 | 副作用 |
```

### 6. Landmark Trials（適用時）

```markdown
## Landmark Trials

| 試驗名稱 | 年份 | 主要結果 |
|----------|------|----------|
| 試驗名稱 | 年份 | 結果說明 |
```
```

## 翻譯原則

### 保留英文的術語
- 疾病名稱：sepsis, ARDS, shock,心衰竭
- 藥物名稱：norepinephrine, vasopressin, propofol
- 檢查名稱：ECG, PA catheter, CVP
- 技術術語：mechanical ventilation, hemodynamic monitoring

### 翻譯為中文的內容
- 敘述性文字 → 流暢繁體中文
- 症狀描述
- 治療原則說明
- 流行病學數據（數值保留）

### 數值與單位
- 劑量：劑量 mg/kg 或 mg/hr
- 數值：100 mg/dL、5.2 mmol/L
- 百分比：5%
- 溫度：37°C

### 表格格式
- 標題用 **粗體**
- 表頭用 `:----` 對齊（左/中/右）
- 表格來源用斜體註明

## 範例：導讀摘要

```markdown
## 導讀摘要

- **休克分類**：distributive shock（septic、neurogenic、anaphylactic）、cardiogenic shock、hypovolemic shock、obstructive shock 的病理生理與治療差異
- **血流動力學監測**：CVP、PA pressure、cardiac output、 SvO2 的測量方法與臨床意義
- **休克復甦**：早期目標導向治療（EGDT）的原則，液體復甦的種類與劑量，血管活性藥物的選擇
- **器官功能衰竭**：SOFA score、Lactate、AKI 的定義與管理
- **特殊族群**：心臟手術後休克、敗血症休克的處置要點
```

## 範例：開場引言

```markdown
> It is not a bad definition of man to describe him as a tool-making animal.
> — Charles Babbage
```

## 範例：Introduction

```markdown
## Introduction

敗血症（sepsis）仍是加護病房中最常見的死亡原因之一。雖然近年對其病理生理學的了解有長足進步，但臨床處置的核心原則不變：早期辨識、盡快給予抗生素、積極液體復甦、以及必要時使用血管活性藥物。本章節將系統性介紹休克的分類、評估方法與治療策略。
```

---

*最後更新：2026-07-29*
