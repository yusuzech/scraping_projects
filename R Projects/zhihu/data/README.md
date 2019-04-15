zhihu.db is where all the scraping results are stored.

# Structure of database:

(Becasue the web-scraping started from bitcoin topic, so all tables are named bitcoin)

## topic_bitcoin

**Where evertything starts, choose a topic and scrape related aiticles/questions/answers:**

|| thread_id | question_id         | answer_id | content_type | title  | content_href               | user_id                              | user_name                          | user_link     | upvote                                                    | record_date | |
|----|-------|---------------------|-----------|--------------|--------|----------------------------|--------------------------------------|------------------------------------|---------------|-----------------------------------------------------------|-------------|-----------| 
| 1         | 275508580_397922150 | 275508580 | 397922150    | answer | 如何看待币圈四月底暴跌？               | /question/275508580/answer/397922150 | mei-you-si-xiang-de-yi-la-guan     | 没有思想的易拉罐      | //www.zhihu.com/people/mei-you-si-xiang-de-yi-la-guan     | 0           | 2018/5/21 | 
| 2         | 277975398_397920433 | 277975398 | 397920433    | answer | 如何看待阮一峰的博客攻击者比特币签名是ywwuyi？ | /question/277975398/answer/397920433 | NA                                 | 知乎用户          | NA                                                        | 0           | 2018/5/21 | 
| 3         | 277899814_397913242 | 277899814 | 397913242    | answer | 如何评价「比特币挖矿将令我们三年后无电可用？」？   | /question/277899814/answer/397913242 | wu-ding-he-78                      | 无定河           | //www.zhihu.com/people/wu-ding-he-78                      | 0           | 2018/5/21 | 
| 4         | 277061220_397900643 | 277061220 | 397900643    | answer | 二线城市投资比特币挖矿有前景吗？           | /question/277061220/answer/397900643 | leo-89-26-90                       | Leo           | //www.zhihu.com/people/leo-89-26-90                       | 0           | 2018/5/21 | 
| 5         | 277205083_397891691 | 277205083 | 397891691    | answer | 作为庄如何抬高自己发行的虚拟货币的价钱?       | /question/277205083/answer/397891691 | engineer-coin                      | Engineer Coin | //www.zhihu.com/people/engineer-coin                      | 0           | 2018/5/21 | 
| 6         | 49100704_397884584  | 49100704  | 397884584    | answer | 比特币交易平台哪个最靠谱？              | /question/49100704/answer/397884584  | zui-li-lun-dao-xing-shi-zhe-hua-19 | 醉里论道醒时折花      | //www.zhihu.com/people/zui-li-lun-dao-xing-shi-zhe-hua-19 | 5           | 2018/5/21 | 


## user_detail_bitcoin

**Detailed information of users, including how many lives they held/attended, how many upvotes they have. Also include information like their job/education/company/location and etc.**

