---
id: post.color.color
site: post
type: article
lang: zh
translation_key: post.color.color
translation_status: source
title: "调色：先统一，再风格"
summary: "调色先解决白平衡、曝光和镜头匹配，再谈 LUT 和风格。镜头之间不连，风格越多越乱。"
slug: color
aliases: [color, 调色, 色彩]
canonical_site: post
canonical_path: /article/color/
status: published
difficulty: intermediate
stage: post
format: short-film
tools: [color, edit]
authors: ["TVCN 后期组"]
reviewers: [technical-reviewer]
cover: /images/post/color.webp
diagram: /images/diagrams/zh/color.png
diagram_alt: "调色顺序：白平衡、曝光、匹配、风格"
diagram_caption: "先解决白平衡、曝光和镜头匹配，再谈 LUT 和风格。镜头之间不连，风格越多越乱。"
last_verified: '2026-11-26'
review_due: '2027-05-26'
source_kind: experience
related: [post.color.color-management, post.delivery.conform-online, shoot.camera.composition]
---
<!-- DIAGRAM_START -->
## 图解

<figure>
  <img src="/images/diagrams/zh/color.png" alt="调色顺序：白平衡、曝光、匹配、风格">
  <figcaption>先解决白平衡、曝光和镜头匹配，再谈 LUT 和风格。镜头之间不连，风格越多越乱。</figcaption>
</figure>
<!-- DIAGRAM_END -->

## 先做镜头匹配

同一场戏，不同镜头可能来自不同时间、不同镜头、不同白平衡。先并排看，把曝光、色温、对比拉到接近，再往下做。

匹配不是让每个镜头一模一样，是让观众看不出切换。人脸亮度差半档，观众就会觉得“跳”。

## 肤色是锚点

观众对肤色最敏感。先保证人脸不绿、不灰、不过红，再决定整体冷暖。示波器看肤色线，比凭感觉可靠。

风格可以偏，但同一场戏里的肤色要一致。广告可以冷，纪录片可以暖，但不能一条片里两种脸色。

## 风格只用一个方向

风格不是把每个工具都拉满。选一个方向：低饱和、高对比、冷阴影、暖高光，或者反过来。其他参数为它服务。

LUT 是起点，不是终点。套完之后还要回到一级校正，检查暗部有没有死、高光有没有爆。

## 3 条验收

- 同一场戏的人脸亮度与色温一致。
- 白色物体在画面里是中性的。
- 风格只有一个主方向，没有每个镜头换一种。

## 匹配失败先回白平衡

两个镜头怎么拉都不像，先别动风格。回到白平衡和曝光，把白纸或灰卡并排看；这一步不对，后面所有节点都在补救。

示波器比眼睛可靠：看肤色的矢量位置、看黑位的起点、看高光有没有贴顶。眼睛会适应，示波器不会。

## 肤色不是记忆色

观众记得的肤色通常比真实暖一点。广告可以再暖半档，纪录片最好留在中性附近；同一场戏里，至少保证人脸之间一致。

不要用“电影感”给所有人脸加青。青脸在夜景里像病人，在回忆里像鬼片，除非这是你要的叙事。

## 一场戏只留一个 LUT

LUT 是起点，不是风格本身。套完先回到一级校正，检查黑位、高光和肤色，再决定要不要二级。

同一场戏用两个 LUT，镜头之间就会跳。要变，就在叙事转折点变，并让观众看出这是有意的。

<!-- V11_DEEPEN -->


> 意图分工：本页负责「调色：先统一，再风格」的可执行细节；同集群先读 <a href="https://post.tvcn.org/article/lut/">LUT：起点不是终点</a> 建立总判断，再回到本页。

<!-- INTENT_SCOPE -->

<section><h2>边界</h2><p>本页只解决「调色：先统一，再风格」这一个问题；不替代 色彩管理：把 LUT 放在正确的位置、Conform / Online：套底、回批与母版、构图：先让观众知道看哪里。如果现场问题属于后者，先读对应页，不要在本页继续加参数。</p></section>
<!-- SOURCES_START -->
## 经验说明

经验说明：本页来自 5 个后期项目的操作复盘，条件为页面所列软件版本、素材格式与交付平台；只讨论「调色：先统一，再风格」的操作顺序，不含外部实验室测试；不适用于未列版本、影院母版、广播级安全认证或法律意见。
<!-- SOURCES_END -->

