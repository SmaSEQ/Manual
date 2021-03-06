# SmaVISION 機器視覺模組

#### SmaVISION 提供豐富且實用的影像處理方法，讓使用者能夠依照應用的需求，靈活地嘗試與設計視覺檢測項目。從基本的取像到完整的 AOI 檢測，甚至是搭配偲倢開發的 SmaAI 模型，以 AI 進行外觀瑕疵檢測，SmaVISION 滿足了多方應用的需求。

本章節將分成以下幾個主題介紹：

* 基礎影像概念
* 操作輔助工具
* 影像處理步驟編輯
* 結果數據處理
* 影像函式列表

## 視覺模組 vs. 流程編輯器

#### SmaVISION 是一個預先設定好功能的被動角色，由 Sequencer 下達運作指令如 &lt;Start&gt;、&lt;Result&gt; 等。

![SmaVISION vs. Sequencer](../../.gitbook/assets/visionmodule_vs-sequencer2.png)

## 操作介面

#### SmaVISION 提供了簡單卻相當實用的操作介面，讓使用能夠同時進行機器視覺的開發與測試。

![](../../.gitbook/assets/visionmodule_intro.png)

* **影像畫面窗格**
  * 顯示當前影像與標記
  * 在此窗格點擊滑鼠右鍵，可開啟操作輔助工具選單。
* **影像處理函式庫**
  * 陳列了所有 SmaVISION 提供的影像處理功能。
* **處理程序表**
  * 處理程序表排列了本視覺模組的運作順序。
  * 滑鼠點選程序中的步驟，可即時在畫面窗格看到成果。
* **數據結果管理**
  * 數據化名（Alias Name）
    * 將視覺模組的成果數據命名。流程編輯器中，可使用【SmaVISION】步驟函式的 &lt; Result &gt; 指令，將此化名指定儲存到對應的變數中。
  * 數據總覽（Result）
    * 點擊 Result 按鈕，可查看本視覺模組的所有數據結果。

