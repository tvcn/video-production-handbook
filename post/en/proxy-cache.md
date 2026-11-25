---
id: post.assets.proxy-cache.en
site: post
type: article
lang: en
translation_key: post.assets.proxy-cache
translation_status: reviewed
title: 'Proxy and Cache: Do Not Fill the Drive First'
summary: Keep proxies and cache on a separate drive; a full edit drive drops frames.
slug: proxy-cache
aliases:
- proxy-cache
canonical_site: post
canonical_path: /en/article/proxy-cache/
status: published
diagram: /images/diagrams/en/proxy-cache.svg
diagram_alt: 'Structure diagram for Proxy and Cache: Do Not Fill the Drive.'
diagram_caption: Watch “Put proxies and cache on a second SSD.” and “Keep twenty percent
  free on the system drive”; judge whether removing one shot makes the scene faster
  rather than muddier.
difficulty: beginner
stage: field-note
format: handbook
authors:
- TVCN Post Desk
last_verified: '2026-11-25'
review_due: '2027-05-25'
related:
- post.assets.project-structure.en
- post.assets.backup-recovery.en
- post.delivery.qc.en
source_kind: experience
---

<p>A proxy is a low-resolution copy for editing; a cache is a preview file generated for playback. Deleting cache does not lose media; deleting proxies takes the timeline offline. Keep them in separate folders.</p>
<!-- DIAGRAM_START -->
<h2>Diagram</h2>
<figure>
  <img src="/images/diagrams/en/proxy-cache.svg" alt="Structure diagram for Proxy and Cache: Do Not Fill the Drive.">
  <figcaption>Watch “Put proxies and cache on a second SSD.” and “Keep twenty percent free on the system drive”; judge whether removing one shot makes the scene faster rather than muddier.</figcaption>
</figure>
<!-- DIAGRAM_END -->
<section><h2 id="section-1">Proxies and cache are different things</h2><p>Put proxies in a Proxy folder and cache in the software's cache directory; clean cache only.</p><h2 id="section-2">Limits</h2><p>Do not let a cleaner app delete “media cache” in one click. It may sweep proxies and originals. Confirm the path before deleting.</p></section><section><h2 id="section-3">On set</h2><p>Put proxies and cache on a second SSD and keep 20 percent free on the system drive. When the edit drive fills, clear cache, not originals.</p></section><section><h2 id="section-4">Do this</h2><p>Proxies and cache belong on a separate drive; a full edit drive drops frames.</p><ol><li>Put proxies and cache on a second SSD.</li><li>Keep twenty percent free on the system drive and never let the edit drive go red.</li><li>When space runs out, clear cache first; never delete originals.</li></ol></section><section><h2 id="section-5">Avoid</h2><p>Do not delete originals for space; cache can be rebuilt, media cannot.</p></section><section><h2>Judge</h2><p>Three signals are observable on set:</p><ul><li>removing one shot makes the scene faster, not muddier</li><li>skin, highlights and blacks sit inside scope limits</li><li>loudness, subtitles and file specs pass one delivery check</li></ul></section><section><h2>Failures</h2><p>These three moves erase the detail you just built:</p><ul><li>cuts follow the music, not the action</li><li>style before unity: shots jump in color</li><li>loudness and subtitles are checked at the very end</li></ul></section><section><h2>Extend</h2><p><strong>10-minute exercise:</strong> Take 30 seconds of footage and make an A/B, changing only “Put proxies and cache on a second SSD.”. Note one timecode and one difference before keeping it.</p></section>
<h2>Check</h2><ul><li>Proxies and cache sit on the second drive and the edit drive still has free space.</li><li>The system drive keeps at least twenty percent free with no red warning.</li><li>After clearing cache, the project rebuilds and every original remains.</li></ul>
