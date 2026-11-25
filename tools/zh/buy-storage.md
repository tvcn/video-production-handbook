---
id: tools.guide.buy-storage
site: tools
type: article
lang: zh
translation_key: tools.guide.buy-storage
translation_status: source
title: 购买项目存储：速度、容量与备份
summary: 存储不是“越大越好”，是“拍摄不断、拷回不丢、项目结束还能找得到”。先算一个项目日的真实数据量，再买盘。
slug: buy-storage
aliases:
- buy-storage
canonical_site: tools
canonical_path: /article/buy-storage/
status: published
diagram: /images/diagrams/zh/buy-storage.svg
diagram_alt: 购买项目存储专题图解
diagram_caption: 示意：持续写入、容量、接口、散热、保修，五项决定拍摄日会不会停机。
difficulty: intermediate
stage: handbook
format: guide
authors:
- TVCN 工具组
last_verified: 2026-11-23
review_due: 2027-11-22
sources:
- S23
- S25
- S26
- S29
- S38
test_context: 复核环境：Windows 11 工作站 + iPhone 13，Chrome 131；机身/镜头按公开规格与短时样片核对，不做实验室仪器测量。
known_failures: 已知失败：低价渠道固件/保修不一致；样片不能代表量产；页内价格与库存会过期。
verified: 2026-11-23
related:
- tools.guide.buy-storage-cards.en
- tools.guide.buy-nas-raid.en
- tools.capability.ssd-raid.en
source_kind: experience
---

<!-- DIAGRAM_START -->
<h2>图解</h2>
<figure>
  <img src="/images/diagrams/zh/buy-storage.svg" alt="购买项目存储专题图解">
  <figcaption>示意：持续写入、容量、接口、散热、保修，五项决定拍摄日会不会停机。</figcaption>
