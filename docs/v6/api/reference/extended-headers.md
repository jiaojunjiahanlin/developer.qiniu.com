---
layout: docs
title: HTTP扩展字段
order: 200
---

<a id="extended-headers"></a>
# HTTP扩展字段

除了HTTP 1.1规范自带的各种字段外，七牛云存储还支持一系列扩展的请求头和响应头字段。

<a id="extended-request-headers"></a>
## 请求扩展字段

无。

<a id="extended-response-headers"></a>
## 响应扩展字段

字段名称    | 字段说明
:---------- | :------------
X-Reqid     | 上传请求的唯一ID。<br>通过该ID可快速定位用户请求的相关日志。在请求支持时提供该ID可大大提升问题解决速度。
X-Log       | 用于快速定位请求处理错误的参考信息。

如果下载过程中遇到任何错误，我们建议开发者将这些详细信息都写入日志。请求技术支持时如能提供这些错误信息以便快速排查。
