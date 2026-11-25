---
id: tools.capability.field-recorder
site: tools
type: tool
lang: zh
translation_key: tools.capability.field-recorder
translation_status: source
title: 录音机：32-bit 浮点
summary: 32-bit 浮点录音能救回削波，但救不回被风吞掉的对白；麦克风和位置还是第一位。
slug: field-recorder
aliases:
- field-recorder
canonical_site: tools
canonical_path: /article/field-recorder/
status: published
diagram: /images/diagrams/zh/field-recorder.svg
diagram_alt: 录音机：32-bit 浮点的结构示意图。
diagram_caption: 看“录一段小声对白，峰值开到 -12 d…”和“故意削波一次，回放看 32-bit …”两处，判断这个参数能不能对应到一个具体的拍摄问题。
difficulty: beginner
stage: field-note
format: handbook
authors:
- TVCN 工具组
last_verified: '2026-11-25'
review_due: '2027-05-25'
related:
- tools.capability.lav-system.en
- tools.capability.headphone-monitor.en
- tools.capability.shotgun-mic.en
source_kind: experience
---

<p>单机直接进相机且声音可控时，独立录音机是额外同步步骤；先解决麦距和相机话放。不要用设备数量掩盖监听缺失。</p>
<!-- DIAGRAM_START -->
<h2>图解</h2>
<figure>
  <img src="/images/diagrams/zh/field-recorder.svg" alt="录音机：32-bit 浮点的结构示意图。">
  <figcaption>看“录一段小声对白，峰值开到 -12 d…”和“故意削波一次，回放看 32-bit …”两处，判断这个参数能不能对应到一个具体的拍摄问题。</figcaption>
</figure>
<!-- DIAGRAM_END -->
<section><h2 id="section-1">选型先看什么</h2><ul><li><strong>通道与话放：</strong>确认需要几路独立输入、幻象电源和增益范围；话放底噪比 32-bit 标称更重要。</li><li><strong>32-bit 的边界：</strong>它能救爆点，救不了没戴麦、没按录制或风灌咪头；仍要看电平和监听。</li><li><strong>媒体与供电：</strong>卡型、双卡备份、电池续航和外接电源；现场换卡不能停录。</li></ul><h2 id="section-2">什么时候不要用</h2></section><section><h2 id="section-3">现场</h2><p>录一段小声对白，峰值开到 -12 dB；再故意削波一次，回放看 32-bit 能否救回。</p></section><section><h2 id="section-4">怎么做</h2><ol><li>录一段小声对白，峰值开到 -12 dB。</li><li>故意削波一次，回放看 32-bit 能否救回。</li><li>再试风噪，确认它救不回风。别把浮点当保险。</li></ol></section><section><h2 id="section-5">别踩</h2><p>别把 32-bit 当万能保险；风噪和位置错误，它一样救不回来。</p></section>
<h2>验收</h2><ul><li>小声对白峰值在 -12 dB 左右，底噪可听。</li><li>故意削波后 32-bit 能恢复可懂度。</li><li>风噪测试证明浮点救不回被风吞掉的对白。</li></ul>
