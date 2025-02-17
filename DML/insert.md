# 插入单条数据
insert into 表名 (列1，列2) values (值1， 值2);

# 插入多条数据
insert into 表名 (列1，列2) 
select (值1， 值2) from dual
union all
select (值1， 值2) from dual
union all
select (值1， 值2) from dual;
