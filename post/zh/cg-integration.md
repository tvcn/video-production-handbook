---
id: post.vfx.cg-integration
site: post
type: article
lang: zh
translation_key: post.vfx.cg-integration
translation_status: source
title: CG 合成：光、影、雾一起对
summary: CG 合成先对光的方向、影子的软硬、空气的雾，再谈细节。
slug: cg-integration
aliases:
- cg-integration
canonical_site: post
canonical_path: /article/cg-integration/
status: published
diagram: /images/diagrams/zh/cg-integration.svg
diagram_alt: CG 合成：光、影、雾一起对的结构示意图。
diagram_caption: 看“先对主光方向，让 CG 和实拍受光一…”和“再对影子软硬和空气雾，确定空间深度”两处，判断剪掉一个镜头后，节奏是更快还是更乱。
difficulty: beginner
stage: field-note
format: handbook
authors:
- TVCN 后期组
last_verified: '2026-11-25'
review_due: '2027-05-25'
related:
- post.vfx.cleanup.en
- post.vfx.rotoscoping.en
- post.accessibility.sdh.en
source_kind: experience
---

<p>CG 与实拍合成，最容易露馅的是光线方向和镜头畸变。先记录实拍的光位、色温、镜头焦距和光圈，再让 CG 用同一套参数渲染；颜色可以后期，光位不行。</p>
<!-- DIAGRAM_START -->
<h2>图解</h2>
<figure>
  <img src="/images/diagrams/zh/cg-integration.svg" alt="CG 合成：光、影、雾一起对的结构示意图。">
  <figcaption>看“先对主光方向，让 CG 和实拍受光一…”和“再对影子软硬和空气雾，确定空间深度”两处，判断剪掉一个镜头后，节奏是更快还是更乱。</figcaption>
</figure>
<!-- DIAGRAM_END -->
<section><h2 id="section-1">先共享“光”和“镜头”，再共享“颜色”</h2><p>合成前做一张灰球和色卡对比；CG 的反射、阴影和颗粒要匹配实拍。</p><h2 id="section-2">边界</h2><p>CG 不能救没有拍好的 plate。实拍没有运动模糊、没有正确透视，后期加特效只会更假；先拍对。</p></section><section><h2 id="section-3">现场</h2><p>先对三样：主光方向、影子软硬、空气雾；再对颗粒和镜头畸变，最后才加细节。</p></section><section><h2 id="section-4">怎么做</h2><ol><li>先对主光方向，让 CG 和实拍受光一致。</li><li>再对影子软硬和空气雾，确定空间深度。</li><li>最后对颗粒和镜头畸变，细节放在最后。</li></ol></section><section><h2 id="section-5">别踩</h2><p>别先抠细节；光和影不对，细节越多越假。</p></section><section><h2>判断</h2><p>现场只认三个信号：</p><ul><li>剪掉一个镜头，节奏更快而不是更乱</li><li>示波器上肤色、高光和黑位都在范围内</li><li>响度、字幕和文件规格能过一次交付检查</li></ul></section><section><h2>失败</h2><p>下面三种做法会让页面上的细节白做：</p><ul><li>剪辑点跟着音乐，不跟动作</li><li>先定风格再统一，镜头之间跳色</li><li>交付前没查响度和字幕，最后一遍才发现</li></ul></section><section><h2>延伸</h2><p><strong>10 分钟练习：</strong>拿一段 30 秒素材做 A/B，只改“先对主光方向，让 CG 和实拍受光一…”；记下一个时间码和一处差异，再决定是否保留。</p></section>
<h2>验收</h2><ul><li>CG 和实拍的主光方向一致，阴影落在同侧。</li><li>影子软硬和空气雾匹配，前后景没有贴片感。</li><li>颗粒和畸变对上后，成片尺寸看不出 CG 边界。</li></ul>
