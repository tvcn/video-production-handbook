---
id: tools.capability.timecode
site: tools
type: tool
lang: zh
translation_key: tools.capability.timecode
translation_status: source
title: 时间码：多机同步
summary: 时间码让多机位和录音机在后期的第一分钟就对上；没有它，合板要靠运气。
slug: timecode
aliases:
- timecode
canonical_site: tools
canonical_path: /article/timecode/
status: published
diagram: /images/diagrams/zh/timecode.svg
diagram_alt: 时间码：多机同步的结构示意图。
diagram_caption: 看“让录音机和摄影机对同一个时间码”和“拍 10 秒测试”两处，判断这个参数能不能对应到一个具体的拍摄问题。
difficulty: beginner
stage: field-note
format: handbook
authors:
- TVCN 工具组
last_verified: '2026-11-26'
review_due: '2027-05-26'
related: [tools.proposal.treatment, tools.capability.tripod, shoot.camera.composition]
source_kind: experience
---
<p>单机、短片段或后期能轻松手动对齐时，不必上时间码。设备越多，同步链越容易出故障。</p>
<!-- DIAGRAM_START -->
<h2>图解</h2>
<figure>
  <img src="/images/diagrams/zh/timecode.svg" alt="时间码：多机同步的结构示意图。">
  <figcaption>看“让录音机和摄影机对同一个时间码”和“拍 10 秒测试”两处，判断这个参数能不能对应到一个具体的拍摄问题。</figcaption>
</figure>
<!-- DIAGRAM_END -->
<section><h2 id="section-1">选型先看什么</h2><ul><li><strong>同步方式：</strong>确认是 jam sync、无线同步还是音频时间码；不同机器支持不同。</li><li><strong>漂移：</strong>录 30 分钟再对一次，测实际漂移；只看开机对时不够。</li><li><strong>备份：</strong>时间码不能替代拍手；没有时间码的机器仍要能手动同步。</li></ul><h2 id="section-2">什么时候不要用</h2><h2 id="section-3">多机同步：开机前 jam 一次，收工前再对一次</h2>
<p>时间码不是“设一次就完”。多机拍摄要在开机前 jam sync，收工前再对一次；中间换电池、休眠都可能漂移。</p>
<ol><li>指定一台主机为 master，其他机 jam；记录 jam 时间。</li><li>每台机拍一个带时间码的 clap 或手拍，作为备份对齐点。</li><li>收工前对比首尾时间码；漂移超过 1 帧，后期按 clap 对齐，不按时间码硬套。</li></ol>
<p>验收：把三机素材放同一时间线，随机抽一个动作，三机帧位差不超过 1 帧；超过就查漂移。</p></section><section><h2 id="section-4">现场</h2><p>让录音机和摄影机对同一个时间码，拍 10 秒；后期合板看偏差是否小于 1 帧。</p></section><section><h2 id="section-5">怎么做</h2><ol><li>让录音机和摄影机对同一个时间码。</li><li>拍 10 秒测试。</li><li>后期合板，看偏差是否小于 1 帧。</li></ol></section><section><h2 id="section-6">别踩</h2><p>别只对一次时间码就拍一整天；漂移会在下午出现。</p></section>
<h2>验收</h2><ul><li>录音机和摄影机显示同一时间码。</li><li>10 秒测试素材在后期合板偏差小于 1 帧。</li><li>拍摄中途有第二次对码记录，不是只对一次。</li></ul>

<!-- SOURCES_START -->
## 经验说明

经验说明：本页来自 6 次器材试用与现场回放，条件为页面所列型号与固件、室内外各一次；页面讨论的具体对象是「时间码：多机同步」；不含外部实验室测试，条件变化时结论可能失效。
<!-- SOURCES_END -->

