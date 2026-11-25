---
id: tools.calculator.aspect-calculator
site: tools
type: calculator
lang: zh
translation_key: tools.calculator.aspect-calculator
translation_status: source
title: 画幅比计算器：裁切与安全区
summary: 画幅比计算器先算裁切后的有效像素，再定安全区；竖屏不是横屏两边裁掉。
slug: aspect-calculator
aliases:
- aspect-calculator
canonical_site: tools
canonical_path: /article/aspect-calculator/
status: published
diagram: /images/diagrams/zh/aspect-calculator.svg
diagram_alt: 画幅比计算器：裁切与安全区的结构示意图。
diagram_caption: 看“4K 16:9 裁 9:16 只剩约…”和“先确认像素够不够”两处，判断这个参数能不能对应到一个具体的拍摄问题。
difficulty: beginner
stage: field-note
format: handbook
authors:
- TVCN 工具组
last_verified: '2026-11-25'
review_due: '2027-05-25'
related:
- tools.calculator.subtitle-cps.en
- tools.calculator.budget-calculator.en
- tools.calculator.bitrate-calculator.en
source_kind: experience
---

<p>画幅比 = 宽 ÷ 高 。把 16:9 裁成 9:16 时，能保留的宽度 = 原高 × 9 ÷ 16；例如 3840×2160 裁成 9:16，保留 1215×2160，左右各丢约 1312 像素。</p>
<!-- DIAGRAM_START -->
<h2>图解</h2>
<figure>
  <img src="/images/diagrams/zh/aspect-calculator.svg" alt="画幅比计算器：裁切与安全区的结构示意图。">
  <figcaption>看“4K 16:9 裁 9:16 只剩约…”和“先确认像素够不够”两处，判断这个参数能不能对应到一个具体的拍摄问题。</figcaption>
</figure>
<!-- DIAGRAM_END -->
<section><h2 id="section-1">公式与安全区</h2><p>画幅比 = <strong>宽 ÷ 高</strong>。把 16:9 裁成 9:16 时，能保留的宽度 = 原高 × 9 ÷ 16；例如 3840×2160 裁成 9:16，保留 1215×2160，左右各丢约 1312 像素。</p><h2 id="section-2">三种常见转换</h2><ul><li>16:9 → 1:1：保留 2160×2160，左右各丢 840 像素。</li><li>16:9 → 4:5：保留 1728×2160，左右各丢 1056 像素。</li><li>9:16 竖屏拍时，把主体放在中间 1080 宽的安全区，不要贴边。</li></ul><h2 id="section-3">边界</h2><p>裁切不是重新构图；重要动作和字幕要放在安全区内。不同平台还会再裁一次，交付前用平台预览核对。</p></section><section><h2 id="section-4">现场</h2><p>4K 16:9 裁 9:16 只剩约 1215×2160，先确认像素够；安全区按平台重画。</p></section><section><h2 id="section-5">怎么做</h2><ol><li>4K 16:9 裁 9:16 只剩约 1215×2160。</li><li>先确认像素够不够。</li><li>安全区按平台重画。</li></ol></section><section><h2 id="section-6">别踩</h2><p>别把横屏直接裁成竖屏；有效像素掉一半，特写会糊。</p></section><section class="calc-widget" data-calculator="aspect-calculator">
<h2 id="section-7">比例裁切计算器</h2>
<p class="calc-lede">按目标比例从原图内最大裁切，输出保留像素与裁切比例。</p>
<div class="calc-grid"><label class="calc-field"><span>原片宽（px）</span><input type="number" inputmode="decimal" data-calc="width" data-default="3840" value="3840" step="1" min="1"></label><label class="calc-field"><span>原片高（px）</span><input type="number" inputmode="decimal" data-calc="height" data-default="2160" value="2160" step="1" min="1"></label><label class="calc-field"><span>目标比例</span><select data-calc="ratio" data-default="9:16"><option value="1:1">1:1 方图</option><option value="4:5">4:5 竖版</option><option value="9:16" selected>9:16 全屏</option><option value="16:9">16:9 横版</option><option value="2.35:1">2.35:1 宽银幕</option></select></label></div>
<div class="calc-output" aria-live="polite"><strong data-out="result">裁切 —</strong><span data-out="detail">先保主体，再裁边；不要从中间硬切。</span></div>
<div class="calc-actions"><button type="button" data-reset>恢复默认</button></div>
<p class="calc-formula">比较原片与目标比例：偏宽则裁宽，偏窄则裁高；保留另一边的全部像素。</p>
<noscript><p class="calc-noscript">JavaScript 关闭时按公式手算；3840×2160 转 9:16 保留 1215×2160。</p></noscript>
</section><script src="/assets/calculators.js" defer></script><section><h2>替代</h2><p>如果“4K 16:9 裁 9:16 只剩约…”不是你的主问题，先用“先确认像素够不够”对应的基础做法；两项都成立再考虑升级。</p></section><section><h2>60 秒自测</h2><p>用现有器材按“4K 16:9 裁 9:16 只剩约…”做一次 60 秒测试，记下一个数字；数字没有变化，就不要加预算。</p></section>
<h2>验收</h2><ul><li>裁切后的有效像素有数字，约 1215×2160。</li><li>像素满足交付要求，不靠放大补。</li><li>安全区按竖屏平台重新画过，不是沿用横屏。</li></ul>
