# 網頁介面與 Dashboard

適用於網站、後台、Dashboard、行動網頁及瀏覽器中的前端。先辨識目前框架、設計系統、資料與元件，不為套用本 Skill 改用另一套技術。

## 六種 Dashboard 布局參考

這六種取自第五支明標 `DASHBOARD · WEB` 的影片，為使用者素材分類，不是所有 Dashboard 的唯一標準分類。

| 模式 | 適合的任務 | 邊界與需驗證的地方 |
|---|---|---|
| 主次布局／Hero Module | 一個核心指標或趨勢決定主要判斷 | 期間、單位、比較基準與重要性清楚；不只放大數字 |
| 橫帶分層／Stacked Bands | 概覽 → 趨勢 → 明細的追查 | 按閱讀順序分層，避免每張卡片同等重要 |
| 主區加側欄／Main + Aside | 主要任務旁持續保留提醒與輔助資訊 | 定義捲動容器及側欄行為；窄視窗重排／收合、不遮內容 |
| 全幅畫布＋浮動面板／Full-bleed Canvas + Floating Panels | 地圖、空間或圖像本身是主要工作內容 | 面板不遮關鍵位置，文字可讀，必要時可收合／調整 |
| 看板分列／Kanban Columns | 管理工作狀態與跨狀態移動 | 列名與數量清楚，移動更新資料，失敗恢復，提供點按移動方式 |
| 時間軸泳道／Timeline Swimlanes | 排程、資源占用、時間起訖與重疊 | 時間尺度、資源、時區依需求明確；時間重疊不必然是業務衝突 |

可有目的地組合：設備總覽可用主次或橫帶分層，再評估提醒側欄。只在需要工作狀態或排程時加入看板或泳道；不用為了湊足六種而堆疊。

影片示例中的欄數、側欄寬、間距與面板距邊數值不作為預設規範；根據內容、現有設計系統及實際視窗決定。

## 網頁實作與驗證

- `position: sticky` 受捲動祖先、容器及定位門檻影響；與 `fixed` 分清。它不會自動建立「只有主區捲動」。有問題時檢查實際容器與 overflow，再決定修法。[MDN position](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference/Properties/position)
- 檢查窄視窗、放大、文字重排與長內容；不要將整個固定畫布等比縮小當成已完成響應式。必要的地圖、資料表等二維內容可有 Reflow 例外，例外不能擴張到無關文字與控制項。[W3C Reflow](https://www.w3.org/WAI/WCAG22/Understanding/reflow.html)
- 檢查連結／按鈕是否實際操作、表單狀態、鍵盤、焦點與拖曳的點按替代。公開內容有搜尋需求時再處理 SEO。
- 減少動態可查 `prefers-reduced-motion`；不要因此宣稱原生 App 已支援相同設定。[MDN prefers-reduced-motion](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference/At-rules/@media/prefers-reduced-motion)
- 動畫可優先評估 transform／opacity，但需看實際布局與重繪；文字展開不可只縮放內容代替占位。低效能環境、長清單及連續操作需視變更實測。[web.dev 動畫效能](https://web.dev/articles/animations-guide)
- 程式審查、瀏覽器操作、建置成功與真實 API 串接分別回報。沒有執行工具時，不能宣稱實測通過。

## 第一、二支的工具分工啟發

本 Skill 使用獨立改寫的原則，沒有內建這些第三方工具。需要使用時先確認安裝、文件、能力及授權；不需要時可直接依原則分析。

| 工具 | 參考用途 |
|---|---|
| Taste Skill | 依任務選擇風格、改版或參考圖方向 |
| frontend-design | 根據內容與任務探索視覺方向 |
| UI/UX Pro Max | 建立字體、色彩、間距及元件規範 |
| Impeccable | 先評估，再按問題收斂、加強、調整字體或審查 |
| Make Interfaces Feel Better | 打磨對齊、換行、數字、陰影與互動細節 |
| web-design-guidelines | 檢查具體前端檔案與問題位置 |

Live Mode、hooks、上線阻擋、參考圖生成或來源寫回各有工具與環境條件；不能把影片演示或命令名稱當成當下可用能力。不固定影片時點的工具數量，也不要求全部執行。作者來源見 [來源與維護](sources.md)。
