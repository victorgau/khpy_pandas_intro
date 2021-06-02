# pandas使用簡介

## 關於唯客學院：

* [唯客學院網址](https://www.victorgau.com)
* [唯客學院部落格](https://victorgau.com/blog/)
* [高雄Python學院粉絲團](https://www.facebook.com/KHPYAcademy/)

## 課程內容：

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/victorgau/khpy_pandas_intro/)

簡單介紹 pandas 的使用。

### 1. 文件導覽

* [官網說明](https://pandas.pydata.org/pandas-docs/stable/index.html)

### 2. 實作引導

#### Pandas的資料結構

* Series
* DataFrame

#### 匯入資料

* .json => read_json()
* .csv => read_csv()
* .xlsx => read_excel()
* .txt => read_csv()
* .sql => read_sql()
* html table => read_html()

#### 匯出資料

* to_csv
* to_excel
* to_sql
  
#### 檢視資料

* head
* tail
* info
* describe

#### 索引及切片

* 讀取欄
  * 讀取一個欄
  * 讀取多個欄
* 讀取列
  * iloc
  * loc
* booling indexing / filtering / subsetting

#### 插入欄 / 刪除欄 / 刪除列

* drop
* booling indexing 篩選後指定給新變數

#### 缺失值處理

* dropna
* fillna
* replace

#### 重複值處理

* duplicated
* unique
* drop_duplicates

#### 合併DataFrame

* merge
* concat

#### 資料運算

* mean
* sum
* count
* corr

#### 分組及聚合

* groupby
* aggregate

#### 長寬表轉換

* stack / unstack
* melt

#### apply跟applymap

* map (用在Series)
* apply
* applymap (用在DataFrame)

#### 樞紐分析表

* pivot_table
* crosstab

#### 時間序列

* resample

#### 資料視覺化

* plot

#### 金融資料分析

* pct_chg
* cumsum
* cumprod

### 3. 自我挑戰

* 使用Pandas讀取政府資料開放平台上的資料下來做分析(e.g., 實價登陸資訊)