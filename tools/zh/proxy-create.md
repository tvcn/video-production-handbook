---
id: tools.tutorial.proxy-create
site: tools
type: article
lang: zh
translation_key: tools.tutorial.proxy-create
translation_status: source
title: 代理生成：剪辑不卡
summary: 代理按时间线和交付分辨率生成，别用完整分辨率硬剪；代理不对，字幕和构图会错。
slug: proxy-create
aliases:
- proxy-create
canonical_site: tools
canonical_path: /article/proxy-create/
status: published
diagram: /images/diagrams/zh/proxy-create.svg
diagram_alt: 代理生成：剪辑不卡的结构示意图。
diagram_caption: 看“按四分之一分辨率生成 ProRes …”和“放独立 SSD”两处，判断这个参数能不能对应到一个具体的拍摄问题。
difficulty: beginner
stage: field-note
format: handbook
authors:
- TVCN 工具组
last_verified: '2026-11-25'
review_due: '2027-05-25'
related:
- tools.tutorial.sync-multicam.en
- tools.tutorial.color-checker.en
- tools.tutorial.night-practical.en
source_kind: experience
---

<p>生成代理时不要改文件名，也不要换目录结构。剪辑软件靠原名和时间码回批；改名会让回批变成手工找文件。</p>
<!-- DIAGRAM_START -->
<h2>图解</h2>
<figure>
  <img src="/images/diagrams/zh/proxy-create.svg" alt="代理生成：剪辑不卡的结构示意图。">
  <figcaption>看“按四分之一分辨率生成 ProRes …”和“放独立 SSD”两处，判断这个参数能不能对应到一个具体的拍摄问题。</figcaption>
</figure>
<!-- DIAGRAM_END -->
<section><h2 id="section-1">代理要保留原名、时间码和卷名</h2><p>代理分辨率按时间线需要选：多机位 4K 可以降到 1080p 或 720p，但帧率和色彩空间要跟原素材一致。</p><h2 id="section-2">边界</h2><p>代理不是交付。输出母版前确认时间线链接的是原素材；链接代理直接导出，画质会掉一档。</p><h2 id="section-3">代理规格：能剪、能回套、不丢原片</h2>
<p>代理不是“压小就行”。要在同一时间码、同一帧率、同一文件名下回套原片；否则剪辑一换回原片就错位。</p>
<ol><li>常用：1080p ProRes Proxy 或 H.264 高码率，帧率与源一致，音频保留。</li><li>文件名加 <code>_proxy</code>，不要改卷名和 reel；回套用原始媒体路径。</li><li>原片单独存放，代理单独项目；不要在代理上做最终调色。</li></ol>
<p>验收：随机抽一个剪切点，回套原片后帧位不偏移；音频同步不掉。偏移就检查帧率和时间码。</p></section><section><h2 id="section-4">现场</h2><p>按四分之一分辨率生成 ProRes Proxy，放独立 SSD；回套时检查时间码和构图。</p></section><section><h2 id="section-5">怎么做</h2><ol><li>按四分之一分辨率生成 ProRes Proxy。</li><li>放独立 SSD。</li><li>回套时检查时间码和构图。</li></ol></section><section><h2 id="section-6">别踩</h2><p>别用代理做最终导出；一换回原片，字幕位置全偏。</p></section><section><h2>判断</h2><p>现场只认三个信号：</p><ul><li>每一项参数都能对应一个具体的拍摄问题</li><li>重量、供电和接口在真实机位上成立</li><li>60 秒测试能留下一个可比较的数字</li></ul></section><section><h2>失败</h2><p>下面三种做法会让页面上的细节白做：</p><ul><li>只看参数，不看接口、供电和重量</li><li>买回来才发现电池、存储或机身不匹配</li><li>没有 60 秒测试，问题被带到正式拍摄</li></ul></section><section><h2>延伸</h2><p><strong>10 分钟练习：</strong>用现有器材做 60 秒测试，只测“按四分之一分辨率生成 ProRes …”；记下两个数字：一个是你需要的，一个是器材实际给出的。</p></section>
<h2>验收</h2><ul><li>代理是四分之一分辨率 ProRes Proxy，放在独立 SSD。</li><li>时间线和代理命名能对应回原片。</li><li>回套后时间码和构图与代理版一致。</li></ul>
