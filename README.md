# ch5_1 
# url_address : 118.89.25.125:8080
#environments : python2;
#		tornado framework;
#		mysql;
#		ps:Create 'University database' in mysql（'create database University'），and 	#		run files'Create_tables.sql' and 'insert_datas.sql' in this project to create #               tables and insert datas)

#(Terminal)First input :
```
pip install tornado
```

#Next,enter project folder and input：
```
python ch5_1.py
```

#Then you can input address 'localhost:8080' on the brower to visit

### 整个网站是一个数据库应用，可以对university数据库的student数据表进行CURD操作

- 在`/select`下，通过输入学生id来查找学生记录；若输入为空，则返回前20条学生记录
- 在`/delete`下，通过输入学生id来删除学生记录，不支持空输入，否则会返回空页面，且命令行报错
- 在`/update`，`/insert`下通过输入学生记录的所有字段来进行更新和插入操作，不支持空输入，否则会返回空页面，且命令行报错
