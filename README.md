# GPX 合併工具 · Merge GPX Files

**線上使用 → https://easterjhan.github.io/gpx-merge/**

跑步到一半不小心停錶，一次跑步被拆成兩個、三個活動？把各段 GPX 丟進網頁，它會依時間排好，接成**一個活動**。心率、步頻、海拔等每點資料和原始格式都會保留，可以直接匯入 **Garmin Connect**、**Strava**。

> Accidentally stopped your watch and got your run split into several activities? This page merges multiple GPX files into one activity, keeping heart rate, cadence and elevation. It works with Garmin Connect, Strava, Coros, Suunto and Polar exports. Everything runs in your browser, and nothing is uploaded.

## 功能

- 一次合併任意多個 GPX 檔，自動依時間排序
- 兩種輸出方式
  - **接成單一軌跡段**：和手錶原本匯出的格式一樣，只有一個 `trkseg`
  - **保留分段**：一個活動、每段一個 `trkseg`，停錶期間不計距離
- 保留每點的 `time`、`ele`、心率 `hr`、步頻 `cad` 等 TrackPointExtension，檔頭與命名空間沿用第一個檔
- 預覽軌跡圖、時間軸，並算出總距離、時間、配速、停錶次數與停了多久
- 偵測時間重疊與重複加入的檔案
- 純前端單一 HTML 檔：沒有伺服器，也不需要安裝

## 使用步驟

1. 從 Garmin Connect、Strava 或 Coros 把各段活動**匯出成 GPX**
2. 打開網頁，把檔案拖進去
3. 選擇輸出方式，按「合併並下載」
4. 回到 Garmin Connect，用「匯入資料」上傳合併後的 `.gpx`，並**刪除原本那幾段**，避免里程重複

## 離線使用

下載 `index.html`，直接用瀏覽器開啟即可。

## 關鍵字

GPX 合併、合併 GPX、GPX 檔案合併、跑步停錶、不小心停錶、活動合併、Garmin 合併活動、Garmin Connect 合併、Strava 合併活動、Coros 合併、軌跡合併、merge GPX, combine GPX files, join GPX tracks, merge Garmin activities, merge Strava activities, GPX joiner

## License

MIT
