[返回导航页](https://cqzhen.github.io/blog.html "导航页面")

# mysql

### mysql 常用命令 

#### mysql 全局常用命令 
1. 显示 mysql 用户：
    1. 切换到数据库 mysql：use mysql
    2. 查看 user 表结构：desc user
    3. 查看 user 表里面的所有用户：select user,host from user
2. 显示 mysql 用户：select user();

#### mysql 常用命令 
1. 显示所有数据库：show databases
2. 选用数据库：use database
3. 显示当前数据库所有表：show tables;
4. 创建数据：CREATE DATABASE 数据库名;
5. 删除数据库：DROP DATABASE 数据库名;
6. 创建表：
7. 备份数据库：mysqldump -u root -p database_name > '../database_dump.txt'
8. 导入数据库：mysql -u root -p database_name < '../dump.txt'
9. 检查表结构：desc 'table_name'
