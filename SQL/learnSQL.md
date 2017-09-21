#检索出有不同值的列表
#关键字：DISTINCT，指示MYSQL返回不同的值
SELECT DISTINCT vend_id FROM products

#限制LIMIT,LIMIT 5指示返回不多于5行
SELE:CT prod_name FROM products LIMIT 5; 

#指定开始的行和行数
SELECT prod_name FROM products LIMIT 5,5;

#输出排序
SELECT prod_name FROM products ORDER BY prod_name
#指定排序方向，默认升序，使用DESC指定降序
SELECT prod_name FROM products ORDER BY pro_price DESC;

#找到最大的
SELECT prod_price FROM products ORDER BY DESC LIMIT 1;

#############################################################
#过滤数据
#同时使用ORDER BY和WHERE子句时，应该让ORDER BY位于WHERE之后
#两值之间BETWEEN...AND...

#空置检测
IS NULL

