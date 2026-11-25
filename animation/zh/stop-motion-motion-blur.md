---
id: animation.stop-motion.stop-motion-motion-blur
site: animation
type: article
lang: zh
translation_key: animation.stop-motion.stop-motion-motion-blur
translation_status: source
title: 定格运动模糊：拍两遍
summary: 定格运动模糊靠两次曝光或后期合成，不是把帧率调低。
slug: stop-motion-motion-blur
aliases:
- stop-motion-motion-blur
canonical_site: animation
canonical_path: /article/stop-motion-motion-blur/
status: published
diagram: /images/diagrams/zh/stop-motion-motion-blur.svg
diagram_alt: 定格运动模糊：拍两遍的结构示意图。
diagram_caption: 看“每个姿势拍两遍”和“第二遍把可动部分挪 2 到 3 毫米”两处，判断前景、中景、背景的速度差能不能在一次移动里看出来。
difficulty: beginner
stage: field-note
format: handbook
authors:
- TVCN 动画组
last_verified: '2026-11-25'
review_due: '2027-05-25'
related:
- animation.stop-motion.armature.en
- animation.stop-motion.stop-motion-set.en
- animation.motion-graphics.mg-transition.en
source_kind: experience
---

<p>定格不是真实快门连续曝光，运动模糊要靠后期或多次曝光模拟。先决定哪些帧需要模糊：快速挥手、转头、掉落；静态帧不要加，否则会糊。</p>
<!-- DIAGRAM_START -->
<h2>图解</h2>
<figure>
  <img src="/images/diagrams/zh/stop-motion-motion-blur.svg" alt="定格运动模糊：拍两遍的结构示意图。">
  <figcaption>看“每个姿势拍两遍”和“第二遍把可动部分挪 2 到 3 毫米”两处，判断前景、中景、背景的速度差能不能在一次移动里看出来。</figcaption>
</figure>
<!-- DIAGRAM_END -->
<section><h2 id="section-1">定格的运动模糊要“每帧决定”</h2><p>后期模糊要沿运动方向，长度匹配速度；全画面统一加模糊，看起来像雾。</p><h2 id="section-2">边界</h2><p>不是所有定格都需要模糊。逐帧清晰的“定格感”也是一种风格；先定风格，再决定加不加。</p></section><section><h2 id="section-3">现场</h2><p>每个姿势拍两遍，第二遍把可动部分挪 2 到 3 毫米；后期叠两帧，得到方向性模糊。</p></section><section><h2 id="section-4">怎么做</h2><ol><li>每个姿势拍两遍。</li><li>第二遍把可动部分挪 2 到 3 毫米。</li><li>后期叠两帧，得到方向性模糊。</li></ol></section><section><h2 id="section-5">别踩</h2><p>别用低帧率制造模糊；那只会让动作抖，不是运动模糊。</p></section><section><h2>判断</h2><p>现场只认三个信号：</p><ul><li>前景、中景、背景的速度差能在一次 pan 里看出来</li><li>动作在 0.5 秒内能读出重量或预备</li><li>关掉任意一层，空间感仍然成立</li></ul></section><section><h2>失败</h2><p>下面三种做法会让页面上的细节白做：</p><ul><li>层数堆上去了，但每层速度一样，空间还是扁的</li><li>动作有预备却没有跟随，重量只做了一半</li><li>资产没锁就进渲染，返工从合成端一路补</li></ul></section><section><h2>延伸</h2><p><strong>10 分钟练习：</strong>用 24 fps 画 3 个关键帧，只改“第二遍把可动部分挪 2 到 3 毫米”，导出 2 秒；如果重量仍读不出来，先加预备帧，不要加模糊。</p></section>
<h2>验收</h2><ul><li>每个动作姿势都有两遍曝光，第二遍有 2 到 3 毫米位移。</li><li>叠帧后模糊有方向，和运动方向一致。</li><li>没有靠降低帧率制造假模糊。</li></ul>
