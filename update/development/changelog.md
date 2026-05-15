> [!NOTE]
> 之前由于某些原因，导致停更了几周。因此囤积了很多Issue没有被解决<br>
> 所以此版本就是解决这些BUG以及优化的，并且实行新的版本发行规则

## 更新

* **依赖**
  + **SharpCompress**: `0.42.1` -> `0.48.1` 因为此前的 `0.42.1` 版本被标记为易受攻击的版本
* **关于**: 添加常见问题查看入口 [#189](https://github.com/PvzLauncher/PvzLauncher/issues/189)
* **更新**: 检测到更新时添加查看Release界面的入口 [#174](https://github.com/PvzLauncher/PvzLauncher/issues/174)

## 更改

* **错误报告**: 非严重性错误现改为Snackbar提示，而非显示一个骇人的`错误对话框` [#186](https://github.com/PvzLauncher/PvzLauncher/issues/186)
* **更新器**: 添加条件判断，避免两个更新器同时运行导致冲突 [#198](https://github.com/PvzLauncher/PvzLauncher/issues/198)
