---
id: shoot.live.live-encoding
site: shoot
type: article
lang: zh
translation_key: shoot.live.live-encoding
translation_status: source
title: "直播编码：码率、推流、备份"
summary: "直播编码先算上行带宽，再定码率；永远留一条本地录制备份。"
slug: live-encoding
aliases: [live-encoding]
canonical_site: shoot
canonical_path: /live/live-encoding/
status: published
diagram: /images/diagrams/zh/live-encoding.svg
diagram_alt: "直播编码：码率、推流、备份 三步图解"
diagram_caption: "把三步按顺序做完，再回看画面或文件。"
difficulty: beginner
stage: field-note
format: handbook
authors: [editor]
last_verified: 2026-11-20
review_due: 2027-05-20
related: [main.paths.first-film]
---

<p>直播编码先算上行带宽，再定码率；永远留一条本地录制备份。</p>
<!-- DIAGRAM_START -->
<h2>图解</h2>
<figure>
  <img src="/images/diagrams/zh/live-encoding.svg" alt="直播编码：码率、推流、备份 三步图解">
  <figcaption>把三步按顺序做完，再回看画面或文件。</figcaption>
</figure>
<!-- DIAGRAM_END -->
<h2>现场</h2>
<p>先测上传速度：要达到目标码率的 1.5 倍才留得出余量。设主推流和热点备份，同时本地录一份高码率。</p>
<h2>怎么做</h2>
<p>直播编码先算上行带宽，再定码率；永远留一条本地录制备份。</p><ol><li>测上传速度，目标码率的 1.5 倍才安全。</li><li>设主推流、热点备份，同时本地录一份高码率。</li><li>彩排一次断网切换，记录断流时间和恢复步骤。</li></ol>
<h2>别踩</h2>
<p>别只推一路、别把直播当一次性；断流比画质差更致命。</p>
<h2>验收</h2>
<ul><li>上行带宽至少是目标码率的 1.5 倍，余量有记录。</li><li>主推流断掉时，热点备份和本地录制都还能工作。</li><li>彩排记录里能查到断流时间、原因和恢复用了多久。</li></ul>
