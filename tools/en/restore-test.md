---
id: tools.tutorial.restore-test.en
site: tools
type: article
lang: en
translation_key: tools.tutorial.restore-test
translation_status: reviewed
title: 'Restore Test: Pick One Random File'
summary: Restore one random file from backup; a backup that will not open does not
  exist.
slug: restore-test
aliases:
- restore-test
canonical_site: tools
canonical_path: /en/article/restore-test/
status: published
diagram: /images/diagrams/en/restore-test.svg
diagram_alt: 'Structure diagram for Restore Test: Pick One Random File.'
diagram_caption: Watch “Pick one file at random.” and “Restore it to another machine.”;
  judge whether the spec maps to one concrete shooting problem.
difficulty: beginner
stage: field-note
format: handbook
authors:
- TVCN Tools Desk
last_verified: '2026-11-25'
review_due: '2027-05-25'
related:
- tools.tutorial.set-mediabay.en
- tools.tutorial.white-balance-gray.en
- tools.tutorial.boom-swing.en
source_kind: experience
---

<p>Once a month, restore one random project to a different drive, open it, relink media and export ten seconds. If restore fails, the backup is not there.</p>
<!-- DIAGRAM_START -->
<h2>Diagram</h2>
<figure>
  <img src="/images/diagrams/en/restore-test.svg" alt="Structure diagram for Restore Test: Pick One Random File.">
  <figcaption>Watch “Pick one file at random.” and “Restore it to another machine.”; judge whether the spec maps to one concrete shooting problem.</figcaption>
</figure>
<!-- DIAGRAM_END -->
<section><h2 id="section-1">A backup passes when it restores, not when it exists</h2><p>Record restore time and missing files; if every restore needs manual hunting, the structure or checksum is broken.</p><h2 id="section-2">Limits</h2><p>RAID and sync folders are not backup. They sync deletions and encryption. Keep one offline, read-only or versioned copy and test restore regularly.</p><h2 id="section-3">Restore drill: pick a random file and actually restore it</h2>
<p>A backup that has never been restored is not a backup. Run a 30-minute drill monthly: pick a random project file, restore to a clean disk, open it and compare the hash.</p>
<ol><li>Pick at random, not “the most important,” so you do not only rehearse the familiar path.</li><li>Restore to a machine without the original; never overwrite in place.</li><li>Check size, hash and that it opens. Log the time; over two hours means change the plan.</li></ol>
<p>Acceptance: the file opens, the timeline has no offline media and the hash matches. Missing one means the backup plan is not proven.</p></section><section><h2 id="section-4">On set</h2><p>Restore one random file to another machine and play it. If it fails, redo the backup.</p></section><section><h2 id="section-5">Do this</h2><p>A restore drill pulls one random file from backup and opens it; a backup that will not open does not exist.</p><ol><li>Pick one file at random.</li><li>Restore it to another machine.</li><li>Open and play; if it fails, redo the backup.</li></ol></section><section><h2 id="section-6">Avoid</h2><p>Do not trust a green check in backup software; without a restore, you do not know it opens.</p></section><section><h2>Judge</h2><p>Three signals are observable on set:</p><ul><li>every spec maps to one concrete shooting problem</li><li>weight, power and connections hold on a real rig</li><li>a 60-second test leaves one comparable number</li></ul></section><section><h2>Failures</h2><p>These three moves erase the detail you just built:</p><ul><li>specs without connections, power or weight</li><li>batteries, storage or body do not match after purchase</li><li>no 60-second test, so the problem arrives on the shoot</li></ul></section><section><h2>Extend</h2><p><strong>10-minute exercise:</strong> Run a 60-second test with the gear you already own, measuring only “Pick one file at random.”. Record two numbers: what you need and what the gear actually gives.</p></section>
<h2>Check</h2><ul><li>A random file is chosen, not the most familiar one.</li><li>Restore goes to another machine, not the original path.</li><li>The file opens and plays; failures trigger a redo log.</li></ul>
