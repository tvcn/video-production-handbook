---
id: ai.generation.image-to-video
site: ai
type: article
lang: zh
translation_key: ai.generation.image-to-video
translation_status: source
title: "图生视频：首帧、尾帧、运动"
summary: "先把一张图做对，再让它动。首帧和尾帧定住，中间的运动会自己收敛；提示词写再长也替代不了这两张图。"
slug: image-to-video
aliases: [image-to-video]
canonical_site: ai
canonical_path: /generation/image-to-video/
status: published
difficulty: intermediate
stage: generate
format: short-film
tools: []
authors: [editor]
reviewers: [technical-reviewer]
cover: /images/ai/image-to-video.webp
diagram: /images/diagrams/zh/image-to-video.png
diagram_alt: "图生视频：首帧和尾帧先定住"
diagram_caption: "中间的运动不是靠长提示词控制，而是被首尾两张图夹住。首帧和尾帧越明确，中间越不容易漂。"
last_verified: 2026-11-20
review_due: 2027-05-20
source_kind: experience
related: []
depth: deep
deep_minutes: 7
---

<!-- DIAGRAM_START -->
## 图解

<figure>
  <img src="/images/diagrams/zh/image-to-video.png" alt="图生视频：首帧和尾帧先定住">
  <figcaption>中间的运动不是靠长提示词控制，而是被首尾两张图夹住。首帧和尾帧越明确，中间越不容易漂。</figcaption>
</figure>
<!-- DIAGRAM_END -->

先做对一张图，再让它动。图生视频的关键不是提示词写多长，是首尾帧和运动幅度。

## 先图后视频

先用图像模型把构图、光线、人物定下来。图不对，视频只会把错误放大。首帧要留出运动空间：人物前方有路，手边有道具。

不要用一张构图很满的图去生成运动。模型没有地方让人物走，只能让人脸变形。

## 首尾帧

能控首尾帧就控：首帧是起点，尾帧是终点。两帧之间只放一个动作，比如“转身”“放下杯子”“抬头”。

没有尾帧控制时，把提示词写成动作而不是情绪：“她把手从口袋拿出来”，不要写“她感到紧张”。

## 运动小一点

一个镜头只做一个动作，3–5 秒。运动越大，模型越容易崩手、崩脸、崩背景。先拍小动作，再用剪辑制造更大的节奏。

如果一条生成里人物走了三步、镜头还推拉，基本不可用。把动作拆成两条，剪起来更稳。

## 3 条验收

- 首帧有明确的运动空间。
- 一条生成只包含一个主要动作。
- 记录首尾帧与提示词，能复现。

<!-- DEEP_DIVE_START -->
## 深读
<p><strong>约 7 分钟。</strong> 图生视频不是让画面动起来，是让同一个主体在时间里保持是同一个人。</p>
### 先选一张能动的图
<p>主体清楚、四肢可辨、背景不穿越、光线方向明确；一张正面大头照很难动，一张半身、手上有动作的图更好动。</p><p>分辨率不要太高，细节太多模型会抖；先裁成目标比例，避免生成时再拉伸。</p>
### 运动写小一点
<p>第一版只写一个动作：眨眼、转头、手抬起、头发被风吹；不要同时写走路、说话、镜头环绕。动作越多，脸越容易变。</p><p>镜头运动单独写：固定、轻推、横移；不要和人物动作混在一句。先保人物，再保镜头。</p>
### 用首尾帧和参考图
<p>能给尾帧就给尾帧，让模型知道最后停在哪；能给同一人物的多角度参考，就给三张，别只给一张。</p><p>生成后先看脸、手、衣服边缘；脸变了就降运动量，手变了就换姿势，不要用后期修脸掩盖结构问题。</p>
### 五分钟练习：三秒一个动作
<p>用一张半身图，生成三秒视频，只写“眨眼并轻微转头”，镜头固定；生成三次，选脸最稳的一条。</p><p>再把动作换成“抬手”，比较哪类动作更容易崩；把结论写进下一张图的姿势要求。</p>
### 什么时候算能剪
<p>三秒内脸不变、手不穿插、衣服边缘不跳、背景不液化、运动方向和提示词一致；五项都过，才算能剪。</p><p>有一项明显坏，不要靠变速和裁剪硬救；回到图和动作，重新生成一条更小的运动。</p>
### 再看一遍手
<p>逐帧看手：手指有没有多、有没有穿过衣服、有没有突然变短；手是图生视频最容易崩的地方。手一坏，宁可把动作改成双手出画，也不要交给后期修。</p>
### 图生视频，十项检查
<ul><li>主体清楚四肢可辨</li><li>背景不穿越身体</li><li>光线方向明确</li><li>先裁目标比例</li><li>第一版只写一个动作</li><li>镜头运动单独写</li><li>有尾帧就给尾帧</li><li>同一人物三张参考</li><li>先查脸手衣服边缘</li><li>脸变就降运动量</li></ul><p>图生视频的第一原则，是宁可动作小，也不要脸变。</p>
<!-- DEEP_DIVE_END -->
