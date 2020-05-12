# KMeans
[股票分群code](https://github.com/jiaying777/E.SUN_Fugle_project/blob/master/KMeans/Kmeans.ipynb)<br>
## 做法：
### 判斷分群：

* 手軸法
* 輪廓係數分析
* calinski harabaz score

👉 得到結果為分5群最好<br>

### 使用KMeans將股票分群，並定義每一群的特徵：<br>

    label 0：殖利率偏高、群內標準差大
    label 1：beta係數顯著偏高
    label 2：本益比整體偏高、beta係數顯著次高
    label 3：淨值比顯著偏高
    label 4：各項數值皆偏低
