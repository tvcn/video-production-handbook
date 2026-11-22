---
id: tools.guide.buy-storage.en
site: tools
type: article
lang: en
translation_key: tools.guide.buy-storage
translation_status: reviewed
title: "Buying Project Storage: Speed, Capacity, and Backup"
summary: "Storage is not “bigger is better.” It is “the shoot does not stop, the offload does not lose data, and the project is findable later.” Calculate a real shoot day before buying."
slug: buy-storage
aliases: [buy-storage]
canonical_site: tools
canonical_path: /en/guide/buy-storage/
status: published
diagram: /images/diagrams/en/buy-storage.svg
diagram_alt: "Project storage buying diagram"
diagram_caption: "Diagram: sustained write, capacity, interface, heat, and warranty decide whether a shoot day stops."
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
  <img src="/images/diagrams/en/buy-storage.svg" alt="Project storage buying diagram">
  <figcaption>Diagram: sustained write, capacity, interface, heat, and warranty decide whether a shoot day stops.</figcaption>
</figure>
<!-- DIAGRAM_END -->
<h2>First decision: which link is missing</h2><p>Calculate a shoot day: camera bitrate × hours × cameras × copies. 4K 10-bit 422 is roughly 100–200 GB/hour; three cameras for eight hours is 2.4–4.8 TB before copies. Size for the worst day, not “enough this year.”</p><p><strong>Fits:</strong></p><ul><li>Multicam/high-bitrate projects</li><li>On-set offload and backup</li><li>Long-term project archive</li></ul><p><strong>Does not fit:</strong></p><ul><li>Single-camera 1080p lightweight work</li><li>One drive for everything</li><li>Using NAS as an on-set drive</li></ul><h2>Test protocol: reproducible, no invented scores</h2><p>Record 30 minutes at the project bitrate or copy a 100GB file and log real write speed and throttling. Do not trust the interface label: USB-C is not Thunderbolt, and a spinning drive cannot saturate 10GbE.</p><div class="table-scroll"><table class="data-table"><thead><tr><th>Check</th><th>Pass line</th><th>Reference/log</th></tr></thead><tbody><tr><td>持续写入</td><td>项目码率 2 倍以上，30 分钟不降</td><td>满盘/大文件</td></tr><tr><td>容量</td><td>最坏拍摄日 2 份仍有余量</td><td>项目日计算</td></tr><tr><td>接口</td><td>实际拷贝速度达标</td><td>100GB 计时</td></tr><tr><td>散热</td><td>连续工作不烫手/不降速</td><td>30 分钟</td></tr><tr><td>保修</td><td>3–5 年，可换盘/可恢复</td><td>发票/序列</td></tr></tbody></table></div><h2>Price bands: total cost of ownership first</h2><p>Look beyond the sticker: cards, batteries, adapters, gimbal, stands, software subscriptions, and repair. Bands describe the minimum kit for a real project type, not toy pricing.</p><div class="table-scroll"><table class="data-table"><thead><tr><th>Tier</th><th>Reference</th><th>Includes</th><th>Watch</th></tr></thead><tbody><tr><td>Entry</td><td>¥1,000–3,000</td><td>2–4TB portable SSD + backup drive</td><td>Limited capacity/sustained write</td></tr><tr><td>Main</td><td>¥3,000–8,000</td><td>4–8TB fast SSD + two backups</td><td>Interface and heat</td></tr><tr><td>Advanced</td><td>¥8,000–25,000</td><td>NAS/array + 10GbE + offsite</td><td>Ops and power</td></tr></tbody></table></div><p>Prices are China mainland channel references as of November 2026; tax and quotes vary. Not buying advice.</p><h2>Alternatives and upgrades: do not add money on the wrong axis</h2><ul><li>Two ordinary SSDs for double backup</li><li>Rent an on-set DIT</li><li>Existing drives + cloud backup</li></ul><h2>Buying steps: bring footage, not spec sheets</h2><p>Run these in order before paying. If one fails, do not tell yourself post will fix it.</p><ol><li>Calculate worst shoot day</li><li>Record 30 min at project bitrate</li><li>Time a 100GB copy</li><li>Confirm interface and power</li><li>Check warranty/data recovery</li></ol><h2>Check</h2><ul><li>Two copies of the worst day fit.</li><li>Sustained write is 2× bitrate.</li><li>Copy speed meets the real need.</li><li>No throttle in 30 minutes.</li><li>At least two copies on separate media/site.</li><li>Warranty and recovery are known.</li></ul>
<!-- SOURCES_START -->
<h2>Sources</h2>
<p class="source-types">Experience: field notes and buying checklists; tested: short tests against public specs, not lab scores; references: manufacturer and standards links below.</p>
<ul><li><span class="mono">[S23]</span> SMPTE Standards</li><li><span class="mono">[S25]</span> ITU-R BT.709</li><li><span class="mono">[S26]</span> ITU-R BT.2020</li><li><span class="mono">[S29]</span> YouTube Upload Specs</li><li><span class="mono">[S38]</span> State Taxation Administration</li></ul>
<p><a href="../../SOURCES.md">Full links and notes in SOURCES.md</a></p>
<!-- SOURCES_END -->
