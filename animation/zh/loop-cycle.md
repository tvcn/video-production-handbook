---
id: animation.2d.loop-cycle
site: animation
type: article
lang: zh
translation_key: animation.2d.loop-cycle
translation_status: source
title: 循环动作：首尾怎么接
summary: 循环动作首尾帧必须对得上，否则每转一圈就抖一下。
slug: loop-cycle
aliases:
- loop-cycle
canonical_site: animation
canonical_path: /article/loop-cycle/
status: published
diagram: /images/diagrams/zh/loop-cycle.svg
diagram_alt: 循环动作：首尾怎么接的结构示意图。
diagram_caption: 看“首尾各画同一帧”和“中间 8 到 12 帧”两处，判断前景、中景、背景的速度差能不能在一次移动里看出来。
difficulty: beginner
stage: field-note
format: handbook
authors:
- TVCN 动画组
last_verified: '2026-11-26'
review_due: '2027-02-26'
related: [animation.3d.materials, animation.motion-graphics.mg-infographic, formats.documentary.documentary-template]
sources:
- S62
- S63
- S12
- S23
- S59
source_kind: sourced
---
<p>走路、跑步、呼吸的循环，第一帧和最后一帧必须能无缝接上。先做关键姿势，再补中间帧；接点处多留一帧重叠，循环才不跳。</p>
<!-- DIAGRAM_START -->
<h2>图解</h2>
<figure>
  <img src="/images/diagrams/zh/loop-cycle.svg" alt="循环动作：首尾怎么接的结构示意图。">
  <figcaption>看“首尾各画同一帧”和“中间 8 到 12 帧”两处，判断前景、中景、背景的速度差能不能在一次移动里看出来。</figcaption>
</figure>
<!-- DIAGRAM_END -->
<section><h2 id="section-1">循环先保“接点”，再保“变化”</h2><p>循环不是完全重复。每循环一次加一个小变化：手抬高一点、脚步慢一点；完全一样，观众三秒就看腻。</p><h2 id="section-2">边界</h2><p>循环长度由动作决定，不由音乐决定。步子没走完就硬切，脚会滑；先让动作完整，再对节拍。</p></section><section><h2 id="section-3">现场</h2><p>首尾各画同一帧，中间 8 到 12 帧；循环播放，看最后一帧到第一帧有没有跳。</p></section><section><h2 id="section-4">怎么做</h2><ol><li>首尾各画同一帧。</li><li>中间 8 到 12 帧。</li><li>循环播放，看最后一帧到第一帧有没有跳。</li></ol></section><section><h2 id="section-5">别踩</h2><p>别让首尾差一帧；循环一多，抖动会越来越明显。</p></section><section><h2>判断</h2><p>现场只认三个信号：</p><ul><li>前景、中景、背景的速度差能在一次 pan 里看出来</li><li>动作在 0.5 秒内能读出重量或预备</li><li>关掉任意一层，空间感仍然成立</li></ul></section><section><h2>失败</h2><p>下面三种做法会让页面上的细节白做：</p><ul><li>层数堆上去了，但每层速度一样，空间还是扁的</li><li>动作有预备却没有跟随，重量只做了一半</li><li>资产没锁就进渲染，返工从合成端一路补</li></ul></section><section><h2>延伸</h2><p><strong>10 分钟练习：</strong>用 24 fps 画 3 个关键帧，只改“中间 8 到 12 帧”，导出 2 秒；如果重量仍读不出来，先加预备帧，不要加模糊。</p></section>
<h2>验收</h2><ul><li>首帧和尾帧是同一姿势，位置和形状一致。</li><li>中间 8 到 12 帧，节奏均匀。</li><li>循环播放十圈，接缝处没有跳一下或黏一下。</li></ul>

<!-- SOURCES_START -->
## 参考与延伸阅读

- [S62] [Blender Foundation：Blender 官方手册](https://docs.blender.org/manual/en/latest/) — 2026-11-26 访问。用于核对首段“循环动作首尾帧必须对得上，否则每转一圈就抖一下。”中的术语与公开背景（建模、绑定、动画、渲染）；不替代现场测试。
- [S63] [Toon Boom：官方文档](https://docs.toonboom.com/) — 2026-11-26 访问。用于核对首段“循环动作首尾帧必须对得上，否则每转一圈就抖一下。”中的术语与公开背景（2D 动画、绑定与制作管线）；不替代现场测试。
- [S12] [Britannica](https://www.britannica.com/art/animation) — 2026-11-26 访问。用于核对首段“循环动作首尾帧必须对得上，否则每转一圈就抖一下。”中的术语与公开背景（动画原理、技术与产业史的百科条目）；不替代现场测试。
- [S23] [SMPTE 标准入口](https://www.smpte.org/standards) — 2026-11-26 访问。用于核对首段“循环动作首尾帧必须对得上，否则每转一圈就抖一下。”中的术语与公开背景（时间码、色彩、影院与信号链标准的机构入口）；不替代现场测试。
- [S59] [Adobe：After Effects 用户指南](https://helpx.adobe.com/after-effects/user-guide.html) — 2026-11-26 访问。用于核对首段“循环动作首尾帧必须对得上，否则每转一圈就抖一下。”中的术语与公开背景（合成、关键帧、跟踪与导出）；不替代现场测试。
<!-- SOURCES_END -->

