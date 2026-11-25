---
id: tools.capability.davinci-node.en
site: tools
type: tool
lang: en
translation_key: tools.capability.davinci-node
translation_status: reviewed
title: 'DaVinci Nodes: Nodes Are Not Filters'
summary: Nodes are not filter stacks; one node does one job, and disabling it reveals
  its effect.
slug: davinci-node
aliases:
- davinci-node
canonical_site: tools
canonical_path: /en/article/davinci-node/
status: published
diagram: /images/diagrams/en/davinci-node.svg
diagram_alt: 'Structure diagram for DaVinci Nodes: Nodes Are Not Filters.'
diagram_caption: 'Watch “Build five nodes: exposure, white balance, contrast, look,”
  and “Toggle each node and watch the change.”; judge whether the spec maps to one
  concrete shooting problem.'
difficulty: beginner
stage: field-note
format: handbook
authors:
- TVCN Tools Desk
last_verified: '2026-11-25'
review_due: '2027-05-25'
related:
- tools.capability.nle-compare.en
- tools.capability.ai-video-tool.en
- tools.capability.lto-archive.en
source_kind: experience
---

<p>If the problem is camera white balance, exposure or lighting, more nodes only make it dirtier. Go back to the source before grading.</p>
<!-- DIAGRAM_START -->
<h2>Diagram</h2>
<figure>
  <img src="/images/diagrams/en/davinci-node.svg" alt="Structure diagram for DaVinci Nodes: Nodes Are Not Filters.">
  <figcaption>Watch “Build five nodes: exposure, white balance, contrast, look,” and “Toggle each node and watch the change.”; judge whether the spec maps to one concrete shooting problem.</figcaption>
</figure>
<!-- DIAGRAM_END -->
<section><h2 id="section-1">Basic node order</h2><ul><li><strong>Balance then style:</strong> primary correction first, LUT and look later; reversing the order locks a cast into the LUT.</li><li><strong>Local last:</strong> windows, tracking and local grades come after the global grade; local first breaks the overall relationship.</li><li><strong>Cache and versions:</strong> more nodes cost performance; name key versions, do not rely on undo.</li></ul><h2 id="section-2">When not to stack nodes</h2></section><section><h2 id="section-3">On set</h2><p>Build five nodes: exposure, white balance, contrast, look, and output. Toggle each one to see its job; do not stack twenty.</p></section><section><h2 id="section-4">Do this</h2><p>Nodes are not a filter stack; each node does one job, and turning it off reveals what it did.</p><ol><li>Build five nodes: exposure, white balance, contrast, look, output.</li><li>Toggle each node and watch the change.</li><li>Do not stack twenty and lose track of the cause.</li></ol></section><section><h2 id="section-5">Avoid</h2><p>Do not stack twenty nodes; when something breaks, you cannot tell which to disable.</p></section>
<h2>Check</h2><ul><li>Five nodes each do one job with clear names.</li><li>Toggling each shows its specific change.</li><li>No more than ten nodes, and problems map to one node.</li></ul>
