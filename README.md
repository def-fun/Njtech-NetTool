# Njtech-NetTool
南京工业大学宿舍网自动登录/保持在线

非南京工业大学官方制作，仅供参考学习

### 可以实现的功能

1. 可以在客户端中登录Njtech-home，无需额外的网页认证
2. 用于防止Njtech-home掉线
3. 开机自动登录校园网

### 设置详细介绍

1. 防掉线：每隔5分钟自动发送一次网络请求，用来防止掉线

2. 自动登录：软件启动后的3分钟内会不断监测网络状态，如果不在线会自动登录

3. 开机启动：通过修改注册表实现开机启动（360等杀毒软件可能会警告，忽略即可）。勾选后按下保存即设置，取消勾选按下保存键会自动取消。开机启动和自动登录勾选后可以实现开机自动登录宿舍网。

4. 自动隐藏：自动登录成功后软件自动隐藏到系统托盘处（没什么用，只是为了让界面更加整齐）

### 如何使用

初次使用需要设置账号、密码以及运营商网络，功能按需勾选（懒得看直接全部打勾），最后记得按保存。

自动登录的原理是检测网络自动登录校园网，故请手动连接WIFI或者**设置WIFI自动连接**

### 安全

1. 软件不会收集和上传任何有关用户的信息，源代码在Github上。
2. 设置文件保存在其他文件夹而非软件中（非明文储存），可以放心将软件发送给其他同学而不必担心泄露账号密码。
3. 因为开源，可能会被植入恶意代码后传播，所以请使用时仔细辨认软件来源，确保无误后再进行使用。



