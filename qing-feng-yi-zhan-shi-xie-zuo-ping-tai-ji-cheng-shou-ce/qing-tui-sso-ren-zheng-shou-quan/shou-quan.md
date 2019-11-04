## 2.2授权 {#2-2}

### 2.2.1获取用户信息 {#2-2-1}

**获取当前用户基本信息**

|  |  | **URI：/sysmgr/user/info** |
| :--- | :--- | :--- |
|  |  | **请求地址：** |
|  |  | **请求方式：get** |
|  |  | token放在request header内 |
|  |  | **data内容如下：** |
| **id** | **Sting** | **用户id** |
| **name** | **Sting** | **人员名称** |
| **profile** | **Sting** | **头像** |
| **mobile** | **Sting** | **移动电话** |

### 2.2.2获取用户所能看到的菜单 {#2-2-2}

**查询该用户对应的角色拥有的所有菜单**

|  |  | _**URI：sysmgr/resource/menu**_ |
| :--- | :--- | :--- |
|  |  | **请求地址：**[_**https://qaqtqbee.qingtui.cn/auth/\_api/\_sysmgr/resource/menu**_](https://qaqtqbee.qingtui.cn/auth/_api/_sysmgr/resource/menu) |
|  |  | **请求方式：get** |
|  |  | token放在request header内 |
|  |  | **菜单数据基本格式说明** |
| _**id**_ | _**Sting**_ | _**Id（为授权系统菜单唯一标识）**_ |
| _**name**_ | _**Sting**_ | _**菜单名称**_ |
| _**code**_ | _**Sting**_ | _**菜单编码**_ |
| _**outerId**_ | _**Sting**_ | _**outerId（为接入系统菜单唯一标识）**_ |
| _**icon**_ | _**Sting**_ | _菜单的图标_ |
| _linkUrl_ | _**Sting**_ | _菜链接的的url_ |
| _parentO**uterId**_ | _**Sting**_ | _**父节点（为接入系统 父节点id）**_ |
| children | _**Arraylist**_ | _**子节点**_ |
|  |  | _**json示例**_ |
|  |  | { |



