# Service 命令

Service 命令是对Linux系统下的服务状态管理的工具，通过`service`命令可以方便的完成服务的管理

## 启动服务
```
service <service> start
``` 
启动指定服务，将`<service>`换为你使用的服务。
比如
```
service nginx start
```
就是启动Nginx