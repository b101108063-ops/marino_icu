---
source: "Marino's ICU Book (4th Edition)"
specialty: "Critical Care Medicine"
weight: 27
chapter: "CH27"
title: "Conventional Mechanical Ventilation"
---

## Chapter 27: Conventional Mechanical Ventilation

> "Medicine is a science which has been more laboured than advanced. For I find much iteration, but small addition."
> — Sir Francis Bacon (a)

最早的呼吸器（1920 年代末引進）是稱為鐵肺的負壓艙，將患者從頸部到腳踝封閉起來。這些龐然大物（早期型號重約一噸）是通氣支持的唯一手段，直到 1950 年代的小兒麻痺症流行，當時對輔助通氣的需求超過了鐵肺的供應。在丹麥哥本哈根，氣管切開術被引進，醫學生以 8 小時輪班工作，作為人類呼吸器，手動為患者肺部充氣（1）。在波士頓，當地的愛默生公司有一種正壓肺部充氣的原型裝置，在麻省總醫院投入使用，並立即獲得成功。

快進大約 70 年，估計有 174 種不同的通氣模式（2）。然而，只有一種顯示了改善臨床預後的證據（3,4）——而且是因為它限制了正壓通氣所產生的肺損傷（見第 24 章）。這意味著機械通氣比它需要的要複雜得多，而這種支持形式是「少即是多」。

本章描述正壓通氣的基本方法。雖然遠少於可用方法的數量，但這些方法可以為大多數（如果不是全部）患者提供有效的通氣支持。

## 導讀摘要

- 兩種基本正壓通氣模式：**Volume-control ventilation（VCV）**以固定流量送氣，tidal volume 穩定；**Pressure-control ventilation（PCV）**以減速流量送氣，患者接受度更高
- **Plateau pressure（平臺壓）**應維持 **≤30 cm H₂O** 以避免肺泡過度擴張傷害；此為肺保護性通氣的核心目標
- **Lung protective ventilation 協議**：起始 VT **8 mL/kg** **PBW**，逐步降至 **6 mL/kg** **PBW**；若 Pplat >**30 cm H₂O** 則降低 VT
- **PEEP** 用於防止小氣道塌陷，低度 **PEEP**（**5–10 cm H₂O**）防止塌陷，高度 **PEEP**（**10–20 cm H₂O**）可復張肺泡
- Thoracic compliance 正常值 **50–80 mL/cm H₂O**，浸潤性肺病時通常 <**25 mL/cm H₂O**


### 呼吸器呼吸

正壓肺部充氣有兩種基本方法。摘要如下。

1. **Volume-control ventilation (VCV):** 預選所需的充氣容積（tidal volume）。氣體以固定流量遞送，容積和呼吸道壓力穩定上升直到達到目標容積。然後被動吐氣。
2. **Pressure-control ventilation (PCV):** 預選所需的充氣壓力。吸氣流量呈減速模式，峰值流量在吸氣初期，此後流量遞減至吸氣末為零。由於這種流量模式，肺容積和呼吸道壓力在吸氣初期增加較多。所需的（峰值）壓力早期達到，然後由預選的吸氣時間決定吸氣何時結束。吐氣被動進行。

所有變量（即容積、壓力和流量）都由呼吸器記錄和顯示，但測量是在氣管內管層面進行的，可能不能反映末梢空氣腔（肺泡）的狀況。此外，呼吸道壓力測量為經胸壓力（即，相對於大氣壓的呼吸道壓力），並受肺和胸壁兩者的影響。跨肺壓的測量（即，相對於肋膜壓的呼吸道壓力）消除了胸壁的影響，但需要使用食道球囊測量肋膜內壓。

### Volume Control

Volume-control ventilation (VCV) 以固定流量遞送預選的 tidal volume，峰值呼吸道壓力（Ppeak）由肺和胸壁的機械特性（阻力與彈性）決定。可以表示如下：

$$P_{peak} = P_{res} + P_{el}$$

