# 1.登录金蝶显示语言未加载错误

**问题描述：**

登录金蝶时，右侧用户信息没有显示出来，登录显示语言未加载错误。

<img title="" src="file:///images/1.png" alt="">

**原因：**

金蝶管理中心的数据中心列表，数据中心记录对应的数据库被删除了，但是记录还在，登录对应的数据中心时查不到数据库数据。

**解决方案：**

恢复记录数据对应的数据库，或者将没有对应数据库的记录数据删除即可。
