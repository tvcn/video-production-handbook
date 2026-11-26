---
id: animation.3d.blockout
site: animation
type: article
lang: zh
translation_key: animation.3d.blockout
translation_status: source
title: Blockout：先定比例和机位
summary: Blockout 先定比例、机位和时长，不建模细节；这一步错了，后面全返工。
slug: blockout
aliases:
- blockout
canonical_site: animation
canonical_path: /article/blockout/
status: published
diagram: /images/diagrams/zh/blockout.svg
diagram_alt: Blockout：先定比例和机位的结构示意图。
diagram_caption: 看“用盒子人定比例：头、胸、骨盆三块”和“先锁机位和 10 秒时长”两处，判断前景、中景、背景的速度差能不能在一次移动里看出来。
difficulty: beginner
stage: field-note
format: handbook
authors:
- TVCN 动画组
last_verified: '2026-11-26'
review_due: '2027-02-26'
related: [animation.deep.deep-2d-layer-depth, animation.deep.deep-3d-light-material, formats.documentary.documentary-template]
depth: deep
deep_minutes: 6
source_kind: sourced
---
<p>Blockout 只解决三件事：角色和场景的比例、摄影机放在哪、动作占多少时间。用球体、方块和简单道具，不要先做细节。</p>
<!-- DIAGRAM_START -->
<h2>图解</h2>
<figure>
  <img src="/images/diagrams/zh/blockout.svg" alt="Blockout：先定比例和机位的结构示意图。">
  <figcaption>看“用盒子人定比例：头、胸、骨盆三块”和“先锁机位和 10 秒时长”两处，判断前景、中景、背景的速度差能不能在一次移动里看出来。</figcaption>
</figure>
<!-- DIAGRAM_END -->
<section><h2 id="section-1">先定比例、机位和时间</h2><p>先出一版没有材质和灯光的 playblast，检查剪影和构图；如果这一版看不懂，后面加细节也不会突然看懂。</p><h2 id="section-2">边界</h2><p>Blockout 不是低模成品。不要在这里纠结脸和布料；但比例、重心和机位必须已经成立。</p><h2 id="section-3">Blockout 只看三件事</h2>
<p>Blockout 不是低模预览，是决定比例、机位和镜头顺序。用灰模或胶囊人，先不做材质和灯光；这三件事定错，后面全部返工。</p>
<ol><li>比例：人物与场景的高度关系用已知尺寸对照，不要凭感觉拉。</li><li>机位：先定焦段和高度，再定运动；一个镜头只解决一个空间关系。</li><li>顺序：按剪接点排镜头，不按制作方便排；先做能看懂故事的版本。</li></ol>
<p>验收：把 blockout 连起来放一遍，关掉所有材质，仍能看懂“谁在哪、要做什么”。看不懂，先改机位，不要进动画。</p></section><section><h2 id="section-4">现场</h2><p>用盒子人定比例：头、胸、骨盆三块；先锁机位和 10 秒时长，再进建模。</p></section><section><h2 id="section-5">怎么做</h2><ol><li>用盒子人定比例：头、胸、骨盆三块。</li><li>先锁机位和 10 秒时长。</li><li>比例和机位确认后再进建模。</li></ol></section><section><h2 id="section-6">别踩</h2><p>别在机位没锁时做表演；一定返工。</p></section><section><h2>判断</h2><p>现场只认三个信号：</p><ul><li>前景、中景、背景的速度差能在一次 pan 里看出来</li><li>动作在 0.5 秒内能读出重量或预备</li><li>关掉任意一层，空间感仍然成立</li></ul></section><section><h2>失败</h2><p>下面三种做法会让页面上的细节白做：</p><ul><li>层数堆上去了，但每层速度一样，空间还是扁的</li><li>动作有预备却没有跟随，重量只做了一半</li><li>资产没锁就进渲染，返工从合成端一路补</li></ul></section><section><h2>延伸</h2><p><strong>10 分钟练习：</strong>用 24 fps 画 3 个关键帧，只改“先锁机位和 10 秒时长”，导出 2 秒；如果重量仍读不出来，先加预备帧，不要加模糊。</p></section>
<h2>验收</h2><ul><li>盒子人能看出头、胸、骨盆三块比例。</li><li>机位和 10 秒时长已经锁死，有截图和参数。</li><li>最终镜头与 blockout 机位一致，没有中途换构图。</li></ul>

<!-- DEEP_DIVE_START -->
## 深读
<p><strong>约 6 分钟。</strong> blockout 不是草稿，是用最简单的形体决定镜头里发生什么。</p>
### 比例和机位先定
<p>用方盒代表人、门、桌，先定高度和距离；人和门的关系不对，后面建模再准也没用。用实际焦距看一遍，不要用广角把问题藏起来。</p><p>机位定三个：主镜头、反打、一个细节；三个都能讲清空间，再往下做。</p>
### 走位用时间画
<p>不要只摆一个姿势；用简单的代理人物走一遍，标出起点、转折、终点。每段时间写一个动作，不要写“走过去”。</p><p>用手机拍一版真人走位，和 blockout 对比；真人做不到的，动画也会假。</p>
### 灰模只解决三件事
<p>空间、比例、运动；材质、灯光、细节都不属于 blockout。灰模阶段加材质，只会让你舍不得改结构。</p><p>blockout 通过的标准：静音看一遍，能说出谁在哪、要做什么、什么挡着他。</p>
### 五分钟练习：一个房间三个机位
<p>搭一个房间，放一个人和一件障碍物；摆三个机位，每个机位只解决一个信息。用灰模渲染三张，不许加材质。</p><p>把三张给一个人看，问他“他想去哪、什么挡着他”；答不出，改机位，不要改模型。</p>
### 什么时候算 blockout 通过
<p>静音播放，一个没看过剧本的人能说出谁在哪、想做什么、什么挡着他、镜头为什么在这个位置；四项都答对，blockout 才算通过。</p><p>如果答不出，先改机位和走位，不要加模型细节。细节会让问题更难看见，不会让问题消失。</p>
### Blockout，十项检查
<ul><li>方盒定人和门的高度</li><li>先定距离关系</li><li>用实际焦距看构图</li><li>主镜头反打细节三个机位</li><li>代理人物走一遍</li><li>标出起点转折终点</li><li>每段写一个动作</li><li>手机拍真人走位对比</li><li>灰模不加材质灯光</li><li>静音能说出谁在哪要做什么</li></ul><p>blockout 的唯一任务，是让后面的人不用猜空间。</p>
<!-- DEEP_DIVE_END -->

<!-- SOURCES_START -->
## 参考与延伸阅读

- [S62] [Blender Foundation：Blender 官方手册](https://docs.blender.org/manual/en/latest/) — 2026-11-26 访问。用于核对首段“Blockout 先定比例、机位和时长，不建模细节；这一步错了，后面全返工。”中的术语与公开背景（建模、绑定、动画、渲染）；不替代现场测试。
- [S63] [Toon Boom：官方文档](https://docs.toonboom.com/) — 2026-11-26 访问。用于核对首段“Blockout 先定比例、机位和时长，不建模细节；这一步错了，后面全返工。”中的术语与公开背景（2D 动画、绑定与制作管线）；不替代现场测试。
<!-- SOURCES_END -->

