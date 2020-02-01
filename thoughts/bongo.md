# bongo
想法：基于pure golang 的boltdb构建与mongodb具有相似查询与修改语法的数据库
架构：分三层
第一层：与boltdb进行交互
第二层：索引
第三层：查询与修改语法解析与执行层