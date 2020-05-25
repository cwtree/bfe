# 响应状态码相关条件原语

## res_code_in(codes)
* 语义: 判断响应状态码是否为指定的状态码codes之一

* 参数

| 参数      | 描述                   |
| --------- | ---------------------- |
| codes     | String<br>状态码列表, 多个状态码之间使用&#124;分隔 |

* 示例

```go
res_code_in("200|500")
```
