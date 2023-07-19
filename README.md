## v2flydemo
* v2fly 配置文件为 V4版本的配置文件[https://www.v2fly.org/config/overview.html]
* proxy.json 为代理配置，类似常规科学上网用的配置。
* bri-c.json、bri-s.json、nginx.conf 为v2fly 的反向代理相关配置。bri-s.json、nginx.conf为服务端配置(公网)，bri-c.json为客户端配置(内网)
## 启动命令 v2ray run -c ./proxy.json
