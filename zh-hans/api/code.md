## 状态码大致分布

```
200 - 299 接口处理成功，对应不同的成功信息
330 - 339 登陆错误（token错误），需要重新登陆
340 - 349 参数为空
350 - 359 参数错误
400 - 499 相关数据不存在
500 数据处理失败，未知错误
510 - 519 参数处理失败
550 - 559 缓存（读/存）失败
560 - 569 数据库（读/存）失败
600 - 699 第三方接口错误
```