# Daylight Power 网站拆解

原站链接：<https://godaylight.com/?ref=land-book.com>

Daylight 的首页一打开，就是一整块金红渐变的动态背景，带有强烈光晕效果，象征太阳的光辉。
正中是白色的 Daylight 标志，与高饱和背景形成强对比，先吸引注意力，随后 Logo 缩小、淡出，留下一块持续流动的动效区域。

整体是一个 3×3 的不对称 Grid 网格：右侧占 6 格，左侧占 3 格，接近黄金比例的分配，让主视觉和信息区既有秩序又不死板。

- 右侧某一格放动效图，是视觉重心；
- 动效图的上、下、右三侧，用白色小字号文字 + 图标呈现关键信息：
	- 上方是性能数据（如 Kw generated）；
	- 下方是最低工作温度，配雪花图标（Thermostat）；
	- 右侧是 Backup stored 的进度条；
- 左侧三格中，中间一格是核心 CTA 标语：
	- “Join the Daylight network”
	- “Save on energy. Earn rewards. Stay powered when the grid goes down.”

这部分使用两套字体和字号（如 Feature Deck 与 Aeonik Pro），通过大小、粗细对比来划分主次。
左下方是一组并排按钮，大小一致、轻微圆角：一个白底，一个金黄底，对应不同层级的行动按钮。
所有网格之间用细白线切分，进一步强化了“版心内的秩序感”。

背景主视觉是一座林中红砖小屋，黄昏的落日光线打在屋顶的太阳能板上。
红砖 + 森林营造出北欧乡野感，配合光伏板和 UI 动效，整体色调控制在金黄、红和白之间，兼具温暖气氛与现代科技感。

## 中段九宫格：文案 + 产品图

在继续下拉的过程中，页面延续九宫格的结构，但中间的网格占比明显放大，大约接近整体宽度的三分之二。
布局策略是“中间文案、两侧产品图”的组合：

- 中间：分段的文案介绍；
- 左右：一次只出现一张产品图，随着滚动切换；
- 在滚动过程中，左右图块会被中部网格“侵占”，打出一个有节奏的切换效果。

三张代表性图像分别是：

- 家用住宅屋顶的太阳能安装，呼应首页主视觉；
- 一台储能柜产品；
- 一部 iPhone，展示 Daylight App 中节能和费用节省的模拟界面。

对应的文案结构非常有意思：动词用 small caps，这是一种css排版中的设计方法，字母大写但是小一号，其余部分用大号加粗：

- SAVE（small caps）Power your home for less
- PROTECT（small caps）Keep the lights on with battery backup
- EARN（small caps）Get rewarded for using Daylight

小字动词 + 大字描述句的组合，让浏览时形成非常清晰的阅读节奏：
先被大字吸引，再意识到左侧的小字是“动作标签”，文字和图片做了一一呼应。

## HOW DAYLIGHT WORKS：纵向叙事页

第三个滚动页脱离九宫格，采用垂直单栏布局，以一只手托着“温暖太阳”的照片为主视觉（更像是人造光源拍摄出的氛围光）。

这一页通过三种层级的文字节奏来说明产品模式：

1. HOW DAYLIGHT WORKS —— 作为栏目标题；
2. Two ways to power your home. One powerful network. —— 大字号主标题；
3. 下面一段小字正文，用正常大小写描述使用方式：

	 Choose a monthly energy subscription or purchase your system outright. Both options include an oversized backup battery from Daylight at no additional cost. You create enough power for you, and share surplus with the grid.

底部有一个统一风格的按钮：白底黑字，Hover 时反转为黑底白字，形成“白天 / 夜晚”视觉隐喻。

## STEP 1 / STEP 2：分步流程与 small caps

### 第 4 屏：STEP 1 – Join the network

第 4 个页面采用“卡片叠加”的方式：

- 底层是奶白色大底；
- 上层是较深色的内容卡片，四周留出明显的 padding，营造出层次感和版心边界；
- 左侧是三行分级文字：
	- STEP 1 —— 小字 small caps；
	- Join the network —— 大号主标题；
	- TWO WAYS TO CONNECT —— 再次使用全大写 small caps 做副标题标签。

正文部分解释两种接入方式：

Subscribe to get solar + battery backup with no upfront costs. Daylight owns the system, you pay for the power it produces. Or buy your panels outright and we’ll include a battery at no extra cost to you.

可以看到：

- 短句、标签式的信息（如 STEP 1、TWO WAYS TO CONNECT）统一使用全大写、较小字号的 small caps；
- 正文叙述则使用更易读的正文字体和字号，两者在版心内形成明显的主次层级。

右侧是一部 iPhone 的 UI 模拟：

