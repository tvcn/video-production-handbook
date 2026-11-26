---
id: animation.motion-graphics.mg-rhythm
site: animation
type: article
lang: zh
translation_key: animation.motion-graphics.mg-rhythm
translation_status: source
title: 动效节奏：音乐点与帧
summary: 动效节奏先把音乐点对到帧，再决定缓入缓出；点没对上，再顺也乱。
slug: mg-rhythm
aliases:
- mg-rhythm
canonical_site: animation
canonical_path: /article/mg-rhythm/
status: published
diagram: /images/diagrams/zh/mg-rhythm.svg
diagram_alt: 动效节奏：音乐点与帧的结构示意图。
diagram_caption: 看“把音乐波形放到时间线，标出 8 个重…”和“每个重拍对应一个关键帧”两处，判断前景、中景、背景的速度差能不能在一次移动里看出来。
difficulty: beginner
stage: field-note
format: handbook
authors:
- TVCN 动画组
last_verified: '2026-11-26'
review_due: '2027-02-26'
related: [animation.motion-graphics.mg-transition, animation.motion-graphics.mg-typography, formats.brand.brand-film]
source_kind: sourced
sources:
- S59
- S62
---
<p>动态图形不是所有元素同时动。先分组：主信息、辅助线、背景；每组有各自的入场和停顿。观众先读主信息，再读辅助，最后看背景。</p>
<!-- DIAGRAM_START -->
<h2>图解</h2>
<figure>
  <img src="/images/diagrams/zh/mg-rhythm.svg" alt="动效节奏：音乐点与帧的结构示意图。">
  <figcaption>看“把音乐波形放到时间线，标出 8 个重…”和“每个重拍对应一个关键帧”两处，判断前景、中景、背景的速度差能不能在一次移动里看出来。</figcaption>
</figure>
<!-- DIAGRAM_END -->
<section><h2 id="section-1">节奏靠“分组”，不靠每帧动</h2><p>用 2 秒、4 秒、6 秒三个节拍测试；所有元素都在同一拍入场，会像爆炸。</p><h2 id="section-2">边界</h2><p>节奏不是越快越好。信息密度高时，停一拍比加十个动画有用；观众需要时间读字。</p><h2 id="section-3">动效节奏：先画音乐点，再决定谁动</h2>
<p>MG 不是“每个鼓点都动”。先把音乐拆成 4–8 个小节，标出重音和停顿，再决定哪一个元素动；所有元素一起动，观众什么都看不清。</p>
<ol><li>重音上只动一个主体；弱拍用位移或透明度，不用缩放。</li><li>每个动作至少留 4–6 帧静止，让眼睛休息；连续动超过 2 秒会疲劳。</li><li>转场用形状或位置匹配，不要用炫技插件；插件会抢信息。</li></ol>
<p>验收：关掉声音看一遍，节奏还在；打开声音，动作不抢歌词。两者都成立才算对上。</p></section><section><h2 id="section-4">现场</h2><p>先把音乐波形放到时间线，标出 8 个重拍；每个重拍对应一个关键帧，再调缓动。</p></section><section><h2 id="section-5">怎么做</h2><ol><li>把音乐波形放到时间线，标出 8 个重拍。</li><li>每个重拍对应一个关键帧。</li><li>再调缓动，不要先做动画再找音乐。</li></ol></section><section><h2 id="section-6">别踩</h2><p>别先做动画再贴音乐；点对不上，缓动再顺也乱。</p></section><section><h2>判断</h2><p>这一页的判断只看三条可观察的验收，不靠口号：</p><ul><li><strong>1.</strong> 时间线上标出 8 个重拍，每个都有对应关键帧。</li><li><strong>2.</strong> 动画变化与重拍同步，不是音乐在后面追。</li><li><strong>3.</strong> 静音看一遍，节奏仍然成立，不靠音乐硬撑。</li></ul></section><section><h2>失败</h2><p>下面任一条出现，先停，不要靠后期补：</p><ul><li><strong>1.</strong> 只做到“时间线上标出 8 个重拍，每个都有对应关键帧”的形式，换一个机位或场景就重现不了。</li><li><strong>2.</strong> 把“动画变化与重拍同步，不是音乐在后面追”留到后期或口头解释，现场没有留下能复查的记录。</li><li><strong>3.</strong> 别先做动画再贴音乐；点对不上，缓动再顺也乱。</li></ul></section><section><h2>延伸</h2><p><strong>10 分钟练习：</strong>用 24 fps 画 3 个关键帧，只改“每个重拍对应一个关键帧”，导出 2 秒；如果重量仍读不出来，先加预备帧，不要加模糊。</p></section>
<h2>验收</h2><ul><li>时间线上标出 8 个重拍，每个都有对应关键帧。</li><li>动画变化与重拍同步，不是音乐在后面追。</li><li>静音看一遍，节奏仍然成立，不靠音乐硬撑。</li></ul>

<!-- SOURCES_START -->
## 参考与延伸阅读

- [S59] [Adobe：After Effects 用户指南](https://helpx.adobe.com/after-effects/user-guide.html) — 2026-11-26 访问。用于核对首段“动效节奏先把音乐点对到帧，再决定缓入缓出；点没对上，再顺也乱。”中的术语与公开背景（合成、关键帧、跟踪与导出）；不替代现场测试。
- [S62] [Blender Foundation：Blender 官方手册](https://docs.blender.org/manual/en/latest/) — 2026-11-26 访问。用于核对首段“动效节奏先把音乐点对到帧，再决定缓入缓出；点没对上，再顺也乱。”中的术语与公开背景（建模、绑定、动画、渲染）；不替代现场测试。
<!-- SOURCES_END -->

