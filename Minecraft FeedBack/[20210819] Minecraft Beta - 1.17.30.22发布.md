# Minecraft Beta - 1.17.30.22 (Xbox One/Windows 10/Android)

Posted: 18 August 2021
请在体验测试版前阅读一下本次更新摘要
PLEASE READ before participating in the Minecraft Beta

****

- 加入测试版将会覆盖您安装的《我的世界》。

- 在预览测试版时，您将无法访问Realms，也不能加入非测试版玩家。

- 在测试版中游玩的任何世界都不能在以前的游戏版本中打开，所以请记得备份一下你的地图存档以防丢失。

- 测试版本可能不稳定，且不代表最终的版本质量。

- 测试版本仅适用于Xbox One、Windows 10和Android(Google Play)。要加入或退出测试版体验，请参阅aka.ms/JoinMCBeta了解详细步骤
  
  *Joining the beta will replace your game with a work in progress version of Minecraft
  You will not have access to Realms and will not be able to join non-beta players while you're previewing the beta
  Any worlds played while in the beta cannot be opened in previous versions of the game so please make copies of worlds to prevent losing them
  Beta builds can be unstable and are not representative of final version quality
  The beta is available only on Xbox One, Windows 10, and Android (Google Play). To join or leave the beta, see aka.ms/JoinMCBeta for detailed instructions*

****

又到了基岩版测试版本更新的时候了！请记得在https://aka.ms/CavesCliffsFeedback的帖子中向我们发送您的反馈或寄出你的刀片，或在 [此处](https://bugs.mojang.com/) 反馈您在游戏中可能遇到的任何新的“特性”(bug)!  

> _It's time for another Bedrock Beta update! Please continue to send us your feedback in the threads at https://aka.ms/CavesCliffsFeedback, and search and report any new bugs you may encounter at [https://bugs.mojang.com](https://bugs.mojang.com/)._

****

## 实验特性

Experimental Features​

生物 - Mobs​

修复了当你在y=0下卸下任何可骑的实体(船、扫雷器、猪、马、步行者)，当你在水中或熔岩中时，它会将你传送到y=0，导致你死亡的问题。  

