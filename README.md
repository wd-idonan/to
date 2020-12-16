# to
基于ssh登陆服务器工具,可给主机别名,记录登陆信息，方便管理

# 前提
You shoud install python3

# 安装
python setup.py install

# 使用
## 1.登陆
### 用完整信息登陆下主机
to [host] [user] [password] -p [port]
22端口可省略

### 登陆过一次后，会记录信息，可使用host登陆
to [host]

### 也可添加别名，登陆
to [host] -a [alias]
to [alias]

## 2.查看主机
to -l

## 3.删除
### 删除主机和别名
to -d [host]
### 删除别名
to -d [alias]





