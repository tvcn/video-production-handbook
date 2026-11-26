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
deep_minutes: 8
depth: deep
authors:
- TVCN 动画组
last_verified: '2026-11-26'
review_due: '2027-02-26'
related: [animation.2d.2d-animation, animation.2d.2d-camera, formats.documentary.documentary-template]
sources:
- S12
- S62
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
<section><h2 id="section-1">重量靠“支撑”和“延迟”</h2><p>做搬箱测试：同一个人搬空箱和满箱，身体前倾、呼吸、脚步频率都要不同；只改箱子颜色，观众不会信。</p><h2 id="section-2">边界</h2><p>重量不是慢动作。所有动作都放慢，只会像水下；重的是加速和减速的曲线。</p></section><section><h2 id="section-3">现场</h2><p>落地前 2 帧加速，接触后 2 帧停住，再 3 帧回弹；给重物加 1 到 2 帧延迟。</p></section><section><h2 id="section-4">怎么做</h2><ol><li>落地前 2 帧加速。</li><li>接触后 2 帧停住，再 3 帧回弹。</li><li>给重物加 1 到 2 帧延迟，让重量落在接触之后。</li></ol></section><section><h2 id="section-5">别踩</h2><p>别只画姿势不画加减速；姿势再重，落地还是像气球。</p></section><section><h2>判断</h2><p>这一页的判断只看三条可观察的验收，不靠口号：</p><ul><li><strong>1.</strong> 落地前有加速，接触后有停顿和回弹。</li><li><strong>2.</strong> 重物比轻物多 1 到 2 帧延迟，重量有差别。</li><li><strong>3.</strong> 遮住姿势只看落地点，仍能感到重量。</li></ul></section><section><h2>失败</h2><p>下面任一条出现，先停，不要靠后期补：</p><ul><li><strong>1.</strong> 只做到“落地前有加速，接触后有停顿和回弹”的形式，换一个机位或场景就重现不了。</li><li><strong>2.</strong> 把“重物比轻物多 1 到 2 帧延迟，重量有差别”留到后期或口头解释，现场没有留下能复查的记录。</li><li><strong>3.</strong> 别只画姿势不画加减速；姿势再重，落地还是像气球。</li></ul></section><section><h2>延伸</h2><p><strong>10 分钟练习：</strong>用 24 fps 画 3 个关键帧，只改“接触后 2 帧停住，再 3 帧回弹”，导出 2 秒；如果重量仍读不出来，先加预备帧，不要加模糊。</p></section>
<h2>验收</h2><ul><li>落地前有加速，接触后有停顿和回弹。</li><li>重物比轻物多 1 到 2 帧延迟，重量有差别。</li><li>遮住姿势只看落地点，仍能感到重量。</li></ul>

<!-- DEEP_DIVE_START -->
## 深读
<p><strong>约 8 分钟。</strong> 这一节不重复前面的做法，只补三个东西：两种条件、一个反例、一个可复用模型；读完能判断什么时候换做法。</p>
### 条件 A：小重量/轻物件
<p>轻物件不是“没有重量”，是“重量小到能被风、呼吸和手指改变”。纸、杯子、衣角、头发，落地前会飘，落地后会停；动画要让“飘”和“停”之间有清楚的接触帧。没有接触帧，观众觉得物件在飘。</p><p>轻物件的关键是“二次动作”：主体落下后，边缘还在动一下。纸张落地后角翘一下，杯子放下后水面晃一下。二次动作让重量有余波，不是硬停。</p>
### 条件 B：大重量/角色
<p>大重量不是“动作慢”，是“身体必须先承受，再移动”。角色搬重物，先屈膝、再抓、再起身；起身时重心先过脚，物件才离地。没有“承受”帧，角色像在提一个空箱子。</p><p>大重量的落地要有“压缩—回弹—稳定”：脚接触地面，身体下沉一帧，再回弹，再稳定。只做下沉不做回弹，像陷进地；只做回弹不做下沉，像踩弹簧。</p>
### 反例：有弹跳，没有接触
<p>一个球从桌上落下，动画给了很漂亮的弹跳曲线，但球在接触桌面前一帧就开始上升。观众说不出哪里不对，只觉得“假”。问题不是曲线，是缺少接触帧。</p><p>修法不是把弹跳调低，而是在接触点加 1–2 帧压缩：球先扁，再弹。压缩帧让观众相信地面存在；没有地面，弹跳只是上下移动。</p>
### 可复用模型
<p><strong>预备 → 接触 → 压缩 → 回弹 → 稳定。</strong> 五帧组决定重量。预备让身体知道要动，接触让地面存在，压缩让重量可见，回弹让材料有弹性，稳定让动作结束。</p><p>做完拍一遍，关掉音乐看：如果只看轮廓也能说出物件有多重，重量就成立；如果必须靠音效，动作还没做完。</p>
<!-- DEEP_DIVE_END -->

<!-- SOURCES_START -->
## 参考与延伸阅读

- [S12] [Britannica：动画](https://www.britannica.com/art/animation) — 2026-11-26 访问。用于核对「重量靠“支撑”和“延迟”」一节的术语/方法/规则（Britannica 动画史条目，不是软件手册）；不核对其中由本页经验得出的数字、型号与现场结论，也不替代测试。
- [S62] [Blender：官方手册](https://docs.blender.org/manual/en/latest/) — 2026-11-26 访问。用于核对「现场」一节的术语/方法/规则（Blender 官方手册，不是行业流程标准）；不核对其中由本页经验得出的数字、型号与现场结论，也不替代测试。
<!-- SOURCES_END -->

