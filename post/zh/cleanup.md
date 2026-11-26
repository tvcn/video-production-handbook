---
id: post.vfx.cleanup
site: post
type: article
lang: zh
translation_key: post.vfx.cleanup
translation_status: source
title: 清理：去掉穿帮，不擦掉信息
summary: 清理穿帮不是把画面擦空，而是去掉错误的东西，保留观众需要的信息。
slug: cleanup
aliases:
- cleanup
canonical_site: post
canonical_path: /article/cleanup/
status: published
diagram: /images/diagrams/zh/cleanup.svg
diagram_alt: 清理：去掉穿帮，不擦掉信息的结构示意图。
diagram_caption: 看“先列必须保留的信息：人脸、文字、动作”和“只擦错误物件，不要擦掉背景纹理”两处，判断剪掉一个镜头后，节奏是更快还是更乱。
difficulty: beginner
stage: field-note
format: handbook
authors:
- TVCN 后期组
last_verified: '2026-11-26'
review_due: '2027-02-26'
related: [post.color.color, post.color.color-management, shoot.camera.composition]
source_kind: sourced
sources:
- S30
- S35
---
<p>移除电线、麦克风、灯架前，先看背景：纯墙容易补，纹理、树叶、人群难补。拍摄时多拍一条“干净板”或空镜，后期才有源可补。</p>
<!-- DIAGRAM_START -->
<h2>图解</h2>
<figure>
  <img src="/images/diagrams/zh/cleanup.svg" alt="清理：去掉穿帮，不擦掉信息的结构示意图。">
  <figcaption>看“先列必须保留的信息：人脸、文字、动作”和“只擦错误物件，不要擦掉背景纹理”两处，判断剪掉一个镜头后，节奏是更快还是更乱。</figcaption>
</figure>
<!-- DIAGRAM_END -->
<section><h2 id="section-1">擦除先问“背景有没有信息”</h2><p>擦除后匹配颗粒、噪点和运动模糊；静止帧干净、一动就露馅，是最常见的失败。</p><h2 id="section-2">边界</h2><p>不要擦掉叙事信息。移走一个关键道具、一个路标，可能改变观众对空间的理解；先确认它不重要。</p></section><section><h2 id="section-3">现场</h2><p>先列必须保留的信息：人脸、文字、动作；只擦错误物件，擦完在 100% 和 50% 各看一遍。</p></section><section><h2 id="section-4">怎么做</h2><ol><li>先列必须保留的信息：人脸、文字、动作。</li><li>只擦错误物件，不要擦掉背景纹理。</li><li>擦完在 100% 和 50% 各看一遍，确认补丁不显眼。</li></ol></section><section><h2 id="section-5">别踩</h2><p>别为了干净擦掉信息；脸和文字没了，镜头就废了。</p></section><section><h2>判断</h2><p>这一页的判断只看三条可观察的验收，不靠口号：</p><ul><li><strong>1.</strong> 人脸、文字和动作都还在，擦掉的只有错误物件。</li><li><strong>2.</strong> 补丁在 100% 和 50% 下都不显眼，纹理接得上。</li><li><strong>3.</strong> 前后对比能指出擦掉了什么，而不是整块重绘。</li></ul></section><section><h2>失败</h2><p>下面任一条出现，先停，不要靠后期补：</p><ul><li><strong>1.</strong> 只做到“人脸、文字和动作都还在，擦掉的只有错误物件”的形式，换一个机位或场景就重现不了。</li><li><strong>2.</strong> 把“补丁在 100% 和 50% 下都不显眼，纹理接得上”留到后期或口头解释，现场没有留下能复查的记录。</li><li><strong>3.</strong> 别为了干净擦掉信息；脸和文字没了，镜头就废了。</li></ul></section><section><h2>延伸</h2><p><strong>10 分钟练习：</strong>拿一段 30 秒素材做 A/B，只改“先列必须保留的信息：人脸、文字、动作”；记下一个时间码和一处差异，再决定是否保留。</p></section>
<h2>验收</h2><ul><li>人脸、文字和动作都还在，擦掉的只有错误物件。</li><li>补丁在 100% 和 50% 下都不显眼，纹理接得上。</li><li>前后对比能指出擦掉了什么，而不是整块重绘。</li></ul>

<!-- SOURCES_START -->
## 参考与延伸阅读

- [S30] [DaVinci Resolve 产品与文档](https://www.blackmagicdesign.com/products/davinciresolve) — 2026-11-26 访问。用于核对首段“清理穿帮不是把画面擦空，而是去掉错误的东西，保留观众需要的信息。”中的术语与公开背景（剪辑、调色、Fusion 与交付的官方产品入口）；不替代现场测试。
- [S35] [Avid 资源中心](https://www.avid.com/resource-center) — 2026-11-26 访问。用于核对首段“清理穿帮不是把画面擦空，而是去掉错误的东西，保留观众需要的信息。”中的术语与公开背景（Media Composer、协作与交付的资源入口）；不替代现场测试。
<!-- SOURCES_END -->

