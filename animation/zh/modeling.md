---
id: animation.3d.modeling
site: animation
type: article
lang: zh
translation_key: animation.3d.modeling
translation_status: source
title: 建模：面数与轮廓
summary: 建模先看轮廓，再看面数；轮廓不对，细分再多也不像。
slug: modeling
aliases:
- modeling
canonical_site: animation
canonical_path: /article/modeling/
status: published
diagram: /images/diagrams/zh/modeling.svg
diagram_alt: 建模：面数与轮廓的结构示意图。
diagram_caption: 看“先看剪影：把模型全黑渲染”和“轮廓能认出角色再细分”两处，判断前景、中景、背景的速度差能不能在一次移动里看出来。
difficulty: beginner
stage: field-note
format: handbook
authors:
- TVCN 动画组
last_verified: '2026-11-25'
review_due: '2027-05-25'
related:
- animation.3d.materials.en
- animation.3d.lighting-3d.en
- animation.2d.2d-camera.en
source_kind: experience
---

<p>先看剪影：把模型填成纯黑，还能认出角色吗？再看厚度：边缘有没有倒角、关节有没有体积。剪影不对，细节再多也认不出。</p>
<!-- DIAGRAM_START -->
<h2>图解</h2>
<figure>
  <img src="/images/diagrams/zh/modeling.svg" alt="建模：面数与轮廓的结构示意图。">
  <figcaption>看“先看剪影：把模型全黑渲染”和“轮廓能认出角色再细分”两处，判断前景、中景、背景的速度差能不能在一次移动里看出来。</figcaption>
</figure>
<!-- DIAGRAM_END -->
<section><h2 id="section-1">建模先保“剪影”和“厚度”</h2><p>从大块面开始，逐步加边；不要一上来做毛孔。每加一次细节，退回剪影检查。</p><h2 id="section-2">边界</h2><p>面数不是精度。该圆的地方圆、该硬的地方硬；面数堆在看不见的地方，只会拖慢渲染。</p><h2 id="section-3">建模：先剪影，再拓扑，最后 UV</h2>
<p>模型的第一验收标准不是“面数”，是剪影。把模型放进纯黑背景，如果轮廓不能说明它是什么，拓扑再干净也没用。</p>
<div class="table-scroll"><table class="data-table"><thead><tr><th>阶段</th><th>检查</th><th>返工代价</th></tr></thead><tbody>
<tr><td>剪影</td><td>正面/侧面/背面各看一次</td><td>低，改大型</td></tr>
<tr><td>拓扑</td><td>关节环线、弯曲测试</td><td>中，重布线</td></tr>
<tr><td>UV</td><td>接缝位置、纹理密度</td><td>高，重展 UV</td></tr>
<tr><td>细节</td><td>倒角、磨损、凹凸</td><td>最高，烘培后才发现</td></tr>
</tbody></table></div>
<h3>项目级检查</h3>
<ol><li>先做 blockout，确认比例和镜头关系，再进拓扑；不要在错误比例上雕细节。</li><li>关节处至少 3 圈环线，肘、膝、肩单独测试弯曲，不靠平滑修改器硬撑。</li><li>UV 接缝藏在不显眼的位置，纹理密度用棋盘格统一；一个模型多个 UV 集要命名。</li><li>倒角放在最后，但不要晚于烘培；烘培后再加倒角，法线会对不上。</li></ol>
<p>如果模型只出现 2 秒且不特写，不要做全流程高模；用中模 + 法线贴图，把时间给镜头。</p></section><section><h2 id="section-4">现场</h2><p>先看剪影：把模型全黑渲染，轮廓能认出角色再细分；面数按镜头距离分配。</p></section><section><h2 id="section-5">怎么做</h2><ol><li>先看剪影：把模型全黑渲染。</li><li>轮廓能认出角色再细分。</li><li>面数按镜头距离分配，近景多、远景少。</li></ol></section><section><h2 id="section-6">别踩</h2><p>别用细分救轮廓；剪影不对，面数再多也不像。</p></section><section><h2>判断</h2><p>现场只认三个信号：</p><ul><li>前景、中景、背景的速度差能在一次 pan 里看出来</li><li>动作在 0.5 秒内能读出重量或预备</li><li>关掉任意一层，空间感仍然成立</li></ul></section><section><h2>失败</h2><p>下面三种做法会让页面上的细节白做：</p><ul><li>层数堆上去了，但每层速度一样，空间还是扁的</li><li>动作有预备却没有跟随，重量只做了一半</li><li>资产没锁就进渲染，返工从合成端一路补</li></ul></section><section><h2>延伸</h2><p><strong>10 分钟练习：</strong>用 24 fps 画 3 个关键帧，只改“轮廓能认出角色再细分”，导出 2 秒；如果重量仍读不出来，先加预备帧，不要加模糊。</p></section>
<h2>验收</h2><ul><li>全黑剪影能认出角色，不靠颜色和纹理。</li><li>轮廓确认后才细分，没有先堆面数。</li><li>近景面数高于远景，预算按镜头距离分配。</li></ul>
