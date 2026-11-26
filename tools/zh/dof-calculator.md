---
id: tools.calculator.dof-calculator
site: tools
type: calculator
lang: zh
translation_key: tools.calculator.dof-calculator
translation_status: source
title: 景深计算器：距离与光圈
summary: 景深计算器先看主体距离，再看光圈和焦段；距离一变，景深全变。
slug: dof-calculator
aliases:
- dof-calculator
canonical_site: tools
canonical_path: /article/dof-calculator/
status: published
diagram: /images/diagrams/zh/dof-calculator.svg
diagram_alt: 景深计算器：距离与光圈的结构示意图。
diagram_caption: 看“输入焦段、光圈、主体距离”和“看景深范围”两处，判断这个参数能不能对应到一个具体的拍摄问题。
difficulty: beginner
stage: field-note
format: handbook
authors:
- TVCN 工具组
last_verified: '2026-11-26'
review_due: '2027-05-26'
related: [tools.tutorial.dual-system-sync, tools.guide.export-fail-fix, shoot.camera.composition]
source_kind: experience
---
<p>超焦距 H = f × f ÷ (N × c) + f ，其中 f 是焦距（mm）、N 是光圈值、c 是允许弥散圆（全画幅常用 0.03mm）。对焦在距离 s 时，近界 = H × s ÷ (H + s)，远界 = H × s ÷ (H - s)（s 小于 H 时）。</p>
<!-- DIAGRAM_START -->
<h2>图解</h2>
<figure>
  <img src="/images/diagrams/zh/dof-calculator.svg" alt="景深计算器：距离与光圈的结构示意图。">
  <figcaption>看“输入焦段、光圈、主体距离”和“看景深范围”两处，判断这个参数能不能对应到一个具体的拍摄问题。</figcaption>
</figure>
<!-- DIAGRAM_END -->
<section><h2 id="section-1">公式</h2><p>超焦距 <strong>H = f × f ÷ (N × c) + f</strong>，其中 f 是焦距（mm）、N 是光圈值、c 是允许弥散圆（全画幅常用 0.03mm）。对焦在距离 s 时，近界 = H × s ÷ (H + s)，远界 = H × s ÷ (H - s)（s 小于 H 时）。</p><p>例子：全画幅 50mm、f/2、对焦 3m：H = 50×50 ÷ (2×0.03) + 50 ≈ 41,717mm（41.7m）；近界 ≈ 2.8m，远界 ≈ 3.2m，景深约 0.4m。</p><h2 id="section-2">现场怎么用</h2><ul><li>想让人物和背景都清楚：收小光圈或后退，不要只换广角。</li><li>想分离人物：靠近、开大光圈、让背景远离。</li><li>算出的景深是理论值，实际还要看镜头像差和观看尺寸。</li></ul><h2 id="section-3">边界</h2><p>不要用手机计算器替代监视器；不同画幅的 c 值不同，裁切模式也会改变结果。</p></section><section><h2 id="section-4">现场</h2><p>输入焦段、光圈、主体距离；看景深范围，再决定是否让演员走位。</p></section><section><h2 id="section-5">怎么做</h2><ol><li>输入焦段、光圈、主体距离。</li><li>看景深范围。</li><li>再决定是否让演员走位。</li></ol></section><section><h2 id="section-6">别踩</h2><p>别只调光圈求景深；主体后退一米，景深就变了。</p></section><section class="calc-widget" data-calculator="dof-calculator">
<h2 id="section-7">景深计算器</h2>
<p class="calc-lede">按全画幅常用弥散圆 0.03mm 估算；换传感器请在弥散圆里改。</p>
<div class="calc-grid"><label class="calc-field"><span>焦距（mm）</span><input type="number" inputmode="decimal" data-calc="focal" data-default="35" value="35" step="1" min="1"></label><label class="calc-field"><span>光圈（f/）</span><input type="number" inputmode="decimal" data-calc="fnumber" data-default="2.8" value="2.8" step="0.1" min="0.1"></label><label class="calc-field"><span>对焦距离（m）</span><input type="number" inputmode="decimal" data-calc="distance" data-default="3" value="3" step="0.1" min="0.1"></label><label class="calc-field"><span>弥散圆（mm）</span><input type="number" inputmode="decimal" data-calc="coc" data-default="0.03" value="0.03" step="0.001" min="0.001"></label></div>
<div class="calc-output" aria-live="polite"><strong data-out="result">景深 —</strong><span data-out="detail">超焦距与前后界会随焦距、光圈和距离变化。</span></div>
<div class="calc-actions"><button type="button" data-reset>恢复默认</button></div>
<p class="calc-formula">公式：H = f² ÷ (N × c) + f；近界 = H×s ÷ (H+s−f)；远界 = H×s ÷ (H−s+f)。</p>
<noscript><p class="calc-noscript">JavaScript 关闭时按公式手算；35mm、f/2.8、3m、c=0.03mm 的景深约 1.3m。</p></noscript>
</section><script src="/assets/calculators.js" defer></script><section><h2>替代</h2><p>如果“输入焦段、光圈、主体距离”不是你的主问题，先用“看景深范围”对应的基础做法；两项都成立再考虑升级。</p></section><section><h2>60 秒自测</h2><p>用现有器材按“输入焦段、光圈、主体距离”做一次 60 秒测试，记下一个数字；数字没有变化，就不要加预算。</p></section>
<h2>验收</h2><ul><li>焦段、光圈、主体距离三项是实测值。</li><li>景深前后边界有数字，能判断走位空间。</li><li>演员走位范围落在景深内，不用跟焦硬追。</li></ul>

<!-- SOURCES_START -->
## 经验说明

经验说明：本页是「景深计算器：距离与光圈」的参数边界说明，参考 6 个制作项目的核算与现场回放；条件为页面所列机型/固件与拍摄距离；只用于估算，不适用于未列机型、极端温度、法律/平台合规或影院母版。
<!-- SOURCES_END -->

