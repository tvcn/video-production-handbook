---
id: tools.capability.ssd-raid.en
site: tools
type: tool
lang: en
translation_key: tools.capability.ssd-raid
translation_status: reviewed
title: "SSD RAID: Edit Array, Not Archive"
summary: "SSD RAID is an edit workspace, not an archive; rebuilding costs more than backup."
slug: ssd-raid
aliases: [ssd-raid]
canonical_site: tools
canonical_path: /en/capability/ssd-raid/
status: published
diagram: /images/diagrams/en/ssd-raid.svg
diagram_alt: "SSD RAID: Edit Array, Not Archive three-step diagram"
diagram_caption: "Do the three steps in order, then look again at the image or file."
difficulty: beginner
stage: field-note
format: handbook
authors: [editor]
last_verified: 2026-11-20
review_due: 2027-05-20
related: [main.paths.first-film]
---

<p>SSD RAID is an edit workspace, not an archive; rebuilding costs more than backup.</p>
<!-- DIAGRAM_START -->
<h2>Diagram</h2>
<figure>
  <img src="/images/diagrams/en/ssd-raid.svg" alt="SSD RAID: Edit Array, Not Archive three-step diagram">
  <figcaption>Do the three steps in order, then look again at the image or file.</figcaption>
</figure>
<!-- DIAGRAM_END -->
<h2>On set</h2>
<p>Use RAID 0 only for working media and keep a RAID 1 or NAS as backup. Run a full-disk test and watch for slowdown.</p>
<h2>Do this</h2>
<p>SSD RAID is a editing work disk, not an archive; when the array dies, rebuilding costs more than backup.</p><ol><li>Build RAID 0 for working media only.</li><li>Set RAID 1 or NAS for backup.</li><li>Fill the drive and measure the speed drop.</li></ol>
<h2>Avoid</h2>
<p>Do not make RAID 0 the only storage; one drive failure takes all media.</p>
<h2>Check</h2>
<ul><li>RAID 0 holds working media only and originals are backed up elsewhere.</li><li>A RAID 1 or NAS backup job runs.</li><li>A full-drive test logs the write-speed drop.</li></ul>
