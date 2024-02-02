# 账号相关

## 账号获得

账号仅能由管理员创建，当忘记密码时，也仅能由管理员重置。

# 系统相关

系统分文以下几个模块

* [登陆](#login)
* [用户管理](#user)
* [设备管理](#device)

## <span id="login">登陆</span>

获得账号后，需要登陆后才能使用系统

![](/img/login.png)

## <span id="workplace">工作台</span>

登陆后默认显示页，也是系统主页。

![](/img/workplace.png)

## <span id="user">用户管理</span>

本模块用于管理用户账号，可以添加、删除、或修改用户。如需修改密码，点击对应用户后面的编辑按钮即可重置密码。

![](/img/user.png)

## <span id="device">设备管理</span>

本模块主要提供设备的接入、控制和信息查看

![](/img/device.png)

①可切换查看`我的设备`和`所有设备`，但是默认只能查看自己创建的设备，仅管理员可以查看其他人的设备

②设备的控制，控制设备订阅/取消MQTT话题；其他按钮为新建设备时自定义操作，具体信息请查看[设备添加](#add)

③点击3区域，即将显示设备详细信息，具体信息请查看[设备添加](#info)

④添加设备，请查看[设备添加](#add)

### 设备添加

点击添加设备后，按照[填写须知](#alert)填写相关信息即可。

![](/img/add.png)

* 名称和类型为必填项，操作为可选项。

  ==操作==：务必按照示例格式，填写标准数组

  TODO：优化此处输入

#### <span id="alert">填写须知</span>填

![](/img/alert.png)
