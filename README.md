# InfectionFreeZoneMod

## 功能

* 修改移动速度
* 修改工作速度（搜寻、采集、建造速度）
* 任意添加人口
* 关闭地图时自动恢复视角
* 保存游戏
  * 从游戏内的ESC菜单保存游戏。
  * 已添加游戏保存成功的弹窗提醒。
  * 游戏存档保存位置：`%LOCALAPPDATA%Low\JutsuGames\Infection Free Zone Demo\Saves`
  * 可以将游戏存档打包分享给好友哦。
* 加载游戏
  1. 从游戏大厅的主菜单处加载游戏。
  2. 会弹出“在演示版中不可用”的对话框，不用管，直接点确定。
    （现在被我改成了我的小广告>.<）
  3. 载入完成后，游戏会默认隐藏用户界面并暂停游戏。
  4. 此时按`B键`即可显示用户界面，按`F1键`恢复游戏运行。
* 注意，保存与加载游戏功能为游戏内置功能，有少许BUG，但基本不影响使用。

## 已知BUG

* 重新加载游戏存档后，通过鼠标滚轮放大视野后不会切换到网格地图模式。基本没啥影响。
* 第一次保存游戏存档，可能会导致游戏进程自动退出，但是游戏存档是保存成功了的，所以不算问题。

## 热键

* `空格键` 立即查看总部（注意会同时暂停游戏）
* `F1` 循环选择并查看单个小队
* `Ctrl + F1` 连续选择并查看多个小队
* `小键盘数字键0` 重置工作速度和移动速度
* `小键盘数字键1` 添加4个人口
* `小键盘数字键2` 移动速度减少一倍
* `小键盘数字键3` 移动速度增加一倍
* `小键盘数字键4` 查看当前移动速度和工作速度
* `小键盘数字键5` 工作速度减少一倍
* `小键盘数字键6` 工作速度增加一倍

## 安装

1. 下载 [BepInEx-Unity.Mono-win-x64-6.0.0-be.672](https://builds.bepinex.dev/projects/bepinex_be/672/BepInEx-Unity.Mono-win-x64-6.0.0-be.672%2B472e950.zip)，将所有文件解压至游戏根目录，确保 `BepInEx` 文件夹和 `winhttp.dll` 等文件与游戏主程序 `Infection Free Zone Demo.exe` 处在同一目录。
2. 删除旧版本MOD。检查游戏目录 `Infection Free Zone Demo\BepInEx\plugins`，如果存在旧版本的本MOD，请先手动删除，以免发生文件冲突。
3. 从 [Releases](https://github.com/abevol/InfectionFreeZoneMod/releases) 下载 InfectionFreeZoneMod 压缩包文件，将所有文件解压至 `Infection Free Zone Demo\BepInEx\plugins` 目录。

## 其它

### 如何突破Demo版8天游玩限制

删除游戏文件：`Infection Free Zone Demo\Infection Free Zone Demo_Data\StreamingAssets\EventsSystem\Events\event_demo_end.json`

### 游戏内置热键一览

1. `空格键` 暂停/恢复游戏
2. `F1` 一级游戏速度
3. `F2` 二级游戏速度
4. `F3` 三级游戏速度
5. `ESC` 游戏菜单
6. `C` 显示/隐藏 标签名称
7. `V` 显示/隐藏 资源标记
8. `B` 显示/隐藏 用户界面
9. `N` 显示/隐藏 完整信息（Alpha版不可用）
10. `Ctrl` 禁用放置对齐
11. `Q` 旋转视角
12. `E` 旋转视角
13. `Z` 旋转建造模板
14. `X` 旋转建造模板
15. `Shift + 鼠标右键` 小队命令队列
16. `Ctrl + 鼠标左键` 选择多个小队
17. `Ctrl + 数字键1-9` 给选中的多个小队编组
18. `数字键1-9` 加载已编组的小队
