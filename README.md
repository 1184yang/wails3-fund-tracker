# wails3-fund-tracker
定期定額基金損益追蹤系統
1. 在你的電腦建立一個資料夾（例如 D:\MyFundTracker\），把 .exe 複製進去即可直接雙擊啟動。

2. 執行時如果出現此警告,按 <ins>其他資訊</ins> 就會出現 <ins>仍要執行</ins> 按鍵

   Microsoft Defender SmartScreen 已防止某個無法辨識的應用程式啟動。執行此應用程式可能會讓您的電腦暴露在風險中。

3. 資料庫使用的是 Sqlite3，會自動產生在 ./data 目錄下。

4. 日常備份只需定期將 D:\MyFundTracker\data\db01.sqlite 複製一份，或使用系統內建的「匯出 CSV 備份」功能即可。
