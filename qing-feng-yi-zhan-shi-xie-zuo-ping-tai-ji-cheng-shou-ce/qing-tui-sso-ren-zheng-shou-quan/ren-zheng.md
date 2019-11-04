## 2.1认证 {#2-1}

### 2.1.1登录 {#2-1-1}

_注：以下登录下相关的用户名和密码皆为轻推一站式互联协作平台的账号体系，开发者需登录平台获取得到账号和密码。（_[_https://qaqtqbee.qingtui.cn/）_](https://qaqtqbee.qingtui.cn/）)

|  |  |  | **URI：/sysmgr/sso/login** |
| :--- | :--- | :--- | :--- |
|  |  |  | **请求地址：\_**[**https://qaqtqbee.qingtui.cn/auth/\_api/sysmgr/sso/login**](https://qaqtqbee.qingtui.cn/auth/_api/sysmgr/sso/login) |
|  |  |  | **请求方式：post** |
| 参数1 | account | 类型 | String |
| 参数2 | password | 类型 | String |
|  |  |  |  |
|  |  |  | **data内容如下：** |
|  | token | **String** | **token格式如下：** |

### 2.1.2注销 {#2-1-2}

|  |  | **URI：/sysmgr/sso/logout** |
| :--- | :--- | :--- |
|  |  | **请求地址：\_**[**https://qaqtqbee.qingtui.cn/auth/\_api/sysmgr/sso/logout**](https://qaqtqbee.qingtui.cn/auth/_api/sysmgr/sso/logout) |
|  |  | **请求方式：get** |
|  |  | token放在request header内 |
|  |  | **data内容如下：** |
| **code** | **String** | **错误码** |
| **message** | **String** |  |
| **data** |  |  |
|  |  | 无论token是否合法均会注销成功 |

### 2.1.3检查token是否有效 {#2-1-3-token}

| **URI：** | [_**https://qaqtqbee.qingtui.cn/auth**_](https://qaqtqbee.qingtui.cn/auth) | **/api/sysmgr/sso/check** |
| :--- | :--- | :--- |
|  |  | **请求方式：get** |
|  |  | token放在request header内 |
|  |  | **data内容如下：** |
| **code** | **String** | **错误码** |
| **message** | **String** |  |
|  |  | token放在response header内（若token濒临过期，则会返回新的token，否则返回原token） |

### 2.1.4轻蜂平台统一登录系统流程 {#2-1-4}

### 2.1.5轻蜂平台第三方系统统一接入流程 {#2-1-5}

**在轻蜂平台中，创建第三方系统主入口即创建一级虚拟菜单，上传第三方系统的菜单，并采用在轻蜂平台内页打开即可**

