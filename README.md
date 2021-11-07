# Prediction for Opening Week Box Office of Movies 電影首周票房預測

- Purpose: Collecting movie-related data and comments of official trailers from TMDB, Mojo Box office, and Youtube to predict opening week box office of movies. \
目的：利用TMDB、Mojo Box Office電影相關資料，以及Youtube電影預告片留言聲量，進行美國首周票房預測。
-	Method: Constructing a two-stage box office prediction model by XGBoost, MLP, then using VaderSentiment to proceed sentiment analysis on comments of official trailers from Youtube, and constructing Hadoop HA system with spark to accelerate execution. \
方法：透過XGBoost、神經網絡建置兩階段模型，先將票房分群，進而對高票房群進行金額預測。利用vaderSentiment套件對YouTube電影預告片留言進行情感分析，做為模型特徵，並建置Hadoop HA、Spark運算引擎優化運算效能。

