# DemoForSpacecan.
测试题
开发环境：Unity 2021.3.6f1c1  	VisualStudio2019

优化方向：添加开枪，受击特效和音效；完善UI；

《通关！游戏设计之道》里根据怪物的行为模式做出了6种分类：巡逻怪，追踪怪，射击怪，守卫怪，飞行怪，炸弹怪，掘穴怪，瞬移怪，格挡怪，二重身。

目前拥有的怪物种类有：大恶魔：巡逻怪+追踪怪，平时按照一定路线巡逻，玩家进入警戒范围后就进入追击状态；骷髅：”追踪怪，行动敏捷，玩家进入警戒范围后会迅速做出追击；巫师：射击怪，间隔一段时间向玩家方向发射一发火球。

未来计划添加的怪物：梦魇地鼠：掘穴怪，擅长钻地攻击，玩家需要抓准时机攻击；影狼：瞬移怪，行动难以捉摸，会不经意间瞬移到玩家身边，承受一定伤害后再瞬移逃离；大盾哥布林：持有大型盾牌的巨型哥布林，行动迟缓但是正面不会受到任何伤害，玩家需要绕后攻击。

分析：敌人的行动模式应按照关卡难度进行设计，一个典型的例子，《忍者龙剑传3》中，一个关卡的精英怪是三个炼金术师，该敌人的行动模式有：射击怪+瞬移怪+格挡怪+守卫怪（打败后才能前进），能够发射多种魔法远程攻击，同时轻攻击无法破防，每隔一段时间就会瞬移，甚至血量非常之厚，玩家需要同时应对三名这样难缠的角色，游戏体验及其糟糕。怪物的行动模式越丰富确实给玩家的挑战感和新鲜感越强，但是务必保证把这样的设计加入关卡后关卡流程的体验依然是流畅且不令人反感的。
