---
id: animation.3d.lighting-3d
site: animation
type: article
lang: zh
translation_key: animation.3d.lighting-3d
translation_status: source
title: 三维灯光：三点与 HDRI
summary: 三维灯光先用主光、补光、轮廓光定结构，再用 HDRI 补环境；顺序反了，空间会平。
slug: lighting-3d
aliases:
- lighting-3d
canonical_site: animation
canonical_path: /article/lighting-3d/
status: published
diagram: /images/diagrams/zh/lighting-3d.svg
diagram_alt: 三维灯光：三点与 HDRI的结构示意图。
diagram_caption: 看“先关 HDRI，只用主光看形体”和“再加补光和轮廓光”两处，判断前景、中景、背景的速度差能不能在一次移动里看出来。
difficulty: beginner
stage: field-note
format: handbook
authors:
- TVCN 动画组
last_verified: '2026-11-26'
review_due: '2027-05-26'
related: [animation.2d.loop-cycle, animation.3d.materials, formats.documentary.documentary-template]
source_kind: experience
---
<p>三维灯光不是把场景照亮。先定一个主光方向，让影子说明空间；再用环境光和补光控制反差。材质再真，光位错了也会像贴图。</p>
<!-- DIAGRAM_START -->
<h2>图解</h2>
<figure>
  <img src="/images/diagrams/zh/lighting-3d.svg" alt="三维灯光：三点与 HDRI的结构示意图。">
  <figcaption>看“先关 HDRI，只用主光看形体”和“再加补光和轮廓光”两处，判断前景、中景、背景的速度差能不能在一次移动里看出来。</figcaption>
</figure>
<!-- DIAGRAM_END -->
<section><h2 id="section-1">3D 灯光先定“主光方向”，再谈材质</h2><p>每加一盏灯，问它替代了现实里的什么光源；答不出，就删。灯光层要能单独关闭，方便对比。</p><h2 id="section-2">边界</h2><p>HDRI 不是万能。室内、夜景和强方向光需要手动补灯；只靠环境贴图，画面会平、影子会散。</p><h2 id="section-3">三维灯光：先定主光，再谈氛围</h2>
<p>三维灯光最常见的错误是“先加 atmosphere，再补主光”。体积雾、辉光和景深会把方向感吃掉。顺序应该是：主光 → 补光 → 轮廓 → 环境 → 氛围。</p>
<div class="table-scroll"><table class="data-table"><thead><tr><th>层</th><th>作用</th><th>检查</th></tr></thead><tbody>
<tr><td>主光</td><td>决定时间与方向</td><td>阴影是否朝同一方向</td></tr>
<tr><td>补光</td><td>控制反差</td><td>暗部是否有细节但不发灰</td></tr>
<tr><td>轮廓</td><td>分离主体与背景</td><td>边缘是否过曝</td></tr>
<tr><td>环境</td><td>提供反射与天光</td><td>HDRI 是否与场景匹配</td></tr>
</tbody></table></div>
<h3>项目级检查</h3>
<ol><li>先关掉所有氛围层，只留主光看剪影；剪影不成立，氛围救不了。</li><li>用同一套灯光 rig 覆盖所有镜头，单镜头特殊灯要记录原因。</li><li>反射和折射单独渲一层，后期可调；全部烘进 beauty 会锁死。</li><li>输出前看10% 灰和肤色，不看“亮不亮”；曝光以中间调为准。</li></ol>
<p>如果渲染时间不够，先减氛围层，不要减主光采样；主光噪声会毁掉整个镜头。</p></section><section><h2 id="section-4">现场</h2><p>先关 HDRI，只用主光看形体；再加补光、轮廓光；最后开 HDRI 到 20% 到 30% 补环境。</p></section><section><h2 id="section-5">怎么做</h2><ol><li>先关 HDRI，只用主光看形体。</li><li>再加补光和轮廓光。</li><li>最后开 HDRI 到 20% 到 30% 补环境。</li></ol></section><section><h2 id="section-6">别踩</h2><p>别一上来就开 HDRI；环境光一盖，形体就看不清了。</p></section><section><h2>判断</h2><p>现场只认三个信号：</p><ul><li>前景、中景、背景的速度差能在一次 pan 里看出来</li><li>动作在 0.5 秒内能读出重量或预备</li><li>关掉任意一层，空间感仍然成立</li></ul></section><section><h2>失败</h2><p>下面三种做法会让页面上的细节白做：</p><ul><li>层数堆上去了，但每层速度一样，空间还是扁的</li><li>动作有预备却没有跟随，重量只做了一半</li><li>资产没锁就进渲染，返工从合成端一路补</li></ul></section><section><h2>延伸</h2><p><strong>10 分钟练习：</strong>用 24 fps 画 3 个关键帧，只改“再加补光和轮廓光”，导出 2 秒；如果重量仍读不出来，先加预备帧，不要加模糊。</p></section>
<h2>验收</h2><ul><li>关 HDRI 时，主光已经能把形体打出来。</li><li>补光和轮廓光各司其职，没有把主光打平。</li><li>HDRI 只占 20% 到 30%，没有抢走主光。</li></ul>

<!-- SOURCES_START -->
## 经验说明

经验说明：本页来自 6 次动画镜头与资产交接复盘，条件为2D/3D 混合管线之一、镜头不超过 30 秒；页面讨论的具体对象是「三维灯光：三点与 HDRI」；不含外部实验室测试，条件变化时结论可能失效。
<!-- SOURCES_END -->

