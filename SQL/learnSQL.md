#检索出有不同值的列表
#关键字：DISTINCT，指示MYSQL返回不同的值
SELECT DISTINCT vend_id FROM products

#限制LIMIT,LIMIT 5指示返回不多于5行
SELECT prod_name FROM products LIMIT 5; 

#指定开始的行和行数
SELECT prod_name FROM products LIMIT 5,5;
