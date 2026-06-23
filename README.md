# 金融科技概論 — Python 機器學習入門

金融科技概論課程的上課範例與作業：以 Python **從零實作**迴歸與分類（梯度下降），並搭配 scikit-learn。

## 內容
### 上課章節（教材範例）
| 檔案 | 主題 |
|------|------|
| `ch07-regression.ipynb` | 線性／多元迴歸（Boston Housing）|
| `ch08-bi-classify.ipynb` | 二元分類（sigmoid、梯度下降）|
| `ch09-multi-classify.ipynb` / `ch09-multi-classify-dec.ipynb` | 多元分類（Iris，含決策邊界）|

### 作業
| 檔案 | 主題 |
|------|------|
| `金融科技Hw1.ipynb` | 第一題：Boston Housing 梯度下降迴歸；第二題：Iris 梯度下降多分類 |
| `金融科技概論作業3.ipynb` | Iris 多元分類模型 |
| `財數_科技概論作業.ipynb` | 以 GBM（幾何布朗運動）做 S&P 500 蒙地卡羅模擬 |
| `金融科技.ipynb` | 課程工具筆記（Numpy / Pandas / sklearn / Keras 簡介）|

## 資料
`data/BostonHousing.csv`（公開資料集）；Iris 由 `sklearn.datasets.load_iris()` 載入。

## 執行
```bash
pip install numpy pandas scikit-learn matplotlib
```

## 說明
notebook 以相對路徑讀取 `data/BostonHousing.csv`；其餘使用 `load_iris()` 或 `yfinance`，無需附帶資料。
