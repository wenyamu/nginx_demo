## nginx 服务器配置
- 转发服务器 nginx_f 只负责转发请求
  - 配置文件为 f-nginx.conf
- 动态服务器 php-fpm
  -用于 php 文件的解析
- 静态服务器 nginx_s
  -配置文件为 s-nginx.conf

## 创建容器
```
docker compose -f nginx-f.yml up -d
```
