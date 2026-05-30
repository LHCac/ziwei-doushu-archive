# 紫微斗數資料庫｜Ziwei Doushu Archive

這個資料庫用來整理紫微斗數學習資料、書籍筆記、網路文章筆記、流年四化、星曜補充、解盤模板與未來實戰案例。

目前資料來源包含：

1. 《學會看流年：用紫微斗數看懂自己的流年運勢》相關學習資料。
2. 使用者提供的網路文章內容與文章作者補充筆記。
3. 使用者後續實戰解盤資料與案例紀錄。

> 重要提醒：本資料庫以「學習、整理、比對、實戰輔助」為目的。命理內容不可作為醫療、法律、投資或人生重大決策的唯一依據。

---

## 目前整理進度

| 區塊 | 狀態 | 說明 |
|---|---|---|
| 十天干四化 | 已完成第一版 | 甲、乙、丙、丁、戊、己、庚、辛、壬、癸皆已整理 |
| 十四主星補充 | 已完成第一版 | 紫微、天機、太陽、武曲、天同、廉貞、天府、太陰、貪狼、巨門、天相、天梁、七殺、破軍 |
| 輔星、煞星、雜曜 | 已完成第一版 | 昌曲、輔弼、羊陀、火鈴、祿存、魁鉞、天刑、天姚、天馬、空劫、哭虛、天空、鸞喜、孤寡、華蓋、陰煞等 |
| 流年分析 SOP | 已建立 | 以「祿羊陀 → 四化 → 疊宮」作為流年分析主軸 |
| 2026 丙午年資料 | 待查證中 | 丙年四化已確認為天同化祿、天機化權、文昌化科、廉貞化忌，但祿羊陀、紅鸞天喜、流月等仍需查證 |
| 實戰案例 | 尚未正式開始 | 之後若做案例，需匿名化處理 |

---

## 資料夾結構

```text
ziwei-doushu-archive/
├── README.md
├── 00-source-log/
│   └── batch-001-uploaded-pdfs.md
├── 01-basic-concepts/
│   └── 00-overview.md
├── 02-flow-year/
│   ├── liunian-sop.md
│   ├── jia-year-sihua-online-notes.md
│   ├── yi-year-sihua-online-notes.md
│   ├── bing-year-sihua-online-notes.md
│   ├── ding-year-sihua-online-notes.md
│   ├── wu-year-sihua-online-notes.md
│   ├── ji-year-sihua-online-notes.md
│   ├── geng-year-sihua-online-notes.md
│   ├── xin-year-sihua-online-notes.md
│   ├── ren-year-sihua-online-notes.md
│   └── gui-year-sihua-online-notes.md
├── 03-star-notes/
│   ├── article-owner-supplement-001-ziwei-tianji-taiyang-wuqu-tiandong.md
│   └── article-owner-supplement-002-lianzhen-tianfu-taiyin-tanlang-jumen-tianxiang-tianliang-qisha-pojun.md
├── 04-auxiliary-stars/
│   └── article-owner-supplement-001-changqu-fubi-sha-lucun-kuiyue-xingyao-tianma-kongjie-minor-stars.md
├── 04-templates/
│   ├── claude-organize-prompt.md
│   ├── learning-note-template.md
│   └── case-record-template.md
├── 05-cases/
│   └── README.md
└── 99-questions/
    ├── unclear-concepts.md
    └── 2026-bingwu-verification-checklist.md
```

---

## 快速查找

### 1. 查「某一年四化」

請到：

```text
02-flow-year/
```

對照檔案如下：

| 天干 | 四化 | 檔案 |
|---|---|---|
| 甲 | 廉貞化祿、破軍化權、武曲化科、太陽化忌 | `jia-year-sihua-online-notes.md` |
| 乙 | 天機化祿、天梁化權、紫微化科、太陰化忌 | `yi-year-sihua-online-notes.md` |
| 丙 | 天同化祿、天機化權、文昌化科、廉貞化忌 | `bing-year-sihua-online-notes.md` |
| 丁 | 太陰化祿、天同化權、天機化科、巨門化忌 | `ding-year-sihua-online-notes.md` |
| 戊 | 貪狼化祿、太陰化權、右弼化科、天機化忌 | `wu-year-sihua-online-notes.md` |
| 己 | 武曲化祿、貪狼化權、天梁化科、文曲化忌 | `ji-year-sihua-online-notes.md` |
| 庚 | 太陽化祿、武曲化權、太陰化科、天同化忌 | `geng-year-sihua-online-notes.md` |
| 辛 | 巨門化祿、太陽化權、文曲化科、文昌化忌 | `xin-year-sihua-online-notes.md` |
| 壬 | 天梁化祿、紫微化權、左輔化科、武曲化忌 | `ren-year-sihua-online-notes.md` |
| 癸 | 破軍化祿、巨門化權、太陰化科、貪狼化忌 | `gui-year-sihua-online-notes.md` |

---

### 2. 查「2026 丙午年」

優先看：

```text
02-flow-year/bing-year-sihua-online-notes.md
99-questions/2026-bingwu-verification-checklist.md
```

2026 丙午年的四化主軸：

```text
天同化祿：享受、福氣、安逸、精神與物質滿足
天機化權：主動、策畫、變動、謀略與行動力
文昌化科：文書、考試、作品、名聲、表達被看見
廉貞化忌：情緒結、感情糾葛、規範、法律與人際壓力
```

待查證項目：

```text
丙午年祿存、擎羊、陀羅位置
2026 流年命宮
2026 紅鸞、天喜
2026 流月盤
十四主星 2026 年流年解讀
```

---

### 3. 查「十四主星」

請到：

```text
03-star-notes/
```

目前分成兩份：

