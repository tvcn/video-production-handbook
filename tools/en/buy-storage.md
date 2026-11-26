---
id: tools.guide.buy-storage.en
site: tools
type: article
lang: en
translation_key: tools.guide.buy-storage
translation_status: reviewed
title: 'Buying Project Storage: Speed, Capacity, and Backup'
summary: Storage is not “bigger is better.” It is “the shoot does not stop, the offload does not lose data, and the project is findable later.” Calculate a real shoot day before buying.
slug: buy-storage
aliases:
- buy-storage
canonical_site: tools
canonical_path: /en/article/buy-storage/
status: published
diagram: /images/diagrams/en/buy-storage.svg
diagram_alt: Project storage buying diagram
diagram_caption: 'Diagram: sustained write, capacity, interface, heat, and warranty decide whether a shoot day stops.'
difficulty: intermediate
stage: handbook
format: guide
authors:
- TVCN Tools Desk
last_verified: '2026-11-26'
review_due: '2027-02-26'
sources:
- S70
- S29
- S57
test_context: 'Review setup: Windows 11 workstation + iPhone 13, Chrome 131; bodies/lenses checked against public specs and short samples, not lab instruments.'
known_failures: 'Known failures: grey-channel firmware/warranty vary; samples do not prove retail units; prices and stock expire.'
verified: 2026-11-23
related: [tools.guide.buy-storage-cards, tools.guide.buy-timecode, shoot.camera.axis-line]
source_kind: sourced
---
<!-- DIAGRAM_START -->
<h2>Diagram</h2>
<figure>
  <img src="/images/diagrams/en/buy-storage.svg" alt="Project storage buying diagram">
  <figcaption>Diagram: sustained write, capacity, interface, heat, and warranty decide whether a shoot day stops.</figcaption>
