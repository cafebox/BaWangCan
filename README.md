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
    - cron: '0 0 * * */7'  # */7每周运行
```
