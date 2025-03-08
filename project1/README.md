## imdb_reviews.csv
### 資料來源
資料來源為[IMDb](https://www.imdb.com/)各電影的觀眾影評。
### 資料蒐集
透過網路爬蟲[Selenium](https://www.selenium.dev/)，將各種評論添加到imdb_reviews.csv資料集中。
### 資料範圍
本資料集蒐集了600部電影與電視劇，包含：
1. [IMDb Top 250 Movies](https://www.imdb.com/chart/top/)
2. [Lowest Rated Movies](https://www.imdb.com/chart/bottom/)
3. [Top 250 TV Shows](https://www.imdb.com/chart/toptv/?ref_=chttp_ql_6)

在相同載入時間內蒐集各星等的影評，以確保平均星等評論數。
### 資料格式
情緒標籤(Sentiment)的種類分為三類：Negative, Neutral and Positive。Rating也就是星等，1 ~ 3為 Negative，4 ~ 6為Neutral，最後7 ~ 10為 Positive。 Review為觀眾的影評。
| Sentiment | Rating | Review |
|----|----|----|
| negative  | 1      | Shawshank is nothing more than a fairy tale. I.... |
| negative  | 1      | Shawshank Redemption has been elevated in popu... |
