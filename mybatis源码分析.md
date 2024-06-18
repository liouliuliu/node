# 1、Mybatis的核心对象

## 1.Mybatis的核心对象及其作用

1. 数据存储类对象

   ​	概念：在Java中（JVM）对Mybatis相关的配置进行封装

   ​	mybatis-config.xml -------》 Configuration

   ​		Configuration

   ​			1.封装了mybatis-config.xml

   ​			2.封装了mapper 文件 MappedStatement

   ​			3.创建了Mybatis其他相关对象

   ​	XXXXXDAOMapper.xml -------> MappedStatement

