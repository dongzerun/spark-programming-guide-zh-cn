Spark 编程指南简体中文版
=============================

* [Introduction](README.md)
* [快速上手](quick-start/README.md)
  * [Spark Shell](quick-start/using-spark-shell.md)
  * [独立应用程序](quick-start/standalone-applications.md)
  * [开始翻滚吧!](quick-start/where-to-go-from-here.md)
* [编程指南](programming-guide/README.md)
  * [引入 Spark](programming-guide/linking-with-spark.md)
  * [初始化 Spark](programming-guide/initializing-spark.md)
  * [Spark RDDs](programming-guide/rdds/README.md)
    * [并行集合](programming-guide/rdds/parallelized-collections.md)
    * [外部数据集](programming-guide/rdds/external-datasets.md)
    * [RDD 操作](programming-guide/rdds/rdd-operations.md) 
      * [传递函数到 Spark](programming-guide/rdds/passing-functions-to-spark.md)
      * [使用键值对](programming-guide/rdds/working-with-key-value-pairs.md)
      * [Transformations](programming-guide/rdds/transformations.md)
      * [Actions](programming-guide/rdds/actions.md)
    * [RDD持久化](programming-guide/rdds/rdd-persistences.md)
  * [共享变量](programming-guide/shared-variables.md)
  * [从这里开始](programming-guide/from-here.md)
* [Spark Streaming](spark-streaming/README.md)
  * [一个快速的例子](spark-streaming/a-quick-example.md)
  * [基本概念](spark-streaming/basic-concepts/README.md)
    * [关联](spark-streaming/basic-concepts/linking.md)
    * [初始化StreamingContext](spark-streaming/basic-concepts/initializing-StreamingContext.md)
    * [离散流](spark-streaming/basic-concepts/discretized-streams.md)
    * [输入DStreams](spark-streaming/basic-concepts/input-DStreams.md)
    * [DStream中的转换](spark-streaming/basic-concepts/transformations-on-DStreams.md)
    * [DStream的输出操作](spark-streaming/basic-concepts/output-operations-on-DStreams.md)
    * [缓存或持久化](spark-streaming/basic-concepts/caching-persistence.md)
    * [Checkpointing](spark-streaming/basic-concepts/checkpointing.md)
    * [部署应用程序](spark-streaming/basic-concepts/deploying-applications.md)
    * [监控应用程序](spark-streaming/basic-concepts/monitoring-applications.md)
  * [性能调优](spark-streaming/performance-tuning/README.md)
    * [减少批数据的执行时间](spark-streaming/performance-tuning/reducing-processing-time.md)
    * [设置正确的批容量](spark-streaming/performance-tuning/setting-right-batch-size.md)
    * [内存调优](spark-streaming/performance-tuning/memory-tuning.md)
  * [容错语义](spark-streaming/fault-tolerance-semantics/README.md)
* [Spark SQL](spark-sql/README.md)
  * [开始](spark-sql/getting-started.md)
  * [数据源](spark-sql/data-sources/README.md)
    * [RDDs](spark-sql/data-sources/rdds.md)
    * [parquet文件](spark-sql/data-sources/parquet-files.md)
    * [JSON数据集](spark-sql/data-sources/jSON-datasets.md)
    * [Hive表](spark-sql/data-sources/hive-tables.md)
  * [性能调优](spark-sql/performance-tuning.md)
  * [其它SQL接口](spark-sql/other-sql-interfaces.md)
  * [编写语言集成(Language-Integrated)的相关查询](spark-sql/writing-language-integrated-relational-queries.md)
  * [Spark SQL数据类型](spark-sql/spark-sql-dataType-reference.md)
* [GraphX编程指南](graphx-programming-guide/README.md)
  * [开始](graphx-programming-guide/getting-started.md)
  * [属性图](graphx-programming-guide/property-graph.md)
  * [图操作符](graphx-programming-guide/graph-operators.md)
  * [Pregel API](graphx-programming-guide/pregel-api.md)
  * [图构造者](graphx-programming-guide/graph-builders.md)
  * [顶点和边RDDs](graphx-programming-guide/vertex-and-edge-rdds.md)
  * [图算法](graphx-programming-guide/graph-algorithms.md)
  * [例子](graphx-programming-guide/examples.md)

## Copyright

本文翻译自[Spark 官方文档](https://spark.apache.org/docs/latest/)

## License

本文使用的许可请查看[这里](LICENSE)