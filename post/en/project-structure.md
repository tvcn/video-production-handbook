---
id: post.assets.project-structure.en
site: post
type: article
lang: en
translation_key: post.assets.project-structure
translation_status: reviewed
title: 'Project Structure: Folders Beat Software'
summary: Set folders and naming before software; if the app changes, the media still
  makes sense.
slug: project-structure
aliases:
- project-structure
canonical_site: post
canonical_path: /en/article/project-structure/
status: published
diagram: /images/diagrams/en/project-structure.svg
diagram_alt: 'Structure diagram for Project Structure: Folders Beat Software.'
diagram_caption: Watch “Create 01_media, 02_project, 03_exports, and 04_docs at the”
  and “Name files date_scene_camera, never “final”.”; judge whether removing one shot
  makes the scene faster rather than muddier.
difficulty: beginner
stage: field-note
format: handbook
deep_minutes: 7
depth: deep
authors:
- TVCN Post Desk
last_verified: '2026-11-26'
review_due: '2027-02-26'
related: [post.assets.proxy-cache, post.editing.proxy-workflow, shoot.camera.composition]
source_kind: sourced
sources:
- S70
- S35
- S29
- S60
---
<p>The project root holds only three things: 01_media, 02_project, 03_delivery. Media sorts by date and scene; project by edit, grade and sound; delivery by platform and date. Every path should tell you which stage a file belongs to.</p>
<!-- DIAGRAM_START -->
<h2>Diagram</h2>
<figure>
  <img src="/images/diagrams/en/project-structure.svg" alt="Structure diagram for Project Structure: Folders Beat Software.">
  <figcaption>Watch “Create 01_media, 02_project, 03_exports, and 04_docs at the” and “Name files date_scene_camera, never “final”.”; judge whether removing one shot makes the scene faster rather than muddier.</figcaption>
</figure>
<!-- DIAGRAM_END -->
<section><h2 id="section-1">Three folders before any naming debate</h2><p>Name files date_scene_shot_version, never “final” or “revised.” Version numbers only go up, so even the trash shows order.</p><h2 id="section-2">Limits</h2><p>Structure is not decoration. The test is whether someone with the drive can find the original media and the latest project in five minutes.</p></section><section><h2 id="section-3">On set</h2><p>Create 01_media, 02_project, 03_exports, and 04_docs at the root. Name files date_scene_camera; never final version.</p></section><section><h2 id="section-4">Do this</h2><p>Project structure fixes folders and names so the media survives a software change.</p><ol><li>Create 01_media, 02_project, 03_exports, and 04_docs at the root.</li><li>Name files date_scene_camera, never “final”.</li><li>Keep proxies and originals separate and back up the same day.</li></ol></section><section><h2 id="section-5">Avoid</h2><p>Do not leave media on the desktop; a system reinstall erases it.</p></section><section><h2>Judge</h2><p>This page passes on three observable checks, not slogans:</p><ul><li><strong>1.</strong> The four root folders exist and media, project, exports, and docs each live in place.</li><li><strong>2.</strong> Filenames carry date, scene, and camera and sort cleanly.</li><li><strong>3.</strong> On another machine or app, the path still leads to the original media.</li></ul></section><section><h2>Failures</h2><p>Any one of these means stop and fix it before post:</p><ul><li><strong>1.</strong> Check 1 is only staged (“The four root folders exist and media, project…”); another camera position or location exposes it.</li><li><strong>2.</strong> Check 2 is left to post or a verbal explanation (“Filenames carry date, scene, and camera and so…”); nothing on set can be rechecked.</li><li><strong>3.</strong> Do not leave media on the desktop; a system reinstall erases it.</li></ul></section><section><h2>Extend</h2><p><strong>10-minute exercise:</strong> Take 30 seconds of footage and make an A/B, changing only “Create 01_media, 02_project, 03_exports, and 04_docs at the”. Note one timecode and one difference before keeping it.</p></section>
<h2>Check</h2><ul><li>The four root folders exist and media, project, exports, and docs each live in place.</li><li>Filenames carry date, scene, and camera and sort cleanly.</li><li>On another machine or app, the path still leads to the original media.</li></ul>

<!-- DEEP_DIVE_START -->
## Deep dive
<p><strong>About 7 minutes.</strong> This section does not repeat the method above. It adds three things: two conditions, a counterexample and a reusable model, so you can decide when to change the method.</p>
### Condition A: solo project
<p>Solo projects easily become “desktop is the project”: footage in Downloads, project on the desktop, exports on another drive. Three days later you cannot find anything. Solo structure does not need complexity; it needs three things: one project root, four fixed subfolders and one version rule.</p><p>The four: 01_footage, 02_project, 03_audio, 04_export. Everything goes into these four; no more “New Folder”. Version by date plus sequence, never final. Back up even a solo project, at least one copy on another drive.</p>
### Condition B: team or handoff
<p>The first rule of a team project is “someone else can take over”. Use English or numeric folder names, not personal initials; put a README in each folder with source, frame rate, colour, proxies, timecode and contacts. Hand over the README before the project.</p><p>Team versions need a lock folder: every approved version goes into 05_lock and others read only. Do not keep editing the lock; copy to 06_rev, change, then lock again. The lock gives “which version was approved” an answer.</p>
### Counterexample: a folder called final
<p>A project has final, final2, final_ok, final_really and final_to_client. Two months later the client wants one word changed; the team opens five finals and cannot tell which is the master. They reverse-engineer from a compressed platform download.</p><p>The fix is not final_final; use date plus state: 20261126_lock, 20261127_rev, 20261128_client. Date shows order, state shows responsibility. Final is an adjective, not a version name.</p>
### Reusable model
<p><strong>Root → four folders → README → lock.</strong> The root makes the project independent, four folders give files a home, README explains handover, lock answers approval. With all four, the project does not leave when the person does.</p><p>Run a stranger test every quarter: someone uninvolved finds the master, proxies and delivery files using only folders and README. If they cannot, the structure needs work.</p>
<!-- DEEP_DIVE_END -->

<!-- SOURCES_START -->
## References and further reading

- [S70] [FFmpeg: Documentation](https://ffmpeg.org/documentation.html) — Accessed 2026-11-26. Used to check the terminology/method/rule in the “Three folders before any naming debate” section against FFmpeg codec/muxing documentation, not a delivery spec; it does not verify numbers, model choices or on-set conclusions derived from this page, and is not a substitute for a test.
- [S35] [Avid: Resource Center](https://www.avid.com/resource-center) — Accessed 2026-11-26. Used to check the terminology/method/rule in the “Limits” section against Avid resource center, not an independent review; it does not verify numbers, model choices or on-set conclusions derived from this page, and is not a substitute for a test.
- [S29] [YouTube: Upload Encoding Specs](https://support.google.com/youtube/answer/1722171) — Accessed 2026-11-26. Used to check the terminology/method/rule in the “On set” section against YouTube upload encoding recommendations, not creative standards; it does not verify numbers, model choices or on-set conclusions derived from this page, and is not a substitute for a test.
<!-- SOURCES_END -->

