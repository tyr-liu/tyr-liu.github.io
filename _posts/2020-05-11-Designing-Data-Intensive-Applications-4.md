---
layout:     post
title:      "数据密集型应用设计（四）"
subtitle:   "读书手记"
date:       2020-05-10 23:10:00
author:     "Tyr"
header-img: "img/earth-desert-dry-hot-60013.jpg"
tags:
    - 读书笔记
    - 软件架构
    - 数据密集型应用设计
---

## 编码与演化

> 本章主要描绘当应用生命周期中，当数据模式（schema）发生变更时，我们如何通过合适的数据编码去拥抱变化。

其实吧，这章新鲜的内容不多。无非是json和二进制数据，在rest api，数据存储，消息通信和rpc调用中的优劣。

也提到一些基于json存储的二进制变种，类似jsonb，比如avro，有空研究看看。