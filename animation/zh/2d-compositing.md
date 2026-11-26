---
id: animation.2d.2d-compositing
site: animation
type: article
lang: zh
translation_key: animation.2d.2d-compositing
translation_status: source
title: 二维合成：背景、前景、光
summary: 二维合成把背景、人物、光效分层；全压在一张图里，改一个动作就要重画全部。
slug: 2d-compositing
aliases:
- 2d-compositing
canonical_site: animation
canonical_path: /article/2d-compositing/
status: published
diagram: /images/diagrams/zh/2d-compositing.svg
diagram_alt: 二维合成：背景、前景、光的结构示意图。
diagram_caption: 看“背景、角色、前景、光效分四层”和“每层单独调色，别把影子画在角色层”两处，判断前景、中景、背景的速度差能不能在一次移动里看出来。
difficulty: beginner
stage: field-note
format: handbook
authors:
- TVCN 动画组
last_verified: '2026-11-26'
review_due: '2027-02-26'
related: [animation.3d.3d-pipeline, animation.pipeline.animatic-pipeline, formats.documentary.documentary-template]
source_kind: sourced
sources:
- S63
- S62
- S59

---
<p>二维合成最容易露馅的是线宽和颜色不一致。先统一线稿粗细、抗锯齿和色阶，再谈光影；每个图层单独调，不要全局加滤镜。</p>
<!-- DIAGRAM_START -->
<h2>图解</h2>
<figure>
  <img src="/images/diagrams/zh/2d-compositing.svg" alt="二维合成：背景、前景、光的结构示意图。">
  <figcaption>看“背景、角色、前景、光效分四层”和“每层单独调色，别把影子画在角色层”两处，判断前景、中景、背景的速度差能不能在一次移动里看出来。</figcaption>
</figure>
<!-- DIAGRAM_END -->
<section><h2 id="section-1">合成先对齐“线”和“色”</h2><p>用一张对比图检查：前景和背景的黑色是否一样黑、白色是否一样白；不一样，观众会觉得贴上去。</p><h2 id="section-2">边界</h2><p>合成不是加特效。特效再多，线和对不齐仍然假；先把基础层对齐。</p><h2 id="section-3">二维合成：先修边，再调色，最后加光</h2>
<p>合成的问题通常不是“效果不够”，而是顺序错了。先调色再修边，会把边缘的颜色差一起放大；先加光再修边，光会盖住接缝。正确顺序是：清理素材 → 修边 → 色彩统一 → 光效 → 输出。</p>
<div class="table-scroll"><table class="data-table"><thead><tr><th>步骤</th><th>检查</th><th>失败信号</th></tr></thead><tbody>
<tr><td>修边</td><td>1:1 像素看边缘</td><td>白边、黑边、锯齿</td></tr>
<tr><td>色彩</td><td>同一场景的皮肤/天空</td><td>前景比背景偏暖或偏绿</td></tr>
<tr><td>光效</td><td>光源方向一致</td><td>光晕穿过遮挡物</td></tr>
<tr><td>输出</td><td>不同尺寸各看一遍</td><td>小尺寸边缘消失，大尺寸接缝明显</td></tr>
</tbody></table></div>
<h3>项目级检查</h3>
<ol><li>把每个元素单独开关，做一张“元素清单”；缺一个影子或接触阴影，画面就浮。</li><li>修边用最小参数，多次轻修，不要一次拉满；拉满会把细节吃掉。</li><li>色彩统一先看中性灰，再看肤色；只靠眼睛在彩色背景上判断会偏。</li><li>光效层放在最上，但要用遮罩挡住前景物体；否则光会穿墙。</li></ol>
<p>交付前让另一个人看 10 秒，只问“哪里浮”。自己盯久了会看不见接缝。</p></section><section><h2 id="section-4">现场</h2><p>背景、角色、前景、光效分四层；每层单独调色，别把影子画在角色层。</p></section><section><h2 id="section-5">怎么做</h2><ol><li>背景、角色、前景、光效分四层。</li><li>每层单独调色，别把影子画在角色层。</li><li>合成时先对位置，再对光和影。</li></ol></section><section><h2 id="section-6">别踩</h2><p>别把所有东西画在一层；改一笔就要重画全图。</p></section><section><h2>判断</h2><p>这一页的判断只看三条可观察的验收，不靠口号：</p><ul><li><strong>1.</strong> 背景、角色、前景、光效四层分开，文件结构清楚。</li><li><strong>2.</strong> 影子在独立层，没有画死在角色身上。</li><li><strong>3.</strong> 改角色动作时只动角色层，背景和光效不用重画。</li></ul></section><section><h2>失败</h2><p>下面任一条出现，先停，不要靠后期补：</p><ul><li><strong>1.</strong> 只做到“背景、角色、前景、光效四层分开，文件结构清楚”的形式，换一个机位或场景就重现不了。</li><li><strong>2.</strong> 把“影子在独立层，没有画死在角色身上”留到后期或口头解释，现场没有留下能复查的记录。</li><li><strong>3.</strong> 别把所有东西画在一层；改一笔就要重画全图。</li></ul></section><section><h2>延伸</h2><p><strong>10 分钟练习：</strong>用 24 fps 画 3 个关键帧，只改“每层单独调色，别把影子画在角色层”，导出 2 秒；如果重量仍读不出来，先加预备帧，不要加模糊。</p></section>
<h2>验收</h2><ul><li>背景、角色、前景、光效四层分开，文件结构清楚。</li><li>影子在独立层，没有画死在角色身上。</li><li>改角色动作时只动角色层，背景和光效不用重画。</li></ul>

<!-- SOURCES_START -->
## 参考与延伸阅读

- [S63] [Toon Boom：官方文档](https://docs.toonboom.com/) — 2026-11-26 访问。用于核对「二维合成：先修边，再调色，最后加光」一节的术语/方法/规则（Toon Boom 官方文档，不是行业流程标准）；不核对其中由本页经验得出的数字、型号与现场结论，也不替代测试。
- [S62] [Blender：官方手册](https://docs.blender.org/manual/en/latest/) — 2026-11-26 访问。用于核对「合成先对齐“线”和“色”」一节的术语/方法/规则（Blender 官方手册，不是行业流程标准）；不核对其中由本页经验得出的数字、型号与现场结论，也不替代测试。
- [S59] [Adobe：After Effects 官方指南](https://helpx.adobe.com/after-effects/user-guide.html) — 2026-11-26 访问。用于核对「现场」一节的术语/方法/规则（After Effects 官方指南，不是合成美学结论）；不核对其中由本页经验得出的数字、型号与现场结论，也不替代测试。
<!-- SOURCES_END -->

