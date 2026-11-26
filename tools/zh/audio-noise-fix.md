---
id: tools.guide.audio-noise-fix
site: tools
type: article
lang: zh
translation_key: tools.guide.audio-noise-fix
translation_status: source
title: 底噪排查：从房间开始
summary: 底噪排查从房间开始：关空调、关灯、换插座、换线；最后才怪麦克风。
slug: audio-noise-fix
aliases:
- audio-noise-fix
canonical_site: tools
canonical_path: /article/audio-noise-fix/
status: published
diagram: /images/diagrams/zh/audio-noise-fix.svg
diagram_alt: 底噪排查：从房间开始的结构示意图。
diagram_caption: 看“关空调、冰箱和灯，录三十秒静音”和“换插座、换线，把增益放在录音机”两处，判断这个参数能不能对应到一个具体的拍摄问题。
difficulty: beginner
stage: field-note
format: handbook
authors:
- TVCN 工具组
last_verified: '2026-11-26'
review_due: '2027-05-26'
related: [tools.audio.audio-position, tools.tutorial.backup-3-2-1, shoot.camera.composition]
source_kind: experience
---
<p>噪声分三类：持续底噪（空调、风扇）、间歇噪声（关门、车）、人声瑕疵（齿音、喷麦）。持续底噪可以降噪；间歇噪声要剪掉或重录；齿音用 EQ 和 de-ess，不要全局降噪。</p>
<!-- DIAGRAM_START -->
<h2>图解</h2>
<figure>
  <img src="/images/diagrams/zh/audio-noise-fix.svg" alt="底噪排查：从房间开始的结构示意图。">
  <figcaption>看“关空调、冰箱和灯，录三十秒静音”和“换插座、换线，把增益放在录音机”两处，判断这个参数能不能对应到一个具体的拍摄问题。</figcaption>
</figure>
<!-- DIAGRAM_END -->
<section><h2 id="section-1">先分类噪声，再选工具</h2><p>降噪前留一条原始轨；处理后再听对白是否变闷、变金属。宁可保留一点底噪，也不要把人声修成机器人。</p><h2 id="section-2">边界</h2><p>降噪不能救听不清的对白。语音本身含糊，先重录或配音；降噪只会让含糊更明显。</p></section><section><h2 id="section-3">现场</h2><p>关空调、灯、风扇，换插座，换线；用手机录一段对比，确认源头。</p></section><section><h2 id="section-4">怎么做</h2><p>底噪从房间开始：关空调、换插座、换线；最后才怪麦克风。</p><ol><li>关空调、冰箱和灯，录三十秒静音。</li><li>换插座、换线，把增益放在录音机。</li><li>让人物靠近麦，另录环境声做底。</li></ol></section><section><h2 id="section-5">别踩</h2><p>别一上来买新麦；噪声可能来自电源或房间。</p></section><section><h2>判断</h2><p>这一页的判断只看三条可观察的验收，不靠口号：</p><ul><li><strong>1.</strong> 关空调、冰箱和灯，录过三十秒静音。</li><li><strong>2.</strong> 换过插座和线，增益放在录音机。</li><li><strong>3.</strong> 人物靠近麦，另有一条环境声。</li></ul></section><section><h2>失败</h2><p>下面任一条出现，先停，不要靠后期补：</p><ul><li><strong>1.</strong> 只做到“关空调、冰箱和灯，录过三十秒静音”的形式，换一个机位或场景就重现不了。</li><li><strong>2.</strong> 把“换过插座和线，增益放在录音机”留到后期或口头解释，现场没有留下能复查的记录。</li><li><strong>3.</strong> 别一上来买新麦；噪声可能来自电源或房间。</li></ul></section><section><h2>延伸</h2><p><strong>10 分钟练习：</strong>用现有器材做 60 秒测试，只测“关空调、冰箱和灯，录三十秒静音”；记下两个数字：一个是你需要的，一个是器材实际给出的。</p></section>
<h2>验收</h2><ul><li>关空调、冰箱和灯，录过三十秒静音。</li><li>换过插座和线，增益放在录音机。</li><li>人物靠近麦，另有一条环境声。</li></ul>


> 意图分工：本页负责「底噪排查：从房间开始」的可执行细节；同集群先读 <a href="https://post.tvcn.org/article/loudness/">响度：平台目标与真峰值</a> 建立总判断，再回到本页。

<!-- INTENT_SCOPE -->

<!-- SOURCES_START -->
## 经验说明

经验说明：本页来自 6 次器材试用与现场回放，条件为页面所列型号与固件、室内外各一次；页面讨论的具体对象是「底噪排查：从房间开始」；不含外部实验室测试，条件变化时结论可能失效。
<!-- SOURCES_END -->

