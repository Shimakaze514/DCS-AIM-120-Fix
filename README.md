# DCS-AIM-120-Fix
### 中文
### 安装教程
安装：
1. 将"Shimakaze120Fix"文件夹解压后放入保存的游戏\mods\aircraft中
2. 将DCS根目录\CoreMods\aircraft\AircraftWeaponPack文件夹中的"aim120_family.lua"名称改为"aim120_family备份.lua"

卸载：
1. 将DCS根目录\CoreMods\aircraft\AircraftWeaponPack文件夹中的"aim120_family备份.lua"名称改为"aim120_family.lua"

已知问题：
* 若在未安装此mod的服务器上使用该mod有可能导致导弹显示不同步（你的客户端上显示导弹击中敌机，而敌机的客户端上导弹未击中而他直接凌空爆炸。反过来也有可能）；若服务器及所有玩家都安装了此mod则不会出现不同步。

### 原理
很简单，回滚到2.6版本。~~既然sd10曾经抄了120的导引律，那我把sd10的导引律抄到120身上就是回滚120版本了吧，嘿嘿嘿~~

## English
Install:
1. Extract and copy "Shimakaze120Fix" folder into SAVEDGAMES\mods\aircraft
2. Find "aim120_family.lua" in DCS\CoreMods\aircraft\AircraftWeaponPack, and rename it to "aim120_family_backup.lua"

Uninstall:
1. Rename "aim120_family_backup.lua" back to "aim120_family.lua"

Known Issue:
* Using this mod on server which didn't install the mod could cause missile display out of sync(your client indicated a missile hit, while on the other client the missile missed but somebody exploded in the air, or vise versa). If all clients and the server host installed the mod, there will be 0 chance to be out of sync.