</figure>
<!-- DIAGRAM_END -->
<h2>First decision: which link is missing</h2><p>Calculate a shoot day: camera bitrate × hours × cameras × copies. 4K 10-bit 422 is roughly 100–200 GB/hour; three cameras for eight hours is 2.4–4.8 TB before copies. Size for the worst day, not “enough this year.”</p><p><strong>Fits:</strong></p><ul><li>Multicam/high-bitrate projects</li><li>On-set offload and backup</li><li>Long-term project archive</li></ul><p><strong>Does not fit:</strong></p><ul><li>Single-camera 1080p lightweight work</li><li>One drive for everything</li><li>Using NAS as an on-set drive</li></ul><h2>Test protocol: reproducible, no invented scores</h2><p>Record 30 minutes at the project bitrate or copy a 100GB file and log real write speed and throttling. Do not trust the interface label: USB-C is not Thunderbolt, and a spinning drive cannot saturate 10GbE.</p><div class="table-scroll"><table class="data-table"><thead><tr><th>Check</th><th>Pass line</th><th>Reference/log</th></tr></thead><tbody><tr><td>持续写入</td><td>项目码率 2 倍以上，30 分钟不降</td><td>满盘/大文件</td></tr><tr><td>容量</td><td>最坏拍摄日 2 份仍有余量</td><td>项目日计算</td></tr><tr><td>接口</td><td>实际拷贝速度达标</td><td>100GB 计时</td></tr><tr><td>散热</td><td>连续工作不烫手/不降速</td><td>30 分钟</td></tr><tr><td>保修</td><td>3–5 年，可换盘/可恢复</td><td>发票/序列</td></tr></tbody></table></div><h2>Price bands: total cost of ownership first</h2><p>Look beyond the sticker: cards, batteries, adapters, gimbal, stands, software subscriptions, and repair. Bands describe the minimum kit for a real project type, not toy pricing.</p><div class="table-scroll"><table class="data-table"><thead><tr><th>Tier</th><th>Reference</th><th>Includes</th><th>Watch</th></tr></thead><tbody><tr><td>Entry</td><td>¥1,000–3,000</td><td>2–4TB portable SSD + backup drive</td><td>Limited capacity/sustained write</td></tr><tr><td>Main</td><td>¥3,000–8,000</td><td>4–8TB fast SSD + two backups</td><td>Interface and heat</td></tr><tr><td>Advanced</td><td>¥8,000–25,000</td><td>NAS/array + 10GbE + offsite</td><td>Ops and power</td></tr></tbody></table></div><p>Prices are China mainland channel references as of November 2026; tax and quotes vary. Not buying advice.</p><h2>Alternatives and upgrades: do not add money on the wrong axis</h2><ul><li>Two ordinary SSDs for double backup</li><li>Rent an on-set DIT</li><li>Existing drives + cloud backup</li></ul><h2>Buying steps: bring footage, not spec sheets</h2><p>Run these in order before paying. If one fails, do not tell yourself post will fix it.</p><ol><li>Calculate worst shoot day</li><li>Record 30 min at project bitrate</li><li>Time a 100GB copy</li><li>Confirm interface and power</li><li>Check warranty/data recovery</li></ol><h2>Check</h2><ul><li>Two copies of the worst day fit.</li><li>Sustained write is 2× bitrate.</li><li>Copy speed meets the real need.</li><li>No throttle in 30 minutes.</li><li>At least two copies on separate media/site.</li><li>Warranty and recovery are known.</li></ul>
<h2>Decision tree: working disk, backup, archive</h2>
<p>Most people treat storage as one drive, then lose the working disk with no backup or keep an archive too slow to use. Split three layers: working fast, backup independent, archive readable in ten years.</p><ol><li>Working: SSD/RAID 0, capacity covers the current project, speed at least twice the project bitrate.</li><li>Backup: independent HDD/NAS, at least one offline copy.</li><li>Archive: LTO or cold drive, verifiable and restorable.</li><li>Name, checksum and retention for every layer.</li></ol>
<h2>Eight comparisons: capacity, speed and redundancy cannot all win</h2>
<div class="table-scroll"><table class="data-table"><thead><tr><th>Item</th><th>Pass line</th><th>Fits</th><th>Does not fit</th></tr></thead><tbody><tr><td>Working disk</td><td>Sustained write at twice project bitrate</td><td>Editing</td><td>Long archive</td></tr><tr><td>RAID 0</td><td>Two-drive speed with a separate backup</td><td>Working disk</td><td>Only copy</td></tr><tr><td>RAID 1/5</td><td>Rebuilds after one drive failure</td><td>Team share</td><td>Extreme writes</td></tr><tr><td>NAS</td><td>10GbE reaches about 500MB/s</td><td>Multi-user</td><td>Single mobile</td></tr><tr><td>Portable drive</td><td>Stable USB 10Gbps</td><td>On-set backup</td><td>Long cold archive</td></tr><tr><td>LTO</td><td>Offline, verifiable, long life</td><td>Archive</td><td>Frequent access</td></tr><tr><td>Cloud</td><td>Restore time acceptable</td><td>Off-site backup</td><td>Daily edit of large projects</td></tr><tr><td>Total cost</td><td>Working + backup + archive + restore drill</td><td>Every project</td><td>Price per TB only</td></tr></tbody></table></div>
<h2>Test scope: sustained write and restore drill</h2>
<p>Write for thirty minutes and log speed, temperature and dropout; restore a random file from backup and time it; compare checksums. Not measured: lab IOPS or long-term aging.</p>
<h2>Continue: storage and backup hub</h2>
<p>Cards first, then arrays and backup.</p><ul><li><a href="/en/article/buy-storage-cards/">Buying cards: VPG, sustained write, heat</a></li><li><a href="/en/article/buy-nas-raid/">Buying NAS/RAID: throughput, rebuild, noise</a></li><li><a href="/en/article/ssd-raid/">SSD RAID: editing array</a></li><li><a href="/en/article/backup-3-2-1/">3-2-1 backup: finish it today</a></li><li><a href="/en/article/restore-test/">Restore drill: pick one random file</a></li><li><a href="/en/article/storage/">Media management: back up today, name for search</a></li><li><a href="/en/article/set-mediabay/">Media cart: offload and naming on set</a></li><li><a href="/en/article/lto-archive/">LTO archive: long-term cold storage</a></li><li><a href="/en/article/export-prores/">ProRes export: archive and delivery</a></li><li><a href="/en/article/proxy-create/">Proxy creation: edit without stutter</a></li></ul>
<h2>Verification and price date</h2>
<p>Verified 2026-11-23. Prices are China mainland channel references; sustained write and restore times are local short tests, not lab scores.</p>
<!-- P5_EXTRA_START -->
<h2>Buying order: rent before buying</h2>
<p>Borrow a card/SSD for one real project; log sustained write and offload time before choosing capacity and redundancy.</p><ol><li>Rent the target body and a common lens once; shoot a real project.</li><li>Confirm mount, adapter, autofocus and power.</li><li>Total the cards, batteries, monitor, storage and repair.</li><li>Keep 10% for surprises and consumables.</li><li>Buy the second lens after the first delivery.</li></ol>
<h2>Add: failure cases</h2>
<p>The most common storage error is treating RAID 0 as the only copy.</p><div class="table-scroll"><table class="data-table"><thead><tr><th>Move</th><th>Result</th><th>Replace with</th></tr></thead><tbody><tr><td>Keep the only footage on RAID 0</td><td>One drive failure loses the project</td><td>Independent backup</td></tr><tr><td>Test peak speed only</td><td>Sustained writes drop and the edit stalls</td><td>Thirty-minute write</td></tr><tr><td>Use a USB hub</td><td>Shared bandwidth halves speed</td><td>Connect directly</td></tr></tbody></table></div>
<!-- P5_EXTRA2_START -->
<h2>Add: pre-purchase checklist</h2>
<p>Storage fails on the project day. Run a restore drill before buying.</p><div class="table-scroll"><table class="data-table"><thead><tr><th>Check</th><th>Pass line</th><th>Log</th></tr></thead><tbody><tr><td>Sustained write</td><td>Thirty minutes at twice project bitrate</td><td>Speed screenshot</td></tr><tr><td>Backup</td><td>At least one independent copy</td><td>Backup list</td></tr><tr><td>Restore</td><td>A random file restores</td><td>Restore timing</td></tr><tr><td>Checksum</td><td>Matches</td><td>Verification tool</td></tr></tbody></table></div>
<!-- P5_EXTRA3_START -->
<h2>One line for the set</h2>
<p>The working disk may fail; the backup must not fail with it. That is the whole point of three layers.</p>

<!-- SOURCES_START -->
## References and further reading

- [S70] [FFmpeg: Documentation](https://ffmpeg.org/documentation.html) — Accessed 2026-11-26. Used to check the terminology/method/rule in the “Decision tree: working disk, backup, archive” section against FFmpeg codec/muxing documentation, not a delivery spec; it does not verify numbers, model choices or on-set conclusions derived from this page, and is not a substitute for a test.
- [S29] [YouTube: Upload Encoding Specs](https://support.google.com/youtube/answer/1722171) — Accessed 2026-11-26. Used to check the terminology/method/rule in the “First decision: which link is missing” section against YouTube upload encoding recommendations, not creative standards; it does not verify numbers, model choices or on-set conclusions derived from this page, and is not a substitute for a test.
- [S57] [Blackmagic: URSA Mini Pro 12K Specs](https://www.blackmagicdesign.com/products/blackmagicursaminipro/techspecs) — Accessed 2026-11-26. Used to check the terminology/method/rule in the “Buying steps: bring footage, not spec sheets” section against URSA Mini Pro 12K specs, not independent testing; it does not verify numbers, model choices or on-set conclusions derived from this page, and is not a substitute for a test.
<!-- SOURCES_END -->

