---
id: context.history.ai-video-history
site: context
type: history
lang: zh
translation_key: context.history.ai-video-history
translation_status: source
title: AI 影像前史：从滤镜到生成
summary: AI 影像不是从生成视频开始；滤镜、修复、抠像、换脸，每一步都在训练“自动修改画面”。
slug: ai-video-history
aliases:
- ai-video-history
canonical_site: context
canonical_path: /article/ai-video-history/
status: published
diagram: /images/diagrams/zh/ai-video-history.svg
diagram_alt: AI 影像前史：从滤镜到生成的结构示意图。
diagram_caption: 看“按滤镜、修复、抠像、换脸、生成排时间…”和“每一步标出“人还能控制什么””两处，判断它替代了什么旧办法，又新增了什么限制。
difficulty: beginner
stage: field-note
format: handbook
deep_minutes: 8
depth: deep
authors:
- TVCN 研究组
sources:
- S19
- S20
last_verified: '2026-11-26'
review_due: '2027-02-26'
related: [context.literacy.algorithm-feed, context.history.animation.animation-history, formats.documentary.documentary-template]
source_kind: sourced
---
<p>AI 影像不是从生成开始的。它先经过滤镜、风格迁移、超分、抠像和补帧，最后才进入文生视频。每一步都在把“后期修复”变成“前期生成”，也把作者、授权和证据问题推到台前。</p>
<!-- DIAGRAM_START -->
<h2>图解</h2>
<figure>
  <img src="/images/diagrams/zh/ai-video-history.svg" alt="AI 影像前史：从滤镜到生成的结构示意图。">
  <figcaption>看“按滤镜、修复、抠像、换脸、生成排时间…”和“每一步标出“人还能控制什么””两处，判断它替代了什么旧办法，又新增了什么限制。</figcaption>
</figure>
<!-- DIAGRAM_END -->
<section><h2 id="section-2">今天怎么用</h2><ul><li>做 AI 项目时，先记录模型、版本、提示词、参考素材和输出位置，像管理实拍素材一样管理生成素材。</li><li>把 AI 用在空镜、背景、补插和概念图；主角正脸、新闻现场和证词不要用生成替代。</li><li>研究 AI 史时，把算法、算力、版权和平台政策一起看，不要只看 Demo。</li></ul><h2 id="section-3">不要误用</h2><p>不要把“生成”当成“无来源”。没有授权链和版本记录的素材，不进商单交付。</p></section><section><h2 id="section-4">现场</h2><p>从滤镜、修复、抠像到生成，关键变化是可控性；prompt 不是导演。</p></section><section><h2 id="section-5">怎么做</h2><ol><li>按滤镜、修复、抠像、换脸、生成排时间线。</li><li>每一步标出“人还能控制什么”。</li><li>看 prompt 能控制什么、不能控制什么。</li></ol></section><section><h2 id="section-6">别踩</h2><p>别把 prompt 当导演；它给的是概率，不是调度。</p></section><section><h2>来源边界</h2><p>这是解释，不是原始档案；关键年份、人物和法律条文回到 <a href="../../about/">SOURCES.md</a> 的原始链接复核。二手叙述只能当线索，不能当证据。</p></section>
<h2>验收</h2><ul><li>时间线从滤镜、修复、抠像、换脸排到生成。</li><li>每一步都标出人类剩余的控制点。</li><li>能说出 prompt 控制不了的一项，比如精确走位或连续性。</li></ul>

<!-- DEEP_DIVE_START -->
## 深读
<p><strong>约 8 分钟。</strong> 这一节不重复前面的做法，只补三个东西：两种条件、一个反例、一个可复用模型；读完能判断什么时候换做法。</p>
### 条件 A：滤镜/自动剪辑
<p>AI 影像前史不是从生成开始，是从“自动处理”开始：滤镜、稳定、降噪、自动剪辑、风格迁移。这些工具先改变了“后期做什么”，再改变“拍摄做什么”。滤镜让颜色不再是现场事实，自动剪辑让节奏不再是人工选择。</p><p>自动处理的核心是“可预测”：给一个输入，工具按规则输出。它不创作，它执行。理解这一点，才能分清今天的“生成”与昨天的“处理”：生成改变素材，处理改变素材的样子。</p>
### 条件 B：生成/合成
<p>生成模型把“素材”变成“采样”：不是拍到一个东西，是从概率分布里取出一个像它的东西。这带来两个新问题：一致性（同一个角色能不能跨镜头保持）和控制（导演能不能指定动作/镜头/光）。历史上前期是控制问题，今天还是控制问题。</p><p>AI 影像的历史不是一条“越来越真”的线，是一条“控制越来越细”的线：从滤镜的全局参数，到局部遮罩，到关键帧，到镜头/动作/光分别控制。真实感只是副产品，控制才是主线。</p>
### 反例：把 AI 当成全新
<p>“AI 让视频从零到一”是常见的说法。但自动调色、自动剪辑、风格迁移已经存在几十年；生成只是把“选择”换成了“采样”，把“参数”换成了“提示”。说全新，会漏掉前面的控制和伦理问题。</p><p>修法不是否定生成，而是把它放进谱系：处理 → 合成 → 生成。每一阶段都带来新的控制问题，也继承旧的版权/真实性/劳动问题。新工具不等于新问题。</p>
### 可复用模型
<p><strong>自动化 → 表征 → 控制。</strong> 自动化解决“重复劳动”，表征解决“像不像”，控制解决“听不听话”。三段历史，今天仍在同时发生。</p><p>评价一个 AI 影像工具，问三个问题：它自动化了什么、它表征了什么、它能控制到什么粒度。三个答案清楚，工具才有位置；只有一个“很真”，通常还不够。</p>
<!-- DEEP_DIVE_END -->

<!-- SOURCES_START -->
## 参考与延伸阅读

- [S19] [GAN 原始论文（2014）](https://arxiv.org/abs/1406.2661) — 2026-11-26 访问。用于核对「今天怎么用」一节的术语/方法/规则（GAN 原始论文，不是产品评测）；不核对其中由本页经验得出的数字、型号与现场结论，也不替代测试。
- [S20] [DDPM 原始论文（2020）](https://arxiv.org/abs/2006.11239) — 2026-11-26 访问。用于核对「不要误用」一节的术语/方法/规则（DDPM 原始论文，不是产品评测）；不核对其中由本页经验得出的数字、型号与现场结论，也不替代测试。
<!-- SOURCES_END -->

