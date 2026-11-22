---
id: post.color.color-management
site: post
type: article
lang: zh
translation_key: post.color.color-management
translation_status: source
title: "色彩管理：先管好输入输出"
summary: "色彩管理先定输入、时间线、输出三个空间，再谈监看和 LUT。"
slug: color-management
aliases: [color-management]
canonical_site: post
canonical_path: /color/color-management/
status: published
diagram: /images/diagrams/zh/color-management.svg
diagram_alt: "色彩管理：先管好输入输出 三步图解"
diagram_caption: "把三步按顺序做完，再回看画面或文件。"
difficulty: beginner
stage: field-note
format: handbook
authors: [editor]
last_verified: 2026-11-20
review_due: 2027-05-20
related: [main.paths.first-film]
---

<p>色彩管理先定输入、时间线、输出三个空间，再谈监看和 LUT。</p>
<!-- DIAGRAM_START -->
<h2>图解</h2>
<figure>
  <img src="/images/diagrams/zh/color-management.svg" alt="色彩管理：先管好输入输出 三步图解">
  <figcaption>把三步按顺序做完，再回看画面或文件。</figcaption>
</figure>
<!-- DIAGRAM_END -->
<h2>现场</h2>
<p>先确认素材是 S-Log3、HLG 还是 Rec.709，时间线设对应输入，输出 Rec.709 2.4；监看用校准 LUT。</p>
<h2>怎么做</h2>
<p>色彩管理先定输入、时间线、输出三个空间，再谈监看和 LUT。</p><ol><li>确认素材是 S-Log3、HLG 还是 Rec.709。</li><li>时间线设对应输入，输出 Rec.709 2.4。</li><li>监看用校准 LUT，交付前关掉 LUT 再看一遍。</li></ol>
<h2>别踩</h2>
<p>别用错的输入 LUT；色彩一错，后面所有匹配都是假的。</p>
<h2>验收</h2>
<ul><li>时间线输入与素材格式一一对应，没有把 Log 当 Rec.709。</li><li>输出空间和交付平台一致，示波器读数正常。</li><li>关掉监看 LUT 后，黑位和高光没有突然跳变。</li></ul>
