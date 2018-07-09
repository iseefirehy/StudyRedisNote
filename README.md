# Redis学习笔记

![Packagist](https://img.shields.io/packagist/l/doctrine/orm.svg)

----
Redis是一个非关系型数据库(NOSQL--表示Not Only SQL)

#### 三个特点
1. high performance-高并发读写
2. high storage-海量数据的高效率储存的访问
3. high scalability&&high Availability-高可拓展性和高可用性

#### NOSQL数据库的四大分类

类型  | 优缺点|
--------- | --------|
键值(K-V)储存  | Redis |
列储存  | hbase 查询快速/hbase只能部署在hdfs上 |
文档数据库 | MongoDB,快速查询/数据缺少结构化，数据结构不严格，查询性低，缺少统一查询语法 |
图形数据库 | Infogrid，Neo4j，图结构算法，需要图形计算，不易做分布式计算 |

#### NOSQL优点
* 易拓展(数据之间没有关系)
* 灵活的数据模型
* 大数据量，高性能
* 高可用

#### Redis支持的键值数据类型
* 字符串类型
* 列表类型
* 有序集合类型
* 散列类型
* 集合类型

#### Redis应用场景 
* 缓存
* 任务队列--抢购秒杀
* 聊天列表  
* 网站访问统计
* 数据过期处理
* 分布式集群架构中的session分离

Redis持续读写可以达到10万次，读11万次/s,写81000次/s.



