---
id: animation.3d.rigging
site: animation
type: article
lang: zh
translation_key: animation.3d.rigging
translation_status: source
title: "绑定：让关节能转"
summary: "绑定先让关节转得对，再让皮肤变形好看；转不动，权重再细也没用。"
slug: rigging
aliases: [rigging]
canonical_site: animation
canonical_path: /3d/rigging/
status: published
diagram: /images/diagrams/zh/rigging.svg
diagram_alt: "绑定：让关节能转 三步图解"
diagram_caption: "把三步按顺序做完，再回看画面或文件。"
difficulty: beginner
stage: field-note
format: handbook
authors: ["TVCN 动画组"]
last_verified: 2026-11-20
review_due: 2027-05-20
related: [main.paths.first-film]
sources: [S12, S28, S34]
test_context: "复核环境：Windows 11；Blender 4.x / After Effects 2025 公开流程；不声称所有版本一致。"
known_failures: "已知失败：插件/版本差异导致绑定或渲染失败；字体授权与素材版权需单独核对。"
verified: 2026-11-22
---

<p>绑定先让关节转得对，再让皮肤变形好看；转不动，权重再细也没用。</p>
<!-- DIAGRAM_START -->
<h2>图解</h2>
<figure>
  <img src="/images/diagrams/zh/rigging.svg" alt="绑定：让关节能转 三步图解">
  <figcaption>把三步按顺序做完，再回看画面或文件。</figcaption>
</figure>
<!-- DIAGRAM_END -->
<h2>现场</h2>
<p>先转肩、肘、膝三个关节，各拍 10 帧；如果网格塌陷，先调权重，不要加更多骨骼。</p>
<h2>怎么做</h2>
<p>绑定先让关节转得对，再让皮肤变形好看；转不动，权重再细也没用。</p><ol><li>先转肩、肘、膝三个关节，各拍 10 帧。</li><li>如果网格塌陷，先调权重，不要加更多骨骼。</li><li>三个关节都能转到极限再进动画。</li></ol>
<h2>别踩</h2>
<p>别用加骨骼解决塌陷；权重没调对，骨头越多越乱。</p>
<h2>验收</h2>
<ul><li>肩、肘、膝三个关节都能转到极限，网格没有塌陷。</li><li>塌陷处先调权重，不是靠加骨骼盖住。</li><li>十帧旋转回放，皮肤没有突然的撕裂或夹面。</li></ul>
<!-- SOURCES_START -->
<h2>参考与延伸阅读</h2>
<p class="source-types">经验来源：TVCN 现场手册与项目复盘；实测来源：页面标注的复核环境与可复现练习；参考来源：以下公开链接。</p>
<ul><li><span class="mono">[S12]</span> Britannica：动画</li><li><span class="mono">[S28]</span> Netflix 制作与交付帮助</li><li><span class="mono">[S34]</span> Adobe Premiere Pro 用户指南</li></ul>
<p><a href="../../SOURCES.md">完整链接与用途见 SOURCES.md</a></p>
<!-- SOURCES_END -->
