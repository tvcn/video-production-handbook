---
id: tools.guide.buy-storage
site: tools
type: article
lang: zh
translation_key: tools.guide.buy-storage
translation_status: source
title: "购买项目存储：速度、容量与备份"
summary: "存储不是“越大越好”，是“拍摄不断、拷回不丢、项目结束还能找得到”。先算一个项目日的真实数据量，再买盘。"
slug: buy-storage
aliases: [buy-storage]
canonical_site: tools
canonical_path: /guide/buy-storage/
status: published
diagram: /images/diagrams/zh/buy-storage.svg
diagram_alt: "购买项目存储专题图解"
diagram_caption: "示意：持续写入、容量、接口、散热、保修，五项决定拍摄日会不会停机。"
difficulty: intermediate
stage: handbook
format: guide
authors: ["TVCN 工具组"]
last_verified: 2026-11-22
review_due: 2027-11-22
sources: [S23, S25, S26, S29, S38]
test_context: "复核环境：Windows 11 工作站 + iPhone 13，Chrome 131；机身/镜头按公开规格与短时样片核对，不做实验室仪器测量。"
known_failures: "已知失败：低价渠道固件/保修不一致；样片不能代表量产；页内价格与库存会过期。"
verified: 2026-11-22
---

<!-- DIAGRAM_START -->
<h2>图解</h2>
<figure>
  <img src="/images/diagrams/zh/buy-storage.svg" alt="购买项目存储专题图解">
  <figcaption>示意：持续写入、容量、接口、散热、保修，五项决定拍摄日会不会停机。</figcaption>
</figure>
<!-- DIAGRAM_END -->
<h2>先判断：你缺的是哪一环</h2><p>先算一个项目日：相机码率 × 小时 × 机位数 × 备份份数。4K 10-bit 422 约 100–200 GB/小时，三机位一天 8 小时就是 2.4–4.8 TB，再加两份备份。买盘时不要按“今年够用”，按“最坏一天”算。</p><p><strong>适合：</strong></p><ul><li>多机位/高码率项目</li><li>需要现场拷回与备份</li><li>长期项目归档</li></ul><p><strong>不适合：</strong></p><ul><li>单机位 1080p 轻量项目</li><li>只买一块盘存所有</li><li>把 NAS 当现场盘</li></ul><h2>测试口径：可复现，不写假跑分</h2><p>用项目真实码率录满 30 分钟，或拷一个 100GB 大文件，记录实际写入速度与掉速。不要看接口标称；USB-C 不等于雷雳，机械盘也跑不满 10GbE。</p><div class="table-scroll"><table class="data-table"><thead><tr><th>检查项</th><th>通过线</th><th>参考/记录</th></tr></thead><tbody><tr><td>持续写入</td><td>项目码率 2 倍以上，30 分钟不降</td><td>满盘/大文件</td></tr><tr><td>容量</td><td>最坏拍摄日 2 份仍有余量</td><td>项目日计算</td></tr><tr><td>接口</td><td>实际拷贝速度达标</td><td>100GB 计时</td></tr><tr><td>散热</td><td>连续工作不烫手/不降速</td><td>30 分钟</td></tr><tr><td>保修</td><td>3–5 年，可换盘/可恢复</td><td>发票/序列</td></tr></tbody></table></div><h2>价格带：先看总拥有成本</h2><p>不只看标价，还要看卡、电池、转接、云台、灯架、软件订阅和维修。以下按“能完成一类真实项目”的最低配置分档，不是入门玩具价。</p><div class="table-scroll"><table class="data-table"><thead><tr><th>档位</th><th>参考价</th><th>包含</th><th>注意</th></tr></thead><tbody><tr><td>入门</td><td>1,000–3,000</td><td>2–4TB 便携 SSD + 备份盘</td><td>容量与持续写入有限</td></tr><tr><td>主力</td><td>3,000–8,000</td><td>4–8TB 高速 SSD + 双备份</td><td>接口与散热</td></tr><tr><td>进阶</td><td>8,000–25,000</td><td>NAS/阵列 + 10GbE + 异地备份</td><td>运维与电费</td></tr></tbody></table></div><p>价格为 2026 年 11 月中国大陆渠道参考，含税与否以实际报价为准；不构成购买建议。</p><h2>替代与升级：别在错误的轴上加钱</h2><ul><li>买两块普通 SSD 做双备份</li><li>租现场 DIT</li><li>先用现有盘 + 云备份</li></ul><h2>购买执行：带片子去，不带参数去</h2><p>下单前按顺序做一遍；任何一步失败，都不要用“后期能修”说服自己。</p><ol><li>算最坏拍摄日数据量</li><li>用项目码率录 30 分钟</li><li>拷 100GB 计时</li><li>确认接口与供电</li><li>查保修与数据恢复</li></ol><h2>验收</h2><ul><li>最坏一天两份仍有余量。</li><li>持续写入达码率 2 倍。</li><li>拷贝速度实测达标。</li><li>连续 30 分钟不降速。</li><li>至少两份异地/异盘。</li><li>保修与恢复方案可查。</li></ul>
<!-- SOURCES_START -->
<h2>参考与延伸阅读</h2>
<p class="source-types">经验来源：编辑部现场手册与购买检查表；实测来源：短测与公开规格核对，不是实验室跑分；参考来源：以下厂商与标准链接。</p>
<ul><li><span class="mono">[S23]</span> SMPTE 标准入口</li><li><span class="mono">[S25]</span> ITU-R BT.709</li><li><span class="mono">[S26]</span> ITU-R BT.2020</li><li><span class="mono">[S29]</span> YouTube 上传规格</li><li><span class="mono">[S38]</span> 国家税务总局</li></ul>
<p><a href="../../SOURCES.md">完整链接与用途见 SOURCES.md</a></p>
<!-- SOURCES_END -->
