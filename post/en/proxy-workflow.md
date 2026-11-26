---
id: post.editing.proxy-workflow.en
site: post
type: article
lang: en
translation_key: post.editing.proxy-workflow
translation_status: reviewed
title: 'Proxy Workflow: Cut First, Quality Later'
summary: Proxies do not lower the final quality; they let the edit move. Keep the
  originals untouched.
slug: proxy-workflow
aliases:
- proxy-workflow
canonical_site: post
canonical_path: /en/article/proxy-workflow/
status: published
diagram: /images/diagrams/en/proxy-workflow.svg
diagram_alt: 'Structure diagram for Proxy Workflow: Cut First, Quality Later.'
diagram_caption: Watch “Generate ProRes Proxy or quarter-resolution files on a” and
  “Set the originals to read-only and edit only”; judge whether removing one shot
  makes the scene faster rather than muddier.
difficulty: beginner
stage: field-note
format: handbook
authors:
- TVCN Post Desk
last_verified: '2026-11-26'
review_due: '2027-02-26'
related: [post.delivery.qc, post.sound.room-tone, shoot.camera.composition]
depth: deep
deep_minutes: 5
sources:
- S70
- S35
- S29
test_context: 'Review setup: Windows 11 (RTX 3060) + macOS 14 (M1); re-run in DaVinci
  Resolve 20 and Premiere Pro 2025; results vary by machine.'
known_failures: 'Known failures: older-version timelines break; camera Logs need remapping;
  lost proxies require relinking.'
verified: 2026-11-22
source_kind: sourced
---
<p>Proxies solve “the machine cannot cut the originals,” not “quality can drop.” Keep the original filename, timecode and reel name, finish the cut, relink to the originals, then export the master.</p>
<!-- DIAGRAM_START -->
<h2>Diagram</h2>
<figure>
  <img src="/images/diagrams/en/proxy-workflow.svg" alt="Structure diagram for Proxy Workflow: Cut First, Quality Later.">
  <figcaption>Watch “Generate ProRes Proxy or quarter-resolution files on a” and “Set the originals to read-only and edit only”; judge whether removing one shot makes the scene faster rather than muddier.</figcaption>
</figure>
<!-- DIAGRAM_END -->
<section><h2 id="section-1">A proxy is an editing copy, not a delivery file</h2><p>Choose proxy resolution from timeline needs, not always the smallest. On multicam, test how many streams one machine can play before choosing a bitrate.</p><h2 id="section-2">Limits</h2><p>Every proxy must map to one original. Renaming, dropping timecode or mixing frame rates turns relinking into manual file hunting. Before delivery, confirm the master points at originals, not proxies.</p></section><section><h2 id="section-3">On set</h2><p>Use ProRes Proxy or quarter-resolution proxies on a separate SSD. Lock the originals as read-only, edit only proxies, and relink before delivery.</p></section><section><h2 id="section-4">Do this</h2><p>Proxies do not lower delivery quality; they let the edit run. Originals stay untouched beside them.</p><ol><li>Generate ProRes Proxy or quarter-resolution files on a separate SSD.</li><li>Set the originals to read-only and edit only against proxies.</li><li>Relink to originals before delivery and confirm no proxy slipped into the master.</li></ol></section><section><h2 id="section-5">Avoid</h2><p>Do not treat proxies as masters; deliver before relinking and the quality shows.</p></section><section><h2>Judge</h2><p>This page passes on three observable checks, not slogans:</p><ul><li><strong>1.</strong> Proxies and originals live on separate drives and the originals are read-only.</li><li><strong>2.</strong> The timeline references proxies only, with one-to-one names and paths.</li><li><strong>3.</strong> After relinking, three random shots return to original resolution and detail.</li></ul></section><section><h2>Failures</h2><p>Any one of these means stop and fix it before post:</p><ul><li><strong>1.</strong> Check 1 is only staged (“Proxies and originals live on separate drives…”); another camera position or location exposes it.</li><li><strong>2.</strong> Check 2 is left to post or a verbal explanation (“The timeline references proxies only, with one…”); nothing on set can be rechecked.</li><li><strong>3.</strong> Do not treat proxies as masters; deliver before relinking and the quality shows.</li></ul></section><section><h2>Extend</h2><p><strong>10-minute exercise:</strong> Take 30 seconds of footage and make an A/B, changing only “Generate ProRes Proxy or quarter-resolution files on a”. Note one timecode and one difference before keeping it.</p></section>
<h2>Check</h2><ul><li>Proxies and originals live on separate drives and the originals are read-only.</li><li>The timeline references proxies only, with one-to-one names and paths.</li><li>After relinking, three random shots return to original resolution and detail.</li></ul>

