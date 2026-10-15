# 豬事不妙！The Great Pig Escape

**目前完成版：V1-15。V2是較早的動畫試作，並非最新V1的升級完成版。**

## 專案文件

- [遊戲規格書](SPEC.md)：故事、人物、關卡判定、操作、存檔、技術、美術與驗收要求。
- [修改履歷](CHANGELOG.md)：V1-1～V1-15、V2各版需求、實際變更、驗證與限制。
- [原創素材紀錄](ART_SOURCES.md)：圖像來源、生成摘要與檔案雜湊。

遊戲本體為單一 `index.html`；文件與遊戲程式分開維護。

## 版本怎麼選

GitHub上方的分支下拉選單 → **Tags** → 選 **V1-1、V1-2……V1-15或V2**。版本依實際開發順序編號，不以日期辨認。原本的分支與 `pig-v1-stable` 標籤都保留。

版本標籤固定指向當時的遊戲程式。舊標籤內的README會保留當時文字；辨認目前版本請以本頁索引為準。只整理文件不會另外增加遊戲版號。

## V1版本一覽

| 版本 | 名稱 | 主要變更 | 程式提交 |
|---|---|---|---|
| V1-15 **目前最新版** | 場景音樂版本 | 各場景使用原創背景音樂、環境音與事件音效。 | 對應標籤 `V1-15` |
| [V1-14](https://github.com/vitas9313-sketch/the-great-pig-escape/tree/V1-14) | 全場景保鑣定稿 | 全部11張相關圖統一小眼、銳利眼神、鷹勾鼻、黑色開襟衫與頭頂墨鏡；補齊同行鏡頭。 | [d0351a9](https://github.com/vitas9313-sketch/the-great-pig-escape/commit/d0351a9) |
| [V1-13](https://github.com/vitas9313-sketch/the-great-pig-escape/tree/V1-13) | 熊／鹿失敗與保鑣區分 | 新增防熊噴霧失敗圖，鹿路線改保鑣，初步統一成熟保鑣造型。 | [fa8a5db](https://github.com/vitas9313-sketch/the-great-pig-escape/commit/fa8a5db) |
| [V1-12](https://github.com/vitas9313-sketch/the-great-pig-escape/tree/V1-12) | 前導與雙結局角色 | 修正實際MP4殘留的背包豬；湖畔與賞金結局加入保鑣和記者。 | [83a278f](https://github.com/vitas9313-sketch/the-great-pig-escape/commit/83a278f) |
| [V1-11](https://github.com/vitas9313-sketch/the-great-pig-escape/tree/V1-11) | 直接開始與高畫質羊圈 | 移除開始遊戲覆寫確認，替換羊群逃出羊圈的低解析度圖。 | [d3566b9](https://github.com/vitas9313-sketch/the-great-pig-escape/commit/d3566b9) |
| [V1-10](https://github.com/vitas9313-sketch/the-great-pig-escape/tree/V1-10) | 足跡與故事連續性 | 修正足跡點擊與重複山洞演出，加入翻覆車輛、落難記者、吃漢堡與同行畫面。 | [5e2e0c6](https://github.com/vitas9313-sketch/the-great-pig-escape/commit/5e2e0c6) |
| [V1-9](https://github.com/vitas9313-sketch/the-great-pig-escape/tree/V1-9) | 字幕、游標與環境音 | 放大統一按鈕、修正游標、加入環境微動／聲音。 | [bcbb1fe](https://github.com/vitas9313-sketch/the-great-pig-escape/commit/bcbb1fe) |
| [V1-8](https://github.com/vitas9313-sketch/the-great-pig-escape/tree/V1-8) | 穩定前導鏡頭 | 字幕略下移，前導移除持續晃動、平移與縮放。 | [ac414fe](https://github.com/vitas9313-sketch/the-great-pig-escape/commit/ac414fe) |
| [V1-7](https://github.com/vitas9313-sketch/the-great-pig-escape/tree/V1-7) | 記者命名 | 記者更名為克里斯・培根，統一稱呼。 | [36993f4](https://github.com/vitas9313-sketch/the-great-pig-escape/commit/36993f4) |
| [V1-6](https://github.com/vitas9313-sketch/the-great-pig-escape/tree/V1-6) | 電腦版與割繩救援 | 固定桌面構圖，失敗回到選擇步驟，新增救援刀與關鍵畫面清晰度修正。 | [a45a619](https://github.com/vitas9313-sketch/the-great-pig-escape/commit/a45a619) |
| [V1-5](https://github.com/vitas9313-sketch/the-great-pig-escape/tree/V1-5) | 故事銜接與救援選擇 | 補強智能車、記者、背包食物、救援抉擇、字幕與原創聲音。 | [69536e8](https://github.com/vitas9313-sketch/the-great-pig-escape/commit/69536e8) |
| [V1-4](https://github.com/vitas9313-sketch/the-great-pig-escape/tree/V1-4) | 蛋糕失敗演出 | 改善對話框可讀性，加入草莓蛋糕撲倒及追兵失敗。 | [1d6ed48](https://github.com/vitas9313-sketch/the-great-pig-escape/commit/1d6ed48) |
| [V1-3](https://github.com/vitas9313-sketch/the-great-pig-escape/tree/V1-3) | 畫面內操作與全螢幕 | 把操作移入遊戲螢幕，加入全螢幕與失敗重試畫面。 | [4acd802](https://github.com/vitas9313-sketch/the-great-pig-escape/commit/4acd802) |
| [V1-2](https://github.com/vitas9313-sketch/the-great-pig-escape/tree/V1-2) | 原創電影美術與前導 | 加入原創電影動畫風格場景、內嵌前導影片與較合理的選擇結果。 | [caae84d](https://github.com/vitas9313-sketch/the-great-pig-escape/commit/caae84d) |
| [V1-1](https://github.com/vitas9313-sketch/the-great-pig-escape/tree/V1-1) | 三關初版 | 完成三關點擊流程、成功／失敗、雙結局與本機存檔。 | [400a11c](https://github.com/vitas9313-sketch/the-great-pig-escape/commit/400a11c) |

## V2動畫試作

| 版本 | 狀態 | 說明 |
|---|---|---|
| [V2](https://github.com/vitas9313-sketch/the-great-pig-escape/tree/V2) | 動畫試作 | 基於V1-8，使用局部角色與環境動態；未同步V1-9～V1-14，也不是全片逐格角色動畫。 |

V2原分支為 `feature/pig-game-v2`，保留其獨立試作內容；後續差異見 [修改履歷](CHANGELOG.md)。

## V1-15目前內容

- 三關：足跡追蹤 → 洞穴救援 → 食物選擇與湖畔抉擇。
- 野果、蛋糕、熊／鹿錯路與錯誤救援均有失敗結果，可重試；漢堡成功後吃完再同行。
- 富豪賞金與湖畔自由兩種結局，皆算通關。
- 全部保鑣圖採用統一的原創成熟造型，與年輕記者區分。
- 桌面構圖、大字幕、全螢幕、自訂游標、可關閉的原創合成配樂／聲音與環境微動。
- localStorage保存章節檢查點、解鎖、結局與設定；不是跨裝置雲端存檔。
- 圖片、影片與程式皆內嵌於 `index.html`，執行時無框架、CDN或後端。

## 驗證與原創說明

已實測三關、雙結局、失敗重試、存檔與圖像載入；31張內嵌圖可解碼。保鑣定稿更新11張圖，未改遊戲邏輯或前導MP4。本輪另已驗證音樂啟動、靜音與恢復，以及序幕、三關與結局渲染；網站公開連線尚未驗證。

圖像只使用本專案AI原創生成／編修，未下載外部圖片、未指定仿製影劇角色、藝術家或真人演員；音樂與音效由Web Audio API原創合成。詳細來源摘要與雜湊見 [ART_SOURCES.md](ART_SOURCES.md)。

舊植物遊戲仍保留在 `feature/milestone-1`，與本作版本分開，不併入V1或V2編號。
