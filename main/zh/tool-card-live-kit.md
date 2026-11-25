---
id: main.tool.tool-card-live-kit
site: main
type: tool
lang: zh
translation_key: main.tool.tool-card-live-kit
translation_status: source
title: 直播推流
summary: 直播推流：相机、采集卡、有线网络、备用热点、本地录制；先保不中断。
slug: tool-card-live-kit
aliases:
- tool-card-live-kit
canonical_site: main
canonical_path: /article/tool-card-live-kit/
status: published
diagram: /images/diagrams/zh/tool-card-live-kit.svg
diagram_alt: 直播推流的结构示意图。
diagram_caption: 看“最低档： 一台相机、一张采集卡、一台…”和“工作档： 第二路网络（热点或路由器）…”两处，判断症状能不能被复述成一句可观察的话。
difficulty: beginner
stage: field-note
format: handbook
authors:
- TVCN 编辑部
last_verified: '2026-11-25'
review_due: '2027-05-25'
related:
- main.tool.tool-card-interview-kit.en
- main.tool.tool-card-storage-kit.en
- main.tool.tool-card-audio-kit.en
source_kind: experience
---

<p>直播断掉，观众不会等你重开；声音爆掉，画面再清楚也没人看。清单顺序应是网络、音频、备份录制、机位、灯光。</p>
<!-- DIAGRAM_START -->
<h2>图解</h2>
<figure>
  <img src="/images/diagrams/zh/tool-card-live-kit.svg" alt="直播推流的结构示意图。">
  <figcaption>看“最低档： 一台相机、一张采集卡、一台…”和“工作档： 第二路网络（热点或路由器）…”两处，判断症状能不能被复述成一句可观察的话。</figcaption>
</figure>
<!-- DIAGRAM_END -->
<section><h2 id="section-1">先保网络和声音，再谈画面</h2>

<ul><li><strong>最低档：</strong>一台相机、一张采集卡、一台笔记本、有线网络、一个领夹或调音台输出；先做 15 分钟私密测试。</li><li><strong>工作档：</strong>第二路网络（热点或路由器）、独立录音、备份录制、监看耳机和波形；能发现掉帧与爆音。</li><li><strong>保险档：</strong>硬件编码器、UPS、第二台相机和独立备份机；主链路坏了能切。</li></ul>
<h2 id="section-2">开播前测试</h2>
<ol><li>按实际码率推 15 分钟私密流，记录掉帧、延迟和上传波动。</li><li>让主播正常说话，确认直播端和备份录制端都不爆、不延迟。</li><li>拔掉主网络，确认备用网络能接管；再插回，确认不会重复推流。</li></ol>
<h2 id="section-3">不要用无线碰运气</h2>
<p>能插网线就插网线；无线只做备份。不要等开播才发现上行不够，也不要把备份录制放在同一台没有独立电源的机器上。</p></section><section><h2 id="section-4">现场</h2><p>相机、采集卡、有线网络、备用热点、本地录制；断网一次演练。</p></section><section><h2 id="section-5">别踩</h2><p>别只靠现场 Wi-Fi；断一次，整场直播就没了。</p></section>
<h2>验收</h2><ul><li>有线网络推流，备用热点已测速。</li><li>本地同时录制一份完整文件。</li><li>断网演练记录切换秒数，能在 10 秒内恢复。</li></ul>
