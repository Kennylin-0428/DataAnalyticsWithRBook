
# 資料科學與R語言
### 曾意儒 Yi-Ju Tseng

本資源庫存放[資料科學與R語言](http://yijutseng.github.io/DataScienceRBook/)的文字與程式碼，內容包括使用R語言完成以下任務:

- 資料讀取 (檔案、透過API擷取或爬蟲)
- 資料清洗與處理 
- 探索式資料分析
- 資料視覺化
- 資料探勘
- R與Hadoop Ecosystems介接方法

資料探勘章節尚未完成，PDF版本與epub版本格式微調中。

如要一次安裝所有本書會使用到的套件，可在R內執行以下程式碼：
```{r}
install.packages("devtools")
library(devtools)
devtools::install_github("yijutseng/DataAnalyticsWithRBook")
```
