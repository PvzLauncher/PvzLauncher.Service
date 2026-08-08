## 更新

* **游戏库**
  + 添加游戏 `植物娘大战僵尸` [#234](https://github.com/PvzLauncher/PvzLauncher/issues/234)
  + 添加游戏 `植物大战僵尸 BT版` [#235](https://github.com/PvzLauncher/PvzLauncher/issues/235)
  + 添加游戏 `植物大战僵尸 生态版`
  + 添加游戏 `植物大战僵尸 Universe` [#217](https://github.com/PvzLauncher/PvzLauncher/issues/217)
  + 添加游戏 `植物大战僵尸 疯狂的多元宇宙` [#219](https://github.com/PvzLauncher/PvzLauncher/issues/219)
  + 添加游戏 `MC大战僵尸2` 的图标 [#246](https://github.com/PvzLauncher/PvzLauncher/issues/246)
  + 重绘游戏 `植物大战僵尸 基岩版` 的图标
  + 添加游戏 `植物大战僵尸 基岩版` [#220](https://github.com/PvzLauncher/PvzLauncher/issues/220)
  + 添加游戏 `植物大战僵尸 塔防路线地图版` [#223](https://github.com/PvzLauncher/PvzLauncher/issues/223)
  + 添加游戏 `植物大战僵尸 大哥版` [#230](https://github.com/PvzLauncher/PvzLauncher/issues/230)
  + 添加游戏 `植物大战僵尸 Rouge版` [#232](https://github.com/PvzLauncher/PvzLauncher/issues/232)
  + 添加游戏 `植物大战僵尸 Legend` [#233](https://github.com/PvzLauncher/PvzLauncher/issues/233)
  + 添加游戏 `植物大战僵尸 抽卡版` [#237](https://github.com/PvzLauncher/PvzLauncher/issues/237)
  + 添加游戏 `戴夫大战僵尸` [#240](https://github.com/PvzLauncher/PvzLauncher/issues/240)
* **控件**: 滚动控件现在支持按住`Shift键`来横向滚动 [#244](https://github.com/PvzLauncher/PvzLauncher/issues/244)
* **游戏管理**: 添加收藏功能，收藏的游戏会被标记并置顶 [#227](https://github.com/PvzLauncher/PvzLauncher/issues/227)
* **彩蛋**: 愚人节会切换主题色为绿色
* **下载**: 下载游戏时如果游戏较大 *(≥500MB)* ，则会建议手动下载
* **关于**: 补齐缺失的库依赖声明
* **覆盖层**: 可以在游戏窗口上覆盖一层信息，例如：启动器Logo、卡槽快捷键
* **任务页**: **重构**任务页。现在任务完成**不会直接消失**，而是添加进下方的完成列表，并且可以**直接启动该游戏** *`(类 Steam 的任务页面)`*
* **杂项**: 支持使用 `Esc` 键退出当前页面

## 更改

* **杂项**
  + 下载缓存文件名改为Guid生成，而非之前的随机数生成
  + 如果开启存档隔离以及游戏正在运行，关闭启动器会有提示
* **本地化**
  + 修改文本 `保留所有权益` 为更加准确的 `保留所有权利`
  + 调整 `赞助` 为 `支持开发者`
* **图标**: 微调香蒲的右眼
* **提示框**: 延长提示框默认存在时长至5秒
* **错误报告**: 现在对话框不保留继续运行的选项，因为一旦出现未捕获的异常，程序的崩溃就在所难免
* **游戏管理**: 游戏运行时禁止修改游戏设置与更改当前游戏
* **依赖库**: 移除对 `HuaZi.Library` 的依赖

## 优化

* **动画**: 优化TabControl切换动画为渲染偏移而非真实边距
* **游戏**: 结束游戏后不会显示退出代码，而是显示此次游玩时间

## 修复

* **下载详情**: 修复了手动下载对话框点击取消仍然前往网盘的问题

## 移除

* **关于**: 移除Q&A入口
