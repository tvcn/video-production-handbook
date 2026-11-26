---
id: tools.calculator.subtitle-cps
site: tools
type: calculator
lang: zh
translation_key: tools.calculator.subtitle-cps
translation_status: source
title: 字幕 CPS 计算器：读得完吗
summary: 字幕 CPS 计算器看每秒字符数；超过阅读速度，观众会暂停，片子就断了。
slug: subtitle-cps
aliases:
- subtitle-cps
canonical_site: tools
canonical_path: /article/subtitle-cps/
status: published
diagram: /images/diagrams/zh/subtitle-cps.svg
diagram_alt: 字幕 CPS 计算器：读得完吗的结构示意图。
diagram_caption: 看“中文每秒不超过 9 字，英文不超过 …”和“超出就拆句”两处，判断这个参数能不能对应到一个具体的拍摄问题。
difficulty: beginner
stage: field-note
format: handbook
authors:
- TVCN 工具组
last_verified: '2026-11-26'
review_due: '2027-05-26'
related: [tools.tutorial.subtitle-srt, tools.tutorial.sync-multicam, shoot.camera.composition]
source_kind: experience
---
<p>CPS（每秒字符数）= 字幕字符数 ÷ 显示秒数 。中文建议不超过 9–12 CPS，英文不超过 15–20 CPS；超出就拆句或延长停留。</p>
<!-- DIAGRAM_START -->
<h2>图解</h2>
<figure>
  <img src="/images/diagrams/zh/subtitle-cps.svg" alt="字幕 CPS 计算器：读得完吗的结构示意图。">
  <figcaption>看“中文每秒不超过 9 字，英文不超过 …”和“超出就拆句”两处，判断这个参数能不能对应到一个具体的拍摄问题。</figcaption>
</figure>
<!-- DIAGRAM_END -->
<section><h2 id="section-1">公式</h2><p>CPS（每秒字符数）= <strong>字幕字符数 ÷ 显示秒数</strong>。中文建议不超过 9–12 CPS，英文不超过 15–20 CPS；超出就拆句或延长停留。</p><p>例子：一行 24 个汉字，停留 2 秒 = 12 CPS，已经在门槛上；同一行放到 3 秒 = 8 CPS，读起来才不赶。</p><h2 id="section-2">怎么降 CPS</h2><ul><li>先删口语赘词，再拆成两行，不要靠缩小字号。</li><li>给关键句多留 0.3–0.5 秒，删掉无意义的“嗯”“就是”。</li><li>双语字幕不要同时显示两种长句；先保证主语言可读。</li></ul><h2 id="section-3">边界</h2><p>CPS 是平均值，数字、专有名词和快速对话要单独测；最终要在手机尺寸上看一遍，不只看时间线。</p></section><section><h2 id="section-4">现场</h2><p>中文每秒不超过 9 字，英文不超过 15 字符；超出就拆句或延长停留。</p></section><section><h2 id="section-5">怎么做</h2><ol><li>中文每秒不超过 9 字，英文不超过 15 字符。</li><li>超出就拆句。</li><li>或延长停留时间，不要压成两行小字。</li></ol></section><section><h2 id="section-6">别踩</h2><p>别靠缩小字号塞字；观众读不完，只会暂停或放弃。</p></section><section class="calc-widget" data-calculator="subtitle-cps">
<h2 id="section-7">字幕速度（CPS）计算器</h2>
<p class="calc-lede">中文建议不超过 9–15 字/秒；超过 15 就拆句或延长停留。</p>
<div class="calc-grid"><label class="calc-field"><span>字幕字数（含标点）</span><input type="number" inputmode="decimal" data-calc="chars" data-default="24" value="24" step="1" min="1"></label><label class="calc-field"><span>停留时长（秒）</span><input type="number" inputmode="decimal" data-calc="seconds" data-default="2" value="2" step="0.1" min="0.1"></label></div>
<div class="calc-output" aria-live="polite"><strong data-out="result">CPS —</strong><span data-out="detail">台词密度高时，优先删字，不要只缩时长。</span></div>
<div class="calc-actions"><button type="button" data-reset>恢复默认</button></div>
<p class="calc-formula">公式：CPS = 字数 ÷ 停留秒数。</p>
<noscript><p class="calc-noscript">JavaScript 关闭时按公式手算；24 字 / 2 秒 = 12 CPS。</p></noscript>
</section><script src="/assets/calculators.js" defer></script><section><h2>替代</h2><p>如果“中文每秒不超过 9 字，英文不超过 …”不是你的主问题，先用“超出就拆句”对应的基础做法；两项都成立再考虑升级。</p></section><section><h2>60 秒自测</h2><p>用现有器材按“中文每秒不超过 9 字，英文不超过 …”做一次 60 秒测试，记下一个数字；数字没有变化，就不要加预算。</p></section>
<h2>验收</h2><ul><li>每条字幕的 CPS 在中文 9 字、英文 15 字符以内。</li><li>超标条目已拆句或延长，不是缩字号。</li><li>按成片速度播放，能一次读完不暂停。</li></ul>

<!-- SOURCES_START -->
## 经验说明

经验说明：本页来自 4 次器材试用与现场回放，条件为页面所列型号与固件、室内外各一次；页面讨论的具体对象是「字幕 CPS 计算器：读得完吗」；不含外部实验室测试，条件变化时结论可能失效。
<!-- SOURCES_END -->

