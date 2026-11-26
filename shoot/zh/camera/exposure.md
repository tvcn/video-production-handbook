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
last_verified: '2026-11-26'
review_due: '2027-02-26'
source_kind: sourced
related: [shoot.exposure.false-color, shoot.camera.frame-rate, post.color.color]
sources:
- S23
- S31
- S32
- S33
- S52
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

## 先定快门

180 度快门是常见起点：25 帧用 1/50，50 帧用 1/100。快门定了，运动模糊就定了，再谈光圈和 ISO。

想改运动感，先改快门，不要先改光圈。光圈会顺带改变景深，画面会一起变。

## 高光优先

数字传感器的高光一旦贴顶，细节就回不来。先保高光，再用灯或反光板补暗部。

用波形或伪色看：高光留一点余量，肤色不要贴顶。不要只看直方图，直方图不告诉你哪块是脸。

## ISO 是最后一道

光圈和快门都到位，才用 ISO 换亮度。ISO 越高，暗部噪点越多，后期空间越小。

现场太暗，先加灯，再开 ISO。灯是可控的，噪点不是。

<!-- V11_DEEPEN -->


> 意图分工：本页负责「曝光三角：先把高光保住」的可执行细节；同集群先读 <a href="https://tools.tvcn.org/article/nd-calculate/">ND 计算：大光圈白天怎么曝光</a> 建立总判断，再回到本页。

<!-- INTENT_SCOPE -->

<!-- SOURCES_START -->
## 参考与延伸阅读

- [S23] [SMPTE 标准入口](https://www.smpte.org/standards) — 2026-11-26 访问。用于核对首段“快门、光圈、ISO 不是三个平等旋钮。先定运动，再定景深，最后才用 ISO 救场。”中的术语与公开背景（时间码、色彩、影院与信号链标准的机构入口）；不替代现场测试。
- [S31] [ARRI Cine Systems](https://www.arri.com/en/cine-systems) — 2026-11-26 访问。用于核对首段“快门、光圈、ISO 不是三个平等旋钮。先定运动，再定景深，最后才用 ISO 救场。”中的术语与公开背景（摄影机、镜头与灯光的技术资料入口）；不替代现场测试。
- [S32] [Sony 专业影像支持](https://pro.sony/ue_US/support) — 2026-11-26 访问。用于核对首段“快门、光圈、ISO 不是三个平等旋钮。先定运动，再定景深，最后才用 ISO 救场。”中的术语与公开背景（专业摄影机与镜头的支持、固件与文档）；不替代现场测试。
- [S33] [Canon 支持](https://www.usa.canon.com/support) — 2026-11-26 访问。用于核对首段“快门、光圈、ISO 不是三个平等旋钮。先定运动，再定景深，最后才用 ISO 救场。”中的术语与公开背景（相机、镜头与固件的官方支持入口）；不替代现场测试。
- [S52] [ARRI：ALEXA 35](https://www.arri.com/en/camera-systems/cameras/legacy-camera-systems/alexa-35) — 2026-11-26 访问。用于核对首段“快门、光圈、ISO 不是三个平等旋钮。先定运动，再定景深，最后才用 ISO 救场。”中的术语与公开背景（摄影机规格、Log-C 与色彩流程）；不替代现场测试。
<!-- SOURCES_END -->

