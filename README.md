# 一个网络版涂鸦跳跃的前端
> 2016-2017-2学期游戏课程设计

## 1 信息
* 开发工具: Unity 5.6.1
* 软件版本: 1.0.0
* 更新日期: 20170629
* 后端工程: [链接](https://github.com/yziyz/doodle-jump-back-end)

## 2 功能
### 2.1 单机游戏
* 皮肤选择
* 五种道具（蘑菇、弹簧、火箭、爱心、金币）
* 原地复活

### 2.2 在线游戏
> 错误较多,待完善

* 创建/加入队伍
* 皮肤选择
* 队伍成员（暂时支持两人队伍）互相可见

## 3 实现
### 3.1 概述
Unity提供了MonoBehaviour基类,此项目中使用其Start()、Update()方法分别实现初始化、每帧重绘，（回想游戏引擎的作用，为游戏开发者提供开发游戏的各种基础工具，加快开发进程，而不用从零开始；若使用Java GUI技术开发，则需要更多时间）。

### 3.2 地面生成
队列、随机

### 3.3 小人跳跃
自由落体、碰撞检测

### 3.4 道具
状态、父子关系
