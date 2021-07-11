# tfcs 文件管理系统，可以将windows或linux的系统作为对外开放的文件系统

## window10 & centos7
### (1) centos7执行./tfcs;   window10 解压压缩包，点击tfcs.exe， 默认最小化（默认端口号8800，可右击图标查看具体端口号）
### (2) 网页 http://127.0.0.1:8800 默认用户名:admin 密码：admin123###
![login](https://user-images.githubusercontent.com/80773693/121704833-b31a0000-cb06-11eb-8759-8a252170826c.png)
### (3) 点击文件管理，可进入文件管理界面(支持移动端)
#### (3.1)支持基本文件夹操作（非根目录）：重命名、删除、上传文件夹、下载文件夹
#### (3.2)支持基本文件操作： 重命名、删除、上传文件、下载文件、打开播放文件
#### linux文件管理
![filemanagement](https://user-images.githubusercontent.com/80773693/123268390-90d5a880-d530-11eb-9666-c39eb9deb73e.png)
#### window文件管理
![windows-filemanagement](https://user-images.githubusercontent.com/80773693/123269818-ececfc80-d531-11eb-8ed9-f1aeb1273b16.png)
#### mobile文件管理
![mobile-filemanagement](https://user-images.githubusercontent.com/80773693/123270354-6e448f00-d532-11eb-9099-63d7317c7787.png)
### (4) 支持公网映射访问 
#### (4.1)服务端配置-比如再阿里云上启动该服务（一般情况下，同一系统服务端和客户端两选一）
![server](https://user-images.githubusercontent.com/80773693/123268442-9af7a700-d530-11eb-885d-b845dee1ab90.png)
#### 点击更新&启动，将启动服务端监听
#### (4.2)客户端配置（一般情况下，同一系统服务端和客户端两选一）
![client](https://user-images.githubusercontent.com/80773693/123268536-b19dfe00-d530-11eb-9559-1a596e9cc7d0.png)
#### 点击更新&启动，将更新客户端端连接服务端的ip、port和token信息
#### (4.3)客户端端口映射配置
![map](https://user-images.githubusercontent.com/80773693/123268563-ba8ecf80-d530-11eb-9843-089587951d20.png)
#### 点击增加，输入名称（唯一），外部端口，内部端口，内部ip 后 点击更新，如果状态显示connect success, 表示映射成功
#### (4.4)使用服务端ip+外部端口，就可以访问内网内部ip+内部端口的内网服务器


### （5）支持增加普通用户, 限制普通用户的目录访问权限，linux和windows均支持
![user_folder](https://user-images.githubusercontent.com/80773693/123268651-d1352680-d530-11eb-9569-d3ff631e5c51.png)


