【新泰國中校園無聲廣播系統 - Android IFP 觸控大屏接收端部署說明】
1. 本系統採純線上網頁版雲端直連，大屏安裝 APK 後「只需輸入班級名稱（如 807 或 校史室）」即可運作，完全不須設定伺服器 IP。
2. 免裝 Android Studio 雲端編譯 APK 步驟：
   (1) 將解壓縮後的檔案上傳至免費 GitHub 儲存庫。
   (2) 因瀏覽器拖曳上傳會略過隱藏資料夾，請在 GitHub 點選 Add file -> Create new file，
       手動輸入檔名 .github/workflows/build-apk.yml 並貼上對應內容後 Commit。
   (3) 切換至 GitHub 上方 Actions 分頁，待編譯完成（約 2 分鐘）即可在 Artifacts 下載 NTJHS-IFP-Receiver-APK（內含 app-debug.apk）。