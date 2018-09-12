# nginx-haprxy-tomcat-redis-mysql-graylog

### 这个是面试题目，面试官想看一下能不能完成复杂点的DOCKER-COMPOSE的脚本
    这里写了多个应用在里面

### 内容介绍
    NGINX 测试接口
    Haproxy 负载接口
    Tomcat1/Tomcat2 应用服务
    Redis 缓存
    Mysql 数据库
    Graylog 日志
 
### 配置事项
    在全局配置文件里加入graylog的API地址
    全局配置文件是.env

### 使用说明
    TOMCAT打开了MANAGER页面权限用户密码都是test,登录地址是 
    http://ip:8081/manager/html
    http://ip:8082/manager/html
    
    Haproxy配置是在对应目录下的conf，注意修改最后的几个服务器就可以了
    状态查看URL是 http://ip:8123/status
    
    Graylog初始密码是admin/admin
    登录地址是 http://ip:9000/status

### 效果图
![image](https://raw.githubusercontent.com/cychan0115/nginx-haprxy-tomcat-redis-mysql-graylog/master/img/0.png)
![image](https://raw.githubusercontent.com/cychan0115/nginx-haprxy-tomcat-redis-mysql-graylog/master/img/a.png)
![image](https://raw.githubusercontent.com/cychan0115/nginx-haprxy-tomcat-redis-mysql-graylog/master/img/c.png)
    
    

### 相关连接
	[CI脚本展示](https://github.com/cychan0115/ssm01-ci-test)
	
	[DOCKER-COMPOSE展示](https://github.com/cychan0115/nginx-haprxy-tomcat-redis-mysql-graylog)
	
	[GITLAB CI/CD展示](https://github.com/cychan0115/gitlabci-test)
