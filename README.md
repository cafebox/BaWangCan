# BaWangCan_Actions
Actions工具人自动报名大众点评霸王餐（免费试）

 - 微信公众号推送报名结果

## 第八套中小学生广播体操，现在开始...
第一节，_φ(❐_❐✧ 人丑就要多读书

┏(＾0＾)┛   ┏(´0｀)┛   ┏(´0｀)┛   ┏(´0｀)┛

┗(＾0＾)┏   ┗(｀0´)┏   ┗(｀0´)┏   ┗(｀0´)┏

┗(＾0＾)┛   ┏(´0｀)┛   ┏(´0｀)┛   ┗(｀0´)┏   ┗(｀0´)┏

_(:ι」∠)_好饿，但是不想动

睡觉没前途(￣o￣) . z Z　

## 运行环境

 - Github Actions

## 该更执行时间

在【***.github/python-packetage.yml***]更改如下代码

```python
on:
  schedule:
    - cron: '0 0 * * */7'  # */7，每周运行
```

## Secrets参数说明
 - CITY：***城市名（自定义）***
 - CITYID：***城市名的ID（大众点评获取）***
 - COOKIE：***COOKIE（大众点评获取）***
 - NICKNAME：***昵称（自定义）*** 
 - SCKEY：***[Server酱](http://sc.ftqq.com/?c=code)申请的SCKEY***

![Secrets参数](https://img-blog.csdnimg.cn/20210224103358477.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80MjAwOTgwNA==,size_16,color_FFFFFF,t_70)

## 更新 by ZhangJinbao520

 - 写作不易，您的Star✨是我前进的动力，感谢~

### 2021/02/24

 1. 微信公众号自动推送功能
