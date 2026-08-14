---
name: lowfi-wireframe-poster
description: 将活动海报、H5、小程序页面、PPT单页等需求快速转换为“灰度低保真线框草图”，强调模块占比、信息层级、阅读动线和结构，而不是视觉精修。
---

# Low-Fi Wireframe Poster Skill

## 目标

把用户提供的活动信息、页面文案、参考图或现有设计，转换成一张**可直接用于评审和排版沟通的低保真线框草图**。

这个 Skill 的重点不是“做漂亮”，而是先解决：

- 页面怎么分区
- 哪个信息最重要
- 每个模块占多大
- 用户视线怎么走
- 哪些内容需要并列
- 哪些内容需要主次
- CTA / 二维码 / 产品 / 奖品应该放在哪里

最终视觉应接近“设计师的结构草图 / Wireframe”，而不是完整商业海报。

---

## 适用场景

当用户提出以下需求时优先使用本 Skill：

- “先帮我排版”
- “给我一个原型”
- “做成低保真”
- “先不要精修，看看结构”
- “这页太乱了，帮我重新排”
- “给设计师看一个草图”
- “把这个活动海报先做成线框”
- “帮我看信息层级”
- “我要一张页面骨架图”
- “按模块比例排一下”

适用于：

- 活动海报
- 长图
- H5 页面
- 小程序首页
- 营销活动页
- PPT 单页
- 功能介绍页
- 奖品页
- 扫码参与页
- 产品宣传页

---

## 输入信息

尽量从用户提供内容中自动提取，不要重复询问已经给出的信息。

### 必须识别

1. 页面类型
2. 页面尺寸 / 比例
3. 核心标题
4. 主要模块
5. 模块优先级
6. CTA / 扫码 / 转化入口
7. 是否存在主视觉
8. 是否有奖品 / 产品 / 功能入口
9. 是否需要保留品牌 Logo

### 可选信息

- 活动时间
- 奖品层级
- 产品数量
- 功能数量
- 参考图片
- 品牌色
- 用户已有草图
- 文案说明

若缺少非关键内容，可直接使用占位框表示，不必阻塞生成。

---

## 核心输出原则

### 1. 只做结构，不做视觉精修

默认使用：

- 白色背景
- 黑 / 灰线条
- 灰度占位图
- 细边框
- 少量圆角
- 不使用复杂渐变
- 不使用高饱和颜色
- 不做商业 KV 级精修

除非用户明确要求，否则不要加入真实复杂品牌视觉。

---

### 2. 必须显示模块分区

整张草图需要明确展示不同模块边界。

推荐使用：

- 横向分割线
- 卡片边框
- 模块标题
- 区域框
- 页面外框

不能做成一堆漂浮元素。

---

### 3. 必须标注模块占比

在页面左侧或边缘增加结构标注，例如：

- 顶部主视觉区｜约占 25%
- 核心玩法区｜约占 27%
- 奖品区｜约占 22%
- 扫码参与区｜约占 26%

如果是横向页面，则标注宽度 / 栏位关系。

这些百分比用于表达相对视觉权重，不要求数学绝对精确。

---

### 4. 一屏只允许一个最高视觉层级

必须识别全页唯一核心：

- 主标题
- 主产品
- 主利益点
- 主功能
- 关键数据

最高视觉层级只能有一个。

其他内容按 H2 / H3 / 辅助文字逐级降低。

避免：

- 多个超大标题
- 每个模块都很重
- 所有元素都抢视觉中心

---

### 5. 模块内部必须有明确结构

例如功能区：

[模块标题]

[卡片1] [卡片2]

[卡片3] [卡片4]

例如奖品区：

[大奖]

[周边1] [周边2] [周边3]

例如扫码区：

[CTA标题]

[二维码] [活动说明]

[产品陈列]

不要随意散排。

---

### 6. 对营销海报使用默认阅读动线

若用户没有指定，默认顺序：

品牌 / Logo  
↓  
活动主题 / 主视觉  
↓  
核心玩法 / 产品价值  
↓  
利益点 / 奖品  
↓  
扫码 / CTA / 活动时间  
↓  
产品或品牌收口

