# 首先将所有sql文件合并为一个sql文件
cat *.sql > my_new.sql

# 然后执行这个sql文件
1. mysql -u root -p
2. use cc
3. source ....../my_new.sql
