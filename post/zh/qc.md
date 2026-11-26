---
id: post.delivery.qc
site: post
type: article
lang: zh
translation_key: post.delivery.qc
translation_status: source
title: 技术检查：黑帧、静帧、断音
summary: 技术检查按清单看：黑帧、静帧、断音、字幕越界、声道错位。
slug: qc
aliases:
- qc
canonical_site: post
canonical_path: /article/qc/
status: published
diagram: /images/diagrams/zh/qc.svg
diagram_alt: 技术检查：黑帧、静帧、断音的结构示意图。
diagram_caption: 看“按清单过：黑帧、静帧、断音、字幕出画…”和“用校准监视器和耳机看听，不用笔记本喇…”两处，判断剪掉一个镜头后，节奏是更快还是更乱。
difficulty: beginner
stage: field-note
format: handbook
authors:
- TVCN 后期组
last_verified: '2026-11-26'
review_due: '2027-02-26'
related: [post.sound.room-tone, post.vfx.rotoscoping, shoot.camera.composition]
source_kind: sourced
sources:
- S28
- S29
- S13
- S29
---
<p>别用笔记本喇叭判断声音；低频和断音你都听不到。</p>
<!-- DIAGRAM_START -->
<h2>图解</h2>
<figure>
  <img src="/images/diagrams/zh/qc.svg" alt="技术检查：黑帧、静帧、断音的结构示意图。">
  <figcaption>看“按清单过：黑帧、静帧、断音、字幕出画…”和“用校准监视器和耳机看听，不用笔记本喇…”两处，判断剪掉一个镜头后，节奏是更快还是更乱。</figcaption>
</figure>
<!-- DIAGRAM_END -->
<section><h2 id="section-1">现场</h2><p>按清单过：黑帧、静帧、断音、字幕出画、声道左右；用校准监视器看，不用笔记本喇叭判断。</p></section><section><h2 id="section-2">怎么做</h2><p>把这件事拆成现场能检查的动作。</p><ol><li>按清单过：黑帧、静帧、断音、字幕出画、声道左右。</li><li>用校准监视器和耳机看听，不用笔记本喇叭判断。</li><li>发现问题标时间码，回到母版修，不在平台版上补。</li></ol></section><section></section><section><h2 id="section-4">QC 清单</h2><p>按交付规格过一遍：分辨率、帧率、时长、声道、响度、字幕、安全框、文件命名。不要只看画面；声音和字幕是最容易漏的两项。</p><ol><li>黑帧/静帧：从片头到片尾 1x 速度过一遍，记录时间码。</li><li>断音/爆音：用耳机听，不是看波形；检查左右声道和相位。</li><li>字幕：检查出画、错字、换行、时间轴、强制字幕。</li></ol></section><section><h2 id="section-5">过片顺序</h2><ol><li>先 conform，确认时间线和母版一致；不要拿平台压缩版做 QC。</li><li>再全片 1x 播放，遇到问题立刻标时间码和帧号。</li><li>最后用示波器/校准监视器/耳机复查；笔记本喇叭只做参考。</li></ol><p>QC 不是抽查，是整片过；一次只看 10 分钟，休息后再看，避免注意力疲劳。</p></section><section><h2 id="section-6">最容易漏的</h2><ol><li>笔记本喇叭听不出低频和断音；必须用耳机或监听。</li><li>只看平台预览，不看母版；平台会重编码，问题被掩盖。</li><li>字幕只检查第一屏；后面越界、错字、时间轴漂移没看到。</li><li>声道左右反了，耳机听不出来；要看相位表或单声道检查。</li></ol></section><section><h2 id="section-7">QC 记录</h2><ul><li>每个问题有时间码、帧号、类型、修复状态；修完再回看同一位置。</li><li>黑帧、静帧、断音、字幕、声道、响度六项都有 pass/fail。</li><li>用校准监视器和耳机复查，不用笔记本喇叭做最终判断。</li><li>记录母版文件名、交付版本、QC 人和日期；平台版不代替母版。</li></ul></section><section><h2 id="section-8">交付记录</h2><p>交付前记：母版文件名、时长、分辨率、帧率、响度、字幕版本、QC 人和日期。平台上传版另存，不覆盖母版；发现问题回到母版修。</p></section><section><h2>判断</h2><p>这一页的判断只看三条可观察的验收，不靠口号：</p><ul><li><strong>1.</strong> 黑帧、静帧和断音都按时间码标出并修掉。</li><li><strong>2.</strong> 字幕没有出画，声道左右正确。</li><li><strong>3.</strong> 用校准监视器和耳机复查，笔记本喇叭不作为依据。</li></ul></section><section><h2>失败</h2><p>下面任一条出现，先停，不要靠后期补：</p><ul><li><strong>1.</strong> 只做到“黑帧、静帧和断音都按时间码标出并修掉”的形式，换一个机位或场景就重现不了。</li><li><strong>2.</strong> 把“字幕没有出画，声道左右正确”留到后期或口头解释，现场没有留下能复查的记录。</li><li><strong>3.</strong> 第 3 条验收“用校准监视器和耳机复查，笔记本喇叭不作为依据”没人复核，交片时才发现。</li></ul></section><section><h2>延伸</h2><p><strong>10 分钟练习：</strong>拿一段 30 秒素材做 A/B，只改“按清单过：黑帧、静帧、断音、字幕出画…”；记下一个时间码和一处差异，再决定是否保留。</p></section>
<h2>验收</h2><ul><li>黑帧、静帧和断音都按时间码标出并修掉。</li><li>字幕没有出画，声道左右正确。</li><li>用校准监视器和耳机复查，笔记本喇叭不作为依据。</li></ul>

<section><h2>边界</h2><p>本页只解决「技术检查：黑帧、静帧、断音」这一个问题；不替代 环境音：别让画面住在真空里、遮罩：一笔一笔跟、构图：先让观众知道看哪里。如果现场问题属于后者，先读对应页，不要在本页继续加参数。</p></section>
<!-- SOURCES_START -->
## 参考与延伸阅读

- [S28] [Netflix：合作伙伴帮助](https://partnerhelp.netflixstudios.com/) — 2026-11-26 访问。用于核对「交付记录」一节的术语/方法/规则（Netflix 交付帮助，不是通用平台规则）；不核对其中由本页经验得出的数字、型号与现场结论，也不替代测试。
- [S29] [YouTube：上传编码建议](https://support.google.com/youtube/answer/1722171) — 2026-11-26 访问。用于核对「现场」一节的术语/方法/规则（YouTube 上传编码建议，不是创作标准）；不核对其中由本页经验得出的数字、型号与现场结论，也不替代测试。
- [S13] [DCI：数字电影系统规范](https://www.dcimovies.com/dci-specification/) — 2026-11-26 访问。用于核对「怎么做」一节的术语/方法/规则（DCI 数字电影规范，不是流媒体上传规则）；不核对其中由本页经验得出的数字、型号与现场结论，也不替代测试。
<!-- SOURCES_END -->

