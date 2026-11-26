---
id: animation.motion-graphics.mg-typography
site: animation
type: article
lang: zh
translation_key: animation.motion-graphics.mg-typography
translation_status: source
title: 字效：先读清再动
summary: 字效先保证静止时读得清，再决定怎么动；边动边读，阅读速度会掉一半。
slug: mg-typography
aliases:
- mg-typography
canonical_site: animation
canonical_path: /article/mg-typography/
status: published
diagram: /images/diagrams/zh/mg-typography.svg
diagram_alt: 字效：先读清再动的结构示意图。
diagram_caption: 看“先做静止版，手机宽度下读清”和“再做 6 帧入场，只动位置和透明度”两处，判断前景、中景、背景的速度差能不能在一次移动里看出来。
difficulty: beginner
stage: field-note
format: handbook
authors:
- TVCN 动画组
last_verified: '2026-11-26'
review_due: '2027-02-26'
related: [animation.3d.modeling, animation.3d.render, formats.documentary.documentary-template]
sources:
- S59
- S62
test_context: 复核环境：Windows 11；Blender 4.x / After Effects 2025 公开流程；不声称所有版本一致。
known_failures: 已知失败：插件/版本差异导致绑定或渲染失败；字体授权与素材版权需单独核对。
verified: 2026-11-22
source_kind: sourced
---
<p>文字动画最容易犯的错，是每个字飞入、旋转、变形，观众读不完。先保一行字停留足够时间，再做入场；入场不超过 0.3 秒，停留至少 1.5 秒。</p>
<!-- DIAGRAM_START -->
<h2>图解</h2>
<figure>
  <img src="/images/diagrams/zh/mg-typography.svg" alt="字效：先读清再动的结构示意图。">
  <figcaption>看“先做静止版，手机宽度下读清”和“再做 6 帧入场，只动位置和透明度”两处，判断前景、中景、背景的速度差能不能在一次移动里看出来。</figcaption>
</figure>
<!-- DIAGRAM_END -->
<section><h2 id="section-1">字体动画先保“可读”，再保“好看”</h2><p>一行只用一个动作：淡入、上移或遮罩，不要同时加三种。</p><h2 id="section-2">边界</h2><p>字体不是装饰画。可读性优先：对比、字号、行距；风格化字体用在标题，不要用在长句。</p><h2 id="section-3">MG 字体：先定网格，再做动画</h2>
<p>字体动画看起来乱，通常不是动画问题，是排版没有网格。先定基线、字距和安全区，再让字动；没有网格，动得越多越乱。</p>
<div class="table-scroll"><table class="data-table"><thead><tr><th>先定</th><th>数值</th><th>作用</th></tr></thead><tbody>
<tr><td>基线网格</td><td>按画面高度 8–12 等分</td><td>多行字对齐</td></tr>
<tr><td>字距</td><td>中文 0，英文 -2% 至 +2%</td><td>避免过松或挤</td></tr>
<tr><td>安全区</td><td>竖屏上下各留 12%</td><td>平台 UI 不挡字</td></tr>
<tr><td>字重</td><td>最多 2 种</td><td>层级清楚</td></tr>
</tbody></table></div>
<h3>项目级检查</h3>
<ol><li>字体授权先查商用范围；标题字和正文字分开授权，不要默认“下载就能用”。</li><li>动画只做 2–3 种运动：位移、遮罩、字重变化；不要每个字都飞。</li><li>中英混排时，英文用中文基线的 80%–90% 字号，视觉才齐。</li><li>输出前在手机尺寸看一遍，最小字号不小于 24px（按 1080 宽）。</li></ol>
<p>如果客户要求“所有字都动”，先给一条 5 秒样片；动效过多时，信息会被动画吃掉。</p></section><section><h2 id="section-4">现场</h2><p>先做静止版，手机宽度下读清；再做 6 帧入场，只动位置和透明度，别同时旋转、缩放、发光。</p></section><section><h2 id="section-5">怎么做</h2><ol><li>先做静止版，手机宽度下读清。</li><li>再做 6 帧入场，只动位置和透明度。</li><li>不要同时旋转、缩放、发光，先保信息。</li></ol></section><section><h2 id="section-6">别踩</h2><p>别用白闪和推拉当万能转场；字没读清，动效再花也白费。</p></section><section><h2>判断</h2><p>这一页的判断只看三条可观察的验收，不靠口号：</p><ul><li><strong>1.</strong> 静止版在手机宽度下能读清，最长一行不出画。</li><li><strong>2.</strong> 入场只动了位置和透明度，没有同时旋转缩放。</li><li><strong>3.</strong> 静音看一遍，能说出信息出现的顺序。</li></ul></section><section><h2>失败</h2><p>下面任一条出现，先停，不要靠后期补：</p><ul><li><strong>1.</strong> 只做到“静止版在手机宽度下能读清，最长一行不出画”的形式，换一个机位或场景就重现不了。</li><li><strong>2.</strong> 把“入场只动了位置和透明度，没有同时旋转缩放”留到后期或口头解释，现场没有留下能复查的记录。</li><li><strong>3.</strong> 别用白闪和推拉当万能转场；字没读清，动效再花也白费。</li></ul></section><section><h2>延伸</h2><p><strong>10 分钟练习：</strong>用 24 fps 画 3 个关键帧，只改“再做 6 帧入场，只动位置和透明度”，导出 2 秒；如果重量仍读不出来，先加预备帧，不要加模糊。</p></section>
<h2>验收</h2><ul><li>静止版在手机宽度下能读清，最长一行不出画。</li><li>入场只动了位置和透明度，没有同时旋转缩放。</li><li>静音看一遍，能说出信息出现的顺序。</li></ul>

<!-- SOURCES_START -->
## 参考与延伸阅读

- [S59] [Adobe：After Effects 官方指南](https://helpx.adobe.com/after-effects/user-guide.html) — 2026-11-26 访问。用于核对「MG 字体：先定网格，再做动画」一节的术语/方法/规则（After Effects 官方指南，不是合成美学结论）；不核对其中由本页经验得出的数字、型号与现场结论，也不替代测试。
- [S62] [Blender：官方手册](https://docs.blender.org/manual/en/latest/) — 2026-11-26 访问。用于核对「字体动画先保“可读”，再保“好看”」一节的术语/方法/规则（Blender 官方手册，不是行业流程标准）；不核对其中由本页经验得出的数字、型号与现场结论，也不替代测试。
<!-- SOURCES_END -->

