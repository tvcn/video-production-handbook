---
id: post.sound.loudness
site: post
type: article
lang: zh
translation_key: post.sound.loudness
translation_status: source
title: 响度：平台目标与真峰值
summary: 响度按平台目标交付，真峰值留余量；声音大不等于声音好。
slug: loudness
aliases:
- loudness
canonical_site: post
canonical_path: /article/loudness/
status: published
diagram: /images/diagrams/zh/loudness.svg
diagram_alt: 响度：平台目标与真峰值的结构示意图。
diagram_caption: 看“先混到平台目标，常用 -14 LUF…”和“真峰值压到 -1 dB，再留 0.5…”两处，判断剪掉一个镜头后，节奏是更快还是更乱。
difficulty: beginner
stage: field-note
format: handbook
authors:
- TVCN 后期组
last_verified: '2026-11-25'
review_due: '2027-05-25'
related:
- post.delivery.platform-deliverables.en
- shoot.virtual-production.led-virtual-production.en
- story.screenplay.three-act.en
depth: deep
deep_minutes: 5
sources:
- S24
- S27
- S28
- S30
- S34
- S35
test_context: 复核环境：Windows 11（RTX 3060）+ macOS 14（M1）；DaVinci Resolve 20 与 Premiere
  Pro 2025 复跑；不声称每台机器结果一致。
known_failures: 已知失败：旧版软件时间线不兼容；不同相机 Log 需重新映射；代理丢失时需回套原片。
verified: 2026-11-22
source_kind: sourced
---

<p>先让对白在正常监听下清楚，再把整体响度对到平台目标；不要用拉总音量救对白。导出前看真峰值，给编码留 1–2 dB 余量，避免平台二次压缩削顶。</p>
<!-- DIAGRAM_START -->
<h2>图解</h2>
<figure>
  <img src="/images/diagrams/zh/loudness.svg" alt="响度：平台目标与真峰值的结构示意图。">
  <figcaption>看“先混到平台目标，常用 -14 LUF…”和“真峰值压到 -1 dB，再留 0.5…”两处，判断剪掉一个镜头后，节奏是更快还是更乱。</figcaption>
</figure>
<!-- DIAGRAM_END -->
<section><h2 id="section-1">对白优先，响度按平台，真峰值留余量</h2><p>不同平台目标不同，交付前查当前规格；同一母版投多个平台时，分别导出版本，不要一版通投。</p><h2 id="section-2">边界</h2><p>响度不是越响越好。把音乐拉满、对白靠字幕，短期刺激，长期没人愿意听完。对白听不清时，先回混音，不要只加总增益。</p></section><section><h2 id="section-3">现场</h2><p>平台常用 -14 LUFS、真峰值 -1 dB；先混到目标，再留 0.5 到 1 dB 余量，别靠压限器硬顶。</p></section><section><h2 id="section-4">怎么做</h2><ol><li>先混到平台目标，常用 -14 LUFS。</li><li>真峰值压到 -1 dB，再留 0.5 到 1 dB 余量。</li><li>不要靠压限器硬顶，回到对白和动态检查。</li></ol></section><section><h2 id="section-5">别踩</h2><p>别把响度当竞争力；压限器压扁了，对白会更累。</p></section><section><h2>判断</h2><p>现场只认三个信号：</p><ul><li>剪掉一个镜头，节奏更快而不是更乱</li><li>示波器上肤色、高光和黑位都在范围内</li><li>响度、字幕和文件规格能过一次交付检查</li></ul></section><section><h2>失败</h2><p>下面三种做法会让页面上的细节白做：</p><ul><li>剪辑点跟着音乐，不跟动作</li><li>先定风格再统一，镜头之间跳色</li><li>交付前没查响度和字幕，最后一遍才发现</li></ul></section><section><h2>延伸</h2><p><strong>10 分钟练习：</strong>拿一段 30 秒素材做 A/B，只改“先混到平台目标，常用 -14 LUF…”；记下一个时间码和一处差异，再决定是否保留。</p></section>
<h2>验收</h2><ul><li>整片积分响度落在平台目标附近，不是凭耳朵猜。</li><li>真峰值不超过 -1 dB，没有连续红区。</li><li>对白仍然清楚，音乐和环境没有把动态压死。</li></ul>

<!-- DEEP_DIVE_START -->
## 深读
<p><strong>约 5 分钟。</strong> 响度不是把音量拧大，而是让对白在平台、耳机和外放上都站得住。</p>
### LUFS 不是音量旋钮
<p>LUFS 是整条片的平均响度，不是某一秒的音量。平台常用 -14 到 -16 LUFS，真峰值控制在 -1 dB 左右；具体以平台最新说明为准。</p><p>先让对白站住，再加音乐和环境。音乐一进来就把对白推高，最后整条片会又吵又听不清。</p>
### 检查顺序
<p>先 solo 对白听一遍，加音乐听一遍，加环境再听一遍；然后手机外放、耳机、笔记本各播一次。响度表只告诉你数字，听不懂的句子还是要回剪。</p><p>把最安静的一句和对最吵的一句各记一个时间码，交付前直接跳过去听。两个极端都成立，中间通常不会太差。</p>
### 手机外放是最终考场
<p>把片子放到手机上，音量开到一半，走到两米外听。听不清的句子，不是观众的问题，是混音的问题。</p><p>手机外放会砍掉低频，音乐里的低频越多，对白越糊。先保中频，再谈氛围。</p>
### 音乐和环境声的比例
<p>对白场里，音乐只做底，环境声填房间；没有对白的段落，音乐才可以走到前面。不要用音乐从头铺到尾，观众会累。</p><p>每加一层声音， Solo 一次对白，确认它还站得住。站不住就降新加的那层，不要推对白。</p>
### 交付前，用这十步听一遍
<ul><li>先 solo 对白，确认每句都能听懂</li><li>加音乐再听一遍</li><li>加环境再听一遍</li><li>手机外放，音量一半，站到两米外</li><li>耳机听一遍，注意齿音和爆音</li><li>笔记本外放再听一遍</li><li>记下最安静那句的时间码</li><li>记下最吵那句的时间码</li><li>交付前直接跳到这两个点复查</li><li>确认真峰值没有超过负一</li></ul><p>响度表只能证明数字对，不能证明观众听懂。最后一遍一定要用耳朵，不是眼睛。最后让一个没看过片子的人听一遍，问他哪一句没听清，那通常就是你要修的地方。</p>
<!-- DEEP_DIVE_END -->
<!-- SOURCES_START -->
