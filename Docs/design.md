# 贪吃蛇网页版

## 游戏设计

1. **游戏界面设计**
   - 游戏界面主要分为游戏区域和控制区域。
   - 游戏区域包括贪吃蛇和食物的位置。
   - 控制区域包括游戏模式选择、难度选择、开始游戏按钮、重新开始按钮和游戏说明按钮。

2. **游戏逻辑设计**
   - 贪吃蛇的移动由定时器控制，每隔一定时间更新蛇的位置。
   - 检测贪吃蛇是否吃到食物，如果吃到食物，则增加蛇的长度。
   - 检测游戏结束条件，包括蛇撞墙、蛇撞到自己的身体（单人模式）以及两条蛇相撞（双人模式）。

3. **游戏模式设计**
   - 单人模式：玩家控制一条贪吃蛇，通过吃食物增加分数，直到游戏结束。
   - 双人模式：两位玩家分别控制两条贪吃蛇，竞争吃食物，最后一条存活的蛇获胜。

4. **难度设计**
   - 游戏难度分为简单、适中和困难三个等级，难度越高，贪吃蛇的移动速度越快，食物生成频率越低。

## 技术方案

1. **HTML5**
   - 使用 HTML5 绘制游戏界面，包括贪吃蛇、食物和游戏控制区域。

2. **CSS3**
   - 使用 CSS3 进行样式设计，美化游戏界面，提升用户体验。

3. **JavaScript**
   - 使用 JavaScript 实现游戏逻辑，包括贪吃蛇的移动、食物的生成、碰撞检测、模式切换等功能。

4. **游戏控制**
   - 单人模式默认使用上下左右控制移动
   - 双人模式玩家一使用上下左右控制移动，玩家二使用WASD控制移动

## 测试方案

1. **功能测试**
   - 测试单人模式下贪吃蛇的移动和吃食物功能。
   - 测试双人模式下两条蛇的移动和碰撞检测功能。
   - 测试游戏结束条件是否正确。
   - 测试切换模式后游戏逻辑是否正确。

2. **界面测试**
   - 测试游戏界面布局是否合理。
   - 测试游戏界面样式是否美观。

3. **性能测试**
   - 测试不同难度下游戏的性能表现，包括运行流畅度和响应速度。

## 迭代计划

1. **迭代一：多人游戏功能实现**
   - 实现多人模式下的贪吃蛇移动和吃食物功能。

2. **迭代二：历史记录**
   - 对于单人模式记录前十。

3. **迭代三：性能优化**
   - 优化游戏性能，提升运行流畅度。
   - 增加游戏难度选择功能，使游戏更具挑战性。