---
id: tools.capability.cfexpress
site: tools
type: tool
lang: zh
translation_key: tools.capability.cfexpress
translation_status: source
title: CFexpress 卡：速度与发热
summary: CFexpress 卡先看持续写入和发热，不看峰值；拍长条时，热降速比容量更致命。
slug: cfexpress
aliases:
- cfexpress
canonical_site: tools
canonical_path: /article/cfexpress/
status: published
diagram: /images/diagrams/zh/cfexpress.svg
diagram_alt: CFexpress 卡：速度与发热的结构示意图。
diagram_caption: 看“录 10 分钟最高码率，摸卡温度”和“拷到 SSD，测持续写入是否掉速”两处，判断这个参数能不能对应到一个具体的拍摄问题。
difficulty: beginner
stage: field-note
format: handbook
authors:
- TVCN 工具组
last_verified: '2026-11-26'
review_due: '2027-05-26'
related: [tools.capability.cine-camera, tools.capability.cloud-render, shoot.camera.composition]
source_kind: experience
---
<p>只拍低码率照片或短视频时，不必为最高规格付钱。卡的速度超过机身写入上限，多出的钱不会变成画质。</p>
<!-- DIAGRAM_START -->
<h2>图解</h2>
<figure>
  <img src="/images/diagrams/zh/cfexpress.svg" alt="CFexpress 卡：速度与发热的结构示意图。">
  <figcaption>看“录 10 分钟最高码率，摸卡温度”和“拷到 SSD，测持续写入是否掉速”两处，判断这个参数能不能对应到一个具体的拍摄问题。</figcaption>
</figure>
<!-- DIAGRAM_END -->
<section><h2 id="section-1">选型先看什么</h2><ul><li><strong>持续写入：</strong>看持续写入，不看峰值；高码率录制几分钟后掉速的卡，会在长镜头中途停。</li><li><strong>发热：</strong>卡和读卡器都会热；连续拷卡时降速或掉盘，说明散热不够。</li><li><strong>容量与备份：</strong>按一天拍摄量和双卡备份算，不要按“能录多久”的广告数字算。</li></ul></section><section><h2 id="section-3">现场</h2><p>录 10 分钟最高码率，摸卡温度；再拷贝到 SSD，测持续写入是否掉速。</p></section><section><h2 id="section-4">怎么做</h2><ol><li>录 10 分钟最高码率，摸卡温度。</li><li>拷到 SSD，测持续写入是否掉速。</li><li>掉速就换卡或降码率。</li></ol></section><section><h2 id="section-5">别踩</h2><p>别只看峰值写入；十分钟后热降速，长条就会断。</p></section>
<h2>验收</h2><ul><li>最高码率连录 10 分钟没有中断，卡温有记录。</li><li>拷到 SSD 的持续写入曲线没有明显掉速。</li><li>掉速时有换卡或降码率的处理方案。</li></ul>

<!-- SOURCES_START -->
## 经验说明

经验说明：本页来自 3 次器材试用与现场回放，条件为页面所列型号/固件、室内外各一次；只讨论「CFexpress 卡：速度与发热」的选型与使用边界，不含外部实验室测试；不适用于未列型号、个体品控、保修/租赁合同与安全认证。
<!-- SOURCES_END -->

