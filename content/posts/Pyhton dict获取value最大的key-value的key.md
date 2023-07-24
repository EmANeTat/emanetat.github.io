---
title: "Pyhton dict 获取 value 最大的 key-value 的 key"
author: emanetat
description: 
date: 2023-07-24T16:36:41+08:00
draft: false
weight: 
hidemeta: false

cover:
    image: "<image path/url>" # image path/url
    alt: "<alt text>" # alt text
    caption: "<text>" # display caption under cover
    relative: false # when using page bundles set this to true
    hidden: true # only hide on current single page

categories: []
tags: [pyhton, test]

comments: false
---
```python
max_key = max(dict, key=dict.get)
```

相比于先用`items()`获得 k-y 的元组再用`max()`函数或者`sort()`排序的方法，这种方法更简洁。
