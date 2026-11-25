---
id: post.color.hdr
site: post
type: article
lang: zh
translation_key: post.color.hdr
translation_status: source
title: HDR：先有 HDR 的素材和监看
summary: HDR 不是把 SDR 拉亮；拍摄、监看、交付都得真的支持 HDR。
slug: hdr
aliases:
- hdr
canonical_site: post
canonical_path: /article/hdr/
status: published
diagram: /images/diagrams/zh/hdr.svg
diagram_alt: HDR：先有 HDR 的素材和监看的结构示意图。
diagram_caption: 看“确认监看支持 HDR，素材有 10-…”和“交付 HDR10 或 HLG 时单独…”两处，判断剪掉一个镜头后，节奏是更快还是更乱。
difficulty: beginner
stage: field-note
format: handbook
authors:
- TVCN 后期组
last_verified: '2026-11-25'
review_due: '2027-05-25'
related:
- post.color.lut.en
- post.color.scopes.en
- post.color.secondary-correction.en
source_kind: experience
---

<p>HDR 不是把暗部无限拉亮，而是保留从窗到暗角的信息。曝光时让高光刚好不贴顶，用假色或波形确认；暗部留噪声空间，后期再决定压多少。</p>
<!-- DIAGRAM_START -->
<h2>图解</h2>
<figure>
  <img src="/images/diagrams/zh/hdr.svg" alt="HDR：先有 HDR 的素材和监看的结构示意图。">
  <figcaption>看“确认监看支持 HDR，素材有 10-…”和“交付 HDR10 或 HLG 时单独…”两处，判断剪掉一个镜头后，节奏是更快还是更乱。</figcaption>
</figure>
<!-- DIAGRAM_END -->
<section><h2 id="section-1">HDR 先保高光，再谈“亮”</h2><p>交付前用目标屏幕看一遍：HDR 母版在普通屏上可能发灰，需要单独做 SDR 版本，不要一版通投。</p><h2 id="section-2">边界</h2><p>HDR 不是风格滤镜。没有 HDR 屏幕和正确元数据，观众看到的可能比 SDR 更差；先确认交付链，再决定拍不拍。</p><h2 id="section-3">HDR 先有监看，再谈交付</h2>
<p>没有 HDR 监视器就做 HDR，等于闭眼调色。先确认监看链路：摄影机 log → HDR 监视器 → 交付 PQ/HLG；任何一段是 SDR，都只能做“猜”。</p>
<ol><li>监看亮度按交付标准设置，不要用电视默认“鲜艳”模式；环境光保持低。 </li><li>先在 PQ 里调高光，再做 SDR trim；不要用 SDR 版本反推 HDR。</li><li>交付前在普通 SDR 电视上看一遍，确认高光不刺眼、暗部不死黑。</li></ol>
<p>验收：HDR 和 SDR 两版都看，肤色一致、高光有细节；只有一版能看，说明转换不是可逆的。</p></section><section><h2 id="section-4">现场</h2><p>先确认监看支持 HDR、素材有 10-bit 和 Log；交付 HDR10 或 HLG 时单独做一版，不要从 SDR 拉。</p></section><section><h2 id="section-5">怎么做</h2><ol><li>确认监看支持 HDR，素材有 10-bit 和 Log。</li><li>交付 HDR10 或 HLG 时单独做一版。</li><li>不要从 SDR 版本拉亮，保留 HDR 的高光和暗部。</li></ol></section><section><h2 id="section-6">别踩</h2><p>别把 SDR 拉亮当 HDR；高光是假的，暗部也没有信息。</p></section><section><h2>判断</h2><p>现场只认三个信号：</p><ul><li>剪掉一个镜头，节奏更快而不是更乱</li><li>示波器上肤色、高光和黑位都在范围内</li><li>响度、字幕和文件规格能过一次交付检查</li></ul></section><section><h2>失败</h2><p>下面三种做法会让页面上的细节白做：</p><ul><li>剪辑点跟着音乐，不跟动作</li><li>先定风格再统一，镜头之间跳色</li><li>交付前没查响度和字幕，最后一遍才发现</li></ul></section><section><h2>延伸</h2><p><strong>10 分钟练习：</strong>拿一段 30 秒素材做 A/B，只改“确认监看支持 HDR，素材有 10-…”；记下一个时间码和一处差异，再决定是否保留。</p></section>
<h2>验收</h2><ul><li>素材是 10-bit Log，监看链路真的支持 HDR。</li><li>HDR 版是单独做的，不是从 SDR 拉亮。</li><li>HDR 和 SDR 两版都看一遍，高光与暗部都能各自成立。</li></ul>
