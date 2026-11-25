---
id: animation.2d.run-cycle
site: animation
type: article
lang: zh
translation_key: animation.2d.run-cycle
translation_status: source
title: 跑步循环：脚与重心
summary: 跑步循环先定重心和脚掌着地顺序，再修手臂；脚不对，全身都飘。
slug: run-cycle
aliases:
- run-cycle
canonical_site: animation
canonical_path: /article/run-cycle/
status: published
diagram: /images/diagrams/zh/run-cycle.svg
diagram_alt: 跑步循环：脚与重心的结构示意图。
diagram_caption: 看“先画 4 个关键姿势：接触、下压、通…”和“脚掌从脚跟滚到脚尖”两处，判断前景、中景、背景的速度差能不能在一次移动里看出来。
difficulty: beginner
stage: field-note
format: handbook
authors:
- TVCN 动画组
last_verified: '2026-11-25'
review_due: '2027-05-25'
related:
- animation.2d.loop-cycle.en
- animation.principles.anticipation.en
- animation.principles.weight.en
source_kind: experience
---

<p>跑步循环的关键不是腿抬多高，而是脚什么时候落地、身体什么时候最低。先标接触帧和腾空帧，再做中间；接触帧错了，整段会滑。</p>
<!-- DIAGRAM_START -->
<h2>图解</h2>
<figure>
  <img src="/images/diagrams/zh/run-cycle.svg" alt="跑步循环：脚与重心的结构示意图。">
  <figcaption>看“先画 4 个关键姿势：接触、下压、通…”和“脚掌从脚跟滚到脚尖”两处，判断前景、中景、背景的速度差能不能在一次移动里看出来。</figcaption>
</figure>
<!-- DIAGRAM_END -->
<section><h2 id="section-1">跑步循环先定“接触帧”</h2><p>用侧视图检查：头是否上下跳、胯是否左右摆、手臂是否和腿反向。三项有一项不对，循环就不稳。</p><h2 id="section-2">边界</h2><p>跑步不是走路加速。走路总有一只脚着地，跑步有腾空；把走路循环加快，会像竞走。</p></section><section><h2 id="section-3">现场</h2><p>先画 4 个关键姿势：接触、下压、通过、腾空；脚掌从脚跟滚到脚尖，重心上下不超过一个头。</p></section><section><h2 id="section-4">怎么做</h2><ol><li>先画 4 个关键姿势：接触、下压、通过、腾空。</li><li>脚掌从脚跟滚到脚尖。</li><li>重心上下不超过一个头，再修手臂。</li></ol></section><section><h2 id="section-5">别踩</h2><p>别先修手臂；脚一滑，手臂再顺也像飘。</p></section><section><h2>判断</h2><p>现场只认三个信号：</p><ul><li>前景、中景、背景的速度差能在一次 pan 里看出来</li><li>动作在 0.5 秒内能读出重量或预备</li><li>关掉任意一层，空间感仍然成立</li></ul></section><section><h2>失败</h2><p>下面三种做法会让页面上的细节白做：</p><ul><li>层数堆上去了，但每层速度一样，空间还是扁的</li><li>动作有预备却没有跟随，重量只做了一半</li><li>资产没锁就进渲染，返工从合成端一路补</li></ul></section><section><h2>延伸</h2><p><strong>10 分钟练习：</strong>用 24 fps 画 3 个关键帧，只改“脚掌从脚跟滚到脚尖”，导出 2 秒；如果重量仍读不出来，先加预备帧，不要加模糊。</p></section>
<h2>验收</h2><ul><li>四个关键姿势齐全，接触、下压、通过、腾空都能认出来。</li><li>支撑脚从脚跟滚到脚尖，没有整只脚平移。</li><li>重心上下不超过一个头，循环播放不飘。</li></ul>
