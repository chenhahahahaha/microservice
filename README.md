# microservice
cloud_demo

# 使用方法 
1. 首先启动provider-user项目
 - 访问http://127.0.0.1:8000/1
 - 返回结果
 ```
 {"id":1,"username":"account1","name":"张三","age":20,"balance":100.00}
 ```
2. user启动成功后 再启动consumer-movie
  - 访问http://127.0.0.1:8010/user/1
  - 返回结果
  ```
  {"id":1,"username":"account1","name":"张三","age":20,"balance":100.00}
  ```

