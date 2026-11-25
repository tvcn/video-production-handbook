---
id: post.color.scopes
site: post
type: article
lang: zh
translation_key: post.color.scopes
translation_status: source
title: 示波器：黑位、白位、肤色
summary: 示波器先看三件事：黑位有没有死、白位有没有爆、肤色线偏没偏。
slug: scopes
aliases:
- scopes
canonical_site: post
canonical_path: /article/scopes/
status: published
diagram: /images/diagrams/zh/scopes.svg
diagram_alt: 示波器：黑位、白位、肤色的结构示意图。
diagram_caption: 看“黑位不低于 0，白位不高于 100”和“肤色线落在矢量示波器的肤色区”两处，判断剪掉一个镜头后，节奏是更快还是更乱。
difficulty: beginner
stage: field-note
format: handbook
authors:
- TVCN 后期组
last_verified: '2026-11-25'
review_due: '2027-05-25'
related:
- post.color.hdr.en
- post.color.lut.en
- post.color.secondary-correction.en
source_kind: experience
---

<p>波形图看整体亮度和高光贴顶；矢量示波器看饱和度和色相；RGB parade 看三个通道是否对齐。三者一起用，才能判断“亮”和“偏色”是两件事。</p>
<!-- DIAGRAM_START -->
<h2>图解</h2>
<figure>
  <img src="/images/diagrams/zh/scopes.svg" alt="示波器：黑位、白位、肤色的结构示意图。">
  <figcaption>看“黑位不低于 0，白位不高于 100”和“肤色线落在矢量示波器的肤色区”两处，判断剪掉一个镜头后，节奏是更快还是更乱。</figcaption>
</figure>
<!-- DIAGRAM_END -->
<section><h2 id="section-1">波形看亮度，矢量看颜色， parade 看分离</h2><p>先看 parade 的黑白平衡，再看矢量肤色线，最后回波形确认高光；不要只看一个示波器就下结论。</p><h2 id="section-2">边界</h2><p>示波器不是创作裁判。风格化低对比、夜景和逆光都可能“不好看”；先定意图，再读示波器。</p></section><section><h2 id="section-3">现场</h2><p>黑位不低于 0、白位不高于 100；肤色线落在矢量示波器的肤色区，偏红就降饱和或调白平衡。</p></section><section><h2 id="section-4">怎么做</h2><ol><li>黑位不低于 0，白位不高于 100。</li><li>肤色线落在矢量示波器的肤色区。</li><li>偏红就降饱和或调白平衡，不要凭眼睛猜。</li></ol></section><section><h2 id="section-5">别踩</h2><p>别用肉眼代替示波器；监看没校准，眼睛也会骗你。</p></section><section><h2>判断</h2><p>现场只认三个信号：</p><ul><li>剪掉一个镜头，节奏更快而不是更乱</li><li>示波器上肤色、高光和黑位都在范围内</li><li>响度、字幕和文件规格能过一次交付检查</li></ul></section><section><h2>失败</h2><p>下面三种做法会让页面上的细节白做：</p><ul><li>剪辑点跟着音乐，不跟动作</li><li>先定风格再统一，镜头之间跳色</li><li>交付前没查响度和字幕，最后一遍才发现</li></ul></section><section><h2>延伸</h2><p><strong>10 分钟练习：</strong>拿一段 30 秒素材做 A/B，只改“黑位不低于 0，白位不高于 100”；记下一个时间码和一处差异，再决定是否保留。</p></section>
<h2>验收</h2><ul><li>黑位没有压到 0 以下，白位没有顶到 100 以上。</li><li>肤色线落在肤色区，没有明显偏红或偏绿。</li><li>调整前后各截一张示波器图，差别能对应到具体参数。</li></ul>
