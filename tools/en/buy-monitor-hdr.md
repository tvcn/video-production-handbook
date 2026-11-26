---
id: tools.guide.buy-monitor-hdr.en
site: tools
type: article
lang: en
translation_key: tools.guide.buy-monitor-hdr
translation_status: reviewed
title: 'Buying an HDR Monitor: Peak Nits Is Not Everything'
summary: HDR monitoring depends on peak, black level, gamut, tone mapping, and calibration. Buying on “1000 nits” alone gets a bright screen with clipped highlights.
slug: buy-monitor-hdr
aliases:
- buy-monitor-hdr
canonical_site: tools
canonical_path: /en/article/buy-monitor-hdr/
status: published
diagram: /images/diagrams/en/buy-monitor-hdr.svg
diagram_alt: HDR monitor buying diagram
diagram_caption: 'Diagram: peak, black, gamut, tone mapping, and calibration decide whether HDR grading is trustworthy.'
difficulty: intermediate
stage: handbook
format: guide
deep_minutes: 7
depth: deep
authors:
- TVCN Tools Desk
last_verified: '2026-11-26'
review_due: '2027-02-26'
sources:
- S24
- S26
test_context: 'Review setup: Windows 11 workstation + iPhone 13, Chrome 131; bodies/lenses checked against public specs and short samples, not lab instruments.'
known_failures: 'Known failures: grey-channel firmware/warranty vary; samples do not prove retail units; prices and stock expire.'
verified: 2026-11-22
related: [tools.guide.buy-nas-raid, tools.guide.buy-post-software, shoot.camera.axis-line]
source_kind: sourced
---
<!-- DIAGRAM_START -->
<h2>Diagram</h2>
<figure>
  <img src="/images/diagrams/en/buy-monitor-hdr.svg" alt="HDR monitor buying diagram">
  <figcaption>Diagram: peak, black, gamut, tone mapping, and calibration decide whether HDR grading is trustworthy.</figcaption>
</figure>
<!-- DIAGRAM_END -->
<h2>First decision: which link is missing</h2><p>Decide whether you deliver HDR or only view HDR references. For reference only, a calibrated SDR screen with a transform LUT can work. For an HDR master, peak, black, gamut, and tone mapping must all pass. Do not use a TV as a grading monitor; its sharpening and dynamic contrast lie.</p><p><strong>Fits:</strong></p><ul><li>HDR master/grading</li><li>Platform HDR delivery QC</li><li>PQ/HLG reference</li></ul><p><strong>Does not fit:</strong></p><ul><li>SDR-only delivery</li><li>Under ¥10k, do SDR first</li><li>Viewing only, no grading</li></ul><h2>Test protocol: reproducible, no invented scores</h2><p>Bring an HDR clip with a window, neon, and a dark scene. Use a signal generator to confirm PQ/HLG. Check whether blacks go grey and highlights clip to white. Use a color chart for P3 coverage.</p><div class="table-scroll"><table class="data-table"><thead><tr><th>Check</th><th>Pass line</th><th>Reference/log</th></tr></thead><tbody><tr><td>峰值</td><td>窗外/霓虹有层次，不切白</td><td>HDR 测试片</td></tr><tr><td>黑位</td><td>暗场黑得下去，不发灰</td><td>黑场片段</td></tr><tr><td>色域</td><td>P3 色卡无明显偏差</td><td>色卡</td></tr><tr><td>色调映射</td><td>PQ/HLG 切换正确</td><td>信号发生器</td></tr><tr><td>校准</td><td>3D LUT/自动校准可查</td><td>校准报告</td></tr></tbody></table></div><h2>Price bands: total cost of ownership first</h2><p>Look beyond the sticker: cards, batteries, adapters, gimbal, stands, software subscriptions, and repair. Bands describe the minimum kit for a real project type, not toy pricing.</p><div class="table-scroll"><table class="data-table"><thead><tr><th>Tier</th><th>Reference</th><th>Includes</th><th>Watch</th></tr></thead><tbody><tr><td>Entry</td><td>¥5,000–12,000</td><td>Bright SDR/entry HDR</td><td>Limited HDR calibration</td></tr><tr><td>Main</td><td>¥12,000–35,000</td><td>HDR monitoring, P3, 3D LUT</td><td>Calibration extra</td></tr><tr><td>Advanced</td><td>¥35,000–100,000</td><td>Pro HDR master monitor</td><td>Environment/calibration</td></tr></tbody></table></div><p>Prices are China mainland channel references as of November 2026; tax and quotes vary. Not buying advice.</p><h2>Alternatives and upgrades: do not add money on the wrong axis</h2><ul><li>Calibrated SDR + transform LUT</li><li>Rent an HDR suite</li><li>SDR master first</li></ul><h2>Buying steps: bring footage, not spec sheets</h2><p>Run these in order before paying. If one fails, do not tell yourself post will fix it.</p><ol><li>Bring HDR test clip</li><li>Signal generator PQ/HLG</li><li>Check black level</li><li>Color chart P3</li><li>Check calibration report/LUT</li></ol><h2>Check</h2><ul><li>Highlights have layers, not clipped white.</li><li>Dark scenes are not grey.</li><li>P3 gamut is acceptable.</li><li>PQ/HLG switch correct.</li><li>3D LUT/calibration report exists.</li><li>Room light is controllable.</li></ul>

