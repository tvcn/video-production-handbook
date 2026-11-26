---
id: animation.3d.render
site: animation
type: article
lang: zh
translation_key: animation.3d.render
translation_status: source
title: 渲染：采样与噪点
summary: 渲染先看采样和噪点，再看分辨率；噪点没压住，4K 也只是更大的脏。
slug: render
aliases:
- render
canonical_site: animation
canonical_path: /article/render/
status: published
diagram: /images/diagrams/zh/render.svg
diagram_alt: 渲染：采样与噪点的结构示意图。
diagram_caption: 看“先 50% 分辨率、低采样看噪点分布”和“把灯光采样和材质采样分开调”两处，判断前景、中景、背景的速度差能不能在一次移动里看出来。
difficulty: beginner
stage: field-note
format: handbook
authors:
- TVCN 动画组
last_verified: '2026-11-26'
review_due: '2027-02-26'
related: [animation.3d.rigging, animation.2d.run-cycle, formats.documentary.documentary-template]
source_kind: sourced
sources:
- S62
- S59
---
<p>确认时间线帧率、分辨率、色彩空间和音频采样率；渲染设置必须与交付表一致。不要一边改时间线一边渲染，出来的文件对不上。</p>
<!-- DIAGRAM_START -->
<h2>图解</h2>
<figure>
  <img src="/images/diagrams/zh/render.svg" alt="渲染：采样与噪点的结构示意图。">
  <figcaption>看“先 50% 分辨率、低采样看噪点分布”和“把灯光采样和材质采样分开调”两处，判断前景、中景、背景的速度差能不能在一次移动里看出来。</figcaption>
</figure>
<!-- DIAGRAM_END -->
<section><h2 id="section-1">渲染前先锁时间线，再锁设置</h2><p>渲染后抽三个点回放：开头、中间动作、结尾字幕；检查黑帧、静帧、断音和字幕溢出。文件大小和时长也要对。</p><h2 id="section-2">边界</h2><p>渲染不是交付。渲染通过只说明文件生成成功，不说明内容正确；QC 仍要单独做。</p><h2 id="section-3">渲染：先锁采样，再谈降噪</h2>
<p>渲染噪声不是靠降噪“抹”掉的。采样不够，降噪会把细节一起抹平；采样够，降噪只是最后 10%。先把采样和光线反弹调到稳定，再用降噪收尾。</p>
<div class="table-scroll"><table class="data-table"><thead><tr><th>参数</th><th>先调</th><th>症状</th></tr></thead><tbody>
<tr><td>采样</td><td>从 64 起，逐级加倍</td><td>暗部噪点、边缘闪烁</td></tr>
<tr><td>反弹</td><td>3–4 次，按场景复杂度</td><td>暗部死黑或过亮</td></tr>
<tr><td>降噪</td><td>最后开，保留细节</td><td>皮肤像塑料、纹理消失</td></tr>
<tr><td>输出</td><td>EXR 多通道</td><td>后期无法单独调光</td></tr>
</tbody></table></div>
<h3>项目级检查</h3>
<ol><li>先渲一张 50% 分辨率测试，确认构图、材质和灯；不要直接等 4K。</li><li>把采样翻倍，噪点应明显下降；如果没变，问题在灯光或材质，不在采样。</li><li>降噪前后各存一版，比较毛孔、布料纹理和头发；降噪吃细节就降强度。</li><li>输出 EXR 带 Beauty、Light、Reflection、Depth；交付 MP4 之外，保留可调版本。</li></ol>
<p>渲染农场排队时，先提交低采样预览占位，确认镜头再接高采样；不要用最终参数试错。</p></section><section><h2 id="section-4">现场</h2><p>先 50% 分辨率、低采样看噪点分布；把灯光采样和材质采样分开调，别只加总采样。</p></section><section><h2 id="section-5">怎么做</h2><ol><li>先 50% 分辨率、低采样看噪点分布。</li><li>把灯光采样和材质采样分开调。</li><li>不要只加总采样，先找出噪点来自哪一项。</li></ol></section><section><h2 id="section-6">别踩</h2><p>别用总采样硬压噪点；找不到来源，时间全烧在渲染上。</p></section><section><h2>判断</h2><p>这一页的判断只看三条可观察的验收，不靠口号：</p><ul><li><strong>1.</strong> 50% 低采样下能看出噪点集中在灯光还是材质。</li><li><strong>2.</strong> 灯光采样和材质采样分开调整过。</li><li><strong>3.</strong> 最终噪点来自具体一项，不是靠无脑拉高总采样。</li></ul></section><section><h2>失败</h2><p>下面任一条出现，先停，不要靠后期补：</p><ul><li><strong>1.</strong> 只做到“50% 低采样下能看出噪点集中在灯光还是材质”的形式，换一个机位或场景就重现不了。</li><li><strong>2.</strong> 把“灯光采样和材质采样分开调整过”留到后期或口头解释，现场没有留下能复查的记录。</li><li><strong>3.</strong> 别用总采样硬压噪点；找不到来源，时间全烧在渲染上。</li></ul></section><section><h2>延伸</h2><p><strong>10 分钟练习：</strong>用 24 fps 画 3 个关键帧，只改“把灯光采样和材质采样分开调”，导出 2 秒；如果重量仍读不出来，先加预备帧，不要加模糊。</p></section>
<h2>验收</h2><ul><li>50% 低采样下能看出噪点集中在灯光还是材质。</li><li>灯光采样和材质采样分开调整过。</li><li>最终噪点来自具体一项，不是靠无脑拉高总采样。</li></ul>

<!-- SOURCES_START -->
## 参考与延伸阅读

- [S62] [Blender Foundation：Blender 官方手册](https://docs.blender.org/manual/en/latest/) — 2026-11-26 访问。用于核对首段“渲染先看采样和噪点，再看分辨率；噪点没压住，4K 也只是更大的脏。”中的术语与公开背景（建模、绑定、动画、渲染）；不替代现场测试。
- [S59] [Adobe：After Effects 用户指南](https://helpx.adobe.com/after-effects/user-guide.html) — 2026-11-26 访问。用于核对首段“渲染先看采样和噪点，再看分辨率；噪点没压住，4K 也只是更大的脏。”中的术语与公开背景（合成、关键帧、跟踪与导出）；不替代现场测试。
<!-- SOURCES_END -->

