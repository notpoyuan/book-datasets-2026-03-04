# book-datasets-2026-03-04
《[您的書名]》配套實戰數據集。包含紐約 Airbnb、計程車派遣等教學子集，用於演示 Python 數據清洗、商業指標建立與統計分析。

## 關於此儲存庫 (About)
本儲存庫託管《[您的書名]》中所使用的所有範例數據集。為了學習效率，部分數據已進行抽樣 (Sampling) 與清洗 (Preprocessing)。

## 如何在 Python 中使用 (Quick Start)
請複製以下代碼快速載入數據：
import pandas as pd
url = "https://raw.githubusercontent.com/notpoyuanbook-datasets-2026-03-04/main/ny_airbnb_sample.csv"
df = pd.read_csv(url, storage_options={'User-Agent': 'Mozilla/5.0'})

## 數據清單 (Dataset List)
* 檔案名稱                      內容描述                  原始來源
* ny_airbnb_sample.csv2024     紐約房源 (1,000 筆)        Inside Airbnb
* taxis_sample.csv             紐約計程車行程數據          Seaborn Datasets
* marketing_campaign_full.csv  [marketing_campaign_full](https://www.kaggle.com/code/pkdarabi/marketing-campaign-patterns/input)
