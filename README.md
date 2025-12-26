# Global Offshore Wind Farm Scraper

這是一個用於抓取全球離岸風場資料的 Python 工具。
資料來源為維基百科公開列表。

## 功能
- 自動抓取運維中 (Operational) 與施工中 (Under Construction) 的風場。
- 自動偽裝瀏覽器 User-Agent 以繞過基礎反爬蟲機制。
- 輸出整理好的 `.csv` 檔案。

## 安裝與使用

1. 安裝相依套件：
   ```bash
   pip install -r requirements.txt
2. 執行程式：
   python scraper_wind_farm.py