其中 Pres 是氣道阻力引起的壓力，Pel 是肺和胸壁彈性回縮力引起的壓力（彈性）。（注意：彈性是物體對變形的阻力。）

#### Plateau Pressure

可以通過在肺部充氣末暫時阻塞呼吸器管路來識別峰值和彈性對峰值呼吸道壓力的相對貢獻（5）。這個「充氣-保持」操作在原文中有所說明。在充氣保持期間，峰值壓力最初下降，然後達到恆定的 plateau pressure，直到阻塞釋放並開始吐氣。由於在充氣-保持操作期間沒有氣流，plateau pressure 等於肺泡內壓力（Palv），這是肺和胸壁彈性回縮力（Pel）產生的壓力：

$$P_{plateau} = P_{alv} = P_{el}$$

（注意：正壓吐氣末壓力，即 **PEEP**，在機械通氣中常用，必須從 plateau pressure 中減去才能得到實際的肺泡壓力。）峰值壓力和 plateau pressure 之間的差異是克服氣流阻力所需的壓力（Pres）：

$$(P_{peak} - P_{plateau}) = P_{res}$$

> **肺泡損傷的風險：** VCV 期間的峰值呼吸道壓力高於壓力控制通氣，有一種誤解認為這會增加肺泡破裂的風險。然而，這種風險取決於肺泡壓力；即 plateau pressure。臨床研究表明，如果肺泡壓力（plateau pressure）≤**30 cm H₂O**，肺泡破裂的風險可以忽略不計（2,4），這是肺保護性通氣的主要目標之一，見後文描述。

**VCV 的優勢：** VCV 的主要優勢是能夠在肺機械特性變化時維持恆定的 tidal volume。這對於限制機械通氣期間使用的 tidal volume 尤其重要，這是肺保護性通氣的基礎。

**VCV 的劣勢：** VCV 期間恆定的吸氣流量帶來兩個潛在劣勢。首先，吸氣時間相對較短，這可能導致肺泡填充不均。其次，當流量恆定時，最大吸氣流量是有限的；因此，對於高通氣需求的患者，吸氣流量可能不足。VCV 有減速流量模式可用，已被證明可以改善患者舒適度（6）。

### Pressure Control

使用壓力控制通氣（PCV），預選所需的充氣壓力，減速吸氣流量在充氣開始時提供高流量以快速達到所需的充氣壓力。調整吸氣時間以允許足夠的時間讓吸氣流量在吸氣末降至零。由於在吸氣末沒有氣流，吸氣末呼吸道壓力等於肺泡內壓力。

**PCV 的優勢：** PCV 的主要優勢是與 VCV 相比增加了患者接受度和降低了通氣不同步的風險（7）。這一優勢歸因於 PCV 初期的高流量和較長的吸氣時間。

**PCV 的劣勢：** PCV 的主要劣勢是 tidal volume 隨氣道阻力或肺彈性變化而變化，因為這可能增加肺泡過度擴張和呼吸器誘發肺損傷的風險（見第 24 章）。然而，下面描述的自適應模式可以糾正這一劣勢。

### 壓力調節容積控制

壓力調節容積控制通氣（PRVC）是一種自適應通氣模式，提供恆定的 tidal volume（如容積控制），但限制吸氣末呼吸道壓力（如壓力控制）。PRVC 像一種智慧形式的容積控制；即呼吸器監測肺順應性並使用這些測量來選擇遞送所需 tidal volume 所需的最低呼吸道壓力（8）。這已成為一種流行的機械通氣模式，但具有高通氣驅動力的患者可能無法獲得所需的吸氣流量，導致呼吸器不同步（9）。

### 吐氣末壓力

吐氣末壓力是通氣週期中肺泡內的最低壓力。不同形式的吐氣末壓力描述如下。

#### **ZEEP**

在正常肺的適當通氣期間，吐氣末沒有氣流，肺泡內的壓力等於大氣壓。由於大氣壓是呼吸的零參考點，這種情況稱為零吐氣末壓力，或 **ZEEP**。

