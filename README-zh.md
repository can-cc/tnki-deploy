
## 配置数据库
如果不使用 `docker-compose` 里的 `mysql`，需要设置外部 mysql 的环境变量

创建 `.env` 文件，并写入 JDBC 的设置

``` 
SPRING_DATASOURCE_URL=jdbc:mysql://127.0.0.1:3306/tnki
SPRING_DATASOURCE_USERNAME=tnki
SPRING_DATASOURCE_PASSWORD=tnki-secret-pw
```