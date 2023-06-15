# CODIS-opendata-web-crawler
- 此為資料萃取、資料清理、格式轉換的進階方法，當公開的目標資料沒辦法直接透過政府開放 WEB API 方式下載的客製化方案
- 可以針對站點、年/月/日時間範圍彈性獲取紀錄資料(站點可以用觀測系統網頁查詢/或從附件 xlsx 檔中匯入使用)

## 使用技術
- Beautifulsoup 模組
- Pandas 模組
- CSV 模組
- 利用 GET request 訪問網站 server


## 目的
- 用來取得中央氣象局觀測系統內觀測資料的爬蟲程式，由於網站原始資料為 HTML 格式，無法直接用來資料分析，所以利用程式中針對處理資料格式是 HTML 的方法取出標籤內資料，並進一步過濾清理，最後進行轉換成 Data Table


## 設立環境

```
pip install requests
pip install bs4
pip install pandas
pip install lxml
```
