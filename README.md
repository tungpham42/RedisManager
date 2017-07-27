# RedisManager
Redis 管理工具

## 为什么要写这款Redis管理工具呢？

由于市面上Redis工具真的是太少，还有跨平台问题，只局限于Windows或者Mac平台.

虽然Redis支持5大类型，但工具功能有限，使用起来非常不方便，所以决定写这款Redis管理工具，希望大家喜欢。也期待志同道合的同学们加入共同完善此工具。

## 操作步骤
1、配置Redis服务器信息 \application\extra\redis.php

    'servers' => array(
            array(
            'name'   => 'mf server', // Optional name.
            'host'   => '127.0.0.1',
            'port'   => 6379,
            // Optional Redis authentication.
            'auth' => '' // Warning: The password is sent in plain-text to the Redis server.
            )
        ),

2、启动Redis服务
3、安装php Redis扩展


### 联系方式

邮箱：626512443@qq.com

QQ：626512443

在此感谢大家对此工具的支持，也期待大家提出宝贵建议

                    _._
               _.-``__ ''-._
          _.-``    `.  `_.  ''-._           Redis
      .-`` .-```.  ```\/    _.,_ ''-._
     (    '      ,       .-`  | `,    )     Running in stand alone mode
     |`-._`-...-` __...-.``-._|'` _.-'|     Port: 6379
     |    `-._   `._    /     _.-'    |     PID: 888
      `-._    `-._  `-./  _.-'    _.-'
     |`-._`-._    `-.__.-'    _.-'_.-'|
     |    `-._`-._        _.-'_.-'    |
      `-._    `-._`-.__.-'_.-'    _.-'
     |`-._`-._    `-.__.-'    _.-'_.-'|
     |    `-._`-._        _.-'_.-'    |
      `-._    `-._`-.__.-'_.-'    _.-'
          `-._    `-.__.-'    _.-'
              `-._        _.-'
                  `-.__.-'

