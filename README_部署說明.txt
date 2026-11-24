新泰國中校園無聲廣播系統 - Android IFP 觸控大屏接收端部署說明
============================================================
1. 本系統為純線上網頁版，安裝 APK 後只需輸入「班級」（如 807 或 校史室）即可執行，無需輸入伺服器 IP。
2. 若使用 GitHub Actions 雲端自動編譯 APK：
   - 將所有檔案上傳至 GitHub 儲存庫。
   - 點選 Actions -> New workflow -> set up a workflow yourself，貼上 .github/workflows/build-apk.yml 內容並 Commit。
   - 等待約 2 分鐘變綠燈後，於下方 Artifacts 下載 NTJHS-IFP-Receiver-APK 解壓縮取得 app-debug.apk。