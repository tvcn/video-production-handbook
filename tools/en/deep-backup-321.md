---
id: tools.deep.deep-backup-321
site: tools
type: article
lang: en
translation_key: tools.deep.deep-backup-321
translation_status: source
title: '3-2-1 backup: from card to off-site'
summary: Backup is not one copy; three copies, two media types and one off-site copy bring footage home.
slug: deep-backup-321
aliases:
- deep-backup-321
canonical_site: tools
canonical_path: /en/article/deep-backup-321/
status: published
diagram: /images/diagrams/en/deep-backup-321.svg
diagram_alt: 'Diagram: 3-2-1 backup: from card to off-site.'
diagram_caption: 'Read "3-2-1 Backup: Finish It Today" and "NAS: Shared Storage, Shared Rules": write the condition first, then check whether the failure can be recorded.'
difficulty: intermediate
stage: deep-guide
depth: deep
deep_minutes: 9
format: deep-guide
authors:
- TVCN Editorial
last_verified: '2026-11-26'
review_due: '2027-02-26'
related: [tools.deep.deep-camera-lens-kit, tools.deep.deep-live-stream-chain, shoot.camera.axis-line]
sources:
- S17
- S29
- S23
- S30
- S70
source_kind: sourced
---
<p>Backup is not one copy; three copies, two media types and one off-site copy bring footage home. One page of &amp;quot;3-2-1 Backup: Finish It Today&amp;quot; solves one local problem; joining &amp;quot;3-2-1 Backup: Finish It Today&amp;quot;, &amp;quot;NAS: Shared Storage, Shared Rules&amp;quot; and &amp;quot;LTO Archive: Cold, Cheap, Slow&amp;quot; exposes the real failure: conditions are missing, too many variables move, and the result cannot be reproduced.</p>
<!-- DEEP_DIVE_START -->
<!-- DIAGRAM_START -->
<h2>图解</h2>
<figure>
  <img src="/images/diagrams/en/deep-backup-321.svg" alt="Diagram: 3-2-1 backup: from card to off-site.">
  <figcaption>Read &quot;3-2-1 Backup: Finish It Today&quot; and &quot;NAS: Shared Storage, Shared Rules&quot;: write the condition first, then check whether the failure can be recorded.</figcaption>
</figure>
<!-- DIAGRAM_END -->



