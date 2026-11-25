---
id: post.assets.archive-reuse.en
site: post
type: article
lang: en
translation_key: post.assets.archive-reuse
translation_status: reviewed
title: 'Archive and Asset Reuse: Make the Next Film Faster'
summary: Archiving is not dragging a folder onto a drive. It lets the next person open the project, find media, know the rights, and restore grade and sound. Reuse is indexed retrieval, not digging through old films.
slug: archive-reuse
aliases:
- archive-reuse
canonical_site: post
canonical_path: /en/article/archive-reuse/
status: published
diagram: /images/diagrams/en/archive-reuse.svg
diagram_alt: Archive and reuse package diagram
diagram_caption: 'Diagram: an archive is five retrievable parts, not one zip. Without rights, footage cannot be reused.'
difficulty: intermediate
stage: handbook
format: workflow
authors:
- TVCN Post Desk
last_verified: 2026-11-22
review_due: 2027-11-22
sources:
- S24
- S27
- S28
- S30
- S34
- S35
test_context: 'Review setup: Windows 11 (RTX 3060) + macOS 14 (M1); re-run in DaVinci Resolve 20 and Premiere Pro 2025; results vary by machine.'
known_failures: 'Known failures: older-version timelines break; camera Logs need remapping; lost proxies require relinking.'
verified: 2026-11-22
related:
- post.color.color-management.en
- shoot.safety.set-safety.en
- story.screenplay.logline.en
source_kind: experience
---

<!-- DIAGRAM_START -->
<h2>Diagram</h2>
<figure>
  <img src="/images/diagrams/en/archive-reuse.svg" alt="Archive and reuse package diagram">
  <figcaption>Diagram: an archive is five retrievable parts, not one zip. Without rights, footage cannot be reused.</figcaption>
</figure>
<!-- DIAGRAM_END -->
<h2>First decision: what is worth archiving</h2><p>Three things are worth archiving: reusable shots (brand, person, place), versions that may change (a client may return), and rights that must be proven (releases, likeness, music). One-off, no-reuse, no-rights footage should not take archive space.</p><p>Ask what the next person will do with it. If there is no answer, keep the delivery package and project, not every source clip.</p><h2>Archive package: five parts, none optional</h2><p>Project file, source/proxies, LUTs and fonts, rights and likeness, index and metadata. The project must open offline; source must relink; LUTs and fonts must restore the look; rights must prove use; the index must be searchable.</p><p>Name every file with project, date, scene, version. No “final,” “New Folder,” or “copy.” The index lists filename, scene, person, rights, expiry, location.</p><h2>Restore test: the pass line for an archive</h2><p>After archiving, pick one random shot, open the project on another machine, relink, apply the LUT, and export. If it will not open, relink, or match color, the archive is not done. Restore testing is part of archiving, not optional.</p><p>Log the test: date, machine, software version, missing files, fix. Read the last log before the next archive.</p><h2>Reuse: rights before creative</h2><p>Before reusing, check three things: scope (organic/paid/advertising), term, territory. An organic license does not cover paid media; a one-year license expires; mainland-only footage cannot go to overseas platforms.</p><p>Reuse is not cutting the old film into the new one; it is extracting reusable shots, sound, graphics, and templates. Build a reusable-asset index tagged by person, scene, action, and light.</p><h2>Failure case: three years archived, all media offline</h2><p>A brand project archived only the project and proxies; source stayed on an old drive. Three years later the client wanted a re-cut. The project opened, but every clip was offline, the old drive interface was gone, and proxies were too weak to grade. The only option was a re-shoot.</p><p>The fix is not a new drive; it is a restore test at archive time. A project opening does not mean media relinks; media relinking does not mean color restores.</p><h2>Cost and acceptance</h2><p>Low: one project archive, index, one restore test, ¥1,000–3,000. Mid: multi-project library, LTO/cloud archive, rights ledger, ¥3,000–15,000. High: department MAM, migration, long-term verification, ¥15,000–50,000+.</p><h2>Check</h2><ul><li>Reuse value is defined before archiving.</li><li>Five parts present: project/media/LUT/rights/index.</li><li>Project opens offline and media relinks.</li><li>Restore test runs on another machine.</li><li>Reuse checks scope, term, and territory.</li><li>Index tags person, scene, action, and light.</li></ul>
<!-- SOURCES_START -->
<h2>Sources</h2>
<p class="source-types">Experience: TVCN field notes and project reviews; tested: the review setup and reproducible exercises noted on the page; references: public links below.</p>
<ul><li><span class="mono">[S24]</span> ACES Color Management</li><li><span class="mono">[S27]</span> EBU R128 Loudness</li><li><span class="mono">[S28]</span> Netflix Partner Help</li><li><span class="mono">[S30]</span> DaVinci Resolve</li><li><span class="mono">[S34]</span> Adobe Premiere Pro Guide</li><li><span class="mono">[S35]</span> Avid Resource Center</li></ul>
<p><a href="../../about/">Full links and notes in SOURCES.md</a></p>
<!-- SOURCES_END -->