#### 應用的 **PEEP**

正壓吐氣末壓力（**PEEP**）可以通過通氣管路添加（通過管路呼氣肢上的壓力敏感閥），這樣當呼吸道壓力降至預選的 **PEEP** 水平時，吐氣就會停止。應用的 **PEEP** 是機械通氣期間的常規使用，以防止小氣道在吐氣末塌陷，並打開塌陷的肺泡（復張）。應用的 **PEEP** 的用途、優勢和劣勢在本章後面描述。

#### 隱匿性 **PEEP**

當吐氣末持續有氣流時，肺不完全排空，肺泡壓力保持為正，儘管近端呼吸道壓力降至大氣壓（零）。這種壓力有時稱為內源性 **PEEP** 或自動 **PEEP**，但也使用隱匿性 **PEEP** 是因為 **PEEP** 在近端呼吸道壓力記錄中不明顯（10）。隱匿性 **PEEP** 可能源於哮喘和 COPD 患者的動態過度充氣（如第 23 章所述），或源於傾向於吐氣末氣流的呼吸器設定（例如：高 tidal volume、減少吐氣時間）。

隱匿性 **PEEP** 可以通過注意吐氣末是否有氣流來在流量追蹤上檢測。如果存在隱匿性 **PEEP**，可以通過在吐氣末阻塞呼氣管路來量化。在呼氣末阻塞期間，肺泡壓力將與近端呼吸道壓力平衡，隱匿性 **PEEP** 表現為呼吸道壓力的突然升高。此操作僅在患者沒有呼吸努力時才成功。隱匿性 **PEEP** 在第 28 章有更詳細的描述。

### 平均呼吸道壓力

平均呼吸道壓力是通氣週期中呼吸道的平均壓力，受幾個變量的影響，包括：峰值呼吸道壓力、壓力波形的輪廓、**PEEP** 水平、呼吸頻率，以及充氣時間相對於整個通氣週期時間的比例（TI/Ttot）。呼吸器顯示的平均呼吸道壓力是通過積分呼吸道壓力波形下的面積獲得的。

平均呼吸道壓力與正壓通氣的血流動力學效應有關。（肋膜內壓對心臟功能有重要影響，但這個壓力需要用食道內球囊測量，常規不進行監測。）正壓通氣期間平均呼吸道壓力的典型值為：正常肺 **5–10 cm H₂O**，氣流阻塞 **10–20 cm H₂O**，順應性差（僵硬）的肺 **20–30 cm H₂O**（11）。

### 胸順應性

順應性（Δvolume/Δpressure）是彈性的倒數，是傳統用於表達有腔室結構（如心臟和肺）彈性特性的術語。順應性表達了順應性，即腔室在暴露於給定擴張壓力時增加容積的傾向。機械通氣期間測量的順應性是胸順應性，包括肺和胸壁。

#### Volume-Control Ventilation

在 VCV 期間，胸廓的靜態順應性（Cstat）表示為預選的 tidal volume（VT）除以 plateau pressure 與總 **PEEP** 水平（應用加隱匿性 **PEEP**）之間的差值：

$$C_{stat} = V_T / [P_{plateau} - PEEP_{(tot)}]$$

這是「靜態」順應性，因為涉及的壓力是在沒有氣流的情況下測量的。在正常肺患者中，Cstat 為 **50–80 mL/cm H₂O**（12），在有浸潤性肺疾病的患者中（例如：肺水腫或急性呼吸窘迫症候群），Cstat 通常為 **<25 mL/cm H₂O**（13）。

#### Pressure-Control Ventilation

在 PCV 期間，Cstat 是吐出的 tidal volume（呼出 VT）除以吸氣末呼吸道壓力（Paw）與總 **PEEP** 水平之間的差值：

$$C_{stat} = \text{Exhaled } V_T / [P_{aw(end-insp)} - PEEP_{(tot)}]$$

