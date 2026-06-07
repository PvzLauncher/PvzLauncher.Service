> [!note]
> 此次更新为 2026-6 月度更新

## 更新

* **依赖**
  + **SharpCompress**: `0.42.1` -> `0.48.1` 因为此前的 `0.42.1` 版本被标记为易受攻击的版本
* **关于**: 添加常见问题查看入口 [#189](https://github.com/PvzLauncher/PvzLauncher/issues/189)
* **更新**: 检测到更新时添加查看Release界面的入口 [#174](https://github.com/PvzLauncher/PvzLauncher/issues/174)
* * **虚拟导入**
  + 如果你需要导入一个**体积较大**的游戏，传统导入方法会**直接复制**一份到 `PvzLauncher游戏库` 下，导入过程非常慢；**虚拟导入**正是来解决此问题的，它可以直接创建一个**引用链接**。直接指向游戏原位置，不复制游戏文件就把游戏添加进库内 [#199](https://github.com/PvzLauncher/PvzLauncher/issues/199)

## 更改

* **错误报告**: 非严重性错误现改为Snackbar提示，而非显示一个骇人的`错误对话框` [#186](https://github.com/PvzLauncher/PvzLauncher/issues/186)
* **更新器**: 添加条件判断，避免两个更新器同时运行导致冲突 [#198](https://github.com/PvzLauncher/PvzLauncher/issues/198)

## 修复

* **启动**: 修复启动启动器时，程序工作目录未设置导致的加载错误 [#203](https://github.com/PvzLauncher/PvzLauncher/issues/203)
