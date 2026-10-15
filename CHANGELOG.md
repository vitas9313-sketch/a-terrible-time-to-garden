# 修改履歷

以遊戲版本編號記錄，不以日期分類。V1-14是目前完成版；V2為自V1-8分出的動畫試作。程式提交與標籤固定保留，不重寫歷史。

## 後續紀錄規則

- 遊戲內容的新修改依序建立V1-15、V1-16等版本；V2續作另記錄其實際基底與差異。
- 只改文件不增加遊戲版號。
- 每版記錄需求、實際變更、真正執行的驗證、未完成項目及提交；修正舊缺陷時指出取代哪版行為。
- 下列歷史摘要描述各版當時的狀態；現行要求以 [SPEC.md](SPEC.md) 為準。

## V1修改履歷

### V1-14｜全場景保鑣定稿

- **程式版本：** [{sha}](https://github.com/vitas9313-sketch/a-terrible-time-to-garden/commit/d0351a9)；[版本快照](https://github.com/vitas9313-sketch/a-terrible-time-to-garden/tree/V1-14)。
- **需求：** 保鑣要更兇、小眼銳利、鷹勾鼻，且所有保鑣畫面都須統一。
- **實際修改：** 替換全部11張相關圖，含上版未更新的同行鏡頭、野果追豬與第一人稱黑袖；年輕記者維持不同造型。
- **驗證紀錄：** 逐張目視覆核；自動確認11個圖像鍵更新、其餘20張未動、遊戲邏輯／CSS／MP4未改；Chromium解碼31張圖及檢查場景對應，另測熊／鹿重試、豬足跡、前導及雙結局，無JavaScript錯誤。
- **後續／限制：** 取代V1-13尚未完成的同行鏡頭編修。

### V1-13｜熊／鹿失敗與保鑣區分

- **程式版本：** [{sha}](https://github.com/vitas9313-sketch/a-terrible-time-to-garden/commit/fa8a5db)；[版本快照](https://github.com/vitas9313-sketch/a-terrible-time-to-garden/tree/V1-13)。
- **需求：** 熊路線需獨立防熊噴霧失敗圖；鹿路線不能誤用記者，保鑣與記者須區分。
- **實際修改：** 新增熊圖與失敗流程，替換鹿群追蹤者，調整8張相關圖。
- **驗證紀錄：** 實際操作熊／鹿故事演出、失敗與重試，確認豬足跡仍通關；檢查31張圖解碼及8個更新對應。
- **後續／限制：** 當時有一張同行鏡頭被圖片工具拒絕編修而沿用原圖，後於V1-14補齊。

### V1-12｜前導與雙結局角色

- **程式版本：** [{sha}](https://github.com/vitas9313-sketch/a-terrible-time-to-garden/commit/83a278f)；[版本快照](https://github.com/vitas9313-sketch/a-terrible-time-to-garden/tree/V1-12)。
- **需求：** 前導仍見背包豬；兩種結局需同時呈現保鑣與記者。
- **實際修改：** 修正實際MP4第16～20秒的舊鏡頭；湖畔加入保鑣，豪宅加入兩人抱賞金；THE END移到上緣避免擋臉。
- **驗證紀錄：** 檢查MP4第18秒、20秒片長、前四幕中點像素一致、結束進第一關及A／B結局載入；無JavaScript錯誤。
- **後續／限制：** 此版替換影片本身，並非只改封面或靜態圖。

### V1-11｜直接開始與高畫質羊圈

- **程式版本：** [{sha}](https://github.com/vitas9313-sketch/a-terrible-time-to-garden/commit/d3566b9)；[版本快照](https://github.com/vitas9313-sketch/a-terrible-time-to-garden/tree/V1-11)。
- **需求：** 開局仍被舊進度判為覆寫；羊群逃出畫面過於模糊。
- **實際修改：** 開始遊戲一律直接進序幕並備份原進度；羊群圖由836×470重製為1672×941。
- **驗證紀錄：** 五種開局存檔情況、三種繼續情況，以及開羊圈載入新圖後回兩束繩索救援，均已實測。
- **後續／限制：** 取代V1-10仍依進度詢問覆寫的作法。

### V1-10｜足跡與故事連續性

- **程式版本：** [{sha}](https://github.com/vitas9313-sketch/a-terrible-time-to-garden/commit/5e2e0c6)；[版本快照](https://github.com/vitas9313-sketch/a-terrible-time-to-garden/tree/V1-10)。
- **需求：** 修正足跡點不到、山洞演出重複、車未翻覆、人物混淆與漢堡成功跳接。
- **實際修改：** 字幕不再擋點擊；熊掌與叫聲取代狼；更新15張圖；新增吃漢堡與同行；記錄實際進度旗標。
- **驗證紀錄：** 實測足跡九個位置、錯路、救援與食物失敗重試、雙結局、存檔、音訊波形及三種桌面尺寸。
- **後續／限制：** 覆寫判定仍不符使用需求，後於V1-11直接移除；MP4殘留背包豬後於V1-12修正。

### V1-9｜字幕、游標與環境音

- **程式版本：** [{sha}](https://github.com/vitas9313-sketch/a-terrible-time-to-garden/commit/bcbb1fe)；[版本快照](https://github.com/vitas9313-sketch/a-terrible-time-to-garden/tree/V1-9)。
- **需求：** 字幕按鈕不夠清楚、游標回退、環境缺少細微動態與聲音。
- **實際修改：** 統一大型按鈕與DOM游標；加入環境微動、原創音效、本機台灣華語朗讀支援；更新主要記者圖。
- **驗證紀錄：** 當時已記錄桌面介面、游標、前導、環境／聲音開關、全螢幕、關卡、雙結局與存檔測試。
- **後續／限制：** 測試機無本機台灣語音，未宣稱真實朗讀聽感通過；V2未同步此版。

### V1-8｜穩定前導鏡頭

- **程式版本：** [{sha}](https://github.com/vitas9313-sketch/a-terrible-time-to-garden/commit/ac414fe)；[版本快照](https://github.com/vitas9313-sketch/a-terrible-time-to-garden/tree/V1-8)。
- **需求：** 字幕略下移，前導持續鏡頭運動造成不適。
- **實際修改：** 調整字幕位置，重剪固定鏡位MP4，移除平移、推鏡與縮放，只保留淡入淡出。
- **驗證紀錄：** 歷史驗證細節保留於此提交的README及差異。
- **後續／限制：** 後續V2由本版分出。

### V1-7｜記者命名

- **程式版本：** [{sha}](https://github.com/vitas9313-sketch/a-terrible-time-to-garden/commit/36993f4)；[版本快照](https://github.com/vitas9313-sketch/a-terrible-time-to-garden/tree/V1-7)。
- **需求：** 記者需要較自然、有質感的西方幽默名字。
- **實際修改：** 統一更名為克里斯・培根。
- **驗證紀錄：** 歷史驗證細節見對應提交。
- **後續／限制：** 後續角色圖與對話沿用此姓名。

### V1-6｜電腦版與割繩救援

- **程式版本：** [{sha}](https://github.com/vitas9313-sketch/a-terrible-time-to-garden/commit/a45a619)；[版本快照](https://github.com/vitas9313-sketch/a-terrible-time-to-garden/tree/V1-6)。
- **需求：** 維持電腦版、重試不要重聽故事與開背包、繩索要清楚且用刀割。
- **實際修改：** 固定桌面構圖，調整重試檢查點、大型繩束與救援刀熱區，補強關鍵場景清晰度。
- **驗證紀錄：** 歷史紀錄包含守衛／棄救／食物重試、刀具熱區、割繩及結局檢查。
- **後續／限制：** 重整頁面的章節存檔恢復與局部重試分開處理。

### V1-5｜故事銜接與救援選擇

- **程式版本：** [{sha}](https://github.com/vitas9313-sketch/a-terrible-time-to-garden/commit/69536e8)；[版本快照](https://github.com/vitas9313-sketch/a-terrible-time-to-garden/tree/V1-5)。
- **需求：** 補強智能車雨中翻覆、記者遭遇、救援選擇、食物來源與安全結局地點。
- **實際修改：** 加入前後銜接的記者對話、羊圈線索、棄救失敗、背包食物、原創煞車聲與場景配樂，調整電影字幕。
- **驗證紀錄：** 當時紀錄包含前導、記者、羊圈、棄救、三食物、湖畔雙結局與存檔檢查。
- **後續／限制：** 之後的視覺、重試及背包豬修正由後續版本接續。

### V1-4｜蛋糕失敗演出

- **程式版本：** [{sha}](https://github.com/vitas9313-sketch/a-terrible-time-to-garden/commit/1d6ed48)；[版本快照](https://github.com/vitas9313-sketch/a-terrible-time-to-garden/tree/V1-4)。
- **需求：** 對話框文字難讀，蛋糕成功不合理。
- **實際修改：** 改善對話框對比；蛋糕改為愛心、撲倒、追兵包圍的失敗序列。
- **驗證紀錄：** 歷史驗證細節見對應提交。
- **後續／限制：** 當時仍保留新遊戲覆寫確認，V1-11才移除。

### V1-3｜畫面內操作與全螢幕

- **程式版本：** [{sha}](https://github.com/vitas9313-sketch/a-terrible-time-to-garden/commit/4acd802)；[版本快照](https://github.com/vitas9313-sketch/a-terrible-time-to-garden/tree/V1-3)。
- **需求：** 把操作放回遊戲畫面，提供全螢幕、清楚結局與失敗重試。
- **實際修改：** 操作列移入螢幕、加入全螢幕和失敗覆蓋層，強化THE END。
- **驗證紀錄：** 歷史驗證細節見對應提交。
- **後續／限制：** 後續字幕與結局避臉位置持續調整。

### V1-2｜原創電影美術與前導

- **程式版本：** [{sha}](https://github.com/vitas9313-sketch/a-terrible-time-to-garden/commit/caae84d)；[版本快照](https://github.com/vitas9313-sketch/a-terrible-time-to-garden/tree/V1-2)。
- **需求：** 提升原創電影動畫質感，加入影片及更合乎情境的選擇。
- **實際修改：** 整合原創場景與內嵌前導，調整故事結果及互動呈現。
- **驗證紀錄：** 歷史驗證細節見對應提交。
- **後續／限制：** 後續仍持續修正人物、前導與場景連續性。

### V1-1｜三關初版

- **程式版本：** [{sha}](https://github.com/vitas9313-sketch/a-terrible-time-to-garden/commit/400a11c)；[版本快照](https://github.com/vitas9313-sketch/a-terrible-time-to-garden/tree/V1-1)。
- **需求：** 以簡單三關故事冒險取代舊植物模擬器。
- **實際修改：** 建立新遊戲標題、前導、三關互動、錯誤重試、雙結局及本機存檔。
- **驗證紀錄：** 歷史驗證細節見對應提交。
- **後續／限制：** 這是新遊戲初版，不代表後續美術與流程修正已完成。

## V2｜局部動態試作

- **提交：** [185730a](https://github.com/vitas9313-sketch/a-terrible-time-to-garden/commit/185730a)；[版本快照](https://github.com/vitas9313-sketch/a-terrible-time-to-garden/tree/V2)。
- **基底：** V1-8，不是V1-14。
- **內容：** 與V1分離的局部角色、動作及環境動畫試作，保持獨立存檔與分支。
- **限制：** 尚未合入V1-9～V1-14後續角色圖、故事與錯誤修正；不宣稱全部場景已成為完整角色動畫。
- **續作前提：** 先同步最新V1修正，重新對位新圖的眼睛、手部與動作座標，再增加動態。

## 文件維護

- 專案首頁、規格與本履歷屬開發文件；不以繳交稿或個人資料欄位替代正式規格。
- 已移除繳交用途的文件與截圖目錄，歷史提交保留；本次整理不修改遊戲、不移動既有標籤。
