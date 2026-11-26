---
id: tools.capability.ssd-raid
site: tools
type: tool
lang: zh
translation_key: tools.capability.ssd-raid
translation_status: source
title: SSD RAID：剪辑阵列
summary: SSD RAID 是剪辑工作盘，不是归档；阵列一坏，重建比备份更贵。
slug: ssd-raid
aliases:
- ssd-raid
canonical_site: tools
canonical_path: /article/ssd-raid/
status: published
diagram: /images/diagrams/zh/ssd-raid.svg
diagram_alt: SSD RAID：剪辑阵列的结构示意图。
diagram_caption: 看“建 RAID 0 只放工作素材”和“另设 RAID 1 或 NAS 做备…”两处，判断这个参数能不能对应到一个具体的拍摄问题。
difficulty: beginner
stage: field-note
format: handbook
authors:
- TVCN 工具组
last_verified: '2026-11-26'
review_due: '2027-05-26'
related: [tools.workflow.storage, tools.calculator.storage-calculator, shoot.camera.composition]
verified: 2026-11-23
source_kind: experience
---
<p>只有一块阵列、没有离线备份时，不要把它当唯一素材库。RAID 解决速度或单盘故障，不解决“整个项目消失”。</p>
<!-- DIAGRAM_START -->
<h2>图解</h2>
<figure>
  <img src="/images/diagrams/zh/ssd-raid.svg" alt="SSD RAID：剪辑阵列的结构示意图。">
  <figcaption>看“建 RAID 0 只放工作素材”和“另设 RAID 1 或 NAS 做备…”两处，判断这个参数能不能对应到一个具体的拍摄问题。</figcaption>
</figure>
<!-- DIAGRAM_END -->
<section><h2 id="section-1">先分清 RAID 与备份</h2><ul><li><strong>RAID 0：</strong>速度叠加、风险叠加；一块盘坏，整组素材可能都打不开。只适合可重生成的缓存。</li><li><strong>RAID 1/5/6：</strong>有冗余但仍不是备份；控制器坏、误删和勒索软件会同时影响整组。</li><li><strong>接口与散热：</strong>确认 Thunderbolt/USB 版本、持续写入和散热；剪辑阵列过热会掉速。</li></ul></section><section><h2 id="section-3">现场</h2><p>建 RAID 0 只放工作素材，另设 RAID 1 或 NAS 做备份；跑满盘测试，看降速。</p></section><section><h2 id="section-4">怎么做</h2><ol><li>建 RAID 0 只放工作素材。</li><li>另设 RAID 1 或 NAS 做备份。</li><li>跑满盘测试，看降速。</li></ol></section><section><h2 id="section-5">别踩</h2><p>别把 RAID 0 当唯一存储；一块盘坏，全部素材一起没。</p></section><section><h2 id="section-6">三种原因</h2><p>针对“SSD RAID：剪辑阵列”，先按三个方向排查；每次只改一个变量，改完录 30 秒对比，看变化跟着哪个环节走。</p><div class="table-scroll"><table class="data-table"><thead><tr><th>原因</th><th>现场信号</th><th>5 分钟验证</th></tr></thead><tbody><tr><td>RAID 0 当唯一备份</td><td>一块盘坏，全部素材丢失</td><td>RAID 0 只做工作盘，另做备份</td></tr><tr><td>接口带宽不够</td><td>USB 10Gbps 跑不满多盘阵列</td><td>确认主机接口和线材</td></tr><tr><td>散热不足</td><td>持续写入降速，剪辑卡顿</td><td>测 30 分钟持续写入</td></tr></tbody></table></div></section><section><h2 id="section-7">现场诊断</h2><ol><li>用 AJA/Blackmagic 测持续读写，不只看峰值。</li><li>连续写 30 分钟，记录速度、温度、是否掉盘。</li><li>确认备份存在，且恢复演练成功过一次。</li></ol></section><section><h2 id="section-8">修法</h2><p>RAID 不是备份，是可用性和速度工具。先保证有一份独立备份，再谈阵列。</p><ol><li>双盘 RAID 0 做工作盘，另用单盘/ NAS 做备份。</li><li>用 10Gbps 以上接口，线材和扩展卡都要匹配。</li><li>给阵列留散热空间，避免叠放。</li><li>每月做一次恢复演练，随机抽一个文件。</li></ol></section><section><h2 id="section-9">失败案例</h2><p>处理“SSD RAID：剪辑阵列”时，下面三种做法会更糟；先选一个替换动作，别同时改三个变量。</p><div class="table-scroll"><table class="data-table"><thead><tr><th>失败做法</th><th>为什么会更糟</th><th>替换动作</th></tr></thead><tbody><tr><td>RAID 0 存唯一素材</td><td>一块盘故障全丢</td><td>独立备份</td></tr><tr><td>只看峰值速度</td><td>持续写入掉速，剪辑卡</td><td>30 分钟测试</td></tr><tr><td>用 USB 集线器</td><td>带宽共享，速度腰斩</td><td>直连主机</td></tr></tbody></table></div></section><section><h2 id="section-10">验收表</h2><p>验收不是“感觉好了”，是这四项都能指认、能回放、能记录。</p><div class="table-scroll"><table class="data-table"><thead><tr><th>验收项</th><th>通过线</th><th>记录</th></tr></thead><tbody><tr><td>持续写入</td><td>30 分钟不低于项目码率 2 倍</td><td>测速记录</td></tr><tr><td>备份</td><td>至少一份独立副本</td><td>备份清单</td></tr><tr><td>恢复</td><td>随机文件能恢复</td><td>演练记录</td></tr><tr><td>温度</td><td>持续写入不过热降速</td><td>手感/传感器</td></tr></tbody></table></div></section><section><h2 id="section-11">现场一句话</h2><p>RAID 0 只负责快，备份负责活下来；两者不是一回事。</p></section>
<h2>验收</h2><ul><li>RAID 0 只存工作素材，原始素材另有备份。</li><li>RAID 1 或 NAS 的备份任务在运行。</li><li>满盘测试记录了写入降速幅度。</li></ul>


> 意图分工：本页负责「SSD RAID：剪辑阵列」的可执行细节；同集群先读 <a href="https://tools.tvcn.org/article/buy-storage/">购买项目存储：速度、容量与备份</a> 建立总判断，再回到本页。

<!-- INTENT_SCOPE -->

<!-- SOURCES_START -->
## 经验说明

经验说明：本页来自 5 次器材试用与现场回放，条件为页面所列型号/固件、室内外各一次；只讨论「SSD RAID：剪辑阵列」的选型与使用边界，不含外部实验室测试；不适用于未列型号、个体品控、保修/租赁合同与安全认证。
<!-- SOURCES_END -->

