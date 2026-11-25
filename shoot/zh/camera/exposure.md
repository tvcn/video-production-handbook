---
id: shoot.camera.exposure
site: shoot
type: article
lang: zh
translation_key: shoot.camera.exposure
translation_status: source
title: "曝光三角：先把高光保住"
summary: "快门、光圈、ISO 不是三个平等旋钮。先定运动，再定景深，最后才用 ISO 救场。"
slug: exposure
aliases: [exposure]
canonical_site: shoot
canonical_path: /article/exposure/
status: published
difficulty: beginner
stage: shoot
format: short-film
tools: []
authors: ["TVCN 技术组"]
reviewers: [technical-reviewer]
cover: /images/shoot/exposure.webp
diagram: /images/diagrams/zh/exposure.png
diagram_alt: "曝光三角：三项互相换"
diagram_caption: "先定下最不能牺牲的那一项，再让另外两项跟着走。三项都想要，最后通常是高光爆掉。"
last_verified: 2026-11-20
review_due: 2027-05-20
source_kind: experience
related: [shoot.virtual-production.led-virtual-production.en, story.screenplay.three-act.en, tools.guide.buy-wireless-lav.en]
sources: [S23, S31, S32, S33]
test_context: "复核环境：Windows 11 工作站；Sony FX3 / Canon R5 公开菜单与样片对照；镜头以页面标注为准，不声称每支都实测。"
known_failures: "已知失败：不同机型菜单/固件差异；现场色温与监视器未校准会导致误判。"
verified: 2026-11-22
---

<!-- DIAGRAM_START -->
## 图解

<figure>
  <img src="/images/diagrams/zh/exposure.png" alt="曝光三角：三项互相换">
  <figcaption>先定下最不能牺牲的那一项，再让另外两项跟着走。三项都想要，最后通常是高光爆掉。</figcaption>
</figure>
<!-- DIAGRAM_END -->

快门、光圈、ISO 不是三个平等旋钮。先定运动，再定景深，最后才用 ISO 救场。

## 先定快门

24fps 拍摄，快门通常放在 1/48 或 1/50 秒，运动看起来最自然。拍 60fps 慢动作，快门跟着提高到 1/120 左右，否则每一帧都会拖影。

快门是运动的语言。先决定你要“正常的运动”还是“清晰的慢动作”，再谈其他两个参数。

## 高光优先

数字传感器的高光一旦过曝，细节就没了；暗部通常还能救回来。先看波形图或斑马纹，把最亮的脸、窗、灯管压到不爆。

不要用“整体看起来亮”当标准。人脸亮不亮，和画面整体亮不亮，是两件事。

## ISO 是最后一道

先用快门和光圈拿到想要的效果，再考虑 ISO。大多数相机有原生 ISO，画面最干净；再往上，噪点和暗部色彩会变差。

如果光圈已经开到头、快门也不能再慢，宁肯加一块 ND 或补一盏灯，也不要直接把 ISO 拉满。

## 3 条验收

- 能说出 24fps 与 60fps 各自该用什么快门。
- 用波形图或斑马纹确认高光没有爆。
- ISO 不是第一个调整的参数。
<!-- SOURCES_START -->
<h2>参考与延伸阅读</h2>
<p class="source-types">经验来源：TVCN 现场手册与项目复盘；实测来源：页面标注的复核环境与可复现练习；参考来源：以下公开链接。</p>
<ul><li><span class="mono">[S23]</span> SMPTE 标准入口</li><li><span class="mono">[S31]</span> ARRI 技术文档</li><li><span class="mono">[S32]</span> Sony 专业影像支持</li><li><span class="mono">[S33]</span> Canon 支持</li></ul>
<p><a href="../../about/">完整链接与用途见 SOURCES.md</a></p>
<!-- SOURCES_END -->
