---
id: tools.tutorial.color-checker
site: tools
type: article
lang: zh
translation_key: tools.tutorial.color-checker
translation_status: source
title: 色卡拍摄：后期对色
summary: 色卡在场景光下拍一张，后期才有基准；开机后补拍，光已经变了。
slug: color-checker
aliases:
- color-checker
canonical_site: tools
canonical_path: /article/color-checker/
status: published
diagram: /images/diagrams/zh/color-checker.svg
diagram_alt: 色卡拍摄：后期对色的结构示意图。
diagram_caption: 看“开机先拍色卡”和“色卡充满画面三分之一”两处，判断这个参数能不能对应到一个具体的拍摄问题。
difficulty: beginner
stage: field-note
format: handbook
authors:
- TVCN 工具组
last_verified: '2026-11-26'
review_due: '2027-05-26'
related: [tools.guide.crew-management, tools.capability.davinci-node, shoot.camera.composition]
source_kind: experience
---
<p>色卡不是开机仪式，是后期校正的锚点。每个场景、每次换灯或换色温，拍一张色卡占画面 1/3，焦点清楚，曝光正常；不要只在第一条拍。</p>
<!-- DIAGRAM_START -->
<h2>图解</h2>
<figure>
  <img src="/images/diagrams/zh/color-checker.svg" alt="色卡拍摄：后期对色的结构示意图。">
  <figcaption>看“开机先拍色卡”和“色卡充满画面三分之一”两处，判断这个参数能不能对应到一个具体的拍摄问题。</figcaption>
</figure>
<!-- DIAGRAM_END -->
<section><h2 id="section-1">每次换光，先拍一张色卡</h2><p>后期用色卡校准白平衡和肤色，再用示波器统一镜头；色卡不能代替创作判断。</p><h2 id="section-2">边界</h2><p>色卡不能修正混合光。一个画面里两种色温，色卡只能选一个参考；先在现场把光统一，再拍卡。</p><h2 id="section-3">色卡不是开机仪式，是对色坐标</h2>
<p>色卡要放在主体位置、和主体同一光线下拍 3–5 秒；拍完灯光一变，这张卡就失效。后期用卡上的中性灰定白平衡，再用肤色参考微调。</p>
<ol><li>先拍灰卡，再拍色卡；灰卡曝光到波形 50–60%，不要过曝。</li><li>每换一个场景或色温，重拍一次；不要一个场景用整场的卡。</li><li>后期先做相机匹配，再做风格；风格 LUT 放在匹配之后。</li></ol>
<p>验收：把色卡帧和成片对比，中性灰不偏色、肤色自然；偏绿或偏品红，先查现场白平衡。</p></section><section><h2 id="section-4">现场</h2><p>开机先拍色卡，充满画面三分之一；后期用色卡匹配，别凭记忆调。</p></section><section><h2 id="section-5">怎么做</h2><ol><li>开机先拍色卡。</li><li>色卡充满画面三分之一。</li><li>后期用色卡匹配，别凭记忆调。</li></ol></section><section><h2 id="section-6">别踩</h2><p>别在收工前补拍色卡；那时的光和开机时不一样。</p></section><section><h2>判断</h2><p>这一页的判断只看三条可观察的验收，不靠口号：</p><ul><li><strong>1.</strong> 色卡在开机时、场景光下拍摄。</li><li><strong>2.</strong> 色卡占画面约三分之一，色块没有反光。</li><li><strong>3.</strong> 后期匹配用了色卡，没有凭记忆调色。</li></ul></section><section><h2>失败</h2><p>下面任一条出现，先停，不要靠后期补：</p><ul><li><strong>1.</strong> 只做到“色卡在开机时、场景光下拍摄”的形式，换一个机位或场景就重现不了。</li><li><strong>2.</strong> 把“色卡占画面约三分之一，色块没有反光”留到后期或口头解释，现场没有留下能复查的记录。</li><li><strong>3.</strong> 别在收工前补拍色卡；那时的光和开机时不一样。</li></ul></section><section><h2>延伸</h2><p><strong>10 分钟练习：</strong>用现有器材做 60 秒测试，只测“开机先拍色卡”；记下两个数字：一个是你需要的，一个是器材实际给出的。</p></section>
<h2>验收</h2><ul><li>色卡在开机时、场景光下拍摄。</li><li>色卡占画面约三分之一，色块没有反光。</li><li>后期匹配用了色卡，没有凭记忆调色。</li></ul>


> 意图分工：本页负责「色卡拍摄：后期对色」的可执行细节；同集群先读 <a href="https://post.tvcn.org/article/lut/">LUT：起点不是终点</a> 建立总判断，再回到本页。

<!-- INTENT_SCOPE -->

<!-- SOURCES_START -->
## 经验说明

经验说明：本页来自 3 次器材试用与现场回放，条件为页面所列型号与固件、室内外各一次；页面讨论的具体对象是「色卡拍摄：后期对色」；不含外部实验室测试，条件变化时结论可能失效。
<!-- SOURCES_END -->

