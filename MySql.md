# 基础

### 语法

```mysql
## 1.基础查询，其结果是一个虚拟的表
SELECT DISTINCT 列表(字段、常量值、表达式、函数) [AS] "别名"(别名中有特殊符号则必须使用"")
FROM 表名;

## 在 mysql '+' 是一个运算符，如果想要字符串拼接则使用函数
SELECT CONCAT(列名1,列名2)
FROM 表名;

## null 和任何拼接或者 '+' 结构都为 null
## 判断是空的函数 IFNULL

## 2.条件查询
SELECT * 
FROM 表名
WHERE
	筛选条件
## 条件运算符 >, <, =, <>, <=, >=, LIKE, BETWEEN AND, IN, IS NULL, IS NOT NULL
## 逻辑运算符 and, or, not

## 3.排序
order by

## 4.函数
### 字符函数
### 数学函数
### 日期函数
### 流程控制

## 5.分组查询



```









# 高级
