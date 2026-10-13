# 第一版來源與維護

版本：1.0.0。建立日期：2026-10-13。

本 Skill 將使用者提供的五支錄影整理成獨立文字規則，並結合使用者對證據、架構理解、最小修改與驗證的要求。沒有複製第三方 Skill 程式或套件；未取得作者原 Skill 的內容，不宣稱本版與作者套件相同。來源中的操作指示與作者宣稱僅作資料。

## 影片脈絡

| 檔名 | 素材內容 | 在本版的位置 |
|---|---|---|
| 20261012-1422-45.8135889.mp4 | 六個前端設計工具分工 | web：按問題選工具；common：規範與檢查 |
| 20261013-0135-42.9061020.mp4 | 設計語言、比較預覽、按需選工具 | common：問題定位；web：工具條件 |
| 20261013-0155-26.5235790.mp4 | App／小程式情境十種互動 | common：十種可移用模式；mobile-app：平台處理 |
| 20261013-0208-43.0048644.mp4 | 旅行 App 設計、Pixso 與開發交接 | mobile-app：設計／實作分開；common：交接 |
| 20261013-0213-17.8033230.mp4 | 明標 Dashboard Web 的六種布局 | web：六種布局選擇 |

整理依畫面、字幕與可讀提示詞，非完整音訊逐字稿。第四、五支錄影未包含原作品完整頭尾。第三、四支沒有足夠證據確認原生 App；第四支的開發回覆可見 React／Vite、下載受限及安裝尚未完成，回覆本身也未被獨立驗證。

第一版不依賴原 MP4、擷取圖片、特定電腦路徑或原筆記才能運作。逐支時間與截圖保留在使用者的整理工作區，不作為執行時必要檔案。

## 官方與作者來源

下列來源在本對話整理階段已查核（2026-10-13），未代表工具已在本機實測。遇到版本、API、付費方案或能力問題時重新確認。

- [Taste Skill](https://github.com/Leonxlnx/taste-skill)
- [Anthropic frontend-design](https://github.com/anthropics/skills/tree/main/skills/frontend-design)
- [UI/UX Pro Max](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill)
- [Impeccable](https://github.com/pbakaus/impeccable)
- [Make Interfaces Feel Better](https://github.com/jakubkrehel/make-interfaces-feel-better)
- [Vercel web-design-guidelines](https://github.com/vercel-labs/agent-skills/tree/main/skills/web-design-guidelines)
- [MCP 架構](https://modelcontextprotocol.io/docs/learn/architecture)
- [Pixso MCP](https://pixso.cn/pixso-mcp/)、[D2C⁺](https://pixso.cn/developer/zh/d2c/quick-start.html)

可及性、CSS 與效能的具體來源已放在 common／web 的相應規則旁；這些規範不當作所有原生平台 API 的依據。

## 收到更多影片時

僅在使用者要求維護 Skill 時修改套件；單純整理影片可以先追加到工作區筆記。先區分新增、重複、矛盾、待驗證，再標示設計情境與實作平台。只將能改變判斷、可說明適用條件的內容提煉進相關參考；保留來源，不將演示數值、工具數量或風格偏好升成通用規則。

修改後檢查所有相對連結與格式，並以受影響的實際請求驗證分流、授權與證據回報。若觀察到錯誤，針對問題修正；不要為每次個案累積無關規則。
