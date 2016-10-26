## Nginx 排障

## 提示 unknown directive 
在执行`Nginx -t ` 时，可能会遇见这样的报错
![](image/sp161026_125258.png)
这样的报错多为配置文件中有异常文字，可以根据提示查找
比如上图提示为 `/etc/nginx/sites-enabled/default` 文件的第`4`行存在代码错误