<section><h2 id="section-1">Problem</h2><p>The problem is not a lack of methods; each step works alone, but together they fail because the condition was not written, too many variables moved and the result cannot be reproduced.</p><p>The order is condition, judgement, one variable and evidence. A step is complete only when the next person can repeat it.</p></section>
<section><h2 id="section-2">Judgement</h2><ul><li>First gate in &quot;3-2-1 Backup: Finish It Today&quot;: Three copies complete the same day with matching file counts.</li><li>Second gate in &quot;NAS: Shared Storage, Shared Rules&quot;: Two media types are used, one offsite or cloud.</li><li>Third gate in &quot;LTO Archive: Cold, Cheap, Slow&quot;: The card is formatted only after all three are confirmed.</li></ul><p>If one gate fails, return to its single page; do not hide an unsolved point inside a longer chain.</p></section>
<section><h2 id="section-3">Method</h2><ol><li>Write the condition first: turn &quot;Copy the card to SSD the same day.&quot; from &quot;3-2-1 Backup: Finish It Today&quot; into three rows: material, environment, acceptance.</li><li>Run one minimal action: follow &quot;3-2-1 Backup: Finish It Today&quot; for 30 seconds and do not add the second page yet.</li><li>Attach the second page: Copy to a second drive..</li><li>Use the third page as a control: Upload to NAS or cloud, and format the card only after three copies..</li><li>Change one variable at a time; write the other conditions down instead of remembering them.</li><li>Film the failure too: put failure and success side by side to see which step cannot be skipped.</li><li>Ask the next person to reproduce from the record; if they cannot, the record is not finished.</li></ol></section>
<section><h2 id="section-4">Field test</h2><p>A reproducible test, not a client case: take 30 seconds of material, make version A using &quot;Three copies complete the same day with matching file counts.&quot; from &quot;3-2-1 Backup: Finish It Today&quot;, then version B using &quot;Two media types are used, one offsite or cloud.&quot; from &quot;NAS: Shared Storage, Shared Rules&quot;; only one variable may differ. Put them side by side and record what breaks first in &quot;LTO Archive: Cold, Cheap, Slow&quot;: condition, action or acceptance. If it works on the first try, add one real constraint and run it again.</p></section>
<section><h2 id="section-5">Failure table</h2><div class="table-scroll"><table class="data-table"><thead><tr><th>Symptom</th><th>Cause</th><th>Replacement action</th></tr></thead><tbody><tr><td>Do not plan to back up tomorrow; if the card is lost, three copie…</td><td>Condition was not written</td><td>Return to page one and rewrite the three rows</td></tr><tr><td>Do not give everyone read-write; two simultaneous edits erase a v…</td><td>Condition was not written</td><td>Return to page one and rewrite the three rows</td></tr><tr><td>Do not use LTO as an editing disk; a 1 TB restore takes hours and…</td><td>Condition was not written</td><td>Return to page one and rewrite the three rows</td></tr></tbody></table></div></section>
<section><h2 id="section-6">Acceptance</h2><ul><li>Three copies complete the same day with matching file counts.</li><li>Two media types are used, one offsite or cloud.</li><li>The card is formatted only after all three are confirmed.</li><li>Confirm the card plays back before copying</li><li>Copy to the first working drive</li><li>Verify file count and decode with a checksum tool</li><li>Rename date_project_camera_card</li><li>Copy to a second backup drive</li><li>Groups and read-only permissions are set, not open write for all.</li><li>The recycle bin is on and deleted files are recoverable.</li></ul></section>
<section><h2 id="section-7">Alternatives</h2><ul><li>For a single-point problem in "3-2-1 Backup: Finish It Today", go back to <a href="https://tools.tvcn.org/en/article/backup-3-2-1/">3-2-1 Backup: Finish It Today</a>; do not use the whole chain.</li><li>To compare two actions, read <a href="https://tools.tvcn.org/en/article/nas/">NAS: Shared Storage, Shared Rules</a> and leave the third page alone.</li><li>For acceptance only, use <a href="https://tools.tvcn.org/en/article/lto-archive/">LTO Archive: Cold, Cheap, Slow</a> as a self-test sheet.</li></ul></section>

<!-- SOURCES_START -->
## References and further reading

- [S17] [Reuters Trust Principles](https://reutersagency.com/about/our-trust-principles/) — Accessed 2026-11-26. Used to check the terminology and public context in the opening paragraph (“Backup is not one copy; three copies, two media types and on”) against The agency's public commitment to independence, accuracy and freedom from bias; not a substitute for an on-set test.
- [S29] [YouTube Upload Specs](https://support.google.com/youtube/answer/1722171) — Accessed 2026-11-26. Used to check the terminology and public context in the opening paragraph (“Backup is not one copy; three copies, two media types and on”) against Recommended resolution, bitrate, frame rate and audio codec; not a substitute for an on-set test.
- [S23] [SMPTE Standards](https://www.smpte.org/standards) — Accessed 2026-11-26. Used to check the terminology and public context in the opening paragraph (“Backup is not one copy; three copies, two media types and on”) against Entry point for timecode, color, cinema and signal-chain standards; not a substitute for an on-set test.
- [S30] [DaVinci Resolve](https://www.blackmagicdesign.com/products/davinciresolve) — Accessed 2026-11-26. Used to check the terminology and public context in the opening paragraph (“Backup is not one copy; three copies, two media types and on”) against Official entry for editing, grading, Fusion and delivery; not a substitute for an on-set test.
- [S70] [FFmpeg: Documentation](https://ffmpeg.org/documentation.html) — Accessed 2026-11-26. Used to check the terminology and public context in the opening paragraph (“Backup is not one copy; three copies, two media types and on”) against Codec, muxing and filter documentation; not a substitute for an on-set test.
<!-- SOURCES_END -->

