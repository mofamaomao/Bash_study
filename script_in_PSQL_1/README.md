insert_data.sh 将两个.csv文件内容自动插入数据库

pg_dump --clean --create --inserts --username=freecodecamp students > students.sql
此命令将创建好的students库导出
