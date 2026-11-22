---
id: ai.generation.negative-prompt
site: ai
type: article
lang: zh
translation_key: ai.generation.negative-prompt
translation_status: source
title: "负面约束：先排除什么"
summary: "负面约束先排掉最破坏画面的东西：闪烁、多指、文字乱码、脸部变形。"
slug: negative-prompt
aliases: [negative-prompt]
canonical_site: ai
canonical_path: /generation/negative-prompt/
status: published
diagram: /images/diagrams/zh/negative-prompt.svg
diagram_alt: "负面约束：先排除什么 三步图解"
diagram_caption: "把三步按顺序做完，再回看画面或文件。"
difficulty: beginner
stage: field-note
format: handbook
authors: [editor]
last_verified: 2026-11-20
review_due: 2027-05-20
related: [main.paths.first-film]
---

<p>负面约束先排掉最破坏画面的东西：闪烁、多指、文字乱码、脸部变形。</p>
<!-- DIAGRAM_START -->
<h2>图解</h2>
<figure>
  <img src="/images/diagrams/zh/negative-prompt.svg" alt="负面约束：先排除什么 三步图解">
  <figcaption>把三步按顺序做完，再回看画面或文件。</figcaption>
</figure>
<!-- DIAGRAM_END -->
<h2>现场</h2>
<p>先列四类：闪烁、多指、文字乱码、脸变形；每类写一个负面词，别堆 50 个。</p>
<h2>怎么做</h2>
<p>负面约束先排掉最破坏画面的东西：闪烁、多指、文字乱码、脸部变形。</p><ol><li>先列四类：闪烁、多指、文字乱码、脸变形。</li><li>每类只写一个负面词，别堆 50 个。</li><li>跑三次，确认负面词真的减少了这一类问题。</li></ol>
<h2>别踩</h2>
<p>别堆一长串负面词；互相冲突的约束会让模型更乱。</p>
<h2>验收</h2>
<ul><li>负面词只覆盖四类问题，每条都能对应一个可见错误。</li><li>三次输出里该类问题明显减少，不是心理作用。</li><li>删掉某条负面词后问题回来，证明它真的有用。</li></ul>