---

## 默认线框视觉规范

### Canvas

根据用户场景选择：

- 竖版活动海报：9:16
- 手机页面：9:16
- PPT：16:9
- 小红书：3:4
- 方形社交内容：1:1

### 风格

- clean grayscale wireframe
- low fidelity UX layout
- editorial grid
- thin gray strokes
- white canvas
- monochrome placeholder illustrations
- clear hierarchy
- generous spacing
- labeled structural zones
- professional design review sketch

---

## 图像生成规则

当用户要求“直接生成草图 / 图片 / 原型图”时：

### 必须生成

一张完整的灰度低保真线框图。

### 图中应包含

- 页面外框
- Logo 占位
- 标题
- 各模块真实名称
- 图像占位
- 卡片布局
- 二维码占位（若适用）
- 产品占位
- 模块比例标注
- 分区边界
- 关键 CTA
- 必要的辅助说明

### 图中不要包含

- 大面积复杂色彩
- 商业级特效
- 过多装饰
- 写实摄影背景
- 强 3D 渲染
- 随机艺术化构图
- 与需求无关的元素

---

## 推荐 Image Prompt 模板

Create a clean grayscale low-fidelity wireframe for a [页面类型].

Canvas: [尺寸比例].

The goal is NOT to create a polished commercial design.  
The goal is to clearly communicate layout hierarchy, module proportions, reading flow, and information architecture.

Use:
- white background
- thin gray outlines
- monochrome placeholder illustrations
- simple rounded cards
- clear typography hierarchy
- generous whitespace
- structural annotations on the left side
- percentage labels for major page sections
- no bright colors
- no complex visual effects

Page structure from top to bottom:

[模块1]
- content:
- hierarchy:
- approximate height:

[模块2]
- content:
- hierarchy:
- approximate height:

[模块3]
- content:
- hierarchy:
- approximate height:

[模块4]
- content:
- hierarchy:
- approximate height:

Important:
- Only one strongest visual focus on the page.
- Do not scatter elements.
- Keep each module internally aligned.
- Show explicit section boundaries.
- Use real Chinese labels from the brief whenever available.
- This should look like a professional design review wireframe.

---

## 输出前自检

生成前必须检查：

- [ ] 是否只有一个最高视觉中心
- [ ] 是否从上到下能看懂页面逻辑
- [ ] 是否把并列功能排成网格或等宽卡片
- [ ] 是否区分大奖与普通奖品
- [ ] 是否给二维码留出足够空间
- [ ] 是否避免元素漂浮
- [ ] 是否标明主要模块比例
- [ ] 是否保持灰度低保真
- [ ] 是否没有提前进行视觉精修
- [ ] 是否保留用户要求的关键模块

---

## 示例：活动海报

用户输入：

“帮我把一个扫码活动做成低保真原型。上面有活动主视觉，中间4个互动玩法，下面大奖和周边，底部二维码和产品。”

推荐结构：

顶部主视觉区｜25%  
- Logo
- 主标题
- 副标题
- KV 占位

玩法区｜27%  
- 模块标题
- 2×2 四宫格

奖品区｜22%  
- 1 个主奖
- 3 个周边

扫码区｜26%  
- CTA
- 大二维码
- 活动时间
- 产品陈列

最终输出：
一张带分区标注的灰度低保真竖版草图。

---

## 交互策略

### 用户已有完整内容

直接生成结构，不重复问问题。

### 用户只有一张现有设计

先分析：
- 哪里散
- 哪些信息抢层级
- 哪些模块应该合并
- 哪些内容缺失

然后生成新的低保真草图。

### 用户只给文字需求

自动整理成模块后直接生成。

### 用户要求修改现有草图

优先保持原有结构，只修改用户点名的部分，不无故重构整个页面。

---

## 输出语气

简洁、设计评审式、直接。

优先说：

“我先按低保真结构把页面拆成 4 个区。”

而不是：

“我会为你打造一个极具视觉冲击力的设计。”

本 Skill 的价值是“帮助用户快速看清结构”，而不是“包装创意概念”。
