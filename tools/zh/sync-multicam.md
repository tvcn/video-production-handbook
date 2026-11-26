---
id: tools.tutorial.sync-multicam
site: tools
type: article
lang: zh
translation_key: tools.tutorial.sync-multicam
translation_status: source
title: 多机位同步：时间码与手动
summary: 多机位同步先对时间码，再用拍手兜底；两样都做，剪辑才敢切。
slug: sync-multicam
aliases:
- sync-multicam
canonical_site: tools
canonical_path: /article/sync-multicam/
status: published
diagram: /images/diagrams/zh/sync-multicam.svg
diagram_alt: 多机位同步：时间码与手动的结构示意图。
diagram_caption: 看“时间码同步后，再拍手一次”和“剪辑里建多机位片段”两处，判断这个参数能不能对应到一个具体的拍摄问题。
difficulty: beginner
stage: field-note
format: handbook
authors:
- TVCN 工具组
last_verified: '2026-11-26'
review_due: '2027-05-26'
related: [tools.test.test-protocols, tools.capability.timecode, shoot.camera.composition]
source_kind: experience
---
<p>没有时间码时，用一声拍手、一句台词或闪光作为共同事件。每台机器都拍到，剪辑时按波形对齐；不要靠“看起来差不多”手动拖。</p>
<!-- DIAGRAM_START -->
<h2>图解</h2>
<figure>
  <img src="/images/diagrams/zh/sync-multicam.svg" alt="多机位同步：时间码与手动的结构示意图。">
  <figcaption>看“时间码同步后，再拍手一次”和“剪辑里建多机位片段”两处，判断这个参数能不能对应到一个具体的拍摄问题。</figcaption>
</figure>
<!-- DIAGRAM_END -->
<section><h2 id="section-1">多机位先给一个“共同事件”</h2><p>开机前统一帧率、快门和录音采样率；不同帧率的多机位，后期只能靠变速，会破坏声音同步。</p><h2 id="section-2">边界</h2><p>同步一次不等于全程同步。长时间拍摄会有漂移，每 20–30 分钟重新对一次，或使用时间码。</p><h2 id="section-3">多机同步：时间码优先，clap 兜底</h2>
<p>多机位最怕“看起来对齐、实际差 2 帧”。有时间码就 jam，没有就每台机拍一次 clap；后期先对齐波形，再微调帧。</p>
<ol><li>开机前统一帧率和时间码；不同帧率不要混在同一时间线。</li><li>每台机拍手拍 3 次，每次间隔 1 秒；后期用第一次拍手对齐。</li><li>对齐后随机抽一个动作，逐机检查；差 1 帧可以接受，差 2 帧以上要查漂移。</li></ol>
<p>验收：三机同时拍一个秒表，暂停在同一帧，三机读数一致；不一致，回到时间码或帧率。</p></section><section><h2 id="section-4">现场</h2><p>时间码同步后，再拍手一次；剪辑里建多机位片段，按机位图切换。</p></section><section><h2 id="section-5">怎么做</h2><ol><li>时间码同步后，再拍手一次。</li><li>剪辑里建多机位片段。</li><li>按机位图切换，不靠记忆。</li></ol></section><section><h2 id="section-6">别踩</h2><p>别只靠时间码；一台机没对码，整组多机位都偏。</p></section><section><h2>判断</h2><p>现场只认三个信号：</p><ul><li>每一项参数都能对应一个具体的拍摄问题</li><li>重量、供电和接口在真实机位上成立</li><li>60 秒测试能留下一个可比较的数字</li></ul></section><section><h2>失败</h2><p>下面三种做法会让页面上的细节白做：</p><ul><li>只看参数，不看接口、供电和重量</li><li>买回来才发现电池、存储或机身不匹配</li><li>没有 60 秒测试，问题被带到正式拍摄</li></ul></section><section><h2>延伸</h2><p><strong>10 分钟练习：</strong>用现有器材做 60 秒测试，只测“时间码同步后，再拍手一次”；记下两个数字：一个是你需要的，一个是器材实际给出的。</p></section>
<h2>验收</h2><ul><li>所有机位时间码同步，另有一次拍手兜底。</li><li>剪辑里建立了多机位片段，机位数量正确。</li><li>切换按机位图，能说清每个镜头来自哪台。</li></ul>

<!-- SOURCES_START -->
## 经验说明

经验说明：本页来自 5 次器材试用与现场回放，条件为页面所列型号与固件、室内外各一次；页面讨论的具体对象是「多机位同步：时间码与手动」；不含外部实验室测试，条件变化时结论可能失效。
<!-- SOURCES_END -->

