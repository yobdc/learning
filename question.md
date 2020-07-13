# Java
- HashMap底层
- HashMap和CourrentHashMap，为什么HashMap不安全？循环链接是什么时候发生的？segments是什-么？
- Java多线程，如何控制线程顺序执行，同步方法
- 两个线程，一个输出字母，一个输出数字，轮流输出。三个线程呢？
- A B C线程如何指定顺序循环唤醒
- 线程安全的单例
- Java内存模型
- 什么时候FullGC？什么对象会被回收？
- GC算法
- volatile关键字。内存屏障。
- 匿名内部类
- lamda表达式如何实现
- StringBuffer和StringBuilder区别
- ArrayList和LinkedList区别，哪个可以随机访问
- HashMap深挖，和TreeMap比较，put，get，扩容，并发问题，rehash？
- 如何实现零拷贝？具体方式和原理。
- 两个50亿url文件，内存2G，求交集（hashset+分治）。这种方法有什么问题？

# 数据结构与算法
- 插值算法与快排的区别
- 归并最优最坏，平均时间复杂度
- 堆排序手撕
- 1G内存，10G数据，如何排序？ 

# Spark
- Spark中有个节点特别慢，什么原因，如何解决
- Spark三种部署模式的区别
- reduceByKey和groupByKey的区别
- Spark Shuffle的过程
- 宽窄依赖介绍
- RDD介绍
- Spark cache和 persist的区别
- map join实现？应用场景？两张大表怎么选？（通过广播大变量；一般用在大表join小表，可容忍小表数据冗余的场景；两张大表就分而治之，再sort merge）
- spark-submit的过程

# Hadoop
- 什么是cap理论，hadoop哪些体现了cap
- hdfs HA实现原理
- hdfs读写流程 

# Kafka
- Kafka优点
- Kafka如何防止重消费
- Kafka数据丢失后怎么处理
- Kafka与其他mq的对比

# HBase
- 卡口数据为什么存hbase而不存到mysql，hbase的优点
- sqoop如何导入半结构化数据到hbase
- hbase高可用怎么实现
- hbase的读写流程
- HLog写入失败了怎么办
- RegionServer宕机后怎么办

# SQL
- 多表关联需要注意什么，有什么原则，join和=区别。

# Linux
- Linux中的epoll、select这些了解么