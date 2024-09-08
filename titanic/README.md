# Titanic 結果と分析手法について
## 課題について
[課題サイト](https://www.kaggle.com/competitions/titanic)

## 分析手法と結果について
|ファイル名|欠損値処理|予測手法|結果|
|----------|----------|--------|----|
|[k-nn.ipvnb](https://github.com/ShotaArima/kaggle/blob/main/titanic/k-nn.ipynb)|最頻値mode|k-最近傍法|0.60765|
|[xgboost.ipynb](https://github.com/ShotaArima/kaggle/blob/main/titanic/xgboost.ipynb)|なし|GBDTのライブラリの一つのxgboot|0.77033|
|[xgboost2.ipynb](https://github.com/ShotaArima/kaggle/blob/main/titanic/xgboost2.ipynb)|なし|XGBoostとロジスティック回帰のアンサンブル学習(8:2)|0.77033|
