## 管理端

1. 认证
2. 获取服务端信息
	* 版本号
	* 当前监听的服务
	* 每个服务上线的机器
3. 进入主菜单
	* 服务器
		* 增删改查
	* 客户端
		* 删查
	* 选择客户端
4. 进入客户端菜单
	* 列信息
	* 文件操作
		* 上传，下载
	* 隧道操作
		* 增删查
	* 交互式 Shell

### 命令

```
./admin
```

```
>> help
>> connect
>> auth
>> info
>> list
>> select
	common
		>> info
		>> gather
		>> download
		>> upload
		>> interact
		>> delete
		>> back
		>> alias
	rsh
		>> upgrade
		>> pty
	termite
		>> proxy
>> exit
```