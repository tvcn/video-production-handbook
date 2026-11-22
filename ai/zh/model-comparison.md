---
id: ai.ethics.model-comparison
site: ai
type: article
lang: zh
translation_key: ai.ethics.model-comparison
translation_status: source
title: "模型对比：按镜头类型测"
summary: "模型对比别只看总排名，按你的镜头类型测：人脸、手、运动、文字、长镜头。"
slug: model-comparison
aliases: [model-comparison]
canonical_site: ai
canonical_path: /ethics/model-comparison/
status: published
diagram: /images/diagrams/zh/model-comparison.svg
diagram_alt: "模型对比：按镜头类型测 三步图解"
diagram_caption: "把三步按顺序做完，再回看画面或文件。"
difficulty: beginner
stage: field-note
format: handbook
authors: ["TVCN AI 组"]
last_verified: 2026-11-20
review_due: 2027-05-20
related: [main.paths.first-film]
sources: [S04, S05, S19, S20]
test_context: "复核环境：Windows 11 + Chrome 131；公开网页版/API 与 2026-11 版本；模型版本会变。"
known_failures: "已知失败：模型/接口版本变化；同一提示词多次输出不一致；平台水印与标识规则会更新。"
verified: 2026-11-22
---

<p>模型对比别只看总排名，按你的镜头类型测：人脸、手、运动、文字、长镜头。</p>
<!-- DIAGRAM_START -->
<h2>图解</h2>
<figure>
  <img src="/images/diagrams/zh/model-comparison.svg" alt="模型对比：按镜头类型测 三步图解">
  <figcaption>把三步按顺序做完，再回看画面或文件。</figcaption>
</figure>
<!-- DIAGRAM_END -->
<h2>现场</h2>
<p>用同一条 5 秒提示、同一张参考图测五个模型；每个模型跑三次，记录人脸、手、文字、运动四项。</p>
<h2>怎么做</h2>
<p>模型对比别只看总排名，按你的镜头类型测：人脸、手、运动、文字、长镜头。</p><ol><li>用同一条 5 秒提示、同一张参考图测五个模型。</li><li>每个模型跑三次，记录人脸、手、文字、运动四项。</li><li>按你的项目权重打分，不看排行榜总名次。</li></ol>
<h2>别踩</h2>
<p>别用总排名选模型；你的镜头类型才是评分表。</p>
<h2>验收</h2>
<ul><li>五个模型用的是同一条提示和同一张参考图。</li><li>每个模型跑三次，人脸、手、文字、运动都有记录。</li><li>最终排序按项目权重，不是按排行榜总名次。</li></ul>
<!-- SOURCES_START -->
<h2>参考与延伸阅读</h2>
<p class="source-types">经验来源：TVCN 现场手册与项目复盘；实测来源：页面标注的复核环境与可复现练习；参考来源：以下公开链接。</p>
<ul><li><span class="mono">[S04]</span> 《生成式人工智能服务管理暂行办法》</li><li><span class="mono">[S05]</span> 欧盟 AI Act 政策页</li><li><span class="mono">[S19]</span> GAN 原始论文（2014）</li><li><span class="mono">[S20]</span> DDPM 原始论文（2020）</li></ul>
<p><a href="../../SOURCES.md">完整链接与用途见 SOURCES.md</a></p>
<!-- SOURCES_END -->
