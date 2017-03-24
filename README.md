# mongoose_CRUD
ExpressJS+Mongoose的增删改查
# 安装nodemon 
# npm i nodemon -g
# 启动
# nodemon start (记得开启 mongoDB 哦！)
# localhost:3000
## API
---------------------------------------------------------------------------------------------------------

| 操作          |  请求方式                         | 参数  |   说明   |
|:-------------:|:--------------------------------:|:-----:|:-----------------------:|
| /find          | GET                              |   id  |不传 id 则查询全部      |
| /add           | POST                             |name  id |id 与 name 都不可重复 |
| /del          | POST                              |  id     |不传id则什么都不删除   |
| /delall       | POST                               |   无    | 删除全部            |
| /update        | POST                              | id   | 修改id对应的name        |
