## 4.1 获取组织机构数据 {#3-1}

**接口名称: **获取同步组织列表

| URI：/sync/org |
| :--- |


| 请求地址： |
| :--- |
| 请求方式：get |
| 请求头（**Header**） |
|          |
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



