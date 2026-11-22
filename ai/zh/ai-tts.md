---
id: ai.audio.ai-tts
site: ai
type: article
lang: zh
translation_key: ai.audio.ai-tts
translation_status: source
title: "AI 配音：断句与重音"
summary: "AI 配音先把断句、重音、停顿写进文本，再选音色；音色救不了错误断句。"
slug: ai-tts
aliases: [ai-tts]
canonical_site: ai
canonical_path: /audio/ai-tts/
status: published
diagram: /images/diagrams/zh/ai-tts.svg
diagram_alt: "AI 配音：断句与重音 三步图解"
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

<p>AI 配音先把断句、重音、停顿写进文本，再选音色；音色救不了错误断句。</p>
<!-- DIAGRAM_START -->
<h2>图解</h2>
<figure>
  <img src="/images/diagrams/zh/ai-tts.svg" alt="AI 配音：断句与重音 三步图解">
  <figcaption>把三步按顺序做完，再回看画面或文件。</figcaption>
</figure>
<!-- DIAGRAM_END -->
<h2>现场</h2>
<p>把台词改成短句，逗号处停 300 毫秒，句号停 600 毫秒；数字写成中文，缩写展开，再生成。</p>
<h2>怎么做</h2>
<p>AI 配音先把断句、重音、停顿写进文本，再选音色；音色救不了错误断句。</p><ol><li>把台词改成短句，逗号处停 300 毫秒，句号停 600 毫秒。</li><li>数字写成中文，缩写展开，重音标在关键词上。</li><li>生成后用手机外放听一遍，检查齿音、尾音和重音。</li></ol>
<h2>别踩</h2>
<p>别只用耳机听；手机外放会暴露齿音和尾音问题。</p>
<h2>验收</h2>
<ul><li>逗号和句号的停顿能听出来，断句没有连成一串。</li><li>数字和缩写都读对了，重音落在关键词上。</li><li>手机外放听一遍，齿音不刺、尾音不吞、重音不歪。</li></ul>
<!-- SOURCES_START -->
<h2>参考与延伸阅读</h2>
<p class="source-types">经验来源：TVCN 现场手册与项目复盘；实测来源：页面标注的复核环境与可复现练习；参考来源：以下公开链接。</p>
<ul><li><span class="mono">[S04]</span> 《生成式人工智能服务管理暂行办法》</li><li><span class="mono">[S05]</span> 欧盟 AI Act 政策页</li><li><span class="mono">[S19]</span> GAN 原始论文（2014）</li><li><span class="mono">[S20]</span> DDPM 原始论文（2020）</li></ul>
<p><a href="../../SOURCES.md">完整链接与用途见 SOURCES.md</a></p>
<!-- SOURCES_END -->
