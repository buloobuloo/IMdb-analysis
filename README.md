IMdb-analysis
====
## Keras-IMdb introduce
1.先建立一個詞彙轉換字典
2.將文字串轉換成陣列<br>
<img src="https://github.com/buloobuloo/IMdb-analysis/blob/master/IMG/%E6%88%AA%E5%9C%96%202020-05-15%20%E4%B8%8B%E5%8D%885.28.45.png"><br>
3.設定每一個字串的陣列長度，多得刪除，少的補零
## Keras-MLP
建立Model:<br>
<img src="https://github.com/buloobuloo/IMdb-analysis/blob/master/IMG/%E6%88%AA%E5%9C%96%202020-05-15%20%E4%B8%8B%E5%8D%887.20.04.png"><br>
訓練圖表：<br>
<img src="https://github.com/buloobuloo/IMdb-analysis/blob/master/IMG/%E6%88%AA%E5%9C%96%202020-05-15%20%E4%B8%8B%E5%8D%887.20.15.png"><img src="https://github.com/buloobuloo/IMdb-analysis/blob/master/IMG/%E6%88%AA%E5%9C%96%202020-05-15%20%E4%B8%8B%E5%8D%887.20.20.png"><br>
精確度：0.812279999256134
## Keras-RNN
建立Model:<br>
<img src="https://github.com/buloobuloo/IMdb-analysis/blob/master/IMG/%E6%88%AA%E5%9C%96%202020-05-15%20%E4%B8%8B%E5%8D%887.22.07.png"><br>
訓練圖表：<br>
<img src="https://github.com/buloobuloo/IMdb-analysis/blob/master/IMG/%E6%88%AA%E5%9C%96%202020-05-15%20%E4%B8%8B%E5%8D%887.22.14.png"><img src="https://github.com/buloobuloo/IMdb-analysis/blob/master/IMG/%E6%88%AA%E5%9C%96%202020-05-15%20%E4%B8%8B%E5%8D%887.22.18.png"><br>
精確度：0.8344399999999999
## Keras-LSTM
