---
id: post.editing.proxy-workflow
site: post
type: article
lang: zh
translation_key: post.editing.proxy-workflow
translation_status: source
title: 代理流程：先能剪，再谈画质
summary: 代理不是降低成片质量，是让剪辑先跑起来；原始素材永远留在旁边。
slug: proxy-workflow
aliases:
- proxy-workflow
canonical_site: post
canonical_path: /article/proxy-workflow/
status: published
diagram: /images/diagrams/zh/proxy-workflow.svg
diagram_alt: 代理流程：先能剪，再谈画质的结构示意图。
diagram_caption: 看“用 ProRes Proxy 或四分…”和“把原始素材设为只读，剪辑只碰代理”两处，判断剪掉一个镜头后，节奏是更快还是更乱。
difficulty: beginner
stage: field-note
format: handbook
authors:
- TVCN 后期组
last_verified: '2026-11-25'
review_due: '2027-05-25'
related:
- post.editing.rough-cut.en
- shoot.lighting.ratio.en
- story.screenplay.three-act.en
depth: deep
deep_minutes: 5
sources:
- S24
- S27
- S28
- S30
- S34
- S35
test_context: 复核环境：Windows 11（RTX 3060）+ macOS 14（M1）；DaVinci Resolve 20 与 Premiere
  Pro 2025 复跑；不声称每台机器结果一致。
known_failures: 已知失败：旧版软件时间线不兼容；不同相机 Log 需重新映射；代理丢失时需回套原片。
verified: 2026-11-22
source_kind: sourced
---

<p>代理解决的是“机器剪不动原素材”，不是“画质可以降”。生成代理时保留原文件名、时间码和卷名，剪辑完成后回批原素材，再输出母版。</p>
<!-- DIAGRAM_START -->
<h2>图解</h2>
<figure>
  <img src="/images/diagrams/zh/proxy-workflow.svg" alt="代理流程：先能剪，再谈画质的结构示意图。">
  <figcaption>看“用 ProRes Proxy 或四分…”和“把原始素材设为只读，剪辑只碰代理”两处，判断剪掉一个镜头后，节奏是更快还是更乱。</figcaption>
</figure>
<!-- DIAGRAM_END -->
<section><h2 id="section-1">代理是剪辑副本，不是交付文件</h2><p>代理分辨率按时间线需求选，不要一律最小；多机位项目先测一台机器同时播放几条，再决定码率。</p><h2 id="section-2">边界</h2><p>代理和原素材必须能一一对应。改名、丢时间码或混放不同帧率，会让回批变成手工找文件。交付前检查母版链接的是原素材，不是代理。</p></section><section><h2 id="section-3">现场</h2><p>代理用 ProRes Proxy 或四分之一分辨率，放独立 SSD；原始素材设只读，剪辑只碰代理，交付前回套。</p></section><section><h2 id="section-4">怎么做</h2><ol><li>用 ProRes Proxy 或四分之一分辨率生成代理，放在独立 SSD。</li><li>把原始素材设为只读，剪辑只碰代理。</li><li>交付前回套原始，逐条确认没有误用代理。</li></ol></section><section><h2 id="section-5">别踩</h2><p>别把代理当母版；回套前交付，画质会露馅。</p></section><section><h2>判断</h2><p>现场只认三个信号：</p><ul><li>剪掉一个镜头，节奏更快而不是更乱</li><li>示波器上肤色、高光和黑位都在范围内</li><li>响度、字幕和文件规格能过一次交付检查</li></ul></section><section><h2>失败</h2><p>下面三种做法会让页面上的细节白做：</p><ul><li>剪辑点跟着音乐，不跟动作</li><li>先定风格再统一，镜头之间跳色</li><li>交付前没查响度和字幕，最后一遍才发现</li></ul></section><section><h2>延伸</h2><p><strong>10 分钟练习：</strong>拿一段 30 秒素材做 A/B，只改“用 ProRes Proxy 或四分…”；记下一个时间码和一处差异，再决定是否保留。</p></section>
<h2>验收</h2><ul><li>代理和原始分盘存放，原始文件夹是只读的。</li><li>时间线只引用代理，文件名和路径能一一对应。</li><li>回套原始后随机抽三个镜头，分辨率和细节回到原档。</li></ul>

<!-- DEEP_DIVE_START -->
## 深读
<p><strong>约 5 分钟。</strong> 代理不是画质降级，是让剪辑先跑起来。原素材不动，代理只负责响应速度。</p>
### 什么时候需要代理
<p>4K 以上、多机位、老机器，剪起来卡就做代理。1080 单轨流畅就不必，别为了流程而流程。</p><p>代理分辨率按时间线定，别做比时间线还大的代理。时间线 1080，代理也 1080 足够。</p>
### 代理怎么生成
<p>保持文件名、时间码、卷号一致，放在独立 Proxy 文件夹。不要覆盖原素材，也不要改原素材的目录结构。</p><p>生成后先抽三个镜头检查，确认声音和色彩没有丢。代理可以糊，但不能没有声。</p>
### 回套和输出
<p>剪完先锁定剪辑，再回套原素材。回套后检查变速、字幕和转场，代理和原素材的时长可能差一帧。</p><p>交付一定用原素材输出，代理只留在工程里。把代理当母版，画质会在最需要的时候掉下去。</p>
### 代理的命名和目录
<p>原素材在 Camera，代理在 Proxy，工程在 Project。三个文件夹不混。</p><p>代理文件名加 _proxy，回套时一眼能认。不要改原文件名。</p>
### 多机位代理
<p>多机位先做同一分辨率和帧率的代理，否则时间线会拒绝。</p><p>代理生成后先合一次板，确认声音和机位没问题，再开始剪。</p>
### 代理流程，十项确认
<ul><li>只在高分辨率或多机位时做</li><li>代理文件名与原素材一致</li><li>代理放在独立文件夹</li><li>不覆盖原素材</li><li>保留时间码和卷号</li><li>生成后抽查三条</li><li>剪辑用代理</li><li>回套前锁定剪辑</li><li>回套后查变速字幕</li><li>交付用原素材</li></ul><p>代理是脚手架，不是房子。剪完要拆，交付不能住在里面。</p>
### 只剩五分钟时
<ul><li>只在高分辨率或多机位做</li><li>代理文件名与原素材一致</li><li>代理放独立文件夹</li><li>生成后抽查三条</li><li>锁定剪辑再回套</li><li>交付用原素材</li></ul><p>代理让剪辑先跑起来，原素材让片子最后站得住。代理坏了可以重做，原素材丢了没有第二次。</p>
<!-- DEEP_DIVE_END -->
<!-- SOURCES_START -->
