---
id: shoot.live.live-encoding
site: shoot
type: article
lang: zh
translation_key: shoot.live.live-encoding
translation_status: source
title: 直播编码：码率、推流、备份
summary: 直播编码先算上行带宽，再定码率；永远留一条本地录制备份。
slug: live-encoding
aliases:
- live-encoding
canonical_site: shoot
canonical_path: /article/live-encoding/
status: published
diagram: /images/diagrams/zh/live-encoding.svg
diagram_alt: 直播编码：码率、推流、备份的结构示意图。
diagram_caption: 看“测上传速度，目标码率的 1.5 倍才…”和“设主推流、热点备份，同时本地录一份高…”两处，判断高光、肤色和声音有没有被同时保住。
difficulty: beginner
stage: field-note
format: handbook
authors:
- TVCN 拍摄组
last_verified: '2026-11-25'
review_due: '2027-05-25'
related:
- shoot.virtual-production.led-volume.en
- shoot.safety.permit.en
- shoot.multicam.multicam-sync.en
source_kind: experience
---

<p>码率按上传带宽的 70% 设，留余量；关键帧间隔 2 秒，音频 128–192 kbps。分辨率高但码率不够，运动画面会糊成块；宁可 720p 稳，不要 4K 卡。</p>
<!-- DIAGRAM_START -->
<h2>图解</h2>
<figure>
  <img src="/images/diagrams/zh/live-encoding.svg" alt="直播编码：码率、推流、备份的结构示意图。">
  <figcaption>看“测上传速度，目标码率的 1.5 倍才…”和“设主推流、热点备份，同时本地录一份高…”两处，判断高光、肤色和声音有没有被同时保住。</figcaption>
</figure>
<!-- DIAGRAM_END -->
<section><h2 id="section-1">直播先保“不断”，再保“好看”</h2><p>开播前测 10 分钟：丢帧、延迟、声音同步、备用网络。不要用主网络开播才发现上传不够。</p><h2 id="section-2">边界</h2><p>直播不是录播。不能靠后期补，所有信息要一次说清；字幕和图表要提前准备，不要现场找。</p></section><section><h2 id="section-3">现场</h2><p>先测上传速度：要达到目标码率的 1.5 倍才留得出余量。设主推流和热点备份，同时本地录一份高码率。</p></section><section><h2 id="section-4">怎么做</h2><ol><li>测上传速度，目标码率的 1.5 倍才安全。</li><li>设主推流、热点备份，同时本地录一份高码率。</li><li>彩排一次断网切换，记录断流时间和恢复步骤。</li></ol></section><section><h2 id="section-5">别踩</h2><p>别只推一路、别把直播当一次性；断流比画质差更致命。</p></section><section><h2>判断</h2><p>现场只认三个信号：</p><ul><li>高光没有死白，暗部仍保留可恢复的细节</li><li>同一条片子里肤色一致，切机位不跳</li><li>声音有独立音轨，不靠机头麦兜底</li></ul></section><section><h2>失败</h2><p>下面三种做法会让页面上的细节白做：</p><ul><li>曝光对了，但光没有方向，脸和背景粘在一起</li><li>声音只靠机头麦，现场一吵就废</li><li>机位越轴，观众失去空间方向</li></ul></section><section><h2>延伸</h2><p><strong>10 分钟练习：</strong>用同一扇窗拍三条 10 秒，只改“测上传速度，目标码率的 1.5 倍才…”；比较高光、肤色和背景，选一条能直接剪的。</p></section>
<h2>验收</h2><ul><li>上行带宽至少是目标码率的 1.5 倍，余量有记录。</li><li>主推流断掉时，热点备份和本地录制都还能工作。</li><li>彩排记录里能查到断流时间、原因和恢复用了多久。</li></ul>
