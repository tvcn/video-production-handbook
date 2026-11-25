---
id: tools.tutorial.nd-calculate
site: tools
type: article
lang: zh
translation_key: tools.tutorial.nd-calculate
translation_status: source
title: ND 计算：大光圈白天怎么曝光
summary: ND 计算先定快门和光圈，再算需要减几档；凭感觉换滤镜，十次有九次过暗。
slug: nd-calculate
aliases:
- nd-calculate
canonical_site: tools
canonical_path: /article/nd-calculate/
status: published
diagram: /images/diagrams/zh/nd-calculate.svg
diagram_alt: ND 计算：大光圈白天怎么曝光的结构示意图。
diagram_caption: 看“先定 1/50 和 f/2.8”和“用测光表或相机测环境 EV”两处，判断这个参数能不能对应到一个具体的拍摄问题。
difficulty: beginner
stage: field-note
format: handbook
authors:
- TVCN 工具组
last_verified: '2026-11-25'
review_due: '2027-05-25'
related:
- tools.calculator.nd-calculator.en
- tools.capability.nd-gel.en
- tools.guide.buy-light-led.en
verified: 2026-11-23
source_kind: experience
---

<p>别用“看起来差不多”换 ND；档数不对，人脸会暗两档。</p>
<!-- DIAGRAM_START -->
<h2>图解</h2>
<figure>
  <img src="/images/diagrams/zh/nd-calculate.svg" alt="ND 计算：大光圈白天怎么曝光的结构示意图。">
  <figcaption>看“先定 1/50 和 f/2.8”和“用测光表或相机测环境 EV”两处，判断这个参数能不能对应到一个具体的拍摄问题。</figcaption>
</figure>
<!-- DIAGRAM_END -->
<section><h2 id="section-1">现场</h2><p>先定 1/50 和 f/2.8，用测光表或相机测环境 EV；再算需要减几档，换对应 ND。</p></section><section><h2 id="section-2">怎么做</h2><ol><li>先定 1/50 和 f/2.8。</li><li>用测光表或相机测环境 EV。</li><li>算需要减几档，换对应 ND。</li></ol></section><section><h2 id="section-3">别踩</h2></section><section><h2 id="section-4">三种原因</h2><p>针对“ND 计算：大光圈白天怎么曝光”，先按三个方向排查；每次只改一个变量，改完录 30 秒对比，看变化跟着哪个环节走。</p><div class="table-scroll"><table class="data-table"><thead><tr><th>原因</th><th>现场信号</th><th>5 分钟验证</th></tr></thead><tbody><tr><td>ND 标称不准</td><td>滤镜实际档位和标注差半档，曝光不准</td><td>用快门基准实测</td></tr><tr><td>多片叠加</td><td>两片 ND 叠加产生暗角和偏色</td><td>尽量单片，必须叠加时测边缘</td></tr><tr><td>广角暗角</td><td>厚滤镜在广角上挡光</td><td>用薄框/大口径</td></tr></tbody></table></div></section><section><h2 id="section-5">现场诊断</h2><ol><li>先在无 ND 时确定基准快门和光圈。</li><li>加 ND 后保持光圈，降快门到目标；看高光是否回到通过线。</li><li>用广角端拍一张白墙，检查四角是否变暗/偏色。</li></ol></section><section><h2 id="section-6">修法</h2><p>ND 计算不是背公式，是先定基准曝光，再按实际滤镜测偏移。标称档位只是起点。</p><ol><li>基准：25p 用 1/50，光圈按景深定。</li><li>每片 ND 实拍一次，记录实际减光档位。</li><li>优先单片 ND；叠加时用薄框并收一档光圈。</li><li>在广角端检查暗角，必要时换大口径。</li></ol></section><section><h2 id="section-7">失败案例</h2><p>处理“ND 计算：大光圈白天怎么曝光”时，下面三种做法会更糟；先选一个替换动作，别同时改三个变量。</p><div class="table-scroll"><table class="data-table"><thead><tr><th>失败做法</th><th>为什么会更糟</th><th>替换动作</th></tr></thead><tbody><tr><td>只看滤镜刻度</td><td>实际偏半档，高光还是爆</td><td>实拍校准</td></tr><tr><td>两片叠三档</td><td>暗角和偏色一起出现</td><td>用单片可变 ND 或更大口径</td></tr><tr><td>忽略快门</td><td>为了曝光把快门拉到 1/1000，运动变硬</td><td>先 ND 后快门</td></tr></tbody></table></div></section><section><h2 id="section-8">验收表</h2><p>验收不是“感觉好了”，是这四项都能指认、能回放、能记录。</p><div class="table-scroll"><table class="data-table"><thead><tr><th>验收项</th><th>通过线</th><th>记录</th></tr></thead><tbody><tr><td>基准</td><td>无 ND 时快门/光圈/ISO 记录</td><td>曝光表</td></tr><tr><td>实际档位</td><td>每片 ND 的减光量有记录</td><td>实拍对照</td></tr><tr><td>暗角</td><td>广角四角不明显变暗</td><td>白墙测试</td></tr><tr><td>运动</td><td>快门保持 1/50 附近</td><td>看运动模糊</td></tr></tbody></table></div></section><section><h2>判断</h2><p>现场只认三个信号：</p><ul><li>每一项参数都能对应一个具体的拍摄问题</li><li>重量、供电和接口在真实机位上成立</li><li>60 秒测试能留下一个可比较的数字</li></ul></section><section><h2>失败</h2><p>下面三种做法会让页面上的细节白做：</p><ul><li>只看参数，不看接口、供电和重量</li><li>买回来才发现电池、存储或机身不匹配</li><li>没有 60 秒测试，问题被带到正式拍摄</li></ul></section><section><h2>延伸</h2><p><strong>10 分钟练习：</strong>用现有器材做 60 秒测试，只测“先定 1/50 和 f/2.8”；记下两个数字：一个是你需要的，一个是器材实际给出的。</p></section>
<h2>验收</h2><ul><li>快门 1/50、光圈 f/2.8 是先定死的。</li><li>环境 EV 有测光读数，不是估的。</li><li>算出的档数与实际 ND 一致，换后曝光落在目标内。</li></ul>
