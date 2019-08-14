# 后台
## mysql

|表|说明|
|-|-|
|[goods](#goods)|商品表|
|[refer_goods](#refer_goods)|推荐表|
|[richs](#richs)|富文本表|
|[classes](#classes)|类型表|
### goods

|字段|说明|类型|
|-|-|-|
|id|主键|int|
|title|名称|
|info|说明|
|classid|类型1学校食堂 2餐饮小吃 3休闲娱乐 4教室自习 4|
|refer-list|推荐id、数组|varchar|
|banner-list|轮播图、数组|varchar|
|richid|富文本id|
|latitude|经度|
|longitude|维度|

### refer_goods
|字段|说明|类型|
|-|-|-|
|id|主键|
|title|名称|
|info|说明|
|thumb|图片|
|goodsid|对应的商品id|
### richs
|字段|说明|类型|
|-|-|-|
|id|主键|
|rich_node|富文本内容|
|goodsid|商品id|
### classes
|字段|说明|类型|
|-|-|-|
|id|主键|
|class_text|类型内容|