---
id: tools.calculator.storage-calculator
site: tools
type: calculator
lang: zh
translation_key: tools.calculator.storage-calculator
translation_status: source
title: 存储时长计算器：卡能录多久
summary: 存储计算器按码率、时长和备份份数算空间；卡能录多久，不要靠相机剩余时间。
slug: storage-calculator
aliases:
- storage-calculator
canonical_site: tools
canonical_path: /article/storage-calculator/
status: published
diagram: /images/diagrams/zh/storage-calculator.svg
diagram_alt: 存储时长计算器：卡能录多久的结构示意图。
diagram_caption: 看“4K 100 Mbps 约 45 G…”和“再加两份备份，总量乘三”两处，判断这个参数能不能对应到一个具体的拍摄问题。
difficulty: beginner
stage: field-note
format: handbook
authors:
- TVCN 工具组
last_verified: '2026-11-25'
review_due: '2027-05-25'
related:
- tools.calculator.bitrate-calculator.en
- tools.calculator.dof-calculator.en
- tools.calculator.nd-calculator.en
source_kind: experience
---

<p>可录时长（分钟）≈ 容量（GB）× 8 × 1000 ÷ 码率（Mbps）÷ 60 。这是按十进制 GB 算的上限，实际要留 10%–15% 给格式化、音频和末尾文件。</p>
<!-- DIAGRAM_START -->
<h2>图解</h2>
<figure>
  <img src="/images/diagrams/zh/storage-calculator.svg" alt="存储时长计算器：卡能录多久的结构示意图。">
  <figcaption>看“4K 100 Mbps 约 45 G…”和“再加两份备份，总量乘三”两处，判断这个参数能不能对应到一个具体的拍摄问题。</figcaption>
</figure>
<!-- DIAGRAM_END -->
<section><h2 id="section-1">公式</h2><p>可录时长（分钟）≈ <strong>容量（GB）× 8 × 1000 ÷ 码率（Mbps）÷ 60</strong>。这是按十进制 GB 算的上限，实际要留 10%–15% 给格式化、音频和末尾文件。</p><p>例子：128 GB 卡、200 Mbps：128 × 8 × 1000 ÷ 200 ÷ 60 ≈ 85 分钟。按 80% 安全线，只规划 68 分钟。</p><h2 id="section-2">现场表</h2><ul><li>100 Mbps：128 GB ≈ 170 分钟；256 GB ≈ 341 分钟。</li><li>200 Mbps：128 GB ≈ 85 分钟；256 GB ≈ 170 分钟。</li><li>400 Mbps：128 GB ≈ 42 分钟；256 GB ≈ 85 分钟。</li></ul><h2 id="section-3">边界</h2><p>卡的实际可用容量、文件系统和相机缓存都会影响结果；长时间录制还要看过热和卡速，不要用“能录多久”替代现场测试。</p></section><section><h2 id="section-4">现场</h2><p>4K 100 Mbps 约 45 GB 一小时；再加两份备份，卡至少留 20% 余量。</p></section><section><h2 id="section-5">怎么做</h2><ol><li>4K 100 Mbps 约 45 GB 一小时。</li><li>再加两份备份，总量乘三。</li><li>卡至少留 20% 余量。</li></ol></section><section><h2 id="section-6">别踩</h2><p>别信相机剩余时间；它按当前码率估，换格式就全错。</p></section><section class="calc-widget" data-calculator="storage-calculator">
<h2 id="section-7">存储计算器</h2>
<p class="calc-lede">按十进制 GB（1GB=8000 Mb）估算；实际格式化容量和录制开销会更少。</p>
<div class="calc-grid"><label class="calc-field"><span>卡容量（GB）</span><input type="number" inputmode="decimal" data-calc="capacity" data-default="128" value="128" step="1" min="1"></label><label class="calc-field"><span>录制码率（Mbps）</span><input type="number" inputmode="decimal" data-calc="bitrate" data-default="200" value="200" step="1" min="1"></label><label class="calc-field"><span>预留安全空间（%）</span><input type="number" inputmode="decimal" data-calc="safety" data-default="10" value="10" step="1" min="0"></label></div>
<div class="calc-output" aria-live="polite"><strong data-out="result">可录 —</strong><span data-out="detail">长时间录制还要考虑电池、分段和卡速。</span></div>
<div class="calc-actions"><button type="button" data-reset>恢复默认</button></div>
<p class="calc-formula">公式：分钟 = 容量GB × 8000 ÷ 码率Mbps ÷ 60 × (1 − 安全比例)。</p>
<noscript><p class="calc-noscript">JavaScript 关闭时按公式手算；128GB、200Mbps、留 10% 约 76 分钟。</p></noscript>
</section><script src="/assets/calculators.js" defer></script><section><h2>替代</h2><p>如果“4K 100 Mbps 约 45 G…”不是你的主问题，先用“再加两份备份，总量乘三”对应的基础做法；两项都成立再考虑升级。</p></section><section><h2>60 秒自测</h2><p>用现有器材按“4K 100 Mbps 约 45 G…”做一次 60 秒测试，记下一个数字；数字没有变化，就不要加预算。</p></section>
<h2>验收</h2><ul><li>码率、时长、备份份数三项都填了真实值。</li><li>算出的总量包含三份拷贝和 20% 余量。</li><li>结果写进现场检查单，不靠相机剩余时间。</li></ul>
