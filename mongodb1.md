#mongodb
###导语
这是我写的第一个记录学习过程的文章,为了以后方便查阅,避免重复地学习,也为了知道自己这一段时间学习的方向.

###启动mongodb服务（mongod）
mac:
`sudo /usr/local/Cellar/mongodb/3.0.7/bin/mongod`

* 没有后台启动，如果命令窗口关掉，mongod就关闭了

###启动命令行客户端（mongo）
`/usr/local/Cellar/mongodb/3.0.7/bin/mongo`

* mongo是基于javascript的，所以交互方式很像js的控制台e

###mongodb中的各种名词的概念及关系
* 包含关系: 数据库>集合>文档


|操作	|数据库				|集合	|文档	|
|:-:	|:-:				|:-:	|:-:	|
|创建	|use name			|db.createCollection('name')|db.name.insert({})
|使用	|use name			|db.name.xxx	|db.name.save()
|显示	|show dbs			|show collections|db.name.find()
|删除	|db.drowDatabase()	|db.name.drop()	|db.name.remove()

###学习资源
中文文档/教程:
[菜鸟笔记](http://www.runoob.com/mongodb/mongodb-tutorial.html)
[易百教程](http://www.yiibai.com/mongodb/home.html)
[mongo官方文档](https://docs.mongodb.org/getting-started/shell/client/)
