# DeepSeek 大肥魚・幼年

幼年版桌面寵物素材套件。角色以使用者確認的幼年圖為唯一造型基準，保留藍白女僕制服、圍裙鯨魚標、尾巴與原有身形。工作時會趁機偷吃白飯。

## 預覽

![幼年版九種動作總覽](animations/all-states.gif)

![十六方向注視總覽](animations/look-directions.gif)

總表：spritesheet.webp，1536 × 2288，透明背景，v2 格式（192 × 208 單格）。

## 包含內容

- pet.json：寵物素材描述。
- spritesheet.webp：ChatGPT Work 寵物精靈表。
- animations/：九種動作與十六方向注視預覽。
- qa/：接觸表、方向總覽、品質與透明度檢查報告。
- source/：採用的基準圖、最終動作列與注視素材。
- prompts/：最終採用的角色與動畫提示詞。
- docs/WORKLOG.md：製作決策、修正經驗與驗收紀錄。
- LICENSE_STATUS.md：授權與來源狀態。

## 動作

九種標準狀態為 idle、running-right、running-left、waving、jumping、failed、waiting、running、review。running 保留偷吃白飯的特性。另有十六個注視方向。

## 驗收摘要

精靈表結構檢查與品質檢查均通過，沒有阻擋錯誤。跳躍最高離地 22 px，落地基線差為 0 px；注視方向中心最大偏移 2 px。三個中間方向和少數相鄰方向差異被品質報告標記為人工檢視提示，已逐格目視確認並收錄在 qa/direction-semantics.json、qa/direction-continuity.json。

## 安裝狀態

幼年版已建立在 ChatGPT Work 寵物列表中，成年版維持原樣並保持啟用。此資料夾是可審閱的本機發布套件；尚未建立或發布公開 GitHub 儲存庫。

## 開源前

請先確認 LICENSE_STATUS.md 中列出的素材來源與授權，再選擇適用授權並發布。