#### 順應性測量的誤差來源

1. 在被動通氣期間，胸壁可佔總胸順應性的 35%（14,15），當胸壁肌肉收縮時，這個貢獻會增加。因此，為了避免解讀胸順應性變化時出錯，順應性測量應在患者有最少或無呼吸努力時進行。
2. 胸順應性是容積依賴性的；即，隨著肺容積增加而減少。機械通氣期間無法測量絕對肺容積，因此順應性測量應在相同的 tidal volume 下進行。
3. 用於順應性測量的 tidal volume 應根據呼吸器管路的順應性進行調整，這通常為 **3 mL/cm H₂O**（13）。例如，如果在 VCV 期間預選的 tidal volume 為 500 mL，峰值呼吸道壓力為 **40 cm H₂O**，則 3 × 40 = 120 mL 的遞送容積將丟失到呼吸器管路的擴張中，而到達患者的實際 tidal volume 將為 500 – 120 = 380 mL。當使用 PCV 期間呼出 tidal volume 時，應使用吸氣末的呼吸道壓力進行容積調整。

### 輔助-控制通氣

輔助-控制通氣（ACV）允許患者啟動呼吸器呼吸，但如果不可能，則以預選速率（控制或時間觸發通氣）遞送呼吸器呼吸。ACV 期間的呼吸器呼吸可以是容積觸發或壓力觸發的。

#### 觸發

ACV 中的呼吸器呼吸可以通過兩種方式啟動（觸發）：

- **患者觸發：** 壓力波形之前有負壓偏轉，這代表患者自發的吸氣努力。
- **時間觸發：** 壓力波形之前沒有負壓偏轉，表示沒有自發吸氣努力。在這種情況下，患者和呼吸器之間沒有互動，呼吸器呼吸以預選速率遞送。

#### 患者相關觸發

有兩種信號允許患者觸發呼吸器呼吸：負壓和吸氣流量。

| Trigger Type | Mechanism | Considerations |
|---|---|---|
| **負壓** | 患者產生負呼吸道壓力 **2–3 cm H₂O** 來打開壓力敏感閥 | 儘管壓力要求低，但大約三分之一的吸氣努力未能觸發呼吸器呼吸 |
| **流量** | 流量觸發幾乎不涉及壓力和容積的變化 | 比壓力觸發的機械功少；流量已取代壓力成為標準觸發機制；系統漏氣引起的自動觸發是一個潛在問題 |

#### 呼吸週期

機械通氣期間的一個通用原則是允許至少兩倍於吸氣的時間用於吐氣。這相當於吸氣:吐氣時間比（I:E 比）至少為 1:2。目標是允許足夠的時間完全吐氣，以防止動態過度充氣和內源性或隱匿性 **PEEP**。如果吐氣時間太短，可以通過以下方式增加 I:E 比：

1. 增加吸氣流量
2. 減少 tidal volume
3. 減少吸氣時間（用於壓力控制）

#### 快速呼吸

當每次呼吸都是患者觸發的呼吸器呼吸時，快速呼吸會嚴重縮短吐氣時間，並增加動態過度充氣和隱匿性 **PEEP** 的風險。當快速呼吸是由於不適或焦慮以外的情況引起時，通過鎮靜或吸氣流量調整來降低呼吸頻率的嘗試通常不成功。在這種情況下，下面描述的 IMV 模式可能是答案。

### 間歇性強制通氣

新生兒呼吸窘迫症候群患者（在 ACV 期間呼吸頻率通常高於每分鐘 40 次）快速呼吸的困難，導致了間歇性強制通氣（IMV）的引進。

#### 方法

IMV 旨在允許在呼吸器呼吸之間進行自發呼吸。這是通過在呼吸器管路旁放置一個自發呼吸管路來實現的，該管路帶有一個單向閥，在不遞送呼吸器呼吸時打開自發呼吸管路。IMV 中的通氣模式允許呼吸器呼吸與自發呼吸同步遞送，這稱為同步 IMV（SIMV）。