</figure>
<!-- DIAGRAM_END -->
<h2>先判断：你缺的是哪一环</h2><p>先算一个项目日：相机码率 × 小时 × 机位数 × 备份份数。4K 10-bit 422 约 100–200 GB/小时，三机位一天 8 小时就是 2.4–4.8 TB，再加两份备份。买盘时不要按“今年够用”，按“最坏一天”算。</p><p><strong>适合：</strong></p><ul><li>多机位/高码率项目</li><li>需要现场拷回与备份</li><li>长期项目归档</li></ul><p><strong>不适合：</strong></p><ul><li>单机位 1080p 轻量项目</li><li>只买一块盘存所有</li><li>把 NAS 当现场盘</li></ul><h2>测试口径：可复现，不写假跑分</h2><p>用项目真实码率录满 30 分钟，或拷一个 100GB 大文件，记录实际写入速度与掉速。不要看接口标称；USB-C 不等于雷雳，机械盘也跑不满 10GbE。</p><div class="table-scroll"><table class="data-table"><thead><tr><th>检查项</th><th>通过线</th><th>参考/记录</th></tr></thead><tbody><tr><td>持续写入</td><td>项目码率 2 倍以上，30 分钟不降</td><td>满盘/大文件</td></tr><tr><td>容量</td><td>最坏拍摄日 2 份仍有余量</td><td>项目日计算</td></tr><tr><td>接口</td><td>实际拷贝速度达标</td><td>100GB 计时</td></tr><tr><td>散热</td><td>连续工作不烫手/不降速</td><td>30 分钟</td></tr><tr><td>保修</td><td>3–5 年，可换盘/可恢复</td><td>发票/序列</td></tr></tbody></table></div><h2>价格带：先看总拥有成本</h2><p>不只看标价，还要看卡、电池、转接、云台、灯架、软件订阅和维修。以下按“能完成一类真实项目”的最低配置分档，不是入门玩具价。</p><div class="table-scroll"><table class="data-table"><thead><tr><th>档位</th><th>参考价</th><th>包含</th><th>注意</th></tr></thead><tbody><tr><td>入门</td><td>1,000–3,000</td><td>2–4TB 便携 SSD + 备份盘</td><td>容量与持续写入有限</td></tr><tr><td>主力</td><td>3,000–8,000</td><td>4–8TB 高速 SSD + 双备份</td><td>接口与散热</td></tr><tr><td>进阶</td><td>8,000–25,000</td><td>NAS/阵列 + 10GbE + 异地备份</td><td>运维与电费</td></tr></tbody></table></div><p>价格为 2026 年 11 月中国大陆渠道参考，含税与否以实际报价为准；不构成购买建议。</p><h2>替代与升级：别在错误的轴上加钱</h2><ul><li>买两块普通 SSD 做双备份</li><li>租现场 DIT</li><li>先用现有盘 + 云备份</li></ul><h2>购买执行：带片子去，不带参数去</h2><p>下单前按顺序做一遍；任何一步失败，都不要用“后期能修”说服自己。</p><ol><li>算最坏拍摄日数据量</li><li>用项目码率录 30 分钟</li><li>拷 100GB 计时</li><li>确认接口与供电</li><li>查保修与数据恢复</li></ol><h2>验收</h2><ul><li>最坏一天两份仍有余量。</li><li>持续写入达码率 2 倍。</li><li>拷贝速度实测达标。</li><li>连续 30 分钟不降速。</li><li>至少两份异地/异盘。</li><li>保修与恢复方案可查。</li></ul>
<h2>决策树：工作盘、备份、归档分开</h2>
<p>大多数人把“存储”当成一个盘，结果是工作盘坏了没有备份，归档盘又太慢。先分三层：工作盘要快，备份要独立，归档要能读十年。</p><ol><li>工作盘：SSD/RAID 0，容量覆盖当前项目，速度≥项目码率 2 倍。</li><li>备份：独立机械盘/NAS，至少一份离线。</li><li>归档：LTO 或冷备盘，能校验、能恢复。</li><li>每层都写清命名、校验和保留周期。</li></ol>
<h2>八项对比：容量、速度、冗余不能同时最优</h2>
<div class="table-scroll"><table class="data-table"><thead><tr><th>对比项</th><th>通过线</th><th>适用</th><th>不适用</th></tr></thead><tbody><tr><td>工作盘</td><td>持续写入≥项目码率 2 倍</td><td>剪辑</td><td>长期归档</td></tr><tr><td>RAID 0</td><td>双盘速度够，另有备份</td><td>工作盘</td><td>唯一副本</td></tr><tr><td>RAID 1/5</td><td>单盘故障可重建</td><td>团队共享</td><td>极高写入</td></tr><tr><td>NAS</td><td>10GbE 可达 500MB/s</td><td>多人协作</td><td>单人移动</td></tr><tr><td>移动硬盘</td><td>USB 10Gbps 稳定</td><td>现场备份</td><td>长期冷备</td></tr><tr><td>LTO</td><td>离线、可校验、寿命长</td><td>归档</td><td>频繁读取</td></tr><tr><td>云</td><td>恢复时间可接受</td><td>异地备份</td><td>大项目日剪</td></tr><tr><td>总成本</td><td>工作+备份+归档+恢复演练</td><td>任何项目</td><td>只看每 TB 单价</td></tr></tbody></table></div>
<h2>测试口径：持续写入和恢复演练</h2>
<p>连续写 30 分钟，记录速度、温度、掉盘；随机抽一个文件从备份恢复，记录耗时；核对 checksum。没有做的：实验室 IOPS、长期老化测试。</p>
<h2>继续读：存储与备份中枢</h2>
<p>先读卡，再读阵列和备份。</p><ul><li><a href="/article/buy-storage-cards/">购买存储卡：VPG、持续写入与发热</a></li><li><a href="/article/buy-nas-raid/">购买 NAS/RAID：吞吐、重建与噪声</a></li><li><a href="/article/ssd-raid/">SSD RAID：剪辑阵列</a></li><li><a href="/article/backup-3-2-1/">3-2-1 备份：当天做完</a></li><li><a href="/article/restore-test/">恢复演练：随机抽一个文件</a></li><li><a href="/article/storage/">素材管理：当天备份，命名可查</a></li><li><a href="/article/set-mediabay/">素材车：现场拷卡与命名</a></li><li><a href="/article/lto-archive/">LTO 归档：长期冷备</a></li><li><a href="/article/export-prores/">ProRes 导出：归档与交付</a></li><li><a href="/article/proxy-create/">代理生成：剪辑不卡</a></li></ul>
<h2>核验与价格日期</h2>
<p>核验日期：2026-11-23。价格为中国大陆渠道参考；持续写入与恢复时间是本机短测，不是实验室跑分。</p>
<!-- P5_EXTRA_START -->
<h2>购买顺序：先租再买</h2>
<p>先借一块卡/SSD 跑一次真实项目，记录持续写入和拷卡时间；再决定容量和冗余。</p><ol><li>先租一次目标机身和常用镜头，拍一条真实项目。</li><li>确认卡口、转接、自动对焦和供电。</li><li>把卡、电、监看、存储、维修算进总价。</li><li>留 10% 预算给意外和耗材。</li><li>第二支镜头等第一条片子交付后再买。</li></ol>
<h2>补：失败案例</h2>
<p>存储最常见的错误，是拿 RAID 0 当唯一副本。</p><div class="table-scroll"><table class="data-table"><thead><tr><th>失败做法</th><th>后果</th><th>替换动作</th></tr></thead><tbody><tr><td>RAID 0 存唯一素材</td><td>一块盘坏，全项目丢失</td><td>独立备份</td></tr><tr><td>只测峰值速度</td><td>持续写入掉速，剪辑卡</td><td>30 分钟持续写</td></tr><tr><td>用 USB 集线器</td><td>带宽共享，速度腰斩</td><td>直连主机</td></tr></tbody></table></div>
<!-- P5_EXTRA2_START -->
<h2>补：购买前检查表</h2>
<p>存储在项目当天才暴露问题；买之前先做一次恢复演练。</p><div class="table-scroll"><table class="data-table"><thead><tr><th>检查</th><th>通过线</th><th>记录</th></tr></thead><tbody><tr><td>持续写入</td><td>30 分钟不低于项目码率 2 倍</td><td>测速截图</td></tr><tr><td>备份</td><td>至少一份独立副本</td><td>备份清单</td></tr><tr><td>恢复</td><td>随机文件能恢复</td><td>恢复计时</td></tr><tr><td>校验</td><td>checksum 一致</td><td>校验工具</td></tr></tbody></table></div>
<!-- P5_EXTRA3_START -->
<h2>现场一句话</h2>
<p>工作盘可以坏，备份不能一起坏；这就是三层存储的全部意义。</p>
<!-- SOURCES_START -->
<h2>参考与延伸阅读</h2>
<p class="source-types">经验来源：编辑部现场手册与购买检查表；实测来源：短测与公开规格核对，不是实验室跑分；参考来源：以下厂商与标准链接。</p>
<ul><li><span class="mono">[S23]</span> SMPTE 标准入口</li><li><span class="mono">[S25]</span> ITU-R BT.709</li><li><span class="mono">[S26]</span> ITU-R BT.2020</li><li><span class="mono">[S29]</span> YouTube 上传规格</li><li><span class="mono">[S38]</span> 国家税务总局</li></ul>
<p><a href="../../about/">完整链接与用途见 SOURCES.md</a></p>
<!-- SOURCES_END -->
