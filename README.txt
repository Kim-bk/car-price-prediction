## Hướng dẫn chạy code 
---
### CRAWL và EDA dữ liệu
-   Nguồn dữ liệu: Được Crawl dữ liệu từ https://bonbanh.com/
-   Thư viện được yêu cầu cài đặt: 
    + BeautifulSoup (https://pypi.org/project/beautifulsoup4/)
    + seaborn (https://pypi.org/project/seaborn/) 
    + matplotlib (https://pypi.org/project/matplotlib/)
    + pandas (https://pypi.org/project/pandas2/)
    + numpy (https://pypi.org/project/numpy/)
    + csv (https://pypi.org/project/csv23/)
-   Chạy file Crawldata.ipynb để thực hiện việc crawl dữ liệu sau đó ta sẽ thu được 1 file raw_data.csv dữ liệu về Oto
-   Chạy file CleanData.ipynb để thực hiện việc điền các dữ liệu trống. Sau đó sẽ thu được 1 file data_clean.csv và thực hiện EDA dữ liệu
---
### Clean và Featuring dữ liệu,  Modelling sử dụng Linear Regression, RandomForest Regressor để dự đoán giá oto
- Cần nạp các thư viện như seaborn, pandas, numpy, matplotlib, sklearn (https://pypi.org/project/sklearn/), 
- Chạy file model.ipynb để sử dụng 2 mô hình RandomForest Regressor và Linear Regression để dự đoán giá xe 
---