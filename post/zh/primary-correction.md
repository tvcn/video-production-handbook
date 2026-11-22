---
id: post.color.primary-correction
site: post
type: article
lang: zh
translation_key: post.color.primary-correction
translation_status: source
title: "一级校正：曝光与白平衡"
summary: "一级校正先解决曝光和白平衡，别用风格掩盖技术问题。"
slug: primary-correction
aliases: [primary-correction]
canonical_site: post
canonical_path: /color/primary-correction/
status: published
diagram: /images/diagrams/zh/primary-correction.svg
diagram_alt: "一级校正：曝光与白平衡 三步图解"
diagram_caption: "把三步按顺序做完，再回看画面或文件。"
difficulty: beginner
stage: field-note
format: handbook
authors: ["TVCN 后期组"]
last_verified: 2026-11-20
review_due: 2027-05-20
related: [main.paths.first-film]
depth: deep
deep_minutes: 6
sources: [S24, S27, S28, S30, S34, S35]
test_context: "复核环境：Windows 11（RTX 3060）+ macOS 14（M1）；DaVinci Resolve 20 与 Premiere Pro 2025 复跑；不声称每台机器结果一致。"
known_failures: "已知失败：旧版软件时间线不兼容；不同相机 Log 需重新映射；代理丢失时需回套原片。"
verified: 2026-11-22
---

<p>一级校正先解决曝光和白平衡，别用风格掩盖技术问题。</p>
<!-- DIAGRAM_START -->
<h2>图解</h2>
<figure>
  <img src="/images/diagrams/zh/primary-correction.svg" alt="一级校正：曝光与白平衡 三步图解">
  <figcaption>把三步按顺序做完，再回看画面或文件。</figcaption>
</figure>
<!-- DIAGRAM_END -->
<h2>现场</h2>
<p>先拍一张灰卡或色卡：黑位压到 0 到 5，白位不超过 100；同场镜头逐条对齐，再看肤色线。</p>
<h2>怎么做</h2>
<p>一级校正先解决曝光和白平衡，别用风格掩盖技术问题。</p><ol><li>先拍灰卡或色卡，黑位压到 0 到 5，白位不超过 100。</li><li>同场镜头逐条对齐曝光和白平衡，再看肤色线。</li><li>技术问题清零后，才加对比和风格。</li></ol>
<h2>别踩</h2>
<p>别用 LUT 掩盖技术问题；它会把问题染得更好看。</p>
<h2>验收</h2>
<ul><li>同场镜头的黑位和白位对齐，切点不跳。</li><li>肤色线落在同一区域，没有一条偏绿一条偏红。</li><li>关掉风格 LUT 后，画面技术仍然成立。</li></ul>

<!-- DEEP_DIVE_START -->
## 深读
<p><strong>约 6 分钟。</strong> 一级校正只做三件事：曝光对齐、白平衡统一、对比还原。别在这一步做风格。</p>
### 先对齐，再谈好看
<p>同一场戏先找最准的一条做参考，其他镜头向它靠。看波形，不靠眼睛；眼睛会被前后镜头骗。</p><p>户内户外分开调，不要把窗和外景拉成同一个亮度。观众知道窗外更亮，压平反而假。</p>
### 白平衡用中性灰
<p>白墙会偏色，灰卡更准。没有灰卡，用白纸但别过曝；过曝的白纸已经不是白。</p><p>混合光里没有绝对正确，选一个主光源，让其他颜色保留。把所有颜色拉成白色，房间就死了。</p>
### 对比不要压死
<p>提黑位会发灰，压黑位会丢细节。先看示波器，再决定；黑位不是越黑越高级。</p><p>LUT 放在一级之后，别用 LUT 掩盖曝光问题。一级错了，后面所有节点都在给错误打补丁。</p>
### 镜头匹配的顺序
<p>先曝光，再白平衡，再对比，最后肤色。顺序反了，每调一项都会推翻前一项。</p><p>一场戏调完，切到下一场前先回放三个镜头，确认没有跳。</p>
### 肤色和记忆色
<p>天空、草地、肤色是记忆色，偏一点观众就知道。先保肤色，再保天空。</p><p>不要把肤色调到一样白。不同人的肤色本来不同，统一会假。</p>
### 一级校正，十项过一遍
<ul><li>每场选一条参考镜头</li><li>先对曝光</li><li>再对白平衡</li><li>再对肤色</li><li>再看黑位</li><li>再看高光</li><li>混合光保留环境颜色</li><li>LUT 放在一级之后</li><li>用示波器检查</li><li>整场连续回放</li></ul><p>一级校正的目标不是“好看”，是“看不出镜头之间的接缝”。</p>
### 只剩五分钟时
<ul><li>每场选一条参考镜头</li><li>先对曝光</li><li>再对白平衡</li><li>再对肤色</li><li>看黑位和高光</li><li>LUT 放在一级之后</li></ul><p>一级校正做对了，后面的风格才有地基；地基歪了，越调越假。先让一场戏里的脸看起来是同一个人，再谈风格。这场戏的脸，要像同一个人，不是两个色温的人。</p>
<!-- DEEP_DIVE_END -->
<!-- SOURCES_START -->
<h2>参考与延伸阅读</h2>
<p class="source-types">经验来源：TVCN 现场手册与项目复盘；实测来源：页面标注的复核环境与可复现练习；参考来源：以下公开链接。</p>
<ul><li><span class="mono">[S24]</span> ACES 色彩管理</li><li><span class="mono">[S27]</span> EBU R128 响度</li><li><span class="mono">[S28]</span> Netflix 制作与交付帮助</li><li><span class="mono">[S30]</span> DaVinci Resolve 产品与文档</li><li><span class="mono">[S34]</span> Adobe Premiere Pro 用户指南</li><li><span class="mono">[S35]</span> Avid 资源中心</li></ul>
<p><a href="../../SOURCES.md">完整链接与用途见 SOURCES.md</a></p>
<!-- SOURCES_END -->
