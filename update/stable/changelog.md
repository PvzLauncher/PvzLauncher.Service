## 更新

* 支持直接将游戏文件夹拖放至启动器导入 [#279](https://github.com/PvzLauncher/PvzLauncher/issues/279)
* 开始下载更新时显示提示 [#276](https://github.com/PvzLauncher/PvzLauncher/issues/276)
* 统一显示加载屏幕的方法，并扩展加载屏幕至整个窗口
* 内部下载引擎改为多线程下载器，大幅提升下载速度
* 重绘经典游戏图标
* 添加公告时效性，过时的公告将取消显示
* 添加游戏图标 `植物大战僵尸 幼儿园版` [#260](https://github.com/PvzLauncher/PvzLauncher/issues/260)
* 移除了版本过大的下载提示，改为由每个改版信息定义的自定义信息
* 垃圾清理更新，支持删除十日之前的过时日志
* 从现在起程序仅支持单一实例，不可多开
* 现在覆盖窗口运行时无法修改启用状态
* 添加对 `Wine` 环境的特殊判断

## 更改

* 解析游戏图标失败时，显示原版游戏图标，而非骇人的紫黑方格
* 调试与 `CI` 构建提示改为左下角水印，而非之前的Snackbar信息提示
* 日志文件名结构由 `pvzl.log.[时间戳].log` 改为 `pvzl.[时间戳].log`
* `Release` 构建不会输出 `DEBUG` 等级的日志

## 修复

* 修复覆盖界面热键注册异常未被正常捕获的问题 [#288](https://github.com/PvzLauncher/PvzLauncher/issues/288)
* 修复 `日语` 本地化文本的一处符号错误
* 修复了一个潜在的栈溢出问题
* 修复了Overlay信息窗口可能在关闭后被调整可见性的问题
