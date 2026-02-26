# Server fo GenShin CBT 1

# Requirements:
- Proxy is required to redirect dispatch to localhost:8099, or use integrated proxy if you want to use it locally.
- Resources for the server, get from [here](https://github.com/Hiro420/GI_CBT1_Data/tree/GenshinCBTServer_resources) then put them in a folder called "resources" in the same folder as the PS exe file.

# Notes:

- everything with * means it's required
- create new account:
account new (name)* (password)*

Commands:
- account new (name)* (password)*
- elfie (will spawn elfie for change team)
- teleport (uid)* (x)* (y)* (z)*

Features:
- Load in scene
- Enter dungeons
- Working CBT shop
- Teleport to scene points
- Chest gathering + unlock
- Combat system (still no ability manager)
- Seelies almost work!
- Avatar switch
- Weapon switch

---

# 中文翻译

# 原神 CBT1 服务器

# 要求：
- 需要代理将调度服务器重定向至本地 8099 端口，若想在本地使用，可使用集成代理。
- 需要自行编译！！！
- 服务器资源请自行在项目根目录下载zip文件，然后解压将其放入一个名为程序的根目录的文件夹中，该文件夹需与 PS 可执行文件位于同一目录下。

# 备注：

- 带 * 号的表示该项为必填项
- 创建新账户：
  account new (用户名)* (密码)*

命令列表：
- account new (用户名)* (密码)*
- elfie（召唤艾尔菲以更换队伍）
- teleport (玩家ID)* (X坐标)* (Y坐标)* (Z坐标)*

功能特性：
- 加载场景
- 进入秘境
- 可用的 CBT 商店
- 传送至场景锚点
- 宝箱收集与开启
- 战斗系统（暂不支持能力管理）
- 仙灵基本可用！
- 切换角色
- 切换武器
- #本项目不是本人开发，只不过修复了 NET8.0的一个jsonBug
