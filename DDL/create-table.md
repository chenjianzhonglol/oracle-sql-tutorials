# create table
create table 表名 (列名 类型 [default xxx] [约束]) [as select * from table2];

## 列类型
number
varchar2 创建时必须声明长度
date 默认当前时间可以用：sysdate
timestamp 默认当前时间可以用：CURRENT_TIMESTAMP

ex:
create table users (id number primary key, nickname varchar2(50), age number)