SIMV 期間的呼吸器呼吸可以是容積觸發或壓力觸發的。呼吸器呼吸的頻率可以從每分鐘 10 次呼吸開始，然後根據需要進行調整，以達到所需的分鐘通氣量（自發加輔助呼吸）。

#### 不良效應

IMV 的主要不良效應是：

1. **自發呼吸期間呼吸功增加**，歸因於呼吸器管路中的阻力。
2. **心輸出量減少**，主要在左心室功能障礙患者中。

**呼吸功：** 帶有壓力支持的自主呼吸克服了呼吸器管路的額外阻力並降低了呼吸功（18）。因此，在 IMV 期間的自發呼吸週期中，現在常規使用 **10 cm H₂O** 的壓力支持通氣（PSV）。

**心輸出量：** 如第 26 章所述，正壓通氣減少左心室後負荷，可以增加心輸出量。IMV 有相反的效果，在自發呼吸週期增加左心室後負荷，導致左心室功能障礙患者心輸出量減少（20）。

**摘要：** IMV 的主要適應症是輔助-控制通氣期間快速呼吸伴不完全吐氣。IMV 期間的自發呼吸週期促進肺排空，減少空氣滯留和內源性 **PEEP** 的風險。IMV 可以增加呼吸功並損害左心室功能障礙患者的心輸出量；因此，IMV 不建議用於呼吸肌無力或左心衰竭患者。

### 正壓吐氣末壓力

依賴呼吸器的患者通常有氣道阻力增加（例如：由 COPD 引起）或肺順應性降低（例如：由肺實變引起），這兩種情況都促進了小氣道和肺泡在吐氣末的塌陷。這損害了肺部的氣體交換並促進了低血氧。此外，塌陷的空氣腔可以在接下來的肺部充氣中重新打開，小氣道的反覆打開和關閉可以通過產生過度的剪切力來損傷氣道上皮（21）。這種損傷稱為肺泡創傷（atelectrauma）（22），這是呼吸器誘發肺損傷的機制之一，詳見第 24 章。

為對抗肺泡塌陷的趨勢，正壓吐氣末壓力（**PEEP**）在機械通氣期間常規使用。標準做法是從 **5–8 cm H₂O** 的壓力開始，但 **PEEP** 的最佳水平可能因患者而異，見下所述。

#### 最佳 **PEEP**

相對較低水平的 **PEEP**（**5–10 cm H₂O**）可以防止末梢空氣腔塌陷，而較高的 **PEEP** 水平（**10–20 cm H₂O**）可以打開塌陷的空氣腔。後一種效果稱為肺泡復張，它增加了肺部可用於氣體交換摩摣的表面積（23）。然而，較高的 **PEEP** 水平也可能使正常肺部區域的肺泡過度擴張和破裂。這稱為 volutrauma，是呼吸器誘發肺損傷的主要形式（23）。

以下是一些確定 **PEEP** 是否正在促進肺泡復張（有利反應）或促進肺泡過度擴張（不利反應）的方法：

**肺順應性：** 當 **PEEP** 促進肺泡復張時，肺的順應性（順應性）會增加，但當 **PEEP** 使肺泡過度擴張時，肺順應性會減少。因此，監測胸順應性對遞增 **PEEP** 水平的變化可以確定 **PEEP** 是有益還是有害。

**Driving pressure：** 在任何給定的 tidal volume 下，肺順應性是峰值肺泡壓力與 **PEEP** 水平之間差異的函數。這個壓力差異是肺泡擴張的「 driving pressure」，這個壓力的變化可以確定 **PEEP** 是否正在促進肺泡復張或過度擴張。

****PaO₂**/FIO₂ 比：** 當 **PEEP** 促進肺泡復張時，**PaO₂**/FIO₂ 比會增加，但當 **PEEP** 不促進肺泡復張時，**PaO₂**/FIO₂ 比將保持不變或減少。

