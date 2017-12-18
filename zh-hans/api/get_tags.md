## 获取所有预设标签

### 请求 URL `GET`

```
/oauth2/tags
```

### 私有参数

```
无
```

> 通用参数必须，请参见：[通用参数](must.md)

### 数据集 格式`json`

| 字段名 | 变量名 | 类型 | 是否必须 | 示例 |
| ---- | ------ | -------- | ---- | --------- |
| 状态码 | `code` | `int` | 是 | `200` |
| 状态信息 | `msg` | `string` | 是 | `success` |
| 数据集 | `data` | `array` | 是 | ------ |

#### 数据集

| 字段名 | 变量名 | 类型 | 是否必须 | 示例 |
| ---- | ------ | -------- | ---- | ---- |
| 标签id | `id` | `int` | 是 | `2` |
| 标签名 | `name` | `string` | 是 | `测试` |

#### 状态码对应信息

```
200: 信息处理成功
```

#### 成功示例：

```json
{
    "code":200,
    "msg":"success",
    "data":[
        {
            "id":1,
            "name":"幼儿"
        },
        {
            "id":2,
            "name":"爱国"
        }
    ]
}
```