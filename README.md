gini-gapper-auth-nankai
===================

南开一卡通

### 通过 http://nankai-gateway.gapper.in 进行用户账号的验证和用户信息的获取

1. app.yml的配置
```
---
rpc:
  nankai_gateway:
    url: http://nankai-gateway.gapper.in/api
    client_id: <YOURCLIENTID>
    client_secret: <YOURCLIENTSECRET>
...
```

2. [nankai-gateway](https://github.com/genee-projects/nankai-gateway)