> **氧氣遞送：** **PEEP** 對动脉氧合的有益效應可能沒有伴隨對組織氧合的類似益處，因為动脉血中 O₂ 遞送速率（DO₂）取決於心輸出量（CO）以及动脉 O₂ 內容物（CaO₂）：
>
> $$D_O_2 = CO \times CaO_2$$
>
> 正壓通氣影響心臟填充的效應在第 26 章中描述，**PEEP** 放大了這些效應（25）。這意味著 **PEEP** 可以減少心輸出量並抵消對动脉氧合的有益效應。因此，**PEEP** 可以促進肺泡復張並增加动脉氧合，但如果 **PEEP** 也減少了心輸出量，系統性 O₂ 遞送可能不會改善。
>
> **PEEP** 對动脉氧合和心輸出量的相反效應強調了在確定「最佳 **PEEP**」時需要包括系統性 O₂ 遞送的測量。由於在心輸出量機械通氣期間不常監測心輸出量，可以使用中心靜脈 O₂ 飽和度作為心輸出量和 O₂ 遞送變化的替代測量，見第 9 章解釋。

### 呼吸器設定

當開始機械通氣時，呼吸治療師會要求以下參數：

1. 通氣模式
2. Tidal volume
3. 呼吸頻率
4. **PEEP** 水平
5. 吸入 O₂ 濃度

以下是設定機械通氣的建議清單。

#### 輔助-控制通氣

1. 選擇輔助-控制作為初始通氣模式。
2. 在輔助-控制模式下呼吸過快的患者可能需要切換到同步 IMV（見前文）。

#### 容積與壓力控制

1. 使用某種形式的容積控制（標準容積控制或壓力調節容積控制）以使用肺保護性通氣，其中 tidal volume 控制是必需的。
2. 如果肺保護性通氣在 ARDS 患者中未能改善氣體交換，考慮切換到「氣道壓力釋放通氣」。

#### Tidal Volume

以下建議來自肺保護性通氣方案，摘要於表 27.1。

1. 使用預測體重選擇初始 tidal volume 為 **8 mL/kg**。（預測體重的公式在表 27.1 中。）
2. 如果可能的話，在接下來的 2 小時內將 tidal volume 降至 **6 mL/kg**。
3. 監測吸氣末肺泡壓力（即 plateau pressure），並保持其≤**30 cm H₂O**（以限制 volutrauma 的風險）。

**表 27.1：肺保護性通氣方案**

| 階段 | 行動 |
|---|---|
| **第一階段** | 1. 計算預測體重（**PBW**）：男性：**PBW** = 50 + [2.3 ×（身高（英寸）– 60）]；女性：**PBW** = 45.5 + [2.3 ×（身高（英寸）– 60）]。 2. 設定 tidal volume（VT）= **8 mL/kg** **PBW**。 3. 設定 **PEEP** = **5 cm H₂O**。 4. 調整 FIO₂ 以維持 **SpO₂** **88–95%**。 5. 每 2 小時將 VT 降低 **1 mL/kg**，直到 VT = **6 mL/kg**。 |
| **第二階段** | 1. 當 VT = **6 mL/kg** 時，測量 plateau pressure（Pplat）。 2. 若 Pplat >**30 cm H₂O**：將 VT 降低 **1 mL/kg**，直到 Pplat **<30** 或 VT = **4 mL/kg**。 |
| **第三階段** | 1. 監測血氣是否有呼吸性酸中毒。 2. 若 pH 7.15–7.30：增加呼吸頻率（RR）直到 pH **>7.30** 或 RR = **35 breaths/min**。 3. 若 pH **<7.15**：將 RR 增加至 **35 breaths/min**；考慮俯臥姿勢或 ECMO。 |

### Bibliography

