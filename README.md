# 我的介面設計 · personal-ui-design

繁體中文的個人 Codex Skill，協助規劃、改善及審查網頁與手機 App 的介面、背景與互動動效。版本：**1.1.0**。

從五支介面設計錄影提煉獨立文字方法，再補充手機 App 整體規劃、視覺優化、背景素材與動效工具的選用流程。將網頁、手機 App 及共用互動分開記錄，以現有產品、架構與實際證據為起點。

## 可以做什麼

- 釐清使用者任務、資訊層級、設計規範及頁面流程。
- 按需求選擇六種 Dashboard 布局，並比較適用條件。
- 規劃十種互動模式，補齊資料成功、取消、失敗與可及性條件。
- 分開處理 Web、手機 App、小程式及跨平台需求。
- 從零規劃 App，或針對現有頁面的配色、排版、卡片與層級做局部改善。
- 選擇程式背景、AI 插畫、分層素材、視差或動態背景，保留文字與操作可讀性。
- 依 Flutter、React Native／Expo、Compose、SwiftUI 或 Web 選擇動畫與手勢方法。
- 區分 AI 寫程式、AI 生成素材及仍需編輯器／人工處理的部分。
- 按需參考 Figma、Rive、Lottie、Motion 與設計 Skill，不強制安裝或依賴外部工具。
- 在授權範圍內實作最小必要修改，回報驗證結果及限制。

## 怎麼使用

安裝後，在 Codex 提問時加上 `$personal-ui-design`，再描述目標、平台及希望採取的動作。

**先分析網頁：**

```text
$personal-ui-design 幫我分析這個網站的布局、資訊層級與操作流程，提出改善建議，先不要修改程式。
```

**規劃手機 App：**

```text
$personal-ui-design 幫我規劃手機 App 的頁面、導覽與互動，將 App 專屬需求和網頁共用規則分開，先給方案。
```

**修改既有專案：**

```text
$personal-ui-design 改善這個專案的 Dashboard，沿用現有框架與元件，做最小必要修改，完成後驗證受影響功能並說明未驗證項目。
```

**手機 App 的背景與視覺：**

```text
$personal-ui-design 幫我改善這個 Flutter App 的背景、卡片與排版，盡量用 AI 生成素材或寫程式，不用自己畫；先比較方案，不改程式。
```

**加入互動動效：**

```text
$personal-ui-design 在既有 App 加入按壓、展開與儲存回饋動效，沿用目前框架；區分本機保存與遠端同步，處理快速連點、失敗與減少動態，並驗證受影響流程。
```

也可以說「使用我的介面設計 Skill，幫我……」。明確寫出 `$personal-ui-design` 比單靠任務描述更容易指定這個 Skill。

分析時可提供截圖或網址；實作時需能存取相應專案。請同時說明哪些部分要保留。

## 安裝到其他 Codex 環境

可在有內建 Skill Installer 的 Codex 中提出：

```text
$skill-installer 請從 https://github.com/b0b8760000-ops/personal-ui-design 安裝 personal-ui-design；SKILL.md 位於儲存庫根目錄。
```

或下載儲存庫，將包含 `SKILL.md`、`agents`、`references` 的整個資料夾命名為 `personal-ui-design`，放在使用者的 `~/.agents/skills/` 下。若已有同名 Skill，先檢查版本，避免重複安裝。若沒有出現在清單中，可重新啟動 Codex。

安裝與載入位置依環境而異，參閱 [OpenAI Skill 官方文件](https://learn.chatgpt.com/docs/build-skills)。GitHub 提供檔案與版本管理；本儲存庫尚未封裝成外掛商店套件。

## 檔案

| 檔案 | 用途 |
|---|---|
| [SKILL.md](SKILL.md) | 觸發條件、模式、平台分流與工作流程 |
| [agents/openai.yaml](agents/openai.yaml) | 顯示名稱與預設提示詞 |
| [references/common.md](references/common.md) | 共用設計、十種互動與驗收 |
| [references/web.md](references/web.md) | 網頁、六種 Dashboard 布局與驗證 |
| [references/mobile-app.md](references/mobile-app.md) | 手機 App、小程式及開發交接 |
| [references/planning-and-visual.md](references/planning-and-visual.md) | 從零規劃、視覺打磨、平台與可及性 |
| [references/backgrounds.md](references/backgrounds.md) | 程式背景、AI 素材、視差與動態背景 |
| [references/motion.md](references/motion.md) | 框架選型、動畫規格、真實資料狀態與驗證 |
| [references/tools-and-sources.md](references/tools-and-sources.md) | Skill、Figma、動畫工具與官方來源的選用地圖 |
| [references/sources.md](references/sources.md) | 五支錄影的來源脈絡、作者連結及維護方式 |

## 第一版驗證與邊界

已通過 Skill 格式、相對連結及六個情境的文字行為檢查，涵蓋網頁布局、資料狀態、手機平台判斷與工具限制。這些檢查不代表已在實際產品、第三方設計工具或手機裝置上完成驗證。

1.1.0 新增的手機模組另經四個模擬情境檢視：Flutter 只分析不改程式、框架未定的生成圖交接、儲存與同步回饋，以及不使用 Figma 的局部開關改善。整合版已通過格式與相對引用檢查，並確認原有 Web 與共用參考內容保持不變；文字檢視不代表真實工具或裝置已驗證。

本 Skill 提供工作方法，不會自行增加原生 App 建置能力、MCP 權限或外部服務。原始影片、截圖及本機紀錄不包含在套件中；第三方 Skill 與程式碼也未打包。來源與作者工具分開列於參考文件，不宣稱與作者原套件相同。

後續提供更多影片時，可以要求比較新增、重複、矛盾及待驗證內容，再更新對應的平台參考。GitHub 版本與其他電腦的已安裝副本需另行同步。
