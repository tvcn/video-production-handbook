---
id: tools.capability.davinci-node
site: tools
type: tool
lang: zh
translation_key: tools.capability.davinci-node
translation_status: source
title: 达芬奇节点：节点不是滤镜
summary: 节点不是滤镜叠叠乐；每个节点只做一件事，关掉它就能看出它干了什么。
slug: davinci-node
aliases:
- davinci-node
canonical_site: tools
canonical_path: /article/davinci-node/
status: published
diagram: /images/diagrams/zh/davinci-node.svg
diagram_alt: 达芬奇节点：节点不是滤镜的结构示意图。
diagram_caption: 看“建 5 个节点：曝光、白平衡、对比、…”和“每个节点关掉看变化”两处，判断这个参数能不能对应到一个具体的拍摄问题。
difficulty: beginner
stage: field-note
format: handbook
authors:
- TVCN 工具组
last_verified: '2026-11-26'
review_due: '2027-05-26'
related: [tools.deep.deep-ai-toolchain, tools.deep.deep-backup-321, shoot.camera.composition]
source_kind: experience
---
<p>如果问题来自拍摄端的白平衡、曝光或灯光，节点越多只会越脏。先回素材，再谈调色。</p>
<!-- DIAGRAM_START -->
<h2>图解</h2>
<figure>
  <img src="/images/diagrams/zh/davinci-node.svg" alt="达芬奇节点：节点不是滤镜的结构示意图。">
  <figcaption>看“建 5 个节点：曝光、白平衡、对比、…”和“每个节点关掉看变化”两处，判断这个参数能不能对应到一个具体的拍摄问题。</figcaption>
</figure>
<!-- DIAGRAM_END -->
<section><h2 id="section-1">节点顺序的基本原则</h2><ul><li><strong>先平衡，再风格：</strong>一级校正在前，LUT 和风格化在后；顺序反了会把偏色锁进 LUT。</li><li><strong>局部在后：</strong>窗口、跟踪和局部调色放在全局之后；先做局部会破坏整体关系。</li><li><strong>缓存与版本：</strong>节点越多越吃性能；给关键版本命名，不要只靠撤销。</li></ul><h2 id="section-2">什么时候不要用节点堆效果</h2></section><section><h2 id="section-3">现场</h2><p>建 5 个节点：曝光、白平衡、对比、风格、输出；每个节点关掉看变化，别叠 20 个。</p></section><section><h2 id="section-4">怎么做</h2><ol><li>建 5 个节点：曝光、白平衡、对比、风格、输出。</li><li>每个节点关掉看变化。</li><li>别叠 20 个，找不到问题来自哪。</li></ol></section><section><h2 id="section-5">别踩</h2><p>别叠二十个节点；出问题时，你不知道该关哪一个。</p></section>
<h2>验收</h2><ul><li>五个节点各自只做一件事，命名清楚。</li><li>逐个关闭时能看到对应变化。</li><li>没有超过十个节点，问题能定位到单个节点。</li></ul>


> 意图分工：本页负责「达芬奇节点：节点不是滤镜」的可执行细节；同集群先读 <a href="https://post.tvcn.org/article/lut/">LUT：起点不是终点</a> 建立总判断，再回到本页。

<!-- INTENT_SCOPE -->

<!-- SOURCES_START -->
## 经验说明

经验说明：本页来自 5 次器材试用与现场回放，条件为页面所列型号与固件、室内外各一次；页面讨论的具体对象是「达芬奇节点：节点不是滤镜」；不含外部实验室测试，条件变化时结论可能失效。
<!-- SOURCES_END -->

