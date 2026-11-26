---
id: tools.tutorial.export-h264
site: tools
type: article
lang: zh
translation_key: tools.tutorial.export-h264
translation_status: source
title: H.264 导出：码率与兼容
summary: H.264 导出先定平台和码率，再选两遍编码；码率太低，运动画面先烂。
slug: export-h264
aliases:
- export-h264
canonical_site: tools
canonical_path: /article/export-h264/
status: published
diagram: /images/diagrams/zh/export-h264.svg
diagram_alt: H.264 导出：码率与兼容的结构示意图。
diagram_caption: 看“1080p 用 10 到 16 Mb…”和“两遍编码”两处，判断这个参数能不能对应到一个具体的拍摄问题。
difficulty: beginner
stage: field-note
format: handbook
authors:
- TVCN 工具组
last_verified: '2026-11-26'
review_due: '2027-02-26'
related: [tools.tutorial.export-prores, tools.tutorial.exposure-check, shoot.camera.composition]
verified: 2026-11-23
source_kind: sourced
sources:
- S65
- S29
- S29
---
<p>别用 5 Mbps 传 4K；一有运动，画面就糊成块。</p>
<!-- DIAGRAM_START -->
<h2>图解</h2>
<figure>
  <img src="/images/diagrams/zh/export-h264.svg" alt="H.264 导出：码率与兼容的结构示意图。">
  <figcaption>看“1080p 用 10 到 16 Mb…”和“两遍编码”两处，判断这个参数能不能对应到一个具体的拍摄问题。</figcaption>
</figure>
<!-- DIAGRAM_END -->
<section><h2 id="section-1">现场</h2><p>平台 1080p 用 10 到 16 Mbps，4K 用 35 到 45 Mbps；两遍编码，音频 AAC 192 kbps。</p></section><section><h2 id="section-2">怎么做</h2><ol><li>1080p 用 10 到 16 Mbps，4K 用 35 到 45 Mbps。</li><li>两遍编码。</li><li>音频 AAC 192 kbps。</li></ol></section><section></section><section><h2 id="section-4">三种原因</h2><p>针对“H.264 导出：码率与兼容”，先按三个方向排查；每次只改一个变量，改完录 30 秒对比，看变化跟着哪个环节走。</p><div class="table-scroll"><table class="data-table"><thead><tr><th>原因</th><th>现场信号</th><th>5 分钟验证</th></tr></thead><tbody><tr><td>码率不够</td><td>运动和大面积细节出现块，平台二次压缩更糟</td><td>用 2 秒高运动片段试 12/20/35Mbps</td></tr><tr><td>参数不兼容</td><td>色彩、帧率、像素长宽比和平台要求不一致</td><td>用 MediaInfo 对照交付规格</td></tr><tr><td>音频不合规</td><td>采样率/声道/码率不对，平台回放无声或爆音</td><td>导出后单独检查音频轨</td></tr></tbody></table></div></section><section><h2 id="section-5">现场诊断</h2><ol><li>用 MediaInfo 看编码、profile、level、码率、色彩标签和音频参数。</li><li>在目标平台上传 30 秒测试片，看回放是否清晰、颜色是否偏。</li><li>对比源文件和导出文件的同一帧，确认没有意外裁切或拉伸。</li></ol></section><section><h2 id="section-6">修法</h2><p>H.264 的目标不是“最小文件”，是“在目标平台回放正确”。先定交付规格，再选码率和 profile。</p><ol><li>网络交付用 H.264 High Profile，4:2:0 8-bit，AAC 48kHz。</li><li>1080p 用 12–20Mbps，4K 用 35–60Mbps；高运动素材往上取。</li><li>两遍编码或 VBV 限制，避免峰值把码率撑爆。</li><li>导出后检查首帧、末帧、音频同步和平台回放。</li></ol></section><section><h2 id="section-7">失败案例</h2><p>处理“H.264 导出：码率与兼容”时，下面三种做法会更糟；先选一个替换动作，别同时改三个变量。</p><div class="table-scroll"><table class="data-table"><thead><tr><th>失败做法</th><th>为什么会更糟</th><th>替换动作</th></tr></thead><tbody><tr><td>只看文件大小</td><td>文件小了，细节和音频都坏了</td><td>按平台规格测</td></tr><tr><td>用 4:4:4 交付</td><td>平台不支持，直接转码或拒绝</td><td>交付用 4:2:0</td></tr><tr><td>忽略色彩标签</td><td>颜色在平台上偏灰/偏饱和</td><td>写入正确 matrix/primaries</td></tr></tbody></table></div></section><section><h2 id="section-8">验收表</h2><p>验收不是“感觉好了”，是这四项都能指认、能回放、能记录。</p><div class="table-scroll"><table class="data-table"><thead><tr><th>验收项</th><th>通过线</th><th>记录</th></tr></thead><tbody><tr><td>编码</td><td>H.264 High，level 与分辨率匹配</td><td>MediaInfo</td></tr><tr><td>码率</td><td>高运动段无块</td><td>30 秒测试上传</td></tr><tr><td>音频</td><td>AAC 48kHz，声道正确，不削波</td><td>单独监听</td></tr><tr><td>色彩</td><td>平台回放不偏色</td><td>对比源片</td></tr></tbody></table></div></section><figure class="article-audio"><audio controls preload="none" src="../../assets/audio/zh/tool-export-h264.zh.mp3"></audio><figcaption>20 秒语音演示：一个检查点和最常见的失败。文字稿与步骤在正文里。</figcaption></figure><section><h2>判断</h2><p>这一页的判断只看三条可观察的验收，不靠口号：</p><ul><li><strong>1.</strong> 分辨率对应码率在建议区间内。</li><li><strong>2.</strong> 编码方式为两遍，不是单遍赶时间。</li><li><strong>3.</strong> 音频 AAC 192 kbps，声画同步。</li></ul></section><section><h2>失败</h2><p>下面任一条出现，先停，不要靠后期补：</p><ul><li><strong>1.</strong> 只做到“分辨率对应码率在建议区间内”的形式，换一个机位或场景就重现不了。</li><li><strong>2.</strong> 把“编码方式为两遍，不是单遍赶时间”留到后期或口头解释，现场没有留下能复查的记录。</li><li><strong>3.</strong> 第 3 条验收“音频 AAC 192 kbps，声画同步”没人复核，交片时才发现。</li></ul></section><section><h2>延伸</h2><p><strong>10 分钟练习：</strong>用现有器材做 60 秒测试，只测“1080p 用 10 到 16 Mb…”；记下两个数字：一个是你需要的，一个是器材实际给出的。</p></section>
<h2>验收</h2><ul><li>分辨率对应码率在建议区间内。</li><li>编码方式为两遍，不是单遍赶时间。</li><li>音频 AAC 192 kbps，声画同步。</li></ul>

<!-- SOURCES_START -->
## 参考与延伸阅读

- [S65] [ITU-T H.264](https://www.itu.int/rec/T-REC-H.264/en) — 2026-11-26 访问。用于核对「现场」一节的术语/方法/规则（H.264 编码标准，不是平台上传规则）；不核对其中由本页经验得出的数字、型号与现场结论，也不替代测试。
- [S29] [YouTube：上传编码建议](https://support.google.com/youtube/answer/1722171) — 2026-11-26 访问。用于核对「怎么做」一节的术语/方法/规则（YouTube 上传编码建议，不是创作标准）；不核对其中由本页经验得出的数字、型号与现场结论，也不替代测试。
<!-- SOURCES_END -->

