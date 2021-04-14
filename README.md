# Mod推荐

记一下觉得还不错的mod，以辅助类为主。

本页除特殊说明外均为客户端Mod，无需服务端支持。

前置关系可能不全，发现问题请Issue/PR/直接QQ找我（

## Forge/Fabric通用

### OptiFine

光影包的前置，也提供了一些精细化的视频设置和一些优化。~~给作者买杯咖啡可以获得披风。~~

Fabric端依赖[OptiFabric](#OptiFabric)。

[官方](https://www.optifine.net/downloads)  [mcmod](https://www.mcmod.cn/class/36.html)

### Roughly Enough Items (REI)

***部分功能需要服务端支持。***

游戏内物品百科，可以根据物品查询合成表（包括熔炉配方等）。

鼠标指向一个物品（背包中或右侧列表均可），按R显示合成这个物品的合成表，U显示需要用这个物品的合成表，A收藏物品。鼠标指向收藏夹里的物品按A取消收藏。

Forge版支持不是很完善，建议改用[JEI](#Just Enough Items (JEI))。

[CurseForge (Fabric版)](https://www.curseforge.com/minecraft/mc-mods/roughly-enough-items)  [CurseForge (Forge版)](https://www.curseforge.com/minecraft/mc-mods/roughly-enough-items-forge)  [mcmod](https://www.mcmod.cn/class/1674.html)

### What The Hell Is That (WTHIT)

在屏幕上端显示准星指向的方块/实体的信息，加了不熟悉的mod或材质时可能有用。

虽然该mod支持Forge和Fabric，但其附属mod [CIMTB](#cAn i MiNe thIS bLOCk? (CIMTB))仅支持Fabric。在Forge端需要查看方块挖掘条件的话可以改用[Jade](#Jade)。

[CurseForge (Fabric版)](https://www.curseforge.com/minecraft/mc-mods/wthit)  [CurseForge (Forge版)](https://www.curseforge.com/minecraft/mc-mods/wthit-forge)  [mcmod](https://www.mcmod.cn/class/3471.html)

### Inventory HUD+

- 显示盔甲和手持物品的耐久、背包空格子数量、箭的数量，可以配置仅在耐久低于某个比例时显示。
- 替换原版药水效果显示，可以把剩余时间显示为进度条或者数字。
- 显示背包内容，但占地极大且没什么用，可以关。

默认配置快捷键为O。

从CurseForge下载时需要在Description里点对应版本的按钮，或者去Files里挑一下，右上的Download下载到的不太对。

[CurseForge](https://www.curseforge.com/minecraft/mc-mods/inventory-hud-forge)  [mcmod](https://www.mcmod.cn/class/3395.html)

## 仅Fabric

### Fabric API

绝大多数Fabric Mod的前置，装就完事了。

[CurseForge](https://www.curseforge.com/minecraft/mc-mods/fabric-api)  [mcmod](https://www.mcmod.cn/class/3124.html)

### Mod Menu

提供一个图形界面，显示已安装的mod的信息和配置。有一部分mod仅能通过该界面进行配置。

[CurseForge](https://www.curseforge.com/minecraft/mc-mods/modmenu)  [mcmod](https://www.mcmod.cn/class/1675.html)

### Carpet

***服务端Mod，少数功能需要客户端支持。***

为技术流玩家提供许多实用功能，还有一款脚本语言Scarpet。

[CurseForge](https://www.curseforge.com/minecraft/mc-mods/carpet)  [mcmod](https://www.mcmod.cn/class/2361.html)

### cAn i MiNe thIS bLOCk? (CIMTB)

依赖[WTHIT](#What The Hell Is That (WTHIT))。

显示准星指向的方块所需的挖掘工具。

[CurseForge](https://www.curseforge.com/minecraft/mc-mods/can-i-mine-this-block)  [mcmod](https://www.mcmod.cn/class/3084.html)

### Item Scroller

依赖[MaLiLib](#MaLiLib)。

提供了一堆针对物品栏界面的鼠标手势和快捷键，详情参考mcmod页面或者自己探索一下它的设置。

[CurseForge](https://www.curseforge.com/minecraft/mc-mods/item-scroller)  [mcmod](https://www.mcmod.cn/class/1529.html)

### MiniHUD

***少数功能需要服务端支持。***

依赖[MaLiLib](#MaLiLib)。

提供常驻于屏幕左上角的若干行文字（开启F3时自动隐藏），可以作为精简版的F3使用。同时提供了显示结构边界、史莱姆区块、渲染圆柱或球形等实用功能。

默认开关键为H，配置键为H+C。

[CurseForge](https://www.curseforge.com/minecraft/mc-mods/minihud)  [mcmod](https://www.mcmod.cn/class/2311.html)

### Litematica

依赖[MaLiLib](#MaLiLib)。

可以保存一个区域的结构，并投影到其他位置或其他世界，方便建造。

默认主菜单键为M。

[CurseForge](https://www.curseforge.com/minecraft/mc-mods/litematica)  [mcmod](https://www.mcmod.cn/class/2261.html)  [一个教程](https://tieba.baidu.com/p/6230849633?see_lz=1)

### EasierVillagerTrading

修改了村民交易UI的逻辑，安装后：

- 点击交易项会直接进行一次交易
- Shift+点击交易项会进行最大次数的交易
- Ctrl+点击交易项执行原版行为，即选择交易并把物品摆上去

[CurseForge](https://www.curseforge.com/minecraft/mc-mods/easiervillagertrading)  [mcmod](https://www.mcmod.cn/class/3466.html)

### Command GUI Buttons

提供一个图形界面，可以保存一些指令一键执行。（不一定是指令，任何聊天框能发的都可以。）

[CurseForge](https://www.curseforge.com/minecraft/mc-mods/command-gui-buttons)

## 仅Forge

### Just Enough Items (JEI)

***部分功能需要服务端支持。***

使用方法与[REI](#Roughly Enough Items (REI))一致。

游戏内配置界面依赖[FTB GUI Library](#FTB GUI Library)，但其实没什么好配置的，可以不装。

[CurseForge](https://www.curseforge.com/minecraft/mc-mods/jei)  [mcmod](https://www.mcmod.cn/class/459.html)

### Jade

***部分功能需要服务端支持。***

类似[WTHIT](#What The Hell Is That (WTHIT))，自带了显示挖掘条件的功能。

[CurseForge](https://www.curseforge.com/minecraft/mc-mods/jade)  [mcmod](https://www.mcmod.cn/class/3482.html)

## 依赖库

以下mod不直接提供任何功能，仅作为其他mod的前置。

### Architectury API

[CurseForge (Fabric版)](https://www.curseforge.com/minecraft/mc-mods/architectury-fabric)  [CurseForge (Forge版)](https://www.curseforge.com/minecraft/mc-mods/architectury-forge)  [mcmod](https://www.mcmod.cn/class/3434.html)

### FTB GUI Library

依赖[Architectury API](#Architectury API)。

[CurseForge (Fabric版)](https://www.curseforge.com/minecraft/mc-mods/ftb-gui-library-fabric)  [CurseForge (Forge版)](https://www.curseforge.com/minecraft/mc-mods/ftb-gui-library)  [mcmod](https://www.mcmod.cn/class/3184.html)

### MaLiLib

[CurseForge](https://www.curseforge.com/minecraft/mc-mods/malilib)  [mcmod](https://www.mcmod.cn/class/2298.html)

### OptiFabric

[CurseForge](https://www.curseforge.com/minecraft/mc-mods/optifabric)  [mcmod](https://www.mcmod.cn/class/1703.html)

