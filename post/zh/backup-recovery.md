---
id: post.assets.backup-recovery
site: post
type: article
lang: zh
translation_key: post.assets.backup-recovery
translation_status: source
title: 备份恢复：演一次恢复
summary: 备份不是复制完就算，随机抽一个文件恢复一次，才算验证。
slug: backup-recovery
aliases:
- backup-recovery
canonical_site: post
canonical_path: /article/backup-recovery/
status: published
diagram: /images/diagrams/zh/backup-recovery.svg
diagram_alt: 备份恢复：演一次恢复的结构示意图。
diagram_caption: 看“按 3-2-1：三份、两种介质、一份…”和“随机抽一个文件恢复到另一台机器”两处，判断剪掉一个镜头后，节奏是更快还是更乱。
difficulty: beginner
stage: field-note
format: handbook
authors:
- TVCN 后期组
last_verified: '2026-11-25'
review_due: '2027-05-25'
related:
- post.delivery.archive.en
- post.assets.proxy-cache.en
- post.assets.project-structure.en
source_kind: experience
---

<p>别只复制不恢复；坏盘不会提前通知你。</p>
<!-- DIAGRAM_START -->
<h2>图解</h2>
<figure>
  <img src="/images/diagrams/zh/backup-recovery.svg" alt="备份恢复：演一次恢复的结构示意图。">
  <figcaption>看“按 3-2-1：三份、两种介质、一份…”和“随机抽一个文件恢复到另一台机器”两处，判断剪掉一个镜头后，节奏是更快还是更乱。</figcaption>
</figure>
<!-- DIAGRAM_END -->
<section><h2 id="section-1">现场</h2><p>3-2-1：三份、两种介质、一份异地；随机抽一个文件恢复到另一台机器，打开确认。</p></section><section><h2 id="section-2">怎么做</h2><p>把这件事拆成现场能检查的动作。</p><ol><li>按 3-2-1：三份、两种介质、一份异地。</li><li>随机抽一个文件恢复到另一台机器。</li><li>打开确认能播放或能回套，记录恢复耗时。</li></ol></section><section><h2 id="section-3">别踩</h2></section><section><h2 id="section-4">3-2-1 落到桌面</h2><p>三份：卡/机内、现场 SSD、备份盘；两种介质：SSD/HDD 或 LTO；一份异地：云或另一栋楼。不要把 RAID 当备份，它只防盘坏，不防误删、勒索和火灾。</p><ol><li>拷卡后先做校验和，再格式化卡；没有两份可读副本，不要清卡。</li><li>现场 SSD 与备份盘分开供电、分开带走；不要放在同一个包里。</li><li>每天收工前看一次备份日志；失败要当场重跑，不要等回工作室。</li></ol></section><section><h2 id="section-5">恢复演练</h2><ol><li>随机抽一个文件，不要挑刚拷完的那个；从备份盘恢复到另一台机器。</li><li>打开或回套，确认能播放、能进 NLE；不要只看文件大小。</li><li>记录恢复耗时、路径、校验和；下次演练换一个人做。</li></ol><p>恢复演练每季度一次；项目交付前至少做一次。</p></section><section><h2 id="section-6">假备份</h2><ol><li>RAID 当备份：阵列重建时再坏一块，数据全没；RAID 不是版本历史。</li><li>同步盘当备份：删了本地，云也删；同步不是备份。</li><li>只备份到同一栋楼：火灾/水灾一起没；异地必须真的异地。</li><li>只复制不校验：坏文件静默通过，直到打开才发现。</li></ol></section><section><h2 id="section-7">备份验收记录</h2><ul><li>三份副本、两种介质、一份异地都能指认；每份都有校验和。</li><li>随机文件在另一台机器恢复成功，能播放或回套。</li><li>恢复耗时、步骤、校验和有人记录；下次换人也能照做。</li><li>卡格式化前确认两份可读副本；备份日志无失败项。</li></ul></section><section><h2 id="section-8">恢复记录</h2><p>每次演练记：日期、随机文件、来源盘、校验和、恢复到哪台机器、打开结果、耗时、操作人。没有打开结果的演练，不算通过。</p></section><section><h2>判断</h2><p>现场只认三个信号：</p><ul><li>剪掉一个镜头，节奏更快而不是更乱</li><li>示波器上肤色、高光和黑位都在范围内</li><li>响度、字幕和文件规格能过一次交付检查</li></ul></section><section><h2>失败</h2><p>下面三种做法会让页面上的细节白做：</p><ul><li>剪辑点跟着音乐，不跟动作</li><li>先定风格再统一，镜头之间跳色</li><li>交付前没查响度和字幕，最后一遍才发现</li></ul></section><section><h2>延伸</h2><p><strong>10 分钟练习：</strong>拿一段 30 秒素材做 A/B，只改“按 3-2-1：三份、两种介质、一份…”；记下一个时间码和一处差异，再决定是否保留。</p></section>
<h2>验收</h2><ul><li>三份备份、两种介质、一份异地都能指认。</li><li>随机文件在另一台机器恢复成功，能打开。</li><li>恢复耗时和步骤有记录，下一次能照做。</li></ul>
