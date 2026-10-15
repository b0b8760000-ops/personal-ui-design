# 工具選用與來源

這是選用地圖，不是已安裝清單。名稱、路徑、帳號連線、方案、功能旗標與 API 會變動；使用時檢查當下 Skill 目錄、工具與官方文件。不要把 2026-10-15 的查核快照當未來可用保證。

本 Skill 以自行整理的方法為主，不複製或內嵌第三方完整 Skill、執行檔或素材。需要其他 Skill 時讀取其現行原檔並遵循適用規範；不要複製舊命令或一併套用無關流程。

## 選用地圖

| 需求 | 候選 | 邊界 |
|---|---|---|
| 通用介面分析與平台判斷 | 本 Skill 的共用、Web 與手機 App 參考 | 同一入口按需選模組，不重跑多套相同流程 |
| 配色、字體、風格與設計規範 | ui-ux-pro-max | 有多框架指引；風格建議不能代替實際需求與驗證 |
| 圖像式視覺探索 | Product Design ideate | 適合比較畫面方向；遵循當下數量與生成流程，不自動視為可編輯稿 |
| 既有流程審查 | Product Design audit | 依截圖與操作證據；單一畫面不能證明完整資料流 |
| 參考圖／URL 到前端原型 | Product Design image-to-code／url-to-code | 主要為 Web；套手機框不等於原生 App |
| 點陣背景、插畫與透明裝飾 | imagegen；Creative Production produce | 前者製作素材，後者適合視覺方向探索；不把圖片當互動元件 |
| Web 視覺與細節打磨 | Impeccable、Anthropic frontend-design | 排版、層級、色彩與有目的的動效；不能直接保證原生框架實作 |
| React Native／Expo | Expo 官方 Skills | 按需選 native-ui、design-system、animation、router 等目前存在的 Skill |
| Flutter | Flutter 官方 Agent Plugins | 響應式布局、修溢出、元件預覽與測試；偏工程落地 |
| 原生 iOS | SwiftUI Expert Skill、Apple HIG | 前者為社群 Skill；API 與平台規範仍查 Apple 文件 |
| React Web 動效 | Motion Skill／AI Kit | 核對免費與付費功能邊界；不用於替代 React Native runtime |
| 展示／操作示意影片 | HyperFrames 系列 | 影片製作；App 內動效另行實作 |

## Figma 選用路線

僅在需要可編輯設計稿、元件／變數或設計交接時選用；本 Skill 不依賴 Figma。先確認實際連線、檔案權限與可用工具。

- 建立新檔：先讀 figma-create-new-file。
- 操作設計畫面：讀 figma-use；從程式轉畫面時另讀 figma-generate-design。
- 共用規範／元件庫：讀 figma-generate-library 與其要求的基礎 Skill，僅建立需求範圍。
- 設計到程式：先讀 figma-design-to-code；元件對映按需讀 figma-code-connect。
- 設計工具內動畫：讀 figma-use-motion 與 figma-use；旗標不支援時依該 Skill 停止相關嘗試，改提供動效規格或框架方案，不繞過限制。
- Figma 動畫到應用程式：讀 figma-implement-motion。時間軸、節點資料與應用狀態需對應；不能直接把輸出的 CSS 當成原生實作。
- 程序背景／效果：需要操作 Figma shader 時先讀 figma-shaders；Figma 內效果另需確認能否在目標 App 取得或重現。
- SwiftUI 雙向交接時按需讀 figma-swiftui。

這些是 Skill 名稱定位，並非可直接執行的命令。找不到或工具未開放時明確說明，只繼續不依賴該能力的工作。自行寫程式不需要強制繞經 Figma。

## 官方與原作者來源

依當次問題查對應來源，不預設全部開啟；不固定套件版本、價格、數量或安裝命令。

- [UI UX Pro Max](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill)：設計規範與框架指引。
- [Impeccable](https://github.com/pbakaus/impeccable)：視覺審查、打磨與動效工作流程。
- [Anthropic frontend-design](https://github.com/anthropics/skills/tree/main/skills/frontend-design)：視覺方向與前端設計。
- [Expo Skills](https://github.com/expo/skills)：原生 UI、設計系統、導航與動畫。
- [Flutter Agent Plugins](https://github.com/flutter/agent-plugins)／[AI 開發設定](https://docs.flutter.dev/ai/get-started)：官方工具與 Skill。
- [Flutter 動畫](https://docs.flutter.dev/ui/animations)：框架動畫選型。
- [SwiftUI Expert Skill](https://github.com/AvdLee/SwiftUI-Agent-Skill)：社群 SwiftUI 指引。
- [Apple 設計原則](https://developer.apple.com/design/human-interface-guidelines/design-principles/)／[動效](https://developer.apple.com/design/human-interface-guidelines/motion)：平台體驗與動效。
- [Android Material 元件](https://developer.android.com/design/ui/mobile/guides/components/material-overview)／[Compose 動畫](https://developer.android.com/develop/ui/compose/animation/introduction)：Android 平台實作。
- [Reanimated](https://docs.swmansion.com/react-native-reanimated/)／[Gesture Handler](https://docs.swmansion.com/react-native-gesture-handler/)：React Native 動畫與手勢。
- [Motion](https://motion.dev/docs/react)：Web 動效、Skill 與方案界線。
- [Lottie](https://github.com/airbnb/lottie-android)：播放器與支援範圍；Flutter 等 runtime 另外查對應維護者。
- [Rive](https://rive.app/docs)：狀態機、素材與各平台 runtime。
- [Figma 開發者文件](https://developers.figma.com/)：工具整合；特殊功能需另核對本環境 Skill 與權限。