1. Emerson JH. The evolution of iron lungs. J Respir Care 1955; 52:143–150.
2. Chatburn RL. Fundamentals of Mechanical Ventilation. Cleveland, OH: Med Ed, 2014.
3. The Acute Respiratory Distress Syndrome Network. Ventilation with lower tidal volumes as compared with traditional tidal volumes for acute lung injury and the acute respiratory distress syndrome. N Engl J Med 2000; 342:1301–1308.
4. Petrucci N, De Feo C. Lung protective ventilation strategy for the acute respiratory distress syndrome. Cochrane Database Syst Rev 2013; 2:CD003844.
5. Marini JJ, Crooke PS, Truwit JD. Determinants of plateau pressure in mechanical ventilation. Crit Care Med 1989; 17:12–16.
6. MacIntyre NR. Weaning from mechanical ventilation. Respir Care 2019; 64:712–722.
7. Maeda J, Makino K, Ohta H, et al. Comparison of pressure control and volume control ventilation in patients with acute respiratory failure. J Crit Care 2020; 57:88–94.
8. Guldner A, Brasiliano B, Just I, et al. Pressure-regulated volume control vs. volume control ventilation in healthy and injured lung. J Crit Care 2017; 42:272–280.
9. de Wit M, Miller KB, Green DA, et al. Ineffective triggering predicts ventilator-induced lung injury. Anesthesiology 2007; 107:941–948.
10. Pepe PE, Marini JJ. Occult positive end-expiratory pressure in mechanically ventilated patients with airflow obstruction. Am Rev Respir Dis 1982; 126:166–170.
11. Pesenti A, Rossi A, Aprigliano M, et al. Mean airway pressure. Respir Care 2021; 66:1274–1285.
12. Brown DG, Pierson DJ. Radiographic measurement of thoracic compliance. Respir Care 1986; 31:697–703.
13. Harikumar G, Moxham J, Greenough A. Measurement of tidal volumes and thoracic compliance. Pediatr Pulmonol 2009; 44:1–12.
14. Akaki T, Horie T, Tsujimoto H, et al. Chest wall contribution to tidal volume in mechanically ventilated patients. J Crit Care 2018; 46:45–50.
15. Valenza G, Chevallard G, Porra R, et al. Static and dynamic chest wall mechanics in mechanically ventilated patients. Crit Care Med 2004; 32:1101–1108.
16. de Oliveira LH, Lima CO, Barbosa MF, et al. Patient-ventilator asynchrony and its impact on outcomes. J Crit Care 2021; 62:119–127.
17. Thille AW, Rodriguez P, Cabello B, et al. Patient-ventilator asynchrony during assisted mechanical ventilation. Intensive Care Med 2006; 32:1515–1522.
18. Imsand C, Feihl F, Perret C, Fitting JW. Regulation of inspiratory neuromuscular activity during proportional assist ventilation. Eur Respir J 1994; 7:1782–1790.
19. Pinsky MR. Cardiovascular issues in respiratory care. Chest 2005; 128:592S–597S.
20. Lemaire F, Teboul JL, Cinotti L, et al. Acute left ventricular dysfunction during unsuccessful weaning from mechanical ventilation. Anesthesiology 1988; 69:171–179.
21. Muscedere JG, Mullen JB, Gan K, Slutsky AS. Tidal ventilation at low airway pressures can augment lung injury. Am J Respir Crit Care Med 1994; 149:1327–1334.
22. Slutsky AS, Ranieri VM. Ventilator-induced lung injury. N Engl J Med 2013; 369:2126–2136.
23. Lachmann B. Open up the lung and keep the lung open. Intensive Care Med 1992; 18:319–321.
24. Pintado MC, de Pablo R, Trascasa M, et al. Individualized **PEEP** in ARDS. Crit Care Med 2013; 41:2143–2150.
25. Qvist J, Pontoppidan H, Wilson RS, et al. Hemodynamic responses to mechanical ventilation with **PEEP**. Anesthesiology 1975; 43:61–72.
26. Toth I, Leiner T, Mikor A, et al. Hemodynamic and respiratory changes in patients with ARDS during **PEEP** titration. Chest 2019; 155:1004–1011.
