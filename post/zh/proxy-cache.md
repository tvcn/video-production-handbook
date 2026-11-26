---
id: post.assets.proxy-cache
site: post
type: article
lang: zh
translation_key: post.assets.proxy-cache
translation_status: source
title: 代理与缓存：别让硬盘先满
summary: 代理和缓存要放在独立盘，别让剪辑盘先满；满了就会掉帧。
slug: proxy-cache
aliases:
- proxy-cache
canonical_site: post
canonical_path: /article/proxy-cache/
status: published
diagram: /images/diagrams/zh/proxy-cache.svg
diagram_alt: 代理与缓存：别让硬盘先满的结构示意图。
diagram_caption: 看“代理和缓存放第二块 SSD”和“系统盘留 20% 空间，剪辑盘不要红”两处，判断剪掉一个镜头后，节奏是更快还是更乱。
difficulty: beginner
stage: field-note
format: handbook
authors:
- TVCN 后期组
last_verified: '2026-11-26'
review_due: '2027-02-26'
related: [post.editing.proxy-workflow, post.delivery.qc, shoot.camera.composition]
source_kind: sourced
sources:
- S34
- S60
---
<p>代理是低分辨率副本，用来剪辑；缓存是软件生成的预览文件，用来播放特效。删缓存不会丢原素材，删代理会让时间线离线；两者要分目录。</p>
<!-- DIAGRAM_START -->
<h2>图解</h2>
<figure>
  <img src="/images/diagrams/zh/proxy-cache.svg" alt="代理与缓存：别让硬盘先满的结构示意图。">
  <figcaption>看“代理和缓存放第二块 SSD”和“系统盘留 20% 空间，剪辑盘不要红”两处，判断剪掉一个镜头后，节奏是更快还是更乱。</figcaption>
</figure>
<!-- DIAGRAM_END -->
<section><h2 id="section-1">代理和缓存不是一回事</h2><p>代理放“Proxy”文件夹，缓存放软件默认缓存目录；清理时只清缓存，不动代理。</p><h2 id="section-2">边界</h2><p>不要用清理软件一键删“媒体缓存”。它可能把代理和原素材一起扫掉；先确认路径，再删。</p></section><section><h2 id="section-3">现场</h2><p>代理和缓存放第二块 SSD；系统盘留 20% 空间；剪辑盘满了先清缓存，不要删原始。</p></section><section><h2 id="section-4">怎么做</h2><ol><li>代理和缓存放第二块 SSD。</li><li>系统盘留 20% 空间，剪辑盘不要红。</li><li>盘满先清缓存，不要删原始素材。</li></ol></section><section><h2 id="section-5">别踩</h2><p>别删原始素材换空间；缓存可以重建，素材不能。</p></section><section><h2>判断</h2><p>这一页的判断只看三条可观察的验收，不靠口号：</p><ul><li><strong>1.</strong> 代理和缓存在第二块盘，剪辑盘仍有可用空间。</li><li><strong>2.</strong> 系统盘保留至少 20%，没有红色警告。</li><li><strong>3.</strong> 清缓存后项目能重建，原始素材一条没少。</li></ul></section><section><h2>失败</h2><p>下面任一条出现，先停，不要靠后期补：</p><ul><li><strong>1.</strong> 只做到“代理和缓存在第二块盘，剪辑盘仍有可用空间”的形式，换一个机位或场景就重现不了。</li><li><strong>2.</strong> 把“系统盘保留至少 20%，没有红色警告”留到后期或口头解释，现场没有留下能复查的记录。</li><li><strong>3.</strong> 别删原始素材换空间；缓存可以重建，素材不能。</li></ul></section><section><h2>延伸</h2><p><strong>10 分钟练习：</strong>拿一段 30 秒素材做 A/B，只改“代理和缓存放第二块 SSD”；记下一个时间码和一处差异，再决定是否保留。</p></section>
<h2>验收</h2><ul><li>代理和缓存在第二块盘，剪辑盘仍有可用空间。</li><li>系统盘保留至少 20%，没有红色警告。</li><li>清缓存后项目能重建，原始素材一条没少。</li></ul>

<!-- SOURCES_START -->
## 参考与延伸阅读

- [S34] [Adobe Premiere Pro 用户指南](https://helpx.adobe.com/premiere-pro/user-guide.html) — 2026-11-26 访问。用于核对首段“代理和缓存要放在独立盘，别让剪辑盘先满；满了就会掉帧。”中的术语与公开背景（剪辑、代理、色彩与导出的官方文档）；不替代现场测试。
- [S60] [Apple：Final Cut Pro 用户指南](https://support.apple.com/guide/final-cut-pro/welcome/mac) — 2026-11-26 访问。用于核对首段“代理和缓存要放在独立盘，别让剪辑盘先满；满了就会掉帧。”中的术语与公开背景（剪辑、磁性时间线、代理与导出）；不替代现场测试。
<!-- SOURCES_END -->

