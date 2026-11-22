---
id: post.editing.proxy-workflow.en
site: post
type: article
lang: en
translation_key: post.editing.proxy-workflow
translation_status: reviewed
title: "Proxy Workflow: Cut First, Quality Later"
summary: "Proxies do not lower the final quality; they let the edit move. Keep the originals untouched."
slug: proxy-workflow
aliases: [proxy-workflow]
canonical_site: post
canonical_path: /en/editing/proxy-workflow/
status: published
diagram: /images/diagrams/en/proxy-workflow.svg
diagram_alt: "Proxy Workflow: Cut First, Quality Later three-step diagram"
diagram_caption: "Do the three steps in order, then look again at the image or file."
difficulty: beginner
stage: field-note
format: handbook
authors: [editor]
last_verified: 2026-11-20
review_due: 2027-05-20
related: [main.paths.first-film]
depth: deep
deep_minutes: 5
---

<p>Proxies do not lower the final quality; they let the edit move. Keep the originals untouched.</p>
<!-- DIAGRAM_START -->
<h2>Diagram</h2>
<figure>
  <img src="/images/diagrams/en/proxy-workflow.svg" alt="Proxy Workflow: Cut First, Quality Later three-step diagram">
  <figcaption>Do the three steps in order, then look again at the image or file.</figcaption>
</figure>
<!-- DIAGRAM_END -->
<h2>On set</h2>
<p>Use ProRes Proxy or quarter-resolution proxies on a separate SSD. Lock the originals as read-only, edit only proxies, and relink before delivery.</p>
<h2>Do this</h2>
<p>Proxies do not lower delivery quality; they let the edit run. Originals stay untouched beside them.</p><ol><li>Generate ProRes Proxy or quarter-resolution files on a separate SSD.</li><li>Set the originals to read-only and edit only against proxies.</li><li>Relink to originals before delivery and confirm no proxy slipped into the master.</li></ol>
<h2>Avoid</h2>
<p>Do not treat proxies as masters; deliver before relinking and the quality shows.</p>
<h2>Check</h2>
<ul><li>Proxies and originals live on separate drives and the originals are read-only.</li><li>The timeline references proxies only, with one-to-one names and paths.</li><li>After relinking, three random shots return to original resolution and detail.</li></ul>

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
