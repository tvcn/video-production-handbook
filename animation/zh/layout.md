---
id: animation.3d.layout
site: animation
type: article
lang: zh
translation_key: animation.3d.layout
translation_status: source
title: Layout：镜头与资产交接
summary: Layout 把机位、比例、资产版本锁死，再交给动画；交接不清，动画师只能猜。
slug: layout
aliases:
- layout
canonical_site: animation
canonical_path: /article/layout/
status: published
diagram: /images/diagrams/zh/layout.svg
diagram_alt: Layout：镜头与资产交接的结构示意图。
diagram_caption: 看“交付前锁三样：机位、角色比例、资产版…”和“在文件头写版本号”两处，判断前景、中景、背景的速度差能不能在一次移动里看出来。
difficulty: beginner
stage: field-note
format: handbook
authors:
- TVCN 动画组
last_verified: '2026-11-26'
review_due: '2027-02-26'
related: [animation.3d.lighting-3d, animation.2d.loop-cycle, formats.documentary.documentary-template]
source_kind: sourced
sources:
- S62
- S59
- S59
---
<p>三维 Layout 不是摆好看。先画地面线、摄影机高度和焦距，再放角色；三者一定，空间才成立。角色比例错了，后面动画再顺也像贴纸。</p>
<!-- DIAGRAM_START -->
<h2>图解</h2>
<figure>
  <img src="/images/diagrams/zh/layout.svg" alt="Layout：镜头与资产交接的结构示意图。">
  <figcaption>看“交付前锁三样：机位、角色比例、资产版…”和“在文件头写版本号”两处，判断前景、中景、背景的速度差能不能在一次移动里看出来。</figcaption>
</figure>
<!-- DIAGRAM_END -->
<section><h2 id="section-1">Layout 先定“摄影机与地面”</h2><p>用简单方块做一版 playblast，检查遮挡和剪影；不要先做细节。</p><h2 id="section-2">边界</h2><p>Layout 不是最终镜头。它允许粗糙，但摄影机、比例和时间必须已经定下；这三项后面改，成本最高。</p><h2 id="section-3">Layout：把“镜头”变成可交接的空间</h2>
<p>Layout 不是摆好看，而是确定摄影机、角色站位、比例和运动路线，让后面的人不用猜。一个合格的 layout 镜头，换一个动画师也能接上。</p>
<div class="table-scroll"><table class="data-table"><thead><tr><th>交付</th><th>必须写清</th><th>常见缺失</th></tr></thead><tbody>
<tr><td>摄影机</td><td>焦距、机位、运动路径、帧数</td><td>只有一张构图，没有运动</td></tr>
<tr><td>角色</td><td>站位、朝向、视线、比例</td><td>和场景比例不一致</td></tr>
<tr><td>环境</td><td>可动道具、遮挡关系</td><td>前景挡住主体</td></tr>
<tr><td>时间</td><td>镜头时长、关键动作节拍</td><td>动画师自己猜节奏</td></tr>
</tbody></table></div>
<h3>项目级检查</h3>
<ol><li>每个镜头先做灰度 blockout，确认剪影和空间关系，再进细节。</li><li>摄影机运动用 3 个关键帧标出起点、中段、终点；不要只给“推近”。</li><li>角色脚底与地面接触要标出来；悬空是 layout 最常见的穿帮。</li><li>把镜头号和资产名对应表交给动画、灯光、合成，避免同名资产覆盖。</li></ol>
<p>验收时按成片帧率播放，不看单帧。单帧好看但运动不顺，说明 layout 的路径有问题。</p></section><section><h2 id="section-4">现场</h2><p>交付前锁三样：机位、角色比例、资产版本；在文件头写版本号，动画师按 layout 做。</p></section><section><h2 id="section-5">怎么做</h2><ol><li>交付前锁三样：机位、角色比例、资产版本。</li><li>在文件头写版本号。</li><li>动画师按 layout 做，不自行改机位。</li></ol></section><section><h2 id="section-6">别踩</h2><p>别在 layout 里留活机位；动画一开做，改机位就是返工。</p></section><section><h2>判断</h2><p>这一页的判断只看三条可观察的验收，不靠口号：</p><ul><li><strong>1.</strong> 机位、角色比例、资产版本三项都锁死并有版本号。</li><li><strong>2.</strong> 文件头能看到版本和依赖，动画师不用猜。</li><li><strong>3.</strong> 动画段没有擅自改机位，最终镜头和 layout 一致。</li></ul></section><section><h2>失败</h2><p>下面任一条出现，先停，不要靠后期补：</p><ul><li><strong>1.</strong> 只做到“机位、角色比例、资产版本三项都锁死并有版本号”的形式，换一个机位或场景就重现不了。</li><li><strong>2.</strong> 把“文件头能看到版本和依赖，动画师不用猜”留到后期或口头解释，现场没有留下能复查的记录。</li><li><strong>3.</strong> 别在 layout 里留活机位；动画一开做，改机位就是返工。</li></ul></section><section><h2>延伸</h2><p><strong>10 分钟练习：</strong>用 24 fps 画 3 个关键帧，只改“在文件头写版本号”，导出 2 秒；如果重量仍读不出来，先加预备帧，不要加模糊。</p></section>
<h2>验收</h2><ul><li>机位、角色比例、资产版本三项都锁死并有版本号。</li><li>文件头能看到版本和依赖，动画师不用猜。</li><li>动画段没有擅自改机位，最终镜头和 layout 一致。</li></ul>

<!-- SOURCES_START -->
## 参考与延伸阅读

- [S62] [Blender：官方手册](https://docs.blender.org/manual/en/latest/) — 2026-11-26 访问。用于核对「Layout 先定“摄影机与地面”」一节的术语/方法/规则（Blender 官方手册，不是行业流程标准）；不核对其中由本页经验得出的数字、型号与现场结论，也不替代测试。
- [S59] [Adobe：After Effects 官方指南](https://helpx.adobe.com/after-effects/user-guide.html) — 2026-11-26 访问。用于核对「Layout：把“镜头”变成可交接的空间」一节的术语/方法/规则（After Effects 官方指南，不是合成美学结论）；不核对其中由本页经验得出的数字、型号与现场结论，也不替代测试。
<!-- SOURCES_END -->

