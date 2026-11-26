---
id: animation.principles.weight
site: animation
type: article
lang: zh
translation_key: animation.principles.weight
translation_status: source
title: 重量：落地的加速度
summary: 重量不在姿势，在落地那几帧的加减速；没有加速度，一切像气球。
slug: weight
aliases:
- weight
canonical_site: animation
canonical_path: /article/weight/
status: published
diagram: /images/diagrams/zh/weight.svg
diagram_alt: 重量：落地的加速度的结构示意图。
diagram_caption: 看“落地前 2 帧加速”和“接触后 2 帧停住，再 3 帧回弹”两处，判断前景、中景、背景的速度差能不能在一次移动里看出来。
difficulty: beginner
stage: field-note
format: handbook
authors:
- TVCN 动画组
last_verified: '2026-11-26'
review_due: '2027-02-26'
related: [animation.2d.2d-animation, animation.2d.2d-camera, formats.documentary.documentary-template]
sources:
- S62
- S63
- S12
- S23
- S59
source_kind: sourced
---
<p>动画里的重量不是把角色画胖。看三处：脚是否压住地面、膝盖是否弯曲、动作启动和停止是否有延迟。重物起步慢、停下也慢；轻物起步快、停得急。</p>
<!-- DIAGRAM_START -->
<h2>图解</h2>
<figure>
  <img src="/images/diagrams/zh/weight.svg" alt="重量：落地的加速度的结构示意图。">
  <figcaption>看“落地前 2 帧加速”和“接触后 2 帧停住，再 3 帧回弹”两处，判断前景、中景、背景的速度差能不能在一次移动里看出来。</figcaption>
</figure>
<!-- DIAGRAM_END -->
<section><h2 id="section-1">重量靠“支撑”和“延迟”</h2><p>做搬箱测试：同一个人搬空箱和满箱，身体前倾、呼吸、脚步频率都要不同；只改箱子颜色，观众不会信。</p><h2 id="section-2">边界</h2><p>重量不是慢动作。所有动作都放慢，只会像水下；重的是加速和减速的曲线。</p></section><section><h2 id="section-3">现场</h2><p>落地前 2 帧加速，接触后 2 帧停住，再 3 帧回弹；给重物加 1 到 2 帧延迟。</p></section><section><h2 id="section-4">怎么做</h2><ol><li>落地前 2 帧加速。</li><li>接触后 2 帧停住，再 3 帧回弹。</li><li>给重物加 1 到 2 帧延迟，让重量落在接触之后。</li></ol></section><section><h2 id="section-5">别踩</h2><p>别只画姿势不画加减速；姿势再重，落地还是像气球。</p></section><section><h2>判断</h2><p>现场只认三个信号：</p><ul><li>前景、中景、背景的速度差能在一次 pan 里看出来</li><li>动作在 0.5 秒内能读出重量或预备</li><li>关掉任意一层，空间感仍然成立</li></ul></section><section><h2>失败</h2><p>下面三种做法会让页面上的细节白做：</p><ul><li>层数堆上去了，但每层速度一样，空间还是扁的</li><li>动作有预备却没有跟随，重量只做了一半</li><li>资产没锁就进渲染，返工从合成端一路补</li></ul></section><section><h2>延伸</h2><p><strong>10 分钟练习：</strong>用 24 fps 画 3 个关键帧，只改“接触后 2 帧停住，再 3 帧回弹”，导出 2 秒；如果重量仍读不出来，先加预备帧，不要加模糊。</p></section>
<h2>验收</h2><ul><li>落地前有加速，接触后有停顿和回弹。</li><li>重物比轻物多 1 到 2 帧延迟，重量有差别。</li><li>遮住姿势只看落地点，仍能感到重量。</li></ul>

<!-- SOURCES_START -->
## 参考与延伸阅读

- [S62] [Blender Foundation：Blender 官方手册](https://docs.blender.org/manual/en/latest/) — 2026-11-26 访问。用于核对首段“重量不在姿势，在落地那几帧的加减速；没有加速度，一切像气球。”中的术语与公开背景（建模、绑定、动画、渲染）；不替代现场测试。
- [S63] [Toon Boom：官方文档](https://docs.toonboom.com/) — 2026-11-26 访问。用于核对首段“重量不在姿势，在落地那几帧的加减速；没有加速度，一切像气球。”中的术语与公开背景（2D 动画、绑定与制作管线）；不替代现场测试。
- [S12] [Britannica](https://www.britannica.com/art/animation) — 2026-11-26 访问。用于核对首段“重量不在姿势，在落地那几帧的加减速；没有加速度，一切像气球。”中的术语与公开背景（动画原理、技术与产业史的百科条目）；不替代现场测试。
- [S23] [SMPTE 标准入口](https://www.smpte.org/standards) — 2026-11-26 访问。用于核对首段“重量不在姿势，在落地那几帧的加减速；没有加速度，一切像气球。”中的术语与公开背景（时间码、色彩、影院与信号链标准的机构入口）；不替代现场测试。
- [S59] [Adobe：After Effects 用户指南](https://helpx.adobe.com/after-effects/user-guide.html) — 2026-11-26 访问。用于核对首段“重量不在姿势，在落地那几帧的加减速；没有加速度，一切像气球。”中的术语与公开背景（合成、关键帧、跟踪与导出）；不替代现场测试。
<!-- SOURCES_END -->

