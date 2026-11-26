---
id: shoot.multicam.multicam-sync
site: shoot
type: article
lang: zh
translation_key: shoot.multicam.multicam-sync
translation_status: source
title: 多机位同步：时间码与机位图
summary: 多机位先画机位图，再对时间码；剪辑要知道哪台机器站在哪。
slug: multicam-sync
aliases:
- multicam-sync
canonical_site: shoot
canonical_path: /article/multicam-sync/
status: published
diagram: /images/diagrams/zh/multicam-sync.svg
diagram_alt: 多机位同步：时间码与机位图的结构示意图。
diagram_caption: 看“画一张俯视机位图，标清 A、B、C …”和“用时间码或拍手同步，确认三路都能对齐”两处，判断高光、肤色和声音有没有被同时保住。
difficulty: beginner
stage: field-note
format: handbook
authors:
- TVCN 拍摄组
last_verified: '2026-11-26'
review_due: '2027-02-26'
related: [shoot.camera.nd-filter, shoot.lighting.night-interior, post.color.color]
source_kind: sourced
sources:
- S67
- S28
- S23
- S53
---
<p>有时间码就 jam sync，没有就用共同拍手或闪光。每台机位必须拍到同一事件，剪辑按音频波形对齐；不要靠画面猜。</p>
<!-- DIAGRAM_START -->
<h2>图解</h2>
<figure>
  <img src="/images/diagrams/zh/multicam-sync.svg" alt="多机位同步：时间码与机位图的结构示意图。">
  <figcaption>看“画一张俯视机位图，标清 A、B、C …”和“用时间码或拍手同步，确认三路都能对齐”两处，判断高光、肤色和声音有没有被同时保住。</figcaption>
</figure>
<!-- DIAGRAM_END -->
<section><h2 id="section-1">多机位先统一“时间基准”</h2><p>统一帧率、快门、白平衡和录音采样率；不同机位色彩可以后期匹配，帧率不同则无法无损同步。</p><h2 id="section-2">边界</h2><p>同步不是一次性。长时间录制会漂移，每 20–30 分钟重新对齐；重要场次用时间码发生器。</p></section><section><h2 id="section-3">现场</h2><p>画一张俯视机位图，标清 A、B、C 各拍什么。用时间码或拍手同步，剪辑按这张图找条。</p></section><section><h2 id="section-4">怎么做</h2><p>两台机器拍同一个景别，不叫多机位，叫重复。</p><ol><li>画一张俯视机位图，标清 A、B、C 各拍什么景别。</li><li>用时间码或拍手同步，确认三路都能对齐。</li><li>检查每个机位都提供不同信息，没有重复景别。</li></ol></section><section><h2 id="section-5">别踩</h2><p>别让两台机器拍同一个景别；多机位不是重复机位。</p></section><section><h2>判断</h2><p>这一页的判断只看三条可观察的验收，不靠口号：</p><ul><li><strong>1.</strong> 机位图能看出 A、B、C 各自拍什么，没有两台重复。</li><li><strong>2.</strong> 三路素材在时间线上逐帧对齐，没有偏移。</li><li><strong>3.</strong> 剪辑时每个机位都能提供不同信息，切起来有理由。</li></ul></section><section><h2>失败</h2><p>下面任一条出现，先停，不要靠后期补：</p><ul><li><strong>1.</strong> 只做到“机位图能看出 A、B、C 各自拍什么，没有两台重复”的形式，换一个机位或场景就重现不了。</li><li><strong>2.</strong> 把“三路素材在时间线上逐帧对齐，没有偏移”留到后期或口头解释，现场没有留下能复查的记录。</li><li><strong>3.</strong> 别让两台机器拍同一个景别；多机位不是重复机位。</li></ul></section><section><h2>延伸</h2><p><strong>10 分钟练习：</strong>用同一扇窗拍三条 10 秒，只改“画一张俯视机位图，标清 A、B、C …”；比较高光、肤色和背景，选一条能直接剪的。</p></section>
<h2>验收</h2><ul><li>机位图能看出 A、B、C 各自拍什么，没有两台重复。</li><li>三路素材在时间线上逐帧对齐，没有偏移。</li><li>剪辑时每个机位都能提供不同信息，切起来有理由。</li></ul>

<!-- SOURCES_START -->
## 参考与延伸阅读

- [S67] [IETF：RFC 8216（HLS）](https://datatracker.ietf.org/doc/html/rfc8216) — 2026-11-26 访问。用于核对「多机位先统一“时间基准”」一节的术语/方法/规则（HLS 协议规范，不是直播运营建议）；不核对其中由本页经验得出的数字、型号与现场结论，也不替代测试。
- [S28] [Netflix：合作伙伴帮助](https://partnerhelp.netflixstudios.com/) — 2026-11-26 访问。用于核对「现场」一节的术语/方法/规则（Netflix 交付帮助，不是通用平台规则）；不核对其中由本页经验得出的数字、型号与现场结论，也不替代测试。
- [S23] [SMPTE：标准入口](https://www.smpte.org/standards) — 2026-11-26 访问。用于核对「怎么做」一节的术语/方法/规则（SMPTE 标准入口，不是具体机型参数）；不核对其中由本页经验得出的数字、型号与现场结论，也不替代测试。
<!-- SOURCES_END -->

