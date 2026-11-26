---
id: post.sound.sound
site: post
type: article
lang: zh
translation_key: post.sound.sound
translation_status: source
title: "声音：先对白，再音乐"
summary: "观众可以忍受画面粗糙，但很难忍受听不清。先把对白做干净，再谈音乐和氛围。"
slug: sound
aliases: [sound]
canonical_site: post
canonical_path: /article/sound/
status: published
difficulty: beginner
stage: edit
format: short-film
tools: []
authors: ["TVCN 后期组"]
reviewers: [technical-reviewer]
cover: /images/post/sound.webp
diagram: /images/diagrams/zh/sound.png
diagram_alt: "声音的先后：对白在前，音乐在后"
diagram_caption: "观众能忍画面粗糙，很难忍听不清。先把每个字做干净，再铺音乐；音乐盖住对白，片子就废了。"
last_verified: '2026-11-26'
review_due: '2027-02-26'
source_kind: sourced
related: [post.editing.sound-bridge, post.sound.sound-post, shoot.camera.axis-line]
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
  <img src="/images/diagrams/zh/sound.png" alt="声音的先后：对白在前，音乐在后">
  <figcaption>观众能忍画面粗糙，很难忍听不清。先把每个字做干净，再铺音乐；音乐盖住对白，片子就废了。</figcaption>
</figure>
<!-- DIAGRAM_END -->

观众可以忍受画面粗糙，但很难忍受听不清。先把对白做干净，再谈音乐和氛围。

## 对白是主线

先修对白：降噪、去口水、对齐音量，确保每一句都能听清。不要在噪声很大的对白上直接铺音乐，那只是把问题盖住。

如果现场录坏了，先考虑补录对白（ADR），而不是用字幕替代。字幕是辅助，不是声音的替代品。

## 环境声是空间

每个场景录 30 秒干净的环境声。剪辑时把环境声铺在下面，镜头切换才不会像在真空里跳。

环境声不是噪音。它告诉观众“这里是厨房、街道、山谷”。没有它，画面会变薄。

## 音乐别填满

音乐是标点，不是背景墙。把音乐留给转折、决定、结尾；让沉默承担压力。先做一版没有音乐的，确认结构成立，再加。

如果一段音乐去掉后片子就散了，说明问题在剪辑，不在音乐。

## 3 条验收

- 每句对白都能听清，不需要看字幕猜。
- 每个场景都有环境声。
- 至少有一处主动使用沉默。

## 声音先有空间

对白之前先铺环境：室内有冰箱、灯管、窗外车流；室外有风、鸟、远处施工。环境声不是噪音，它告诉观众“这是哪里”。

同一场景的环境声要连续。切镜头时环境不断，观众才不会觉得画面在跳。

## 音乐不是填空

没有对白的地方，不一定需要音乐。可以让环境声承担情绪：水滴、脚步、远处的门。音乐进来，是为了改变能量，不是为了填满安静。

如果一段音乐去掉后画面仍然成立，它可能本来就不该在。

## 三次回放

第一次闭眼听：能不能只听声音就知道人物在做什么。第二次只看画面：声音有没有跟动作错位。第三次正常看：有没有哪一秒你想调音量。

三次都过，才进入混音。不要一边看画面一边修，眼睛会替耳朵做判断。

<!-- V11_DEEPEN -->

<!-- SOURCES_START -->
## 参考与延伸阅读

- [S24] [ACES 色彩管理](https://www.oscars.org/science-technology/aces) — 2026-11-26 访问。用于核对首段“观众可以忍受画面粗糙，但很难忍受听不清。先把对白做干净，再谈音乐和氛围。”中的术语与公开背景（ACES 色彩管线的官方说明与规范）；不替代现场测试。
- [S27] [EBU R128 响度](https://tech.ebu.ch/publications/r128) — 2026-11-26 访问。用于核对首段“观众可以忍受画面粗糙，但很难忍受听不清。先把对白做干净，再谈音乐和氛围。”中的术语与公开背景（广播响度目标、真峰值与测量方法）；不替代现场测试。
- [S28] [Netflix 制作与交付帮助](https://partnerhelp.netflixstudios.com/) — 2026-11-26 访问。用于核对首段“观众可以忍受画面粗糙，但很难忍受听不清。先把对白做干净，再谈音乐和氛围。”中的术语与公开背景（平台交付规格、HDR/SDR 与 QC 要求的公开入口）；不替代现场测试。
- [S30] [DaVinci Resolve 产品与文档](https://www.blackmagicdesign.com/products/davinciresolve) — 2026-11-26 访问。用于核对首段“观众可以忍受画面粗糙，但很难忍受听不清。先把对白做干净，再谈音乐和氛围。”中的术语与公开背景（剪辑、调色、Fusion 与交付的官方产品入口）；不替代现场测试。
- [S34] [Adobe Premiere Pro 用户指南](https://helpx.adobe.com/premiere-pro/user-guide.html) — 2026-11-26 访问。用于核对首段“观众可以忍受画面粗糙，但很难忍受听不清。先把对白做干净，再谈音乐和氛围。”中的术语与公开背景（剪辑、代理、色彩与导出的官方文档）；不替代现场测试。
<!-- SOURCES_END -->

