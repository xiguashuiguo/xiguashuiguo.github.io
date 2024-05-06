---
title: 为什么改host不会即时生效
date: 2024-04-28 16:07:33
tags:
  - host
  - tips
categories:
  - 随手记
---

### 为什么改host不会即时生效
当修改host 后，立马刷新，可能不会即时生效，这是由于存在[http长连接](https://zh.wikipedia.org/wiki/HTTP%E6%8C%81%E4%B9%85%E8%BF%9E%E6%8E%A5)，只需要休息一下，等两分钟就好，需要加速的话，可以去这个页面(chrome://net-internals/#sockets)提前关闭相关长连接。