<!-- DEEP_DIVE_START -->
## Deep dive
<p><strong>About 5 minutes.</strong> A proxy is not a quality downgrade; it makes the edit run. The original stays untouched; the proxy only buys responsiveness.</p>
### When you need proxies
<p>Above 4K, multicam, or an older machine: if playback stutters, make proxies. A smooth 1080 single track does not need them; do not add process for its own sake.</p><p>Set proxy resolution to the timeline. Do not make a proxy larger than the timeline; 1080 proxies are enough for a 1080 cut.</p>
### How to generate proxies
<p>Keep filename, timecode, and reel name identical; put them in a separate Proxy folder. Never overwrite the originals or change their folder structure.</p><p>Spot-check three shots after generating; confirm audio and color survived. A proxy can be soft, but it cannot lose sound.</p>
### Relink and export
<p>Lock the cut before relinking to originals. After relink, check speed changes, captions, and transitions; proxy and original can differ by a frame.</p><p>Always export from the originals; proxies stay in the project. Treat a proxy as a master and quality drops exactly when it matters.</p>
### Proxy naming and folders
<p>Originals in Camera, proxies in Proxy, projects in Project. Keep the three folders separate.</p><p>Add _proxy to the proxy filename so relink is obvious. Never rename the originals.</p>
### Multicam proxies
<p>Make multicam proxies at the same resolution and frame rate, or the timeline refuses them.</p><p>Sync once after generating and confirm audio and camera mapping before editing.</p>
### Ten proxy-workflow checks
<ul><li>Only for high resolution or multicam</li><li>Proxy filenames match originals</li><li>Proxies in a separate folder</li><li>Never overwrite originals</li><li>Keep timecode and reel names</li><li>Spot-check three shots after generating</li><li>Edit with proxies</li><li>Lock the cut before relinking</li><li>Check speed and captions after relink</li><li>Export from originals</li></ul><p>A proxy is scaffolding, not the building. Take it down after the cut; do not deliver from inside it.</p>
### When you have five minutes
<ul><li>Only for high resolution or multicam</li><li>Proxy names match originals</li><li>Keep proxies in a separate folder</li><li>Spot-check three shots</li><li>Lock before relinking</li><li>Export from originals</li></ul><p>Proxies let the edit run; originals let the film stand at the end. A broken proxy can be rebuilt; a lost original has no second take.</p>
<!-- DEEP_DIVE_END -->

<!-- SOURCES_START -->
## References and further reading

- [S70] [FFmpeg: Documentation](https://ffmpeg.org/documentation.html) — Accessed 2026-11-26. Used to check the terminology/method/rule in the “A proxy is an editing copy, not a delivery file” section against FFmpeg codec/muxing documentation, not a delivery spec; it does not verify numbers, model choices or on-set conclusions derived from this page, and is not a substitute for a test.
- [S35] [Avid: Resource Center](https://www.avid.com/resource-center) — Accessed 2026-11-26. Used to check the terminology/method/rule in the “Limits” section against Avid resource center, not an independent review; it does not verify numbers, model choices or on-set conclusions derived from this page, and is not a substitute for a test.
- [S29] [YouTube: Upload Encoding Specs](https://support.google.com/youtube/answer/1722171) — Accessed 2026-11-26. Used to check the terminology/method/rule in the “On set” section against YouTube upload encoding recommendations, not creative standards; it does not verify numbers, model choices or on-set conclusions derived from this page, and is not a substitute for a test.
<!-- SOURCES_END -->

