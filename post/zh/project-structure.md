---
id: post.assets.project-structure
site: post
type: article
lang: zh
translation_key: post.assets.project-structure
translation_status: source
title: 项目结构：文件夹比软件重要
summary: 项目结构先定文件夹和命名，软件换了还能找到素材。
slug: project-structure
aliases:
- project-structure
canonical_site: post
canonical_path: /article/project-structure/
status: published
diagram: /images/diagrams/zh/project-structure.svg
diagram_alt: 项目结构：文件夹比软件重要的结构示意图。
diagram_caption: 看“根目录建 01_media、02_p…”和“文件名用日期_场次_机位，别用“最终…”两处，判断剪掉一个镜头后，节奏是更快还是更乱。
difficulty: beginner
stage: field-note
format: handbook
deep_minutes: 7
depth: deep
authors:
- TVCN 后期组
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
<p>项目根下只放三样：01_素材、02_工程、03_交付。素材按日期和场景分，工程按剪辑/调色/声音分，交付按平台和日期分。任何文件都能从路径判断它属于哪一步。</p>
<!-- DIAGRAM_START -->
<h2>图解</h2>
<figure>
  <img src="/images/diagrams/zh/project-structure.svg" alt="项目结构：文件夹比软件重要的结构示意图。">
  <figcaption>看“根目录建 01_media、02_p…”和“文件名用日期_场次_机位，别用“最终…”两处，判断剪掉一个镜头后，节奏是更快还是更乱。</figcaption>
</figure>
<!-- DIAGRAM_END -->
<section><h2 id="section-1">先建三层文件夹，再谈命名</h2><p>文件名用“日期_场景_镜号_版本”，不要用“最终”“修改后”。版本号只增不减，回收站里也能看出先后。</p><h2 id="section-2">边界</h2><p>结构不是给人看的装饰。别人拿到硬盘，能否在五分钟内找到原素材和最新工程，才是验收标准。</p></section><section><h2 id="section-3">现场</h2><p>根目录建 01_media、02_project、03_exports、04_docs；文件名用日期_场次_机位，别用最终版。</p></section><section><h2 id="section-4">怎么做</h2><ol><li>根目录建 01_media、02_project、03_exports、04_docs。</li><li>文件名用日期_场次_机位，别用“最终版”。</li><li>代理和原始分开放，备份当天做。</li></ol></section><section><h2 id="section-5">别踩</h2><p>别把素材放在桌面；系统重装就没了。</p></section><section><h2>判断</h2><p>这一页的判断只看三条可观察的验收，不靠口号：</p><ul><li><strong>1.</strong> 四个根文件夹存在，媒体、项目、导出、文档各归其位。</li><li><strong>2.</strong> 文件名包含日期、场次和机位，能直接排序。</li><li><strong>3.</strong> 换一台机器或换软件后，仍能按路径找到原始素材。</li></ul></section><section><h2>失败</h2><p>下面任一条出现，先停，不要靠后期补：</p><ul><li><strong>1.</strong> 只做到“四个根文件夹存在，媒体、项目、导出、文档各归其位”的形式，换一个机位或场景就重现不了。</li><li><strong>2.</strong> 把“文件名包含日期、场次和机位，能直接排序”留到后期或口头解释，现场没有留下能复查的记录。</li><li><strong>3.</strong> 别把素材放在桌面；系统重装就没了。</li></ul></section><section><h2>延伸</h2><p><strong>10 分钟练习：</strong>拿一段 30 秒素材做 A/B，只改“根目录建 01_media、02_p…”；记下一个时间码和一处差异，再决定是否保留。</p></section>
<h2>验收</h2><ul><li>四个根文件夹存在，媒体、项目、导出、文档各归其位。</li><li>文件名包含日期、场次和机位，能直接排序。</li><li>换一台机器或换软件后，仍能按路径找到原始素材。</li></ul>

<!-- DEEP_DIVE_START -->
## 深读
<p><strong>约 7 分钟。</strong> 这一节不重复前面的做法，只补三个东西：两种条件、一个反例、一个可复用模型；读完能判断什么时候换做法。</p>
### 条件 A：个人项目
<p>个人项目最容易“桌面即项目”：素材在下载文件夹，工程在桌面，导出在另一个盘。三天后自己都找不到。个人结构不求复杂，只求三件事：一个项目根目录、四个固定子目录、一个版本命名规则。</p><p>四个子目录：01_footage、02_project、03_audio、04_export；所有文件只进这四个，不再新建“新建文件夹”。版本用日期+序号，不用 final。个人项目也要备份，至少一份在另一块盘。</p>
### 条件 B：团队/交接
<p>团队项目的第一原则是“别人能接手”。目录名用英文/数字，不用个人缩写；每个目录放一个 README，写清素材来源、帧率、色彩、代理、时间码、联系人。交接时先交 README，再交工程。</p><p>团队版本要有一个“锁版”目录：所有已通过的版本进 05_lock，其他人只读。不要在锁版上继续改；要改，复制到 06_rev，改完再锁。锁版让“哪一版被批准”有答案。</p>
### 反例：文件夹叫 final
<p>一个项目有 final、final2、final_ok、final_真的、final_交客户。两个月后客户要改一个字，团队打开五个 final，不知道哪个是母版。最后从平台下载了一个压缩版反推。</p><p>修法不是再建一个 final_final，而是用日期+状态：20261126_lock、20261127_rev、20261128_client。日期让顺序可见，状态让责任可见。final 不是版本名，是形容词。</p>
### 可复用模型
<p><strong>根目录 → 四目录 → README → 锁版。</strong> 根目录让项目独立，四目录让文件有家，README 让交接有说明，锁版让批准有答案。四步都在，项目才不会跟着人走。</p><p>每季度做一次“陌生人测试”：让一个没参与的人只靠目录和 README 找到母版、代理和交付文件。找不到，结构还要改。</p>
<!-- DEEP_DIVE_END -->

<!-- SOURCES_START -->
## 参考与延伸阅读

- [S70] [FFmpeg：文档](https://ffmpeg.org/documentation.html) — 2026-11-26 访问。用于核对「先建三层文件夹，再谈命名」一节的术语/方法/规则（FFmpeg 编解码/封装文档，不是交付规范）；不核对其中由本页经验得出的数字、型号与现场结论，也不替代测试。
- [S35] [Avid：资源中心](https://www.avid.com/resource-center) — 2026-11-26 访问。用于核对「现场」一节的术语/方法/规则（Avid 资源中心，不是独立评测）；不核对其中由本页经验得出的数字、型号与现场结论，也不替代测试。
- [S29] [YouTube：上传编码建议](https://support.google.com/youtube/answer/1722171) — 2026-11-26 访问。用于核对「怎么做」一节的术语/方法/规则（YouTube 上传编码建议，不是创作标准）；不核对其中由本页经验得出的数字、型号与现场结论，也不替代测试。
<!-- SOURCES_END -->

