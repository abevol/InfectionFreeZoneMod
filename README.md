# 无感染区模组

* 作者：青青草原专业抓羊（B站）
* QQ频道：[无感染区模组（ifzmod1024）](https://pd.qq.com/s/awxxxjsg2)

## 免责声明

本模组包括其衍生功能仅供学习交流使用，请勿用于商业用途，由于非法使用而产生的法律纠纷，请自行承担，本人概不负责。
游戏开发不易，请支持正版游戏！

## 如何安装

* （推荐）使用一键安装工具[【无感染区模组安装器】](https://gitee.com/floss/InfectionFreeZoneMod/raw/main/无感染区模组安装器.exe)进行安装，可以避免大部分问题。

## 预览

![Preview](https://gitee.com/floss/InfectionFreeZoneMod/raw/main/Preview.png)

## 功能

* 修改移动速度（通过 F5 键呼出模组设置菜单进行修改）
* 修改工作速度（搜寻、采集、建造速度）
* 任意添加人口
* 解锁离线地图
* 解锁全部建筑
* 解锁科技研究
* 解锁候选总部
* 解锁全部武器
* 解锁总部拆除按钮
* 解锁防御塔可装备任意武器
* 防御塔高亮显示已选择的武器
* 防御塔不再占用未选择的武器
* 防御塔夜间可运送武器和弹药
* 自动治疗
* 提前上班
* 推迟下班
* 重新平衡武器数值
* 扩展武器提示信息
* 解锁编组数量限制
* 游戏存档功能（修复中，暂不推荐使用）
* 自动搜寻资源
* 自动暂停后台游戏
* 自动恢复视角
* 禁止后台移动镜头
* 修复游戏暂停BUG
* 修复工人找不到空闲仓库BUG
* 修复小队找不到空闲仓库BUG
* 立即查看总部
* 自定义游戏热键
* 解除8天试玩限制
* 解锁防御建筑移除按钮
* 修复垂直改造建筑无法提升容量BUG
* Ctrl键最大化改造建筑
* 实装工具厂、寺庙、医院等建筑
* 日出时自动分配工人修复受损的建筑物
* 修复已下载地图列表部分中文显示为方块的问题
* 修复人物移动的相关BUG
* 修复小队移动的相关BUG

## 已知问题

1. 插件不能加载，出现红字的问题。可能的原因：
   * 游戏的完整路径内有中文。
   * 模组文件放错了位置。
2. 游戏存档存在诸多问题，这个不用再反馈了，正在修复中。
  （更新：游戏存档的问题太多了，暂时不修了，看看官方序章版是什么情况再说）

## 热键

* `F5` 显示模组设置菜单
* `H` 立即选择总部
* `G` 自动搜寻资源开关
* `F1` 循环选择单个小队
* `F4` 选择全部小队
* `Ctrl + F1` 连续选择多个小队
* `P` 添加人口（上限20）
* `J` 拆除建筑物
* `M` 设置主要总部

## 功能说明

* 保存游戏
  * 从游戏内的ESC菜单保存游戏。
  * 已添加游戏保存成功的弹窗提醒。
  * 游戏存档保存位置：`%LOCALAPPDATA%Low\JutsuGames\Infection Free Zone Prologue\Saves`
  * 可以将游戏存档打包分享给好友哦。
* 加载游戏
  1. 从游戏大厅的主菜单处加载游戏。
  2. 会弹出“在演示版中不可用”的对话框，不用管，直接点确定。
    （现在被我改成了我的小广告>.<）
  3. 载入完成后，游戏会默认隐藏用户界面并暂停游戏。
  4. 此时按`B键`即可显示用户界面，按`F1键`恢复游戏运行。

## 手动安装

1. 注意游戏的完整路径内不能有中文。
2. 下载 [BepInEx-Unity.Mono-win-x64-6.0.0-be.672](https://builds.bepinex.dev/projects/bepinex_be/672/BepInEx-Unity.Mono-win-x64-6.0.0-be.672%2B472e950.zip)，将所有文件解压至游戏根目录，确保 `BepInEx` 文件夹和 `winhttp.dll` 等文件与游戏主程序 `Infection Free Zone Prologue.exe` 处在同一目录。
3. 从 [Releases](https://gitee.com/floss/InfectionFreeZoneMod/releases/latest) 下载 InfectionFreeZoneMod 压缩包文件，将所有文件解压至游戏根目录，确保 `BepInEx` 文件夹与游戏主程序 `Infection Free Zone Prologue.exe` 处在同一目录。

## 其它

### 如何突破Demo版8天试玩限制

* 打上模组后即可自动解除8天试玩限制，无需删除游戏文件。

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
23. `~` 打开游戏控制台

### 游戏技巧

1. 如何增大改造建筑物的容量？
   方法一：使用模组自带的`Ctrl键最大化改造建筑`功能，在改造建筑物时，按住Ctrl键，就可以直接按照该建筑的最大容量改造了（注意，部分建筑物本来就很小，默认就已经是最大容量了，比如美国地图）
   方法二：游戏自带功能，在选择改造建筑物时，按住鼠标左键并拖动鼠标，比较矮的建筑物是向右拖，高的建筑物是往上拖，游戏根据拖动的距离判定改造容量的大小。
2. 建造放置城门时，城门的方向会随机旋转是怎么回事？
   也算是游戏BUG，游戏没有很好的判定玩家是单击放置还是拖动放置。
   解决方法，只需要在放置蓝色模板的时候，按住鼠标左键，然后往任意方向拖动鼠标，这个时候模板就会根据鼠标拖动的方向进行旋转，鼠标离中心点越远，则越容易控制旋转方向，然后选择好方向后放开鼠标就可以了。
3. 游戏过程中遇到各种弹窗错误、游戏崩溃怎么办？
   可以点击上报错误，以帮助游戏开发商收集错误信息，更快的解决游戏BUG。
   也可以反馈给群主，但有些BUG涉及的问题比较复杂，不保证都能解决。

### 推荐模组

* 更多尸潮MOD
  作者：夜舞乱殇（B站）
  简介：从第14天开始，每7天一次，总共20波140天尸潮。
  下载：<https://www.bilibili.com/read/cv25698562>
