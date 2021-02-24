# BaWangCan_Actions

## 大众点评每周自动报名

Actions工具人每周自动报名大众点评霸王餐（免费试）
 - 微信公众号推送报名结果

## 触发器

```python
on:
  push:
    branches: [ master ]
  pull_request:
    branches: [ master ]
  schedule:
    - cron: '0 0 * * */7'  # */7，每周运行
```

## 
# BaWangCan_Actions

## 大众点评每周自动报名

Actions工具人每周自动报名大众点评霸王餐（免费试）
 - 微信公众号推送报名结果

## 触发器

```python
on:
  push:
    branches: [ master ]
  pull_request:
    branches: [ master ]
  schedule:
    - cron: '0 0 * * */7'  # */7，每周运行
```

## Secrets参数
 - CITY：***城市名（自定义）***
 - CITYID：***城市名的ID（大众点评获取）***
 - COOKIE：***COOKIE（大众点评获取）***
 - NICKNAME：***昵称（自定义）*** 
 - SCKEY：***[Server酱](http://sc.ftqq.com/?c=code)申请的SCKEY***

![Secrets参数](https://img-blog.csdnimg.cn/20210224103358477.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80MjAwOTgwNA==,size_16,color_FFFFFF,t_70)
