# Sprint 25 
(2016.11.14 -- 2016.11.25)  

## Features

### **at-users**

- 在输入框中输入'@'字符，触发用户列表弹窗
- 根据用户输入筛选列表
- enter、tab、click将选中用户添加到输入框内
- 上、下切换选中用户
- 获取光标位置、获取'@'位置
- 光标所在位置如与'@'位置之间有换行符'\n'则不触发at弹窗
- 设置一个缓存用户列表存放常用at用户，at触发时优先在该列表中筛选
- 常用列表中筛选不到则向后台发起搜索请求
- 如在某一光标位置后台已搜索不到用户，则标记该位置，光标前移才重新请求

### **magic-search**

- 搜索框、若干下拉搜索框、若干常用搜索条件
- 所有输入或选中搜索条件都可在搜索框中展示
- 搜索条件可以删除
- 有互斥搜索条件
- 搜索框输入进行下拉搜索匹配，选中的匹配项同时显示在下拉搜索框中
- 下拉搜索框可多选

## ToDo

- 将上述功能写成js插件
- chrome插件，如：将图片压缩、转为base64...