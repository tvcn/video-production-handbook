---
id: tools.calculators.fov
site: tools
type: calculator
lang: zh
translation_key: tools.calculators.fov
translation_status: source
title: 镜头视角计算器：焦距、画幅与水平视角
summary: 输入传感器宽度和焦距，算出水平视角；用来判断这支镜头在室内、户外和人物近景里够不够用。
slug: fov
canonical_site: tools
canonical_path: /calculators/fov/
status: published
difficulty: beginner
stage: prep
format: all
tools: [camera, lens]
authors: [editor]
reviewers: [technical-reviewer]
diagram: /images/diagrams/zh/fov.svg
diagram_alt: "视角不是放大：画幅和焦距一起决定"
diagram_caption: "同一焦距，画幅越小，视角越窄；视角变窄不等于把主体放大。"
last_verified: 2026-11-20
review_due: 2027-05-20
source_kind: experience
related: [main.paths.first-film]
---

<!-- DIAGRAM_START -->
## 图解

<figure>
  <img src="/images/diagrams/zh/fov.svg" alt="视角不是放大：画幅和焦距一起决定">
  <figcaption>同一焦距，画幅越小，视角越窄；视角变窄不等于把主体放大。</figcaption>
</figure>
<!-- DIAGRAM_END -->

## 这个计算器解决什么

“这支 24mm 在室内够不够广？”“85mm 拍人物会不会太窄？”不要靠感觉，先算水平视角。

## 公式

\[
\theta = 2 \times \arctan\left(\frac{w}{2f}\right)
\]

其中 \(w\) 是传感器宽度，\(f\) 是焦距，\(\theta\) 是水平视角。

## 常见画幅宽度

- 全画幅：36mm
- APS-C：23.5mm
- M4/3：17.3mm

## 怎么用

1. 选传感器宽度。
2. 输入焦距。
3. 看水平视角。
4. 如果视角小于场景需要的宽度，换广一点；如果人物太变形，换长一点。

## 3 条验收

- 能说清“广角”和“长焦”改变的是什么，不只是放大。
- 知道同一焦距在不同画幅上的视角不同。
- 能用视角反推机位距离。

## 边界

这是水平视角，不含畸变、呼吸效应和镜头实际标称误差；电影镜头以实测为准。
