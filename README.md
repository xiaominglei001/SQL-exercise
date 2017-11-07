
# xiao自增注意事项
例子中的创建语法适用于MySql,如果想看SQLite也可以在**SQL Exercises** [https://en.wikibooks.org/wiki/SQL_Exercises]. 中查看
## 自己笔记
### 外键相关
建立外键可以用如练习1的:FOREIGN KEY (Manufacturer) REFERENCES Manufacturers(Code),其中Manufacturer是表2中的字段,Manufacturers是表2的名字,Code是表2的字段,通过SQLyog查询表2的建表DDL语句,可以发现引擎会自动给这个外键赋值,方便以后管理.


# SQL-exercise
Schemas, Questions &amp; Solutions for SQL Exercising

## Introduction
The schemas and questions are 

[1] from Wikibook **SQL Exercises** [https://en.wikibooks.org/wiki/SQL_Exercises]. Solutions are from both this Wikibook and me (exercise 1-8). I also added some questions by myself.

or

[2] given by me using some practical examples I encountered (exercise 9-10).

## Repository Structure
The repo structure is like below:
```
SQL-exercise
└───SQL_exercise_1
└───......
└───SQL_exercise_*
    │   *_schema_figure.png
    │   *_build_schema.sql
    │   *_questions_and_solutions.sql

└───......

```

## License
Please note this repostory is under the Creative Commons Attribution-ShareAlike License[https://creativecommons.org/licenses/by-sa/3.0/].
