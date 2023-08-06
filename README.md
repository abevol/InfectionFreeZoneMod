# 无感染区模组

## 预览

![Preview](https://github.com/abevol/InfectionFreeZoneMod/blob/main/Preview.png?raw=true)

## 功能

* 修改移动速度
* 修改工作速度（搜寻、采集、建造速度）
* 任意添加人口
* 游戏存档功能（修复中，暂不推荐使用）
* 自动搜寻资源（画个饼先，暂不可用）
* 自动暂停后台游戏
* 自动恢复视角
* 禁止后台移动镜头
* 立即查看总部
* 自定义游戏热键

## 已知BUG

* 游戏存档存在诸多问题，这个不用再反馈了，正在修复中。

## 热键

* `空格键` 立即查看总部（注意会同时暂停游戏）
* `F1` 循环选择并查看单个小队
* `Ctrl + F1` 连续选择并查看多个小队
* `P键` 添加人口

## 功能说明

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

## 安装

1. 下载 [BepInEx-Unity.Mono-win-x64-6.0.0-be.672](https://builds.bepinex.dev/projects/bepinex_be/672/BepInEx-Unity.Mono-win-x64-6.0.0-be.672%2B472e950.zip)，将所有文件解压至游戏根目录，确保 `BepInEx` 文件夹和 `winhttp.dll` 等文件与游戏主程序 `Infection Free Zone Demo.exe` 处在同一目录。
2. 删除旧版本MOD。检查游戏目录 `Infection Free Zone Demo\BepInEx\plugins`，如果存在旧版本的本MOD，请先手动删除，以免发生版本冲突。
3. 从 [Releases](https://github.com/abevol/InfectionFreeZoneMod/releases) 下载 InfectionFreeZoneMod 压缩包文件，将所有文件解压至游戏根目录，注意保持文件结构匹配。

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
11. `Q` 向左旋转视角
12. `E` 向右旋转视角
13. `Z` 向左旋转放置模板
14. `X` 向右旋转放置模板
15. `Shift + 鼠标右键` 小队命令队列
16. `Ctrl + 鼠标左键` 选择多个小队
17. `Ctrl + 数字键1-9` 给选中的多个小队编组
18. `数字键1-9` 加载已编组的小队
19. `小键盘加号键` 拉近镜头
20. `小键盘减号键` 拉远镜头
21. `Alt` 越野行驶
22. `Alt` 强制攻击中立小队
