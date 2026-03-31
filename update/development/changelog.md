## 更新

* **下载详细页**: 支持点击图片并预览
* **关于**: 添加对 `lepoco/wpfui` 的鸣谢
* **回声洞**: 更新6条回声洞文本
* **下载详细页**
  + 支持显示游戏/修改器体积
  + 支持显示修改器支持版本
* **设置**: 支持修改游戏窗口标题 [(在官方文档上查看*)](https://pvzlauncher.github.io/tutorial/settings.html#游戏设置)
* **游戏管理**: 操作按钮在超出视图时支持折行显示
* **库**: 更新依赖库 `ModernWpf` 至版本 `0.9.8`

## 更改

* **颜色**: 降低卡片背景透明度
* **文本**: 将速度单位 `Mb/s` 修改为 `MB/s`
* **关于**: 更改描述文本
* **开发者控制面板**: 重置界面
* **文件系统**: 重命名文件夹 `Assets` 为 `Resources`
* **通知**: 更改通知区域为左下角，而非之前的整个底部
* **任务中心**: 修改部分通知消息文本

## 移除

* **关于**
  + 移除对 `Federerer/Notifications.Wpf` 的鸣谢
  + 移除对 `CounterAPI` 的鸣谢
  + 移除对 `microsoft/WebView2` 的鸣谢

## 修复

* **管理**: 修复空提示未及时隐藏问题 ([#137](https://github.com/PvzLauncher/PvzLauncher/issues/137))
* **主页**: 修复频繁点击回声洞会导致崩溃问题 ([#135](https://github.com/PvzLauncher/PvzLauncher/issues/135))