- 屏幕内是金黄到红的渐变图表；
- 底部是类似“接电话按钮”的圆形 CTA；
- 动效上从 Subscribe 过渡到 Purchase；
- 整个手机一开始由一个小矩形 Logo 变形而来，延续了首页 Logo 动效逻辑。

### 第 5–6 屏：STEP 2 与社区联通

第 5 个页面沿用上一屏的左右分栏和层次结构，但右侧改为一座线框 3D 感的房子：

- 屋顶有太阳能光伏板；
- 一旁是金色的储能柜；
- 整体更偏“结构图 / 线框模型”的科技感表现。

左侧文案同样分为 small caps + 大标题 + 正文：

- Step 2
- Power up
- Your house acts like a mini power plant
- With solar and battery installed, your house produces clean energy and stores surplus.

推动到第 6 页时，画面中的房子会延伸出一条金黄色的线，连接到一个社区场景，暗示“从一户到一片社区”的联通能力。
此时文案不变，只是视觉范围由单一建筑扩展到社区级别。

第 6 页继续说明“多余电力可以卖回电网”，通过一个 earn 曲线图来具象化“收益随时间累积”的概念，延续前文 small caps“earn”的文案线索。

## 后续内容：Why Daylight 与地图页

随后第 7、8、9 页是“Why choose Daylight” 类内容，主要通过全屏动效图来叙事：

- 大风天气、森林火灾、宁静落日等航拍画面；
- 每一屏都搭配不同风格的标题字体，强化“多场景都适用”的品牌承诺。

第 10 页回到更明确的 CTA：

- 按钮文案不是直接“购买”，而是更柔和的 “See if your house qualifies”；
- 背景是美国地图，标出可服务的地区；
- 之后是一张“居家生活”的愿景图，中间用一块紫色动效覆盖人物面部或敏感区域，既保护隐私，也形成视觉焦点；
- 最后一张则是熟悉的金红背景和友链区域，为整页做收束。

在整个滚动过程中，顶部导航始终保持：左侧 Logo + 右侧 “Get Started” CTA，提供随时转化的入口。

## small caps（小字）在页面中的统一用法

这套设计大量使用 small caps（小号全大写 / 小写小字）来做“节奏点”和“标签”：

- STEP 1、STEP 2 等步骤标题；
- HOW DAYLIGHT WORKS、TWO WAYS TO CONNECT 等栏目标签；
- save / protect / earn 这些动词小字；
- 以及一些较短、信息密度高的提示句。

它们的典型特征是：

- 全大写或全部小写，但字号明显小于主标题；
- 行高和字距略紧，整体更“压扁”；
- 常常位于主标题上方或左侧，像 UI 里的“小标签 / tag”。

与之对应：

- 主标题采用更大的字号和较粗的字重，负责抢眼和情绪表达；
- 正文采用易读的正文字体和行距，用来承载完整信息；
- three-level hierarchy（small caps → 大标题 → 正文）在版心宽度内非常清晰，让用户在滚动过程中始终知道“我现在看到的是哪一步 / 哪个部分 / 做什么事”。

## 按钮与交互动效

- CTA 按钮在多个页面重复出现（首页、HOW DAYLIGHT WORKS、步骤页、地图页等），文案有所变化，但样式体系高度统一，有助于强化行动意图；
- 按钮常用白底黑字 + Hover 黑底白字的反转，既简单，又与“日夜切换”的品牌意向呼应；
- 手机、Logo、房子与社区的动效都强调“从小到大、从一点到一片”的成长感，与“你家发电、社区受益”的叙事主线一致。

## 综合感想

整体来看，这个页面依托 Grid 网格与细线分隔，建立了清晰的版心和阅读秩序；
通过不对称布局和大面积动效，打破整齐可能带来的呆板感。

色彩方面，金黄与红色渐变构成温暖、充满能量的氛围，非常贴合太阳能与“白天 / 光”的品牌核心。
结合北欧小屋、社区航拍和 UI 界面，既有自然气息，又具科技感。

字体与 small caps 的搭配，把信息明确分层：

- small caps 负责标记步骤和模块；
- 大标题负责讲故事和情绪；
- 正文补充细节。

这样的层级在版心范围内非常清晰，移动端与桌面端都容易快速扫读。

CTA 在页面中多次重复出现，配合图文呼应的视觉节奏，能够持续提醒用户“加入 Daylight 网络”的主线动作，产品功能点和优势被解释得相对充分。

唯一小小的不足是：后续页面数量较多，讲述内容稍显冗长，部分用户可能在中后段失去耐心。
从设计角度看，这也可能是团队有意为之——希望用更长的叙事路径，建立品牌世界观和信任感，而不仅仅是一个单屏落地页的转化。
