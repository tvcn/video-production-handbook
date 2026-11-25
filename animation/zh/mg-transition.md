---
id: animation.motion-graphics.mg-transition
site: animation
type: article
lang: zh
translation_key: animation.motion-graphics.mg-transition
translation_status: source
title: 图形转场：形状接形状
summary: 图形转场让一个形状变成另一个形状，别用白闪或随便推拉。
slug: mg-transition
aliases:
- mg-transition
canonical_site: animation
canonical_path: /article/mg-transition/
status: published
diagram: /images/diagrams/zh/mg-transition.svg
diagram_alt: 图形转场：形状接形状的结构示意图。
diagram_caption: 看“选一个形状：圆变方、线变箭头”和“用 8 到 12 帧完成变形”两处，判断前景、中景、背景的速度差能不能在一次移动里看出来。
difficulty: beginner
stage: field-note
format: handbook
authors:
- TVCN 动画组
last_verified: '2026-11-25'
review_due: '2027-05-25'
related:
- animation.motion-graphics.mg-infographic.en
- animation.motion-graphics.mg-rhythm.en
- animation.stop-motion.stop-motion-motion-blur.en
source_kind: experience
---

<p>动态图形转场不是加一个花哨划像。它要把上一段的信息带到下一段：一个圆变成图表、一条线变成时间轴、一个词拆成新词。转场结束，观众应该多知道一件事。</p>
<!-- DIAGRAM_START -->
<h2>图解</h2>
<figure>
  <img src="/images/diagrams/zh/mg-transition.svg" alt="图形转场：形状接形状的结构示意图。">
  <figcaption>看“选一个形状：圆变方、线变箭头”和“用 8 到 12 帧完成变形”两处，判断前景、中景、背景的速度差能不能在一次移动里看出来。</figcaption>
</figure>
<!-- DIAGRAM_END -->
<section><h2 id="section-1">转场要“带信息”，不是遮丑</h2><p>先写“从什么变到什么”，再做动画；不要让软件预设决定内容。</p><h2 id="section-2">边界</h2><p>转场不能掩盖结构问题。两段内容没有关系，再顺的转场也只是拖延；先删一段，再谈过渡。</p></section><section><h2 id="section-3">现场</h2><p>选一个形状：圆变方、线变箭头；用 8 到 12 帧完成，别用白闪。</p></section><section><h2 id="section-4">怎么做</h2><ol><li>选一个形状：圆变方、线变箭头。</li><li>用 8 到 12 帧完成变形。</li><li>不要用白闪，前后信息要能接上。</li></ol></section><section><h2 id="section-5">别踩</h2><p>别用白闪和推拉当万能转场；形状接不上，观众就断片。</p></section><section><h2>判断</h2><p>现场只认三个信号：</p><ul><li>前景、中景、背景的速度差能在一次 pan 里看出来</li><li>动作在 0.5 秒内能读出重量或预备</li><li>关掉任意一层，空间感仍然成立</li></ul></section><section><h2>失败</h2><p>下面三种做法会让页面上的细节白做：</p><ul><li>层数堆上去了，但每层速度一样，空间还是扁的</li><li>动作有预备却没有跟随，重量只做了一半</li><li>资产没锁就进渲染，返工从合成端一路补</li></ul></section><section><h2>延伸</h2><p><strong>10 分钟练习：</strong>用 24 fps 画 3 个关键帧，只改“用 8 到 12 帧完成变形”，导出 2 秒；如果重量仍读不出来，先加预备帧，不要加模糊。</p></section>
<h2>验收</h2><ul><li>转场前后是同一个形状在变形，不是硬切。</li><li>变形在 8 到 12 帧内完成，速度可读。</li><li>拿掉白闪后信息仍能接上，观众知道到了哪里。</li></ul>
