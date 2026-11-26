---
id: post.editing.rough-cut
site: post
type: article
lang: zh
translation_key: post.editing.rough-cut
translation_status: source
title: "粗剪：先让片子成立"
summary: "粗剪只做一件事：让陌生人看懂谁想要什么、被什么挡住。节奏、调色、配乐都往后放。"
slug: rough-cut
aliases: [rough-cut]
canonical_site: post
canonical_path: /article/rough-cut/
status: published
difficulty: beginner
stage: edit
format: short-film
tools: []
authors: ["TVCN 后期组"]
reviewers: [technical-reviewer]
cover: /images/post/rough-cut.webp
diagram: /images/diagrams/zh/rough-cut.png
diagram_alt: "粗剪是五步，不是一遍"
diagram_caption: "先让片子完整，再让它好看。粗剪的功能是暴露缺口，不是拿奖。"
last_verified: '2026-11-26'
review_due: '2027-02-26'
source_kind: sourced
related: [post.color.scopes, post.accessibility.sdh, shoot.camera.composition]
sources:
- S24
- S27
- S28
- S30
- S34
test_context: "复核环境：Windows 11（RTX 3060）+ macOS 14（M1）；DaVinci Resolve 20 与 Premiere Pro 2025 复跑；不声称每台机器结果一致。"
known_failures: "已知失败：旧版软件时间线不兼容；不同相机 Log 需重新映射；代理丢失时需回套原片。"
verified: 2026-11-22
---
<!-- DIAGRAM_START -->
## 图解

<figure>
  <img src="/images/diagrams/zh/rough-cut.png" alt="粗剪是五步，不是一遍">
  <figcaption>先让片子完整，再让它好看。粗剪的功能是暴露缺口，不是拿奖。</figcaption>
</figure>
<!-- DIAGRAM_END -->

粗剪只做一件事：让陌生人看懂谁想要什么、被什么挡住。节奏、调色、配乐都往后放。

## 先结构，后节奏

把镜头按分镜顺序放上时间线，先定入点和出点。不要一边剪一边调色，也不要一边剪一边找音乐；那会把“结构问题”误当成“氛围问题”。

第一版只问：观众知不知道现在发生了什么？如果不知道，加镜头或删镜头，不要靠转场救。

## 删三类镜头

第一类，重复：第二个镜头没有带来新信息。第二类，装饰：很好看，但不推动动作。第三类，解释：角色用台词把画面已经说清楚的事再说一遍。

删的时候先标记，不要立刻删除。先把“可能删”的镜头放进废片轨，完整看一遍，再决定。

## 写 3 条修改清单

每次看完粗剪，只写 3 条，每条带时间点：00:12 观众不知道她为什么走；00:38 反应镜头太长；00:51 结尾没有代价。

不要写“感觉不对”。感觉不对不是问题，具体到哪一秒、哪一个信息缺失，才是可修改的问题。

## 3 条验收

- 陌生人看完能说出谁想要什么。
- 没有超过 3 秒的无意义空镜。
- 修改清单有 3 条，且每条带时间点。

## 粗剪不是“少剪一点”

粗剪要回答的是片子成不成立，不是镜头漂不漂亮。先按事件剪一版，哪怕转场很硬；结构对了，再修节奏。

把每个场景写成一句话：谁想要什么、被什么挡住、最后得到什么。写不出来的场景，先标红。

## 先写一句话故事

用“某人想要某物，但因为某原因，必须某做”写一遍。这句话里只能有一个主角、一个目标、一个阻力。

如果一句话里出现三个“但是”，不是故事复杂，是还没决定主线。先删，再剪。

## 删镜头的三类清单

重复动作：人物已经坐下，不要再拍一次坐下。重复信息：上一句已经说了，下一句别再解释。重复情绪：同一个反应给两次，第二次通常更弱。

删完不要马上补拍。先放一天，第二天再看，很多“必须保留”的镜头会自己消失。

<!-- V11_DEEPEN -->


> 意图分工：本页负责「粗剪：先让片子成立」的可执行细节；同集群先读 <a href="https://post.tvcn.org/article/fine-cut/">细剪：把粗剪的毛边修掉</a> 建立总判断，再回到本页。

<!-- INTENT_SCOPE -->

<!-- SOURCES_START -->
## 参考与延伸阅读

- [S24] [ACESCentral：ACES：Academy Color Encoding System](https://acescentral.com/) — 2026-11-27 访问。用于核对首段“粗剪只做一件事：让陌生人看懂谁想要什么、被什么挡住。节奏、调色、配乐都往后放。”中的术语与公开背景（ACES 色彩编码、ACEScg 与交付/归档工作流）；不替代现场测试。
- [S27] [ITU-R：BS.1770 音频响度与真峰值测量](https://www.itu.int/rec/R-REC-BS.1770/en) — 2026-11-27 访问。用于核对首段“粗剪只做一件事：让陌生人看懂谁想要什么、被什么挡住。节奏、调色、配乐都往后放。”中的术语与公开背景（响度测量、真峰值与 EBU R128 所依据的 ITU 算法标准）；不替代现场测试。
- [S28] [Netflix 制作与交付帮助](https://partnerhelp.netflixstudios.com/) — 2026-11-26 访问。用于核对首段“粗剪只做一件事：让陌生人看懂谁想要什么、被什么挡住。节奏、调色、配乐都往后放。”中的术语与公开背景（平台交付规格、HDR/SDR 与 QC 要求的公开入口）；不替代现场测试。
- [S30] [DaVinci Resolve 产品与文档](https://www.blackmagicdesign.com/products/davinciresolve) — 2026-11-26 访问。用于核对首段“粗剪只做一件事：让陌生人看懂谁想要什么、被什么挡住。节奏、调色、配乐都往后放。”中的术语与公开背景（剪辑、调色、Fusion 与交付的官方产品入口）；不替代现场测试。
- [S34] [Adobe Premiere Pro 用户指南](https://helpx.adobe.com/premiere-pro/user-guide.html) — 2026-11-26 访问。用于核对首段“粗剪只做一件事：让陌生人看懂谁想要什么、被什么挡住。节奏、调色、配乐都往后放。”中的术语与公开背景（剪辑、代理、色彩与导出的官方文档）；不替代现场测试。
<!-- SOURCES_END -->

