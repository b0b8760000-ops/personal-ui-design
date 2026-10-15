# 我的介面設計 · personal-ui-design

繁體中文的個人 Codex Skill，僅用免費設計資源，協助規劃、改善及審查網頁與手機 App 的介面、背景與互動動效。版本：**1.2.0**。

從五支介面設計錄影提煉獨立文字方法，再補充手機 App 整體規劃、視覺優化、背景素材與動效工具的選用流程。將網頁、手機 App 及共用互動分開記錄，以現有產品、架構與實際證據為起點。

## 可以做什麼

- 釐清使用者任務、資訊層級、設計規範及頁面流程。
- 按需求選擇六種 Dashboard 布局，並比較適用條件。
- 規劃十種互動模式，補齊資料成功、取消、失敗與可及性條件。
- 分開處理 Web、手機 App、小程式及跨平台需求。
- 從零規劃 App，或針對現有頁面的配色、排版、卡片與層級做局部改善。
- 選擇程式背景、免費授權插畫、分層素材、視差或動態背景，保留文字與操作可讀性。
- 依 Flutter、React Native／Expo、Compose、SwiftUI 或 Web 選擇動畫與手勢方法。
- 由目前助手協助寫程式、SVG 與動效；不因此新增計費生成服務。
- 按需選用已確認免費的開源設計 Skill、框架動畫、Motion 套件與 Lottie 播放器；素材授權另查，不強制安裝工具。
- 在授權範圍內實作最小必要修改，回報驗證結果及限制。

## 免費範圍

本版不推薦付費工具、課程、素材、訂閱、按量計費 API、限時試用或用完需付款的點數。費用或匯出條件不明就略過，改用本機程式原型、框架內建功能與自有素材。開源工具只選列明的開源版本，不延伸到同品牌的商業服務；免費依據與授權見 [免費工具與來源](references/tools-and-sources.md)。

Designeer 只作免費瀏覽的資源目錄，連出的工具與素材逐一核對，不把整站資源視為免費。本 Skill 所選方法不需新增付款，不代表承載它的 AI 助手、既有帳號或硬體全部免費，也不會為了完成設計要求購買硬體、算力或上架服務。

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
$personal-ui-design 幫我改善這個 Flutter App 的背景、卡片與排版，只用免費資源；優先寫程式或 SVG，不用自己畫，不呼叫計費生圖服務。先比較方案，不改程式。
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
| [references/backgrounds.md](references/backgrounds.md) | 程式背景、免費授權素材、視差與動態背景 |
| [references/motion.md](references/motion.md) | 框架選型、動畫規格、真實資料狀態與驗證 |
| [references/tools-and-sources.md](references/tools-and-sources.md) | 免費工具清單、授權依據與 Designeer 篩選規則 |
| [references/sources.md](references/sources.md) | 五支錄影的來源脈絡、作者連結及維護方式 |

## 第一版驗證與邊界

已通過 Skill 格式、相對連結及六個情境的文字行為檢查，涵蓋網頁布局、資料狀態、手機平台判斷與工具限制。這些檢查不代表已在實際產品、第三方設計工具或手機裝置上完成驗證。

1.1.0 新增的手機模組另經四個模擬情境檢視：Flutter 只分析不改程式、框架未定的生成圖交接、儲存與同步回饋，以及不使用外部設計工具的局部開關改善。該版通過格式與相對引用檢查，原有 Web 與共用參考內容保持不變；文字檢視不代表真實工具或裝置已驗證。

本 Skill 提供工作方法，不會自行增加原生 App 建置能力、MCP 權限或外部服務。原始影片、截圖及本機紀錄不包含在套件中；第三方 Skill 與程式碼也未打包。來源與作者工具分開列於參考文件，不宣稱與作者原套件相同。

1.2.0 將所有工作流程改為免費限定，移除商業設計／生成／動畫服務與免費條件未核實的推薦；保留原有頁面規劃、Dashboard、十種互動與資料驗證方法。通過格式、相對引用及三個文字情境審查：沒有本機生圖環境、免費預覽與素材商用權的區分，以及保留既有依賴的局部修改。工具授權已查核，實際 App 與裝置效果仍需在對應專案驗證。

後續提供更多影片時，可以要求比較新增、重複、矛盾及待驗證內容，再更新對應的平台參考；新增內容同樣適用免費限定。GitHub 版本與其他電腦的已安裝副本需另行同步。
