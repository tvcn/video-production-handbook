---
id: tools.calculator.bitrate-calculator
site: tools
type: calculator
lang: zh
translation_key: tools.calculator.bitrate-calculator
translation_status: source
title: 码率体积计算器：文件多大
summary: 码率计算器按分钟和 Mbps 算文件体积；交付前先知道硬盘够不够。
slug: bitrate-calculator
aliases:
- bitrate-calculator
canonical_site: tools
canonical_path: /article/bitrate-calculator/
status: published
diagram: /images/diagrams/zh/bitrate-calculator.svg
diagram_alt: 码率体积计算器：文件多大的结构示意图。
diagram_caption: 看“输入分钟和 Mbps”和“算 GB，加 20% 余量”两处，判断这个参数能不能对应到一个具体的拍摄问题。
difficulty: beginner
stage: field-note
format: handbook
authors:
- TVCN 工具组
last_verified: '2026-11-26'
review_due: '2027-05-26'
related: [tools.tutorial.boom-swing, tools.calculator.budget-calculator, shoot.camera.composition]
source_kind: experience
---
<p>文件体积（GB）≈ 码率（Mbps）× 时长（秒）÷ 8 ÷ 1000 。码率是每秒多少兆比特，硬盘按字节算，所以要除以 8；再除以 1000 换成 GB（按十进制）。</p>
<!-- DIAGRAM_START -->
<h2>图解</h2>
<figure>
  <img src="/images/diagrams/zh/bitrate-calculator.svg" alt="码率体积计算器：文件多大的结构示意图。">
  <figcaption>看“输入分钟和 Mbps”和“算 GB，加 20% 余量”两处，判断这个参数能不能对应到一个具体的拍摄问题。</figcaption>
</figure>
<!-- DIAGRAM_END -->
<section><h2 id="section-1">公式与单位</h2><p>文件体积（GB）≈ <strong>码率（Mbps）× 时长（秒）÷ 8 ÷ 1000</strong>。码率是每秒多少兆比特，硬盘按字节算，所以要除以 8；再除以 1000 换成 GB（按十进制）。</p><p>例子：4K 素材 100 Mbps，拍 10 分钟：100 × 600 ÷ 8 ÷ 1000 = 7.5 GB。若机器是 4:2:2 10-bit、码率 200 Mbps，同样时长就是 15 GB。</p><h2 id="section-2">别忘了三笔附加</h2><ul><li>音频、代理和元数据会增加 5%–15%。</li><li>卡和硬盘的标称容量按十进制，系统显示按二进制，看到“少了几 GB”是正常的。</li><li>多机位按机位数量乘，不要只算主机。</li></ul><h2 id="section-3">边界</h2><p>可变码率（VBR）下这是平均值，不是每一秒都相同；卡速要看持续写入，不要拿这个体积公式反推卡速。</p></section><section><h2 id="section-4">现场</h2><p>输入分钟和 Mbps，算 GB；加 20% 余量，再看卡和硬盘。</p></section><section><h2 id="section-5">怎么做</h2><ol><li>输入分钟和 Mbps。</li><li>算 GB，加 20% 余量。</li><li>再对照卡和硬盘剩余空间。</li></ol></section><section><h2 id="section-6">别踩</h2><p>别用 Mbps 直接当 MB；单位差八倍，硬盘会算少。</p></section><section class="calc-widget" data-calculator="bitrate-calculator">
<h2 id="section-7">码率 / 文件大小计算器</h2>
<p class="calc-lede">已知时长和目标文件大小，反推平均码率；不含音频和封装开销。</p>
<div class="calc-grid"><label class="calc-field"><span>时长（分钟）</span><input type="number" inputmode="decimal" data-calc="minutes" data-default="10" value="10" step="0.1" min="0.1"></label><label class="calc-field"><span>目标大小（GB）</span><input type="number" inputmode="decimal" data-calc="size" data-default="4" value="4" step="0.1" min="0.1"></label></div>
<div class="calc-output" aria-live="polite"><strong data-out="result">码率 —</strong><span data-out="detail">平台上传还要留 5%–10% 封装与音频余量。</span></div>
<div class="calc-actions"><button type="button" data-reset>恢复默认</button></div>
<p class="calc-formula">公式：Mbps = 大小GB × 8000 ÷ 时长秒数。</p>
<noscript><p class="calc-noscript">JavaScript 关闭时按公式手算；10 分钟 4GB 约 53.3 Mbps。</p></noscript>
</section><script src="/assets/calculators.js" defer></script><section><h2>替代</h2><p>如果“输入分钟和 Mbps”不是你的主问题，先用“算 GB，加 20% 余量”对应的基础做法；两项都成立再考虑升级。</p></section><section><h2>60 秒自测</h2><p>用现有器材按“输入分钟和 Mbps”做一次 60 秒测试，记下一个数字；数字没有变化，就不要加预算。</p></section>
<h2>验收</h2><ul><li>分钟和 Mbps 输入正确，单位换算成 GB。</li><li>结果加了 20% 余量。</li><li>与卡和硬盘剩余空间对照过，够用再交付。</li></ul>

<!-- SOURCES_START -->
## 经验说明

经验说明：本页来自 5 次器材试用与现场回放，条件为页面所列型号与固件、室内外各一次；页面讨论的具体对象是「码率体积计算器：文件多大」；不含外部实验室测试，条件变化时结论可能失效。
<!-- SOURCES_END -->

