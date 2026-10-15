# 免費工具與來源

本頁只收錄不需購買的指定版本／方法，不收錄付費推薦或試用方案。查核日期：2026-10-15。這是選用清單，不是安裝清單；本 Skill 可直接運作，不依賴所有候選工具。

## 免費判斷

- 查指定功能與版本，包括編輯、下載、匯出、去除浮水印與使用授權；不能只查首頁有沒有「Free」。
- 開源授權只適用對應程式／文件，不自動包含同站的商業服務、生成 API、課程或動畫素材。依授權保留必要聲明；免費不等於沒有授權條件。
- 不使用訂閱、購買、按量計費、限時試用、免費點數用完需付款或必須綁卡的路線；不要求先付款再退款。
- 條件不明或原本免費功能改收費時，不採用。選框架內建功能、程式繪圖與自有素材作替代，不繞過存取限制。
- 本機方案以已有硬體與環境為前提；需要購買設備、租主機或付費建置服務時，改交付可驗證範圍的程式、規格與本機原型，不宣稱完整裝置建置已完成。

## 免費選用清單

| 需求 | 可選版本／方法 | 免費依據與適用邊界 |
|---|---|---|
| 整體規劃、審查與交接 | 本 Skill 的共用／平台參考、Markdown、程式原型 | 不需外部設計服務；資料狀態與授權仍需驗證 |
| 色彩、字體、元件規範 | [UI UX Pro Max 公開開源版本](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill) | [MIT](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill/blob/main/LICENSE)；只用儲存庫中的開源內容 |
| Web 細節打磨 | [Impeccable 開源版本](https://github.com/pbakaus/impeccable) | [Apache-2.0](https://github.com/pbakaus/impeccable/blob/main/LICENSE)；使用本機流程，不引入外部計費能力 |
| Flutter 布局與預覽 | [Flutter 官方 Agent Plugins](https://github.com/flutter/agent-plugins) | [BSD-3-Clause](https://github.com/flutter/agent-plugins/blob/main/LICENSE)；只選對應本機布局／預覽 Skill |
| React Native／Expo | [Expo 官方 Skills](https://github.com/expo/skills) 的框架部分 | [MIT](https://github.com/expo/skills/blob/main/LICENSE)；限本機 SDK、導航、設計系統與動畫，不選雲端服務流程 |
| 原生 iOS 指引 | [SwiftUI Expert Skill](https://github.com/AvdLee/SwiftUI-Agent-Skill) | [MIT](https://github.com/AvdLee/SwiftUI-Agent-Skill/blob/main/LICENSE)；既有 Apple 開發環境另核對，不承諾可在任意電腦零成本建置 |
| Web 動效 | CSS／WAAPI；[Motion 開源 npm 套件](https://github.com/motiondivision/motion) | Motion 為 [MIT](https://github.com/motiondivision/motion/blob/main/LICENSE.md)；只用開源 API 與自行實作程式，不使用另購範例或外掛 |
| React Native 手勢動效 | [Reanimated](https://github.com/software-mansion/react-native-reanimated)、[Gesture Handler](https://github.com/software-mansion/react-native-gesture-handler) | 兩者皆 [MIT](https://github.com/software-mansion/react-native-reanimated/blob/main/LICENSE)／[MIT](https://github.com/software-mansion/react-native-gesture-handler/blob/main/LICENSE)；驗證專案版本與目標裝置 |
| 預製向量動畫播放 | [Lottie Android 開源播放器](https://github.com/airbnb/lottie-android) | [Apache-2.0](https://github.com/airbnb/lottie-android/blob/master/LICENSE)；播放器免費不代表素材免費；其他平台 runtime 另查維護者授權 |
| 可編輯設計稿 | 程式原型；必要時 [Penpot 開源自架版本](https://github.com/penpot/penpot) | [MPL-2.0](https://github.com/penpot/penpot/blob/develop/LICENSE)；僅用已有環境本機執行，不租主機，不強制安裝 |
| 背景、圖示與簡單插畫 | 框架繪圖、CSS、SVG、Canvas、系統字體 | 自行寫程式，不需購買素材；外部素材與字體逐份核對授權 |

需要其他 Skill 時先核對目前清單並讀取原檔；本頁不複製第三方完整 Skill 或提供固定安裝命令。外部 Skill 要求訂閱、購買或使用計費端點時，不適用本免費流程。沒有該 Skill 也可依本 Skill 的方法完成工作。

## Designeer 只作免費發現入口

[Designeer](https://www.designeer.xyz/) 的目錄目前可免費瀏覽；只用來發現參考，不將其中任何工具、課程、模板、圖片或動畫自動列入免費清單。對候選的實際功能、匯出與素材授權另查原作者來源；不能確認就略過。站內的贊助項目與排名不作免費或相容性的證據。

用法：依需求找「App 流程／背景／元件／動效」→ 選少量候選 → 查原作者文件與授權 → 確認零新增費用與平台相容 → 再設計或實作。不要整站匯入，也不自動串接或安裝網站描述的工具。

## 免費官方文件

以下只閱讀公開文件，不使用其付費產品、上架、託管或雲端建置服務。

- [Flutter 動畫](https://docs.flutter.dev/ui/animations)：本機框架動畫選型。
- [Apple 設計原則](https://developer.apple.com/design/human-interface-guidelines/design-principles/)／[動效](https://developer.apple.com/design/human-interface-guidelines/motion)：平台體驗與動效規範。
- [Android Material 元件](https://developer.android.com/design/ui/mobile/guides/components/material-overview)／[Compose 動畫](https://developer.android.com/develop/ui/compose/animation/introduction)：Android 介面與動畫。
- [Reanimated 文件](https://docs.swmansion.com/react-native-reanimated/)／[Gesture Handler 文件](https://docs.swmansion.com/react-native-gesture-handler/)：開源套件使用方式。
- [MDN CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)／[SVG](https://developer.mozilla.org/en-US/docs/Web/SVG)：程式背景與向量素材。

指定軟體、工具功能或授權可能變動，使用時仍核對當下來源；以上查核不代表已在使用者專案實測。
