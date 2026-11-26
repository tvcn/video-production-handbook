---
id: tools.tutorial.subtitle-srt
site: tools
type: article
lang: zh
translation_key: tools.tutorial.subtitle-srt
translation_status: source
title: SRT 字幕：编码、时间轴、标点
summary: SRT 字幕先保 UTF-8 编码、时间轴和标点；编码错了，平台会显示乱码。
slug: subtitle-srt
aliases:
- subtitle-srt
canonical_site: tools
canonical_path: /article/subtitle-srt/
status: published
diagram: /images/diagrams/zh/subtitle-srt.svg
diagram_alt: SRT 字幕：编码、时间轴、标点的结构示意图。
diagram_caption: 看“存 UTF-8”和“时间轴精确到毫秒”两处，判断这个参数能不能对应到一个具体的拍摄问题。
difficulty: beginner
stage: field-note
format: handbook
authors:
- TVCN 工具组
last_verified: '2026-11-26'
review_due: '2027-02-26'
related: [tools.tutorial.sync-multicam, tools.test.test-protocols, shoot.camera.composition]
verified: 2026-11-23
source_kind: sourced
sources:
- S68
- S29
---
<p>别用 ANSI 存中文 SRT；到平台上全是问号。</p>
<!-- DIAGRAM_START -->
<h2>图解</h2>
<figure>
  <img src="/images/diagrams/zh/subtitle-srt.svg" alt="SRT 字幕：编码、时间轴、标点的结构示意图。">
  <figcaption>看“存 UTF-8”和“时间轴精确到毫秒”两处，判断这个参数能不能对应到一个具体的拍摄问题。</figcaption>
</figure>
<!-- DIAGRAM_END -->
<section><h2 id="section-1">现场</h2><p>存 UTF-8，时间轴精确到毫秒；每条不超过 2 行、每行 16 字。</p></section><section><h2 id="section-2">怎么做</h2><ol><li>存 UTF-8。</li><li>时间轴精确到毫秒。</li><li>每条不超过 2 行、每行 16 字。</li></ol></section><section><h2 id="section-3">别踩</h2></section><section><h2 id="section-4">三种原因</h2><p>针对“SRT 字幕：编码、时间轴、标点”，先按三个方向排查；每次只改一个变量，改完录 30 秒对比，看变化跟着哪个环节走。</p><div class="table-scroll"><table class="data-table"><thead><tr><th>原因</th><th>现场信号</th><th>5 分钟验证</th></tr></thead><tbody><tr><td>编码不对</td><td>UTF-8 被保存成 GBK，平台显示乱码</td><td>用 UTF-8 无 BOM 导出</td></tr><tr><td>时间轴漂移</td><td>帧率或起始时间错，越到后面越不同步</td><td>按帧率换算并用播放器核对</td></tr><tr><td>行长/标点</td><td>一行太长、标点全角/半角混用，读起来断气</td><td>每行 12–16 字，最多两行</td></tr></tbody></table></div></section><section><h2 id="section-5">现场诊断</h2><ol><li>用文本编辑器确认编码是 UTF-8，不要用系统默认。</li><li>在目标播放器里从头到尾看一遍，记录第一处漂移。</li><li>把最长一行数出来；超过 16 字就拆。</li></ol></section><section><h2 id="section-6">修法</h2><p>SRT 是最简单的字幕格式，也最容易在编码、帧率和行长上翻车。先保证能读，再谈翻译。</p><ol><li>统一 UTF-8 无 BOM；不要用 Word 保存。</li><li>时间轴按项目帧率换算，首句和末句都要核。</li><li>每行 12–16 字，最多两行；一行不要断在词中间。</li><li>标点用中文全角或英文半角统一，不要混。</li></ol></section><section><h2 id="section-7">失败案例</h2><p>处理“SRT 字幕：编码、时间轴、标点”时，下面三种做法会更糟；先选一个替换动作，别同时改三个变量。</p><div class="table-scroll"><table class="data-table"><thead><tr><th>失败做法</th><th>为什么会更糟</th><th>替换动作</th></tr></thead><tbody><tr><td>机翻直接上</td><td>语序和术语错，观众读不懂</td><td>至少人工过一遍</td></tr><tr><td>一行塞满</td><td>观众读不完，字幕挡住画面</td><td>拆成两行</td></tr><tr><td>时间轴重叠</td><td>两条字幕同时出现</td><td>检查起止时间</td></tr></tbody></table></div></section><section><h2 id="section-8">验收表</h2><p>验收不是“感觉好了”，是这四项都能指认、能回放、能记录。</p><div class="table-scroll"><table class="data-table"><thead><tr><th>验收项</th><th>通过线</th><th>记录</th></tr></thead><tbody><tr><td>编码</td><td>UTF-8 无 BOM，平台不乱码</td><td>文本编辑器</td></tr><tr><td>同步</td><td>首句/末句误差不超过 1 帧</td><td>播放器核对</td></tr><tr><td>行长</td><td>每行不超过 16 字，最多两行</td><td>最长行统计</td></tr><tr><td>标点</td><td>全角/半角统一</td><td>通读</td></tr></tbody></table></div></section><section><h2>判断</h2><p>这一页的判断只看三条可观察的验收，不靠口号：</p><ul><li><strong>1.</strong> 文件是 UTF-8，中文在播放器里正常显示。</li><li><strong>2.</strong> 时间轴精确到毫秒，首尾没有重叠。</li><li><strong>3.</strong> 每条不超过 2 行、每行 16 字，标点完整。</li></ul></section><section><h2>失败</h2><p>下面任一条出现，先停，不要靠后期补：</p><ul><li><strong>1.</strong> 只做到“文件是 UTF-8，中文在播放器里正常显示”的形式，换一个机位或场景就重现不了。</li><li><strong>2.</strong> 把“时间轴精确到毫秒，首尾没有重叠”留到后期或口头解释，现场没有留下能复查的记录。</li><li><strong>3.</strong> 第 3 条验收“每条不超过 2 行、每行 16 字，标点完整”没人复核，交片时才发现。</li></ul></section><section><h2>延伸</h2><p><strong>10 分钟练习：</strong>用现有器材做 60 秒测试，只测“存 UTF-8”；记下两个数字：一个是你需要的，一个是器材实际给出的。</p></section>
<h2>验收</h2><ul><li>文件是 UTF-8，中文在播放器里正常显示。</li><li>时间轴精确到毫秒，首尾没有重叠。</li><li>每条不超过 2 行、每行 16 字，标点完整。</li></ul>

<!-- SOURCES_START -->
## 参考与延伸阅读

- [S68] [W3C：WebVTT](https://www.w3.org/TR/webvtt1/) — 2026-11-26 访问。用于核对首段“SRT 字幕先保 UTF-8 编码、时间轴和标点；编码错了，平台会显示乱码。”中的术语与公开背景（字幕格式与时间戳）；不替代现场测试。
- [S29] [YouTube 上传规格](https://support.google.com/youtube/answer/1722171) — 2026-11-26 访问。用于核对首段“SRT 字幕先保 UTF-8 编码、时间轴和标点；编码错了，平台会显示乱码。”中的术语与公开背景（分辨率、码率、帧率与音频编码建议）；不替代现场测试。
<!-- SOURCES_END -->

