## 3.2 接口调用 {#3-2}

发送模板消息

| URI：/msg/send/template |
| :--- |


| 请求地址： |
| :--- |
| 请求方式：post |
| 请求头（**Header**） |
| 请求参数（**Request-Body**） |

| 参数 |
| :--- |


|  | 类型 | 格式 | 含义 |
| :--- | :--- | :--- | :--- |
| templateId | String |  | 消息模板id |
| titleParamList | List&lt;Object&gt; |  | 消息模板标题参数与值对象列表 |
| contentParamList | List&lt;Object&gt; |  | 消息模板正文参数与值对象列表 |

| 返回data内容如下 |
| :--- |


| code | Sting | 状态码 |
| :--- | :--- | :--- |
| message | Sting | 状态码对应的信息内容 |

[  
](http://10.88.0.213:4000/3_xiao_xi_fa_song/31_xiao_xi_ding_yi.html)