> Fixed incorrect position when dismounting at a negative world height ([MCPE-136622](https://bugs.mojang.com/browse/MCPE-136622))

****

## 特性和bug修复

Features and Bug Fixes​ 

### 制图师 - Cartographers

我们从第一个制图员那里买到一张地图，我们得到的地图和我们在地图上显示的区域是一样的。从第二个制图师那里购买一张地图会发现同样的地图，但并不显示已探索的部分。  

![](pic\20210819\1629363361208.png)

![](pic\20210819\1629363369383.png)

> Cartographers will now only give maps to undiscovered monuments ([MCPE-29375](https://bugs.mojang.com/browse/MCPE-29375))

### 附魔​ - Enchanting​

修复了附魔台的部分附魔出现几率并不平衡的问题  

> Enchanting Table's enchantment probability is now weighted ([MCPE-101588](https://bugs.mojang.com/browse/MCPE-101588))

### 原版特性 - Vanilla Parity​

修复了当不手持屏障方块时屏障消失的问题  
修复了屏障方块不阻拦弹射物的问题  
修复了屏障方块不会阻止玩家与其后面的方块交互的问题  
潜影盒现在在被销毁时会掉落里面的物品  
弓和三叉戟现在更类似于Java版本内的效果  
草的颜色和水的颜色不再略微随机化，且不再带有噪点  
废弃的村庄现在将更加罕见，更接近Java版的生成机制！**（作者:爷青回）**  

> Fixed Barrier Block hitbox missing when not holding a Barrier Block ([MCPE-137646](https://bugs.mojang.com/browse/MCPE-137646))  
> Fixed Barrier Blocks not blocking projectiles ([MCPE-137646](https://bugs.mojang.com/browse/MCPE-137646))
> 
> Fixed Barrier Blocks not blocking player interaction with blocks behind them  
> Shulker Boxes now drop their contents when destroyed as an item ([MCPE-129470](https://bugs.mojang.com/browse/MCPE-129470), [MCPE-87877](https://bugs.mojang.com/browse/MCPE-87877))  
> Bows and Tridents are now held more similarly to Java Edition ([MCPE-126717](https://bugs.mojang.com/browse/MCPE-126717), [MCPE-44418](https://bugs.mojang.com/browse/MCPE-44418))  
> Grass and water block tint colors are no longer slightly randomized with noise  
> Abandoned villages are now far rarer, more closely matching the Java Edition ([MCPE-71769](https://bugs.mojang.com/browse/MCPE-71769))

### 图形界面 - Graphical​

修复当有其他玩家使用市场通过互联网切换皮肤时，可能会导致三叉戟、盾牌和弩的位置显示不正确的问题  
修复了可能会导致望远镜在使用自定义皮肤时看起来像是被抛出一样的问题  
通过启用RTX时，会增加辐照度缓存样本大小以解决光线反射传播的问题启用抗锯齿后，物品栏不再会太暗（作者:一看就是眼神很好的人）在多人游戏时，准心不再闪烁

> Fixed a bug that could cause the Trident, Shield, and Crossbow to render incorrectly when an additional player is connected over the internet using a Marketplace skin ([MCPE-118358](https://bugs.mojang.com/browse/MCPE-118358))  
> Fixed a bug which could cause the Spyglass to appear as if it's being thrown when using a custom skin ([MCPE-127498](https://bugs.mojang.com/browse/MCPE-127498))  
> Fixed emissive light propagation in ray tracing mode by increasing irradiance cache sample size ([MCPE-135157](https://bugs.mojang.com/browse/MCPE-135157))  
> The hotbar is no longer too dark when anti-aliasing is increased ([MCPE-54213](https://bugs.mojang.com/browse/MCPE-54213))  
> The crosshair no longer flickers during multiplayer sessions ([MCPE-123918](https://bugs.mojang.com/browse/MCPE-123918))

![](pic\20210819\1629363958857.png)

![](pic\20210819\1629363995167.png)

### 市场 -Marketplace​

在市场中用新的旋转加载条替换原来的加载条（作者:旋转加载条也许更加有b格）

> Replaced loading bars with new loading spinner in the Marketplace

### UI部分 - User Interface​

修复了玩家物品栏和经验条并不对齐的问题（作者:太细节了！眼神非常好！）
修复了使用虚拟摇杆，长按输出框时切石机或织布机将会快速地合成物品的问题  
修正了试图启用缺少依赖项的材质包时出现的不正确的弹出信息（作者:我的信息框不会没信息了！）  
修正了一些包含大写字母的键的翻译问题  

> Fixed the hotbar being misaligned with XP bar by 1 pixel ([MCPE-46975](https://bugs.mojang.com/browse/MCPE-46975))  
> Using the touch interface, holding the output slot on the Stonecutter or Loom will now rapidly craft items ([MCPE-128423](https://bugs.mojang.com/browse/MCPE-128423))  
> Fixed an incorrect popup when attempting to activate a pack with a missing dependency ([MCPE-130978](https://bugs.mojang.com/browse/MCPE-130978))  
> Fixed translation issues for some keys containing upper case letters

![](pic\20210819\1629364360208.png)

![](pic\20210819\1629364585360.png)

****

## 技术性更新 - Technical Updates​

### 指令 - Commands​

行为包中定义的动画和事件现在可以通过作弊指令播放，而不需要启用作弊项(例如使用/gamerule命令设置某些规则)  

> Animations and events defined in Behavior Packs can now run commands that require cheats without the player enabling cheats (such as setting certain rules with the /gamerule command)

### 药水 - Potions​

“potion.prefix”和“potion..postfix”药水的字符串源已重命名为“potion_._.name”  
药水的名称已经更改，因此有单独的“Splash”和“Lingeing”的字符串源  
仍支持使用“potion.prefix”和“potion.*.postfix”的旧格式  

> "potion.prefix" and "potion..postfix" potion string resources have been renamed to"potion..name"  
> Potion name string resources have been changed so there are separate "Splash" and "Lingering" string resources  
> The old style of using "potion.prefix" and "potion.*.postfix" is still supported

### UI部分 - User Interface​

如果格式无效，现在会以您的语言的警告消息通知玩家  

> Content warning message now informs the user of issues with their language file if the format is invalid

****

**原文链接: [https://feedback.minecraft.net/hc/e...-Beta-1-17-30-22-Xbox-One-Windows-10-Android-](https://feedback.minecraft.net/hc/en-us/articles/4407359965837-Minecraft-Beta-1-17-30-22-Xbox-One-Windows-10-Android-)  
原文出自: Minecraft Feedback  
发布日期: 2021年8月18日  
翻译者: Glorydark  
部分翻译参考我的世界官方wiki、mcbbs的wiki等内容，由于内容太多，必定存在不准确之处还望各位多多反馈！**
