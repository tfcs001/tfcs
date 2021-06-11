# tfcs 
## window10
### (1) 点击tfcs.exe， 默认最小化（默认端口号8800，可右击图标查看具体端口号）
### (2) 网页 http://127.0.0.1:8800 默认用户名:admin 密码：admin123###
![login](https://user-images.githubusercontent.com/80773693/121704833-b31a0000-cb06-11eb-8759-8a252170826c.png)

### (3) 服务端配置（一般情况下，同一系统服务端和客户端两选一）
![server](https://user-images.githubusercontent.com/80773693/121706156-ef9a2b80-cb07-11eb-9660-506c311dfe9b.png)
点击更新&启动，将启动服务端监听


### (4) 客户端配置（一般情况下，同一系统服务端和客户端两选一）
![client](https://user-images.githubusercontent.com/80773693/121706176-f45edf80-cb07-11eb-8c3e-253fa7a683a0.png)
点击更新&启动，将更新客户端端连接服务端的ip、port和token信息

### (5) 端口映射配置
![map](https://user-images.githubusercontent.com/80773693/121706243-03de2880-cb08-11eb-92dd-5a1d0d1c7004.png)
点击增加，输入名称（唯一），外部端口，内部端口，内部ip 后 点击更新，如果状态显示connect success, 表示映射成功

### （6）使用服务端ip+外部端口，就可以访问内网内部ip+内部端口的内网服务器

## Centos7
