# 第二大腦 Starter / Second Brain Starter

Obsidian vault template: **PARA** for action, **Zettelkasten** for lasting notes. Open this folder in Cursor and the agent follows `AGENTS.md`.

[English summary](#english-summary) · [About BB Studio](#about-bb-studio) · [Full English README](README.en.md) · Chinese follows below.

---

## English summary

This is a **starter Obsidian vault**, not an app. Clone or use it as a GitHub **template**, then write your own notes.

| Folder | Use it for |
|--------|------------|
| `0-Inbox` | Quick capture. Empty it weekly. |
| `1-Projects` | Goals with an end date. Archive when done. |
| `2-Areas` | Ongoing responsibilities (health, money, a craft). |
| `3-Resources` | Reference material and reading notes. |
| `4-Archives` | Finished or inactive items. |
| `5-Zettelkasten` | One idea per note, in your own words, linked with `[[wikilinks]]`. |
| `6-DailyNotes` | `YYYY-MM-DD.md` daily notes. |
| `7-Templates` | Daily, Inbox, Zettel, project, and weekly-inbox templates. |

**Day one:** Obsidian → Open folder as vault → this repo root. Enable **Templates** (`7-Templates`) and **Daily notes** (`6-DailyNotes`, template `7-Templates/DailyNoteTemplate.md`). Cursor already has `AGENTS.md`, `.cursor/rules/`, and the Obsidian Markdown skill.

**Do not put private notes in a public fork.** Click **Use this template**, then keep *your* vault **Private** if it may contain sensitive content. License: [MIT](LICENSE). Bundled community plugins: [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md).

### About BB Studio

Soul partners × business experiments — turning warm trust into products that actually run.

BB Studio is co-named by two engineers — a workspace where we experiment with a "solo company × partnership" model.

We don't build bloated all-in-one platforms. We focus on real scenarios and ship small, deliverable tools and services where data stays in the user's hands.

**What we believe**

- **Sell outcomes, not generic bots** — clients want their time back and their schedules handled, not another dashboard to learn.
- **Works offline too** — not every team can or should put their data in the cloud; we respect data sovereignty.

**How we work**

We prefer: small pilot → interview-driven packaging → a runnable MVP — not selling a massive blueprint upfront.

Built with care — leave the complexity to the system, return calm to the user.

---

# 第二大腦 Starter（PARA + Zettelkasten）

這是一份 **Obsidian 筆記庫範本**：用 **PARA** 管行動，用 **Zettelkasten** 留長期知識。用 Cursor 開啟本資料夾後，Agent 會依根目錄 `AGENTS.md` 協助寫筆記。

---

## 怎麼取得這份範本

1. 在 GitHub 按 **Use this template** 開自己的倉庫（不要直接往本倉庫推你的日記）。
2. `git clone` 你的倉庫，用 Obsidian **Open folder as vault** 開啟根目錄。
3. 筆記若可能含敏感內容，請把**你的倉庫**設為 **Private**。

授權：[MIT](LICENSE)。內附社群外掛聲明：[THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md)。

---

## 目錄怎麼用？

1. **`0-Inbox`（快速收集）**  
   靈感、書籤、文章重點先丟這裡；這是暫存區，**每週**清空並分類。步驟見 [WeeklyInboxRitual.md](7-Templates/WeeklyInboxRitual.md)。

2. **`1-Projects`（專案）**  
   有明確目標與截止日的任務。結案後移到 `4-Archives`。

3. **`2-Areas`（領域）**  
   需長期維護、沒有單一截止日的重心（健康、理財、某領域能力等）。

4. **`3-Resources`（資源）**  
   主題式參考資料（教學、閱讀筆記、素材等）。

5. **`4-Archives`（檔案庫）**  
   已結束的專案、不再關注的領域／資源，移出日常視線但保留可查。

6. **`5-Zettelkasten`（永久筆記）**  
   用自己的話寫、**一則一概念**，並用 `[[雙向連結]]` 與其他卡片串起來；避免整篇複製貼上網文。

7. **`6-DailyNotes`（每日筆記）**  
   當日行事與狀態。可連回 `1-Projects` 與 `5-Zettelkasten`。

8. **`7-Templates`（範本）**  
   Daily、Inbox、Zettel、專案、每週 Inbox 儀式等。

**分類不確定** → 先放 `0-Inbox`。

---

## 第一天：Obsidian 設定

1. **Open folder as vault**，選本倉庫根目錄。

2. **設定 → 核心外掛**
   - 開啟 **Templates**
     - *Template folder location* → `7-Templates`
   - 開啟 **Daily notes**
     - *New file location* → `6-DailyNotes`
     - *Template file location* → `7-Templates/DailyNoteTemplate.md`

3. **開始寫**
   - 日記：側欄日曆或 Open today's daily note（若已安裝 Calendar）。
   - 範本：`Cmd/Ctrl + P` → `Insert template`。

精簡入口：[如何開始使用.md](如何開始使用.md) · English: [Getting Started.md](Getting%20Started.md)

---

## 第一天：Cursor（已預裝）

本 starter 已包含：

- 根目錄 `AGENTS.md`
- `.cursor/rules/second-brain-vault.mdc`
- `.cursor/skills/obsidian-markdown/`

用 Cursor **Open Folder** 開啟 vault 根目錄即可。安裝說明見 [README-安裝到Cursor.md](7-Templates/SecondBrainStarter_Cursor/README-安裝到Cursor.md)。

---

## 每週 Inbox 儀式（約 15 分鐘）

固定每週同一時段整理 `0-Inbox`，依 PARA 決定歸宿，並在當週 Daily 留一行紀錄。

完整步驟：[WeeklyInboxRitual.md](7-Templates/WeeklyInboxRitual.md)。

---

## 換新電腦

1. 安裝 [Obsidian](https://obsidian.md/) 與 [Git](https://git-scm.com/)。
2. `git clone` **你的**倉庫，再用 Obsidian **Open folder as vault** 開啟根目錄。
3. 依上文檢查 Templates 與 Daily notes 路徑。
4. 日常可選：寫筆記前 `git pull`；告一段落再 `commit`／`push`。
5. **隱私**：含敏感內容時請用 **Private** 倉庫，不要 push 回這個公開 template。

---

## 在 iPhone 上

手機與電腦必須是**同一份檔案**，擇一同步：

| 方式 | 說明 |
|------|------|
| **Obsidian Sync** | 官方付費，最省事。 |
| **iCloud Drive** | 整個 vault 放在同一 iCloud 資料夾，兩端都從該資料夾開啟。 |
| **Git** | 手機用 Working Copy 等工具 clone／pull／push，門檻較高。 |

不要在尚未同步完成時，於兩台裝置同時大改同一則筆記。

---

## 長期專案（可選三層）

有明確目標、要長期記數字或儀表板時：

| 層 | 放什麼 | 範本 |
|----|--------|------|
| 主計畫 | 目標、階段、原則 | [LongTermProjectPlanTemplate.md](7-Templates/LongTermProjectPlanTemplate.md) |
| 追蹤表 | 逐日格線、月度紀錄 | [LongTermProjectDashboardTemplate.md](7-Templates/LongTermProjectDashboardTemplate.md) |
| 每日筆記 | 當天數據與體感 | `6-DailyNotes/YYYY-MM-DD.md` |

技術／心法類永久筆記仍放 `5-Zettelkasten`，由專案與 Daily 連過去即可。

---

## 心法

- **不要有分類焦慮**：不確定就先放 `0-Inbox`。
- **Zettelkasten**：一則一概念、自己重述；連結比資料夾更重要。
- **定期回顧**：每週 15 分鐘，見 [WeeklyInboxRitual.md](7-Templates/WeeklyInboxRitual.md)。

---

## 關於 BB Studio

靈魂夥伴 × 商業實驗 — 把溫暖的信任，做成真正能跑的產品。

BB Studio 由兩位工程師共同命名：一個實驗「一人公司 × 夥伴關係」的工作空間。

我們不做臃腫的大而全平台。我們聚焦真實場景，交付小型、可落地的工具與服務，資料留在使用者手中。

**我們相信什麼**

- **賣成果，不是賣通用機器人** — 客戶要的是把時間要回來、把行程處理好，不是再學一塊儀表板。
- **離線也能用** — 不是每個團隊都能或都該把資料放上雲端；我們尊重資料主權。

**我們怎麼做**

我們偏好：小規模試點 → 用訪談包裝 → 做出可跑的 MVP — 而不是先賣一份巨大藍圖。

認真做 — 把複雜留給系統，把從容還給使用者。
