# 设计草案

---

## 剧情

### 双线剧情

游戏剧情分为明暗两条线，一条为正常的模拟器形式通关，另一条为在实验室内搜寻信息解谜，第一条线为主线，负责推进故事内时间，解谜线则为附加线，完成后可以导向第二结局。

### 氛围

剧情起始氛围较为轻快简单，随着剧情推进（主角逐渐发现实验项目的实质），转向轻微压抑的氛围。

两条线的结局都应该给第一次玩到的玩家以【好结局】的印象。

---

## 关卡

### 零件搭配

尽量使玩家能够按当前关卡所需思考如何最优搭配零件，因此需要限定零件的能力和能够搭载的数量，对零件系统的设定将会主导游戏难度和体验。同时，在设计关卡时，需要为玩家营造出 “学习 - 应用 - 创新” 的过程，最大化玩家的成就感，通过提升玩家通关成就感来吸引玩家。在成就感外，还可以增加沉浸感，如：无缝场景转换，自动存储进度，将通过设计零件搭配进行通关的解谜玩法包装在剧情中，增加玩家继续前进的动力。

### 玩家引导

新手引导将放置在第一章，基础操作将以实验室工作人员向主角介绍的方式介绍给玩家。

在虚拟模拟器中出现的新工具，能力，都将由工作人员介绍给主角（玩家），而实验室现实世界解谜故事线则没有引导，全部依赖于场景内的信息提示。

---

## 美术风格

### 环境

整体美术风格为实验室+工厂氛围，两者互为对比，主体区域为实验室，因此应该体现出精密，整洁，有未来感的氛围，主要用于公开展示的部分，给玩家以实验室是在光明正规进行实验的感觉，主要色调偏亮，墙壁尽量采用白色与浅灰色，屏幕等建议用蓝色，而作为对比，实验室的部分施工区域，模拟器内，与机密区域，主色调为深灰色与黑色（用于体现未知区域），警戒线采用黄色与红色，分别代表不同警戒等级（警告，禁止）。

### 角色

角色有向右，向左，向后，向前四种贴图状态

---

## 小结

### 重要性排序

* 零件系统
* 沉浸感
  * 剧情
  * 关卡设计（美术）
* 难度递进
  * 新手引导
  * 关卡设计（难度）
* 其他

### 基础设定

* 主角是一个拥有一条义肢的少女
* 义肢在游戏过程中为能力的载体
* 能力可以通过收集或制作零件进行升级
* 可以通过更换零件来更换新能力
* 部分零件在同时安装时各自的功能会互相结合形成新能力
* 零件会产生磨损，如果一个能力所需的任何一个零件磨损至残骸状态，能力就会不可用或降级为剩余零件还能组合成的能力
* 制作零件需要的原料可以通过分解收集到的零件获得
* 零件收集分为两种方式：击杀敌人掉落；打开物品箱随机获得
* 零件完整度分为三种状态：完整 -> 磨损 -> 残骸
* 磨损零件可以通过维修增加完整度
* 残骸不可维修，只能分解为原料
* 原料可以储存在背包中
* 制作台可以进行分解，维修
* 任何时候都可以对义肢零件进行更换
* 义肢每个部位可挂载零件有限