|| followingCount | voteFromCount | userType | includedText | pinsCount | includedArticlesCount | id | favoriteCount                    | voteupCount | commercialQuestionCount | followingColumnsCount | headline | urlToken                 | participatedLiveCount    | isAdvertiser | followingFavlistsCount | favoritedCount | isOrg | followerCount | type | avatarHue | avatarUrlTemplate | followingTopicCount                                                   | description | avatarUrl                                    | columnsCount                                                      | hostedLiveCount | isActive | thankToCount | mutualFolloweesCount | coverUrl | thankFromCount                                                   | voteToCount | answerCount | articlesCount | name | questionCount | includedAnswersCount | url | logsCount                                                           | followingQuestionCount | thankedCount | gender | badge_topic | badge_type | business | company | job                        | location    | major    | school | record_date |  |
|------|----------|---------------|----------|--------------|-----------|-----------------------|----|----------------------------------|-------------|-------------------------|-----------------------|----------|--------------------------|--------------------------|--------------|------------------------|----------------|-------|---------------|------|-----------|-------------------|-----------------------------------------------------------------------|-------------|----------------------------------------------|-------------------------------------------------------------------|-----------------|----------|--------------|----------------------|----------|------------------------------------------------------------------|-------------|-------------|---------------|------|---------------|----------------------|-----|---------------------------------------------------------------------|------------------------|--------------|--------|-------------|------------|----------|---------|----------------------------|-------------|----------|--------|-------------|-----------| 
| 2              | 3             | 0        | people       |           | 0                     | 0  | 94b4f4b263a8a64bcdf500743500ed59 | 0           | 53                      | 0                     | 0        |                          | da-da-da-ge-bie-sha-wo-2 | 0            | 0                      | 0              | 8     | 0             | 5    | people    | 0x6f8096          | https://pic4.zhimg.com/v2-cec9ded3659b201fad3235a20bf1e06c_{size}.jpg | 0           |                                              | https://pic4.zhimg.com/v2-cec9ded3659b201fad3235a20bf1e06c_is.jpg | 0               | 0        | 1526790455   | 0                    | 0        |                                                                  | 0           | 0           | 3             | 0    | 大大大哥别杀我       | 0                    | 0   | http://www.zhihu.com/api/v4/people/94b4f4b263a8a64bcdf500743500ed59 | 0                      | 3            | 8      | -1          | NA         | NA       | NA      | NA                         | NA          | NA       | NA     | NA          | 2018/5/21 | 
| 3              | 36            | 0        | people       |           | 0                     | 0  | 647ea90a251cc0dfe332ef7f68c7c207 | 0           | 39                      | 0                     | 0        | 工程师                      | engineer-coin            | 0            | 0                      | 0              | 163   | 0             | 92   | people    | 0x7a6239          | https://pic2.zhimg.com/v2-ad4d3ef6a958df286feadff8059c5fd2_{size}.jpg | 1           |                                              | https://pic2.zhimg.com/v2-ad4d3ef6a958df286feadff8059c5fd2_is.jpg | 0               | 0        | 1526722690   | 0                    | 0        |                                                                  | 0           | 0           | 6             | 2    | Engineer Coin | 0                    | 0   | http://www.zhihu.com/api/v4/people/647ea90a251cc0dfe332ef7f68c7c207 | 0                      | 7            | 14     | -1          | NA         | NA       | NA      | NA                         | NA          | NA       | NA     | NA          | 2018/5/21 | 
| 4              | 0             | 0        | people       |           | 0                     | 0  | 8da4621ca2c137b1db34329f3863b2fe | 0           | 321                     | 0                     | 0        | 区块链独立投资者，布道者，心理咨询师，摄影爱好者 | juneorjim                | 0            | 0                      | 0              | 198   | 0             | 386  | people    |                   | https://pic2.zhimg.com/v2-d383b0e2b37cd104ce5392b1384f11c3_{size}.jpg | 4           | 个人vx：「han_juice 」，加我请备注「知乎」                  | https://pic2.zhimg.com/v2-d383b0e2b37cd104ce5392b1384f11c3_is.jpg | 0               | 0        | 1522204218   | 0                    | 0        | https://pic1.zhimg.com/v2-24ac59f8875304db6ddaf6ffc99ad7b6_r.jpg | 0           | 0           | 4             | 5    | Juneorjim     | 0                    | 0   | http://www.zhihu.com/api/v4/people/8da4621ca2c137b1db34329f3863b2fe | 0                      | 4            | 13     | 1           | NA         | NA       | NA      | NA                         | NA          | NA       | NA     | NA          | 2018/5/21 | 
| 5              | 9             | 0        | people       |           | 0                     | 0  | 37655fbb05db12b74326d7c71293989f | 0           | 214                     | 0                     | 7        | 技术营销党                    | microawareness           | 0            | 0                      | 0              | 289   | 0             | 298  | people    |                   | https://pic3.zhimg.com/v2-e06b0f468299d9b8c3566dbd969febc3_{size}.jpg | 5           | 技术营销党，量化交易，区块链社群&lt;币盈会&gt;，公众号&lt;刹那区块链&gt; | https://pic3.zhimg.com/v2-e06b0f468299d9b8c3566dbd969febc3_is.jpg | 1               | 0        | 1            | 0                    | 0        | https://pic2.zhimg.com/v2-90d47d4546441190892171c3270aa288_r.jpg | 0           | 0           | 17            | 73   | 微觉            | 0                    | 0   | http://www.zhihu.com/api/v4/people/37655fbb05db12b74326d7c71293989f | 0                      | 39           | 46     | 1           | NA         | NA       | 高新科技    | jiashidata.com             | NA          | 上海,北京,浙江 | NA     | 杭州电子科技大学    | 2018/5/21 | 
| 6              | 226           | 0        | people       | 编辑推荐      | 2                     | 2  | 803346fc485f89b5232a0d105123cc85 | 6           | 35476                   | 0                     | 51       | 技术分享 咨询：yrjyrj-hero      | li-ming-yang-86-56       | 1            | 0                      | 1              | 11224 | 0             | 8893 | people    |                   | https://pic2.zhimg.com/v2-86ee29fa490595c294c7ec4cd2dc71a2_{size}.jpg | 55          |                                              | https://pic2.zhimg.com/v2-86ee29fa490595c294c7ec4cd2dc71a2_is.jpg | 1               | 0        | 1447593792   | 0                    | 0        | https://pic4.zhimg.com/v2-aedafc643ac56650de728ec342fa6b4c_r.jpg | 0           | 0           | 673           | 29   | 李明阳           | 11                   | 0   | http://www.zhihu.com/api/v4/people/803346fc485f89b5232a0d105123cc85 | 71                     | 780          | 3167   | 1           | NA         | NA       | 互联网     | IBM,大众集团（Volkswagen Group） | 软件工程师,软件工程师 | 北京       | NA     | NA          | 2018/5/21 | 




