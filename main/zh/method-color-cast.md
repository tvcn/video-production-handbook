---
id: main.method.method-color-cast
site: main
type: template
lang: zh
translation_key: main.method.method-color-cast
translation_status: source
title: 颜色偏了
summary: 颜色偏先找白平衡和混合光，不要一上来调色轮；源头不对，越调越脏。
slug: method-color-cast
aliases:
- method-color-cast
canonical_site: main
canonical_path: /article/method-color-cast/
status: published
diagram: /images/diagrams/zh/method-color-cast.svg
diagram_alt: 颜色偏了的结构示意图。
diagram_caption: 看“用灰卡或白纸在每个光位拍一条，确认白…”和“关掉或统一混合光：窗光加 CTO/C…”两处，判断症状能不能被复述成一句可观察的话。
difficulty: beginner
stage: field-note
format: handbook
authors:
- TVCN 编辑部
last_verified: '2026-11-26'
review_due: '2027-05-26'
related: [main.method.method-continuity-break, main.method.method-crew-conflict, context.history.16mm]
source_kind: experience
---
<p>让一个人拿灰卡站在主体位置，拍一张；再把灰卡放到背景，拍一张。两张都按同一白平衡。如果灰卡在两张里不一致，先处理光源，不要先调色。</p>
<!-- DIAGRAM_START -->
<h2>图解</h2>
<figure>
  <img src="/images/diagrams/zh/method-color-cast.svg" alt="颜色偏了的结构示意图。">
  <figcaption>看“用灰卡或白纸在每个光位拍一条，确认白…”和“关掉或统一混合光：窗光加 CTO/C…”两处，判断症状能不能被复述成一句可观察的话。</figcaption>
</figure>
<!-- DIAGRAM_END -->
<section><h2 id="section-1">先判断偏色来自哪里</h2>
<ul><li><strong>白平衡：</strong>同一场景里白纸不白，先拍灰卡，再统一相机和灯。</li><li><strong>混合光：</strong>窗光偏蓝、实用灯偏黄，脸一半冷一半暖。先决定以哪一边为主，再用色纸或黑旗处理另一边。</li><li><strong>Log/监看：</strong>监看 LUT 和输出 LUT 不一致，现场看着对，导出偏绿。用同一套色彩管理，别在监看和输出之间换 LUT。</li></ul>
<h2 id="section-3">什么时候不要用 LUT 掩盖</h2>
<p>偏色来自光源或白平衡时，套 LUT 只会让肤色更脏。先把拍摄端统一，再在后期做风格。肤色不对，不要用“电影感”解释。</p></section><section><h2 id="section-4">现场</h2><p>先查白平衡和混合光；用灰卡对中性，再调色轮。</p></section><section><h2 id="section-5">怎么做</h2><ol><li>用灰卡或白纸在每个光位拍一条，确认白平衡。</li><li>关掉或统一混合光：窗光加 CTO/CTB，别让冷暖打架。</li><li>后期先对灰卡，再动色轮；只改偏色，不改风格。</li></ol></section><section><h2 id="section-6">别踩</h2><p>别用调色掩盖现场混合光；脸会一块青一块黄。</p></section><section><h2>边界</h2><p>本页只解决「颜色偏了」这一个问题；不替代 穿帮了、现场吵架、16mm：电影从影院走到教室。如果现场问题属于后者，先读对应页，不要在本页继续加参数。</p></section><section><h2>替代</h2><p>如果“用灰卡或白纸在每个光位拍一条，确认白平衡”不是你的主问题，先做“关掉或统一混合光：窗光加 CTO/CTB，别让冷暖打架”；两项都成立，再考虑升级。</p></section><section><h2>60 秒自测</h2><p>按验收第 1 条做一次 60 秒测试：每个光位都拍了灰卡或白纸。如果第 2 条“混合光已统一或关掉，冷暖不再打架”没有变化，就不要加设备或预算。</p></section>
<h2>验收</h2><ul><li>每个光位都拍了灰卡或白纸。</li><li>混合光已统一或关掉，冷暖不再打架。</li><li>后期对灰卡，肤色没有一块青一块黄。</li></ul>

<!-- SOURCES_START -->
## 经验说明

经验说明：本页来自 3 个单人或 2–3 人小组项目的现场复盘，预算与周期明确；只讨论「颜色偏了」的判断顺序，不含外部实验室测试；不适用于多机位、工会剧组、特技或高风险场景。
<!-- SOURCES_END -->