<!-- DEEP_DIVE_START -->
## Deep dive
<p><strong>About 7 minutes.</strong> This section does not repeat the method above. It adds three things: two conditions, a counterexample and a reusable model, so you can decide when to change the method.</p>
### Condition A: mostly SDR
<p>If ninety percent of the work is SDR, an HDR monitor is not the first priority. SDR needs accurate black, stable white and a reliable waveform; a 1000-nit HDR monitor with a bad SDR preset is worse. Check whether the SDR preset can be calibrated.</p><p>SDR monitoring also depends on ambient light: a bright room forces brightness up and black drifts. Decide shading and room level before buying; without environment control, an expensive monitor is still guesswork.</p>
### Condition B: HDR delivery
<p>HDR delivery starts with who watches: PQ or HLG, what peak, whether Dolby Vision is required. The monitor must display the target peak and tone-map reliably; “1000 nits” is not enough, check mapping at 100, 400 and 1000 nits.</p><p>HDR also depends on shadows: it is not only brightness; black and near-black separation matter more. Take your own dark footage to test, not the showroom demo; demos are all highlights. If shadows collapse, HDR is only bright.</p>
### Counterexample: buying on peak nits alone
<p>A monitor claims 1600 nits. At home everything below 100 nits is black, shadows have no layers; HDR highlights are bright but faces in shadow are a patch. The spec wins, the image loses.</p><p>The fix is not a brighter monitor; test three bands with your footage: shadow, mid, highlight. If each band shows layers, it is HDR monitoring. Peak is a ceiling, not a capability.</p>
### Reusable model
<p><strong>Delivery target → peak → tone mapping → shadows → environment.</strong> Set delivery, then peak, then mapping, then shadows, then room. With all five, an HDR monitor is not a spec ornament.</p><p>Before buying, run a three-band test: same footage at 100, 400 and 1000 nits, check shadow, skin and highlight. Only pay when all three are acceptable.</p>
<!-- DEEP_DIVE_END -->

<!-- SOURCES_START -->
## References and further reading

- [S24] [ACESCentral: ACES](https://acescentral.com/) — Accessed 2026-11-26. Used to check the terminology/method/rule in the “First decision: which link is missing” section against ACES color specification, not a grading tutorial; it does not verify numbers, model choices or on-set conclusions derived from this page, and is not a substitute for a test.
- [S26] [ITU-R BT.2020](https://www.itu.int/rec/R-REC-BT.2020/en) — Accessed 2026-11-26. Used to check the terminology/method/rule in the “Test protocol: reproducible, no invented scores” section against BT.2020 UHD parameters, not on-set exposure advice; it does not verify numbers, model choices or on-set conclusions derived from this page, and is not a substitute for a test.
<!-- SOURCES_END -->

