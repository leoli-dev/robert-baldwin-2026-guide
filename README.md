# Robert-Baldwin 2026 · 省選一頁通 / Le guide / The guide

> 2026 年魁北克省選(10 月 5 日)**Robert-Baldwin 選區**七位候選人嘅獨立資料頁。
> An independent, unofficial one-page guide to the seven candidates in the Robert-Baldwin electoral district — Québec general election, October 5, 2026.

🔗 **線上版 / Live site:** https://leoli-dev.github.io/robert-baldwin-2026-guide/

---

## 繁體粵語

呢個係為自己社區整嘅**非官方、獨立**投票資料頁,幫街坊喺投票前快速睇清楚:

- 今次省選選乜、幾時投票
- Robert-Baldwin 選區範圍同地圖
- 選區人口組成
- 七位候選人嘅背景同政綱
- 有來源嘅公開紀錄核查
- 所有資料來源連結

**唔會替你決定投邊個**,只係提供有來源嘅資料畀你自己比較。

### 語言

頁面右上角可以即時切換四種語言:

| 語言 | 代碼 |
| --- | --- |
| Français | `fr` |
| English | `en` |
| 简体中文 | `zh-Hans` |
| 繁體粵語 | `yue-Hant` |

### 投票資料

投票地點要按你自己嘅住址查,請以官方資料為準:
[Élections Québec — Où et quand voter](https://www.electionsquebec.qc.ca/voter/ou-et-quand-voter/)

## English

An independent, unofficial reference page made for my own community. It covers the election, the district and its map, population, the seven candidates (background and platforms), a source-based public-record review, and a full source list. It does **not** recommend whom to vote for.

- Four languages, switchable in the page: Français · English · 简体中文 · 繁體粵語
- Your polling place depends on your address — use the official lookup: [Élections Québec](https://www.electionsquebec.qc.ca/voter/ou-et-quand-voter/)

## 技術說明 / Technical notes

- 單一檔案 `index.html`:純 HTML + CSS + JavaScript,冇 build step、冇後端、冇追蹤。
- Single static file — no build step, no backend, no analytics.
- 候選人相片同黨徽係由原本公開來源載入(遠端圖片),要上網先睇到。
- Candidate photos and party logos are loaded remotely from their original public sources, so they need a network connection.
- 頁面冇收集任何個人資料,亦冇包含任何人嘅私人地址。

### 本地預覽 / Run locally

```bash
git clone https://github.com/leoli-dev/robert-baldwin-2026-guide.git
cd robert-baldwin-2026-guide
open index.html          # macOS;或用任何瀏覽器開啟
# 或 / or
python3 -m http.server 8000
```

### 更新內容 / Updating

直接修改 `index.html`,push 去 `main`,GitHub Pages 會自動重新發布(通常 1–2 分鐘)。

## 免責聲明 / Disclaimer

- 本頁為個人獨立整理,**與 Élections Québec、任何政黨或候選人均無關係**。
- 資料核查日期:2026 年 10 月 4 日。如有出入,一律以官方來源為準。
- 候選人相片、黨徽及引用內容之版權屬原權利人所有,此處僅作資訊及評論用途。如權利人要求移除,請開 issue。
- This page is not affiliated with Élections Québec, any political party, or any candidate. Always verify against official sources.
- Photos, logos and quoted material remain the property of their respective owners and are used here for informational purposes. Open an issue to request removal.

## 反饋 / Feedback

發現錯漏?歡迎開 [issue](../../issues) 指正。
Spotted an error? Please [open an issue](../../issues).
