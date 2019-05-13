

## 1. tools
1. mysqldump 最慢，导出导出单线程，导入source，或者 < , 
2. mysqlpump 官方并行,粒度是库，意义不大
3. mydumper - myloader ，并行导出导入，粒度是表