## user_following_bitcoin

**Simple version of user information: only include their follower count, anser count etc. Information like job/education not indcluded**

|| answerCount | articlesCount | avatarUrl | avatarUrlTemplate                                                 | badge                                                                 | followerCount | gender | headline | id                       | isAdvertiser                     | isFollowed | isFollowing | isOrg | name | type    | url    | urlToken                                                            | userType           | record_date |  |
|-------------|------|---------|-----------|-------------------------------------------------------------------|-----------------------------------------------------------------------|---------------|--------|----------|--------------------------|----------------------------------|------------|-------------|-------|------|---------|--------|---------------------------------------------------------------------|--------------------|-------------|-----------| 
| 1           | 126           | 0         | https://pic3.zhimg.com/v2-513daec907fe5a31e57318e385f18c10_is.jpg | https://pic3.zhimg.com/v2-513daec907fe5a31e57318e385f18c10_{size}.jpg | list()        | 164    | 1        | One for all, all for one | 2aeb9587cc3aba38256823dcb28398f0 | 0          | 0           | 0     | 0    | 小刀      | people | http://www.zhihu.com/api/v4/people/2aeb9587cc3aba38256823dcb28398f0 | zengweihong        | people      | 2018/5/21 | 
| 2           | 127           | 15        | https://pic1.zhimg.com/v2-ad8138815e2d962861793d54b8c79fe7_is.jpg | https://pic1.zhimg.com/v2-ad8138815e2d962861793d54b8c79fe7_{size}.jpg | list()        | 1299   | 1        | 区块链投资 研究  微信公众号：区块链朋克    | 9dc8827c68b51e58583886070a809e70 | 0          | 0           | 0     | 0    | 区块链朋克   | people | http://www.zhihu.com/api/v4/people/9dc8827c68b51e58583886070a809e70 | chen-yan-yu-2      | people      | 2018/5/21 | 
| 3           | 2             | 0         | https://pic4.zhimg.com/59a3f51f6_is.jpg                           | https://pic4.zhimg.com/59a3f51f6_{size}.jpg                           | list()        | 48     | 1        | 1                        | 8740f61708fdeab719d76f7bcc30bf12 | 0          | 0           | 0     | 0    | pota水手  | people | http://www.zhihu.com/api/v4/people/8740f61708fdeab719d76f7bcc30bf12 | potacharles        | people      | 2018/5/21 | 
| 4           | 11            | 0         | https://pic4.zhimg.com/v2-4f9a89252c217282d2debf361b813dd7_is.jpg | https://pic4.zhimg.com/v2-4f9a89252c217282d2debf361b813dd7_{size}.jpg | list()        | 278    | 1        | 炒币五载                     | 2f5d477d666df2b12f3056477f294aef | 0          | 0           | 0     | 0    | 水瓜瓜     | people | http://www.zhihu.com/api/v4/people/2f5d477d666df2b12f3056477f294aef | xu-jia-hua-68      | people      | 2018/5/21 | 
| 5           | 26            | 19        | https://pic3.zhimg.com/v2-74143ed4c1e4dec5a6121cbee75a861c_is.jpg | https://pic3.zhimg.com/v2-74143ed4c1e4dec5a6121cbee75a861c_{size}.jpg | list()        | 2030   | 1        |                          | 150d1cb01d19d56810bc13892a01dbdf | 0          | 0           | 0     | 0    | Ruomise | people | http://www.zhihu.com/api/v4/people/150d1cb01d19d56810bc13892a01dbdf | ruomise            | people      | 2018/5/21 | 
| 6           | 5             | 39        | https://pic3.zhimg.com/v2-9494a76c1ae2ee921a85dc4d6dc94508_is.jpg | https://pic3.zhimg.com/v2-9494a76c1ae2ee921a85dc4d6dc94508_{size}.jpg | list()        | 1167   | -1       | 区块链普及者。v:wudatou00       | cfdebe7ab2816f23a7c1379f8bc06a66 | 0          | 0           | 0     | 0    | 大头      | people | http://www.zhihu.com/api/v4/people/cfdebe7ab2816f23a7c1379f8bc06a66 | hui-ren-bu-juan-98 | people      | 2018/5/21 | 


## follower_following_bitcoin

**A two-column table, displays the relationship between users. Useful for uesr relationship analysis.**

| | follower | following        | |
|----------|-----------|-------|---------------| 
| 1        | arthur-wang-9999 | zengweihong   | 
| 2        | baskice          | undefined     | 
| 3        | baskice          | chen-yan-yu-2 | 
| 4        | baskice          | aijunqiang    | 
| 5        | baskice          | potacharles   | 
| 6        | baskice          | xu-jia-hua-68 | 