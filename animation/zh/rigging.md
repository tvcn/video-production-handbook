---
id: animation.3d.rigging
site: animation
type: article
lang: zh
translation_key: animation.3d.rigging
translation_status: source
title: 绑定：让关节能转
summary: 绑定先让关节转得对，再让皮肤变形好看；转不动，权重再细也没用。
slug: rigging
aliases:
- rigging
canonical_site: animation
canonical_path: /article/rigging/
status: published
diagram: /images/diagrams/zh/rigging.svg
diagram_alt: 绑定：让关节能转的结构示意图。
diagram_caption: 看“先转肩、肘、膝三个关节，各拍 10 …”和“如果网格塌陷，先调权重，不要加更多骨…”两处，判断前景、中景、背景的速度差能不能在一次移动里看出来。
difficulty: beginner
stage: field-note
format: handbook
authors:
- TVCN 动画组
last_verified: '2026-11-26'
review_due: '2027-02-26'
related: [animation.2d.run-cycle, animation.stop-motion.stop-motion, formats.documentary.documentary-template]
sources:
- S62
- S59
test_context: 复核环境：Windows 11；Blender 4.x / After Effects 2025 公开流程；不声称所有版本一致。
known_failures: 已知失败：插件/版本差异导致绑定或渲染失败；字体授权与素材版权需单独核对。
verified: 2026-11-22
source_kind: sourced
---
<p>绑定先保证三个基本动作：肘和膝能单向弯、肩能抬起、头能转。每个关节设限位，再做权重测试；不要先加几十根控制棒。</p>
<!-- DIAGRAM_START -->
<h2>图解</h2>
<figure>
  <img src="/images/diagrams/zh/rigging.svg" alt="绑定：让关节能转的结构示意图。">
  <figcaption>看“先转肩、肘、膝三个关节，各拍 10 …”和“如果网格塌陷，先调权重，不要加更多骨…”两处，判断前景、中景、背景的速度差能不能在一次移动里看出来。</figcaption>
</figure>
<!-- DIAGRAM_END -->
<section><h2 id="section-1">关节能转，权重不撕</h2><p>用极限姿势测试：抬手过头、深蹲、转身。看腋下、膝盖和胯部是否撕裂；撕裂处先修权重，不要用修正形态硬盖。</p><h2 id="section-2">边界</h2><p>绑定不是越复杂越专业。一个能稳定完成片中动作的简单骨架，胜过一个功能多但每次都炸的复杂 rig。</p></section><section><h2 id="section-3">现场</h2><p>先转肩、肘、膝三个关节，各拍 10 帧；如果网格塌陷，先调权重，不要加更多骨骼。</p></section><section><h2 id="section-4">怎么做</h2><ol><li>先转肩、肘、膝三个关节，各拍 10 帧。</li><li>如果网格塌陷，先调权重，不要加更多骨骼。</li><li>三个关节都能转到极限再进动画。</li></ol></section><section><h2 id="section-5">别踩</h2><p>别用加骨骼解决塌陷；权重没调对，骨头越多越乱。</p></section><section><h2>判断</h2><p>这一页的判断只看三条可观察的验收，不靠口号：</p><ul><li><strong>1.</strong> 肩、肘、膝三个关节都能转到极限，网格没有塌陷。</li><li><strong>2.</strong> 塌陷处先调权重，不是靠加骨骼盖住。</li><li><strong>3.</strong> 十帧旋转回放，皮肤没有突然的撕裂或夹面。</li></ul></section><section><h2>失败</h2><p>下面任一条出现，先停，不要靠后期补：</p><ul><li><strong>1.</strong> 只做到“肩、肘、膝三个关节都能转到极限，网格没有塌陷”的形式，换一个机位或场景就重现不了。</li><li><strong>2.</strong> 把“塌陷处先调权重，不是靠加骨骼盖住”留到后期或口头解释，现场没有留下能复查的记录。</li><li><strong>3.</strong> 别用加骨骼解决塌陷；权重没调对，骨头越多越乱。</li></ul></section><section><h2>延伸</h2><p><strong>10 分钟练习：</strong>用 24 fps 画 3 个关键帧，只改“如果网格塌陷，先调权重，不要加更多骨…”，导出 2 秒；如果重量仍读不出来，先加预备帧，不要加模糊。</p></section>
<h2>验收</h2><ul><li>肩、肘、膝三个关节都能转到极限，网格没有塌陷。</li><li>塌陷处先调权重，不是靠加骨骼盖住。</li><li>十帧旋转回放，皮肤没有突然的撕裂或夹面。</li></ul>

<!-- SOURCES_START -->
## 参考与延伸阅读

- [S62] [Blender：官方手册](https://docs.blender.org/manual/en/latest/) — 2026-11-26 访问。用于核对「关节能转，权重不撕」一节的术语/方法/规则（Blender 官方手册，不是行业流程标准）；不核对其中由本页经验得出的数字、型号与现场结论，也不替代测试。
- [S59] [Adobe：After Effects 官方指南](https://helpx.adobe.com/after-effects/user-guide.html) — 2026-11-26 访问。用于核对「现场」一节的术语/方法/规则（After Effects 官方指南，不是合成美学结论）；不核对其中由本页经验得出的数字、型号与现场结论，也不替代测试。
<!-- SOURCES_END -->