```text
article-owner-supplement-001-ziwei-tianji-taiyang-wuqu-tiandong.md
article-owner-supplement-002-lianzhen-tianfu-taiyin-tanlang-jumen-tianxiang-tianliang-qisha-pojun.md
```

第一份包含：

```text
紫微、天機、太陽、武曲、天同
```

第二份包含：

```text
廉貞、天府、太陰、貪狼、巨門、天相、天梁、七殺、破軍
```

---

### 4. 查「輔星、煞星、雜曜」

請到：

```text
04-auxiliary-stars/
```

目前主要檔案：

```text
article-owner-supplement-001-changqu-fubi-sha-lucun-kuiyue-xingyao-tianma-kongjie-minor-stars.md
```

包含：

```text
文昌、文曲
左輔、右弼
擎羊、陀羅
火星、鈴星
祿存
天魁、天鉞
天刑、天姚
天馬
地空、地劫
天哭、天虛
天空
紅鸞、天喜
台輔、封誥
孤辰、寡宿
華蓋
陰煞
```

---

## 學習主線

### 第一階段：基礎星曜

先讀：

```text
03-star-notes/
04-auxiliary-stars/
```

目標：先知道每顆星的「本性」。

例如：

```text
紫微：領導、中心、帝座
天機：腦力、計畫、變動
太陽：光明、公開、父親、男性、名聲
武曲：財星、執行、正財、規則
天同：福星、享受、協調、童心
貪狼：慾望、才藝、人脈、桃花
巨門：口才、是非、分析、靠嘴生財
破軍：破耗、改革、變動、投入
```

---

### 第二階段：十天干四化

再讀：

```text
02-flow-year/*-year-sihua-online-notes.md
```

目標：知道每一年四化會刺激哪些星曜。

例如：

```text
2023 癸卯年：破軍化祿、巨門化權、太陰化科、貪狼化忌
2026 丙午年：天同化祿、天機化權、文昌化科、廉貞化忌
```

---

### 第三階段：流年分析 SOP

核心檔案：

```text
02-flow-year/liunian-sop.md
```

目前採用的流年分析順序：

```text
1. 祿羊陀
2. 四化
3. 疊宮
```

白話說：

```text
祿存：機會、資源、財祿
擎羊：明顯風險、衝突、外傷、突破
陀羅：暗中阻力、拖延、內耗
四化：流年刺激與事件方向
疊宮：看流年宮位疊回本命哪個人生領域
```

---

### 第四階段：實戰案例

未來放在：

```text
05-cases/
```

實戰案例必須匿名化，不放完整個資。

建議案例格式：

```text
1. 問題背景
2. 命盤資料確認
3. 本命盤重點
4. 大限背景
5. 流年四化
6. 祿羊陀
7. 流年宮位疊本命宮位
8. 風險提醒
9. 具體行動建議
10. 事後驗證
```

---

## 新增資料流程

### 書籍或掃描資料

```text
1. 先把書本圖片、掃描 PDF 或文字丟給 Claude 初步整理。
2. 請 Claude 分成：固定理論、舊年份範例、當前年份待查證資料。
3. 把 Claude 整理後的 Markdown 貼回 ChatGPT。
4. 由 ChatGPT 協助分類、改寫、建立索引並放入 GitHub。
5. 涉及年份轉換、四化、祿羊陀、流月時，一律標註待查證。
```

### 網路文章資料

```text
1. 保留原始日期、標題、來源網址或作者。
2. 不直接當作定論，先標註為「網路資料」或「作者補充」。
3. 強烈斷語改成現代化風險提醒。
4. 與書本、其他派別或正式四化表交叉比對。
```

### 實戰案例資料

```text
1. 移除真實姓名、電話、地址、身分證、完整生日等敏感資料。
2. 保留問題類型與必要命盤資訊。
3. 結論以「傾向、風險、建議」表達，不做恐嚇式斷語。
4. 事後若有驗證結果，可補充到案例末尾。
```

---

## 寫作與解盤原則

### 1. 不直接恐嚇式斷語

原文若出現：

```text
凶死、入監、風塵、刑剋、血光、墮胎、疾病、災厄
```

統一改成：

```text
交通與安全風險
法律、合約與規則風險
感情界線與人際風險
健康檢查與身心壓力提醒
生育與子女宮需合參
財務與投資保守建議
```

---

### 2. 不單星斷事

不可只看到一顆星就下結論。

至少要合參：

```text
本命宮位
三方四正
四化
祿羊陀
大限
流年
流月
實際問題背景
```

---

### 3. 舊年份資料不可直接套到新年份

例如：

```text
2023 癸卯年資料不能直接套到 2026 丙午年。
```

應先轉換：

```text
2023 癸年四化：破軍、巨門、太陰、貪狼
2026 丙年四化：天同、天機、文昌、廉貞
```

---

### 4. 實戰分析要給具體建議

不要只說吉凶，要落到行動：

```text
適合做什麼
要避開什麼
哪裡要保守
哪裡可主動
哪個月要觀察
哪類人事物要注意
```

---

## 待建立檔案

之後可再補：

```text
02-flow-year/sihua-overview.md
03-star-notes/14-major-stars-overview.md
04-auxiliary-stars/auxiliary-stars-overview.md
05-cases/case-record-template.md
99-questions/source-verification-list.md
```

---

## 專案目標

這個資料庫的最終目標不是只收資料，而是建立一套可以實戰使用的紫微斗數工作流：

```text
資料收集 → 分類整理 → 查證校對 → 建立查表 → 建立解盤 SOP → 實戰案例 → 事後驗證 → 修正資料庫
```

未來分析流年時，優先按照以下邏輯：

```text
先看問題背景
再看本命盤核心
再看大限背景
再看流年祿羊陀
再看流年四化
再做疊宮
最後給行動建議
```
