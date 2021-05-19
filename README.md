# Hotel PricePrediction

This project is about the Hotel Price Prediction Challenge from https://www.heywhale.com/

### Data Description
字段名           | 数据类型      | 字段描述
-------------    | -------------|
数据ID	| string	| 数据的唯一ID，比如test_0，train_1024
容纳人数 |	int|	房间可以允许住几个人
便利设施	| string |	房间提供的便利设施描述，如是否有电视空调
洗手间数量	| float |	洗手间的数量
床的数量	| int	| 房间内床的个数
床的类型	| int	| 床的类型编码
卧室数量	| int	| 卧室的个数
取消条款	| int	| 取消条款的类型编码
所在城市	| int	| 民宿所在的城市编码
清洁费	| int	| 是否需要清洁费的0/1编码
首次评论日期	| string	| 民宿的首次评论日期
房主是否有个人资料图片	| string	| 民宿介绍中是否有房主个人资料照片
房主身份是否验证	| int	| 民宿房主身份是否验证过的0/1编码
房主回复率	| string	| 民宿房主消息回复率
何时成为房主	| string	| 房东何时成为该民宿的房主
是否支持随即预订	| string	| 是否支持随即预定
最近评论日期	| string	| 最近评论日期
维度	| float	| 民宿所在的维度
经度	| float	| 民宿所在的经度
民宿周边	| string	| 民宿周边的景区
评论个数	| int	| 民宿的历史评论个数
房产类型	| int	| 民宿的房产类型编码，如个人住宅、公寓等
民宿评分	| float	| 民宿的用户评分
房型	| int	| 房子类型编码，比如单间还是整间等
邮编	| int	| 民宿的邮编号码
价格	| float	| 民宿价格

Metric:
RMSE
