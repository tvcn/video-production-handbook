---
id: tools.guide.buy-monitor.en
site: tools
type: article
lang: en
translation_key: tools.guide.buy-monitor
translation_status: reviewed
title: "Buying a Monitor: Brightness, Gamut, and Latency"
summary: "A monitor is not a bigger screen. It must be bright enough outdoors, calibratable, and low-latency for focus; if one fails, the camera screen is better."
slug: buy-monitor
aliases: [buy-monitor]
canonical_site: tools
canonical_path: /en/article/buy-monitor/
status: published
diagram: /images/diagrams/en/buy-monitor.svg
diagram_alt: "Monitor buying diagram"
diagram_caption: "Diagram: brightness, gamut, LUT, latency, and interfaces decide whether you can trust it on set."
difficulty: intermediate
stage: handbook
format: guide
authors: ["TVCN Tools Desk"]
last_verified: 2026-11-22
review_due: 2027-11-22
sources: [S23, S25, S26, S29, S38]
test_context: "Review setup: Windows 11 workstation + iPhone 13, Chrome 131; bodies/lenses checked against public specs and short samples, not lab instruments."
known_failures: "Known failures: grey-channel firmware/warranty vary; samples do not prove retail units; prices and stock expire."
verified: 2026-11-22
---

<!-- DIAGRAM_START -->
<h2>Diagram</h2>
<figure>
  <img src="/images/diagrams/en/buy-monitor.svg" alt="Monitor buying diagram">
  <figcaption>Diagram: brightness, gamut, LUT, latency, and interfaces decide whether you can trust it on set.</figcaption>
</figure>
<!-- DIAGRAM_END -->
<h2>First decision: which link is missing</h2><p>500 nits is enough indoors; outdoors needs 1000+ or a hood. Do not buy on specs: bring the camera, your Log footage, load a LUT, and shoot a moving object to check latency.</p><p><strong>Fits:</strong></p><ul><li>Exterior/high light, high nits</li><li>Grade/multicam, LUT and calibration</li><li>Focus pulling, low latency</li></ul><p><strong>Does not fit:</strong></p><ul><li>Indoor locked-off, camera screen is enough</li><li>Client viewing only, no calibration</li><li>Very low budget, buy light/audio first</li></ul><h2>Test protocol: reproducible, no invented scores</h2><p>Take the monitor to a window/outdoors and see whether shadows remain visible at 1000 nits. Connect the camera, load the project LUT, compare with the camera screen. Shoot a moving object and check smear/lag.</p><div class="table-scroll"><table class="data-table"><thead><tr><th>Check</th><th>Pass line</th><th>Reference/log</th></tr></thead><tbody><tr><td>亮度</td><td>户外日光下暗部可见</td><td>窗边/户外</td></tr><tr><td>色域</td><td>Rec.709 色卡无明显偏色</td><td>校准后色卡</td></tr><tr><td>LUT</td><td>3D LUT 加载正确</td><td>Log 素材</td></tr><tr><td>延迟</td><td>移动物体无明显滞后</td><td>横移/手挥</td></tr><tr><td>接口</td><td>SDI/HDMI 与锁定供电</td><td>现场接线</td></tr></tbody></table></div><h2>Price bands: total cost of ownership first</h2><p>Look beyond the sticker: cards, batteries, adapters, gimbal, stands, software subscriptions, and repair. Bands describe the minimum kit for a real project type, not toy pricing.</p><div class="table-scroll"><table class="data-table"><thead><tr><th>Tier</th><th>Reference</th><th>Includes</th><th>Watch</th></tr></thead><tbody><tr><td>Entry</td><td>¥1,000–3,000</td><td>5–7 inch, 500 nits, HDMI</td><td>Limited outdoors/calibration</td></tr><tr><td>Main</td><td>¥3,000–8,000</td><td>7 inch, 1000 nits, SDI, LUT</td><td>Battery/hood extra</td></tr><tr><td>Advanced</td><td>¥8,000–25,000</td><td>High brightness, wide gamut, pro calibration</td><td>Rig and power</td></tr></tbody></table></div><p>Prices are China mainland channel references as of November 2026; tax and quotes vary. Not buying advice.</p><h2>Alternatives and upgrades: do not add money on the wrong axis</h2><ul><li>Camera screen + hood</li><li>Rent a high-bright monitor</li><li>Recorder with monitoring first</li></ul><h2>Buying steps: bring footage, not spec sheets</h2><p>Run these in order before paying. If one fails, do not tell yourself post will fix it.</p><ol><li>Bring camera and Log footage</li><li>View at a window at 1000 nits</li><li>Load 3D LUT and compare</li><li>Moving object latency</li><li>Confirm SDI/power</li></ol><h2>Check</h2><ul><li>Shadows visible outdoors.</li><li>Rec.709 can be calibrated.</li><li>3D LUT loads correctly.</li><li>No obvious focus lag.</li><li>SDI/HDMI and locking power.</li><li>Battery/hood in total price.</li></ul>
<!-- SOURCES_START -->
<h2>Sources</h2>
<p class="source-types">Experience: field notes and buying checklists; tested: short tests against public specs, not lab scores; references: manufacturer and standards links below.</p>
<ul><li><span class="mono">[S23]</span> SMPTE Standards</li><li><span class="mono">[S25]</span> ITU-R BT.709</li><li><span class="mono">[S26]</span> ITU-R BT.2020</li><li><span class="mono">[S29]</span> YouTube Upload Specs</li><li><span class="mono">[S38]</span> State Taxation Administration</li></ul>
<p><a href="../../SOURCES.md">Full links and notes in SOURCES.md</a></p>
<!-- SOURCES_END -->
