# Apply-Deep-learning-for-NBA-game-analysis
A practice for AI project
此目錄是用來存放AI課程的專案作業。該專案目的是想要收集資料，利用深度學習來產生賽前的重點報告提供給教練和球員參考，以及做比賽的勝負分分析。

數據預處理步驟
1.資料檢視
檢視前五筆的資料 - df.head
檢視最後五筆的資料 - df.tail
檢視數據的欄位名稱 - df.columns
檢視數據欄、列的數量 - df.shape
檢視各個欄位的資料型態與該欄位的資料數量 - df.info
檢視整體資料的標準差、平均值等基本統計資料 - df.describe
2.數據清洗
刪除未上場的球員比賽資料(移除comment欄位為DNP的該列資料) - df.drop
刪除不需要的欄位('Unnamed: 0', 'TEAM_CITY', 'NICKNAME', 'START_POSITION', 'COMMENT', 'MIN') - df.drop
刪除缺失值(移除具有缺失值的該列資料) - dropna