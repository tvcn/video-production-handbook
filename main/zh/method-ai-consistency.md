---
id: main.method.method-ai-consistency
site: main
type: template
lang: zh
translation_key: main.method.method-ai-consistency
translation_status: source
title: AI 角色漂
summary: AI 角色漂，先做角色卡和三视图，再把同一张参考图带进每个镜头。
slug: method-ai-consistency
aliases:
- method-ai-consistency
canonical_site: main
canonical_path: /article/method-ai-consistency/
status: published
diagram: /images/diagrams/zh/method-ai-consistency.svg
diagram_alt: AI 角色漂的结构示意图。
diagram_caption: 看“写死十项特征：年龄、发型、脸型、眉、…”和“生成正面、侧面、背面三视图，选一张做…”两处，判断症状能不能被复述成一句可观察的话。
difficulty: beginner
stage: field-note
format: handbook
authors:
- TVCN 编辑部
last_verified: '2026-11-26'
review_due: '2027-02-26'
related: [main.method.method-ai-rights, main.method.method-ai-uncanny, context.history.16mm]
sources:
- S22
- S23
- S02
- S38
source_kind: sourced
---
<p>同一角色生成正面、侧面、低头三个角度，放在同一张图上比较。如果颧骨、鼻梁、发际线和服装细节不能对上，不要开始批量生成。先修参考图，再修提示词。</p>
<!-- DIAGRAM_START -->
<h2>图解</h2>
<figure>
  <img src="/images/diagrams/zh/method-ai-consistency.svg" alt="AI 角色漂的结构示意图。">
  <figcaption>看“写死十项特征：年龄、发型、脸型、眉、…”和“生成正面、侧面、背面三视图，选一张做…”两处，判断症状能不能被复述成一句可观察的话。</figcaption>
</figure>
<!-- DIAGRAM_END -->


<section><h2 id="section-1">先锁四件事</h2>
<ul><li><strong>脸：</strong>正面、侧面、3/4 角度各一张参考，固定发型和眉形。不要每次只用一句文字描述。</li><li><strong>服装：</strong>材质、颜色、领口、纽扣写进角色表；同一场不要换相近色。</li><li><strong>光：</strong>主光方向、色温、柔硬写进镜头卡；换镜头先换光，不要换脸。</li><li><strong>镜头：</strong>焦段和景别决定脸型。同一角色在广角和长焦下会像两个人，先固定焦段。</li></ul>
<h2 id="section-2">三角度测试</h2>

<h2 id="section-3">什么时候不要硬生成</h2>
<p>角色需要长时间说话、复杂表情或与真人同框时，先用实拍定基准，再用生成补远景和插入。不要用“后期统一”掩盖角色漂移。</p></section><section><h2 id="section-4">现场</h2><p>角色卡、三视图、同一参考图；逐镜头比对脸、衣服、发型。</p></section><section><h2 id="section-5">怎么做</h2><ol><li>写死十项特征：年龄、发型、脸型、眉、鼻、服装、鞋、配饰、体型、肤色。</li><li>生成正面、侧面、背面三视图，选一张做母版。</li><li>每个镜头都带同一张参考图和同一段描述，只改动作和机位。</li></ol></section><section><h2 id="section-6">别踩</h2><p>别每个镜头重新写一遍形容词；每次都会长成另一个人。</p></section><section><h2 id="section-7">边界</h2><p>它不保证故事成立；模板只管结构顺序，人物、障碍和代价仍要单独写。</p></section><section><h2 id="section-8">替代</h2><p>如果“写死十项特征：年龄、发型、脸型、眉、…”不是你的主问题，先用“生成正面、侧面、背面三视图，选一张做…”对应的基础做法；两项都成立再考虑升级。</p></section><section><h2 id="section-9">60 秒自测</h2><p>用现有器材按“写死十项特征：年龄、发型、脸型、眉、…”做一次 60 秒测试，记下一个数字；数字没有变化，就不要加预算。</p></section><section><h2 id="section-10">什么时候不该用</h2><p>当“写死十项特征：年龄、发型、脸型、眉、…”还没写清，或“生成正面、侧面、背面三视图，选一张做…”只是凑数时，不要套模板；先回到人物和问题。</p></section><section><h2 id="section-11">三个失败</h2><ul><li>模板每段都有，但人物没有决定。</li><li>中段只换场景，没有新信息。</li><li>结尾靠旁白总结，画面没有变化。</li></ul></section>
<h2 id="section-12">验收</h2><ul><li>十项特征写死，三视图有一张母版。</li><li>每个镜头带同一参考图和同一段描述。</li><li>只改动作和机位，没有重新写形容词。</li></ul>


> 意图分工：本页负责「AI 角色漂」的可执行细节；同集群先读 <a href="https://tools.tvcn.org/article/deep-ai-toolchain/">AI 工具链：生成、配音、渲染</a> 建立总判断，再回到本页。

<!-- INTENT_SCOPE -->

<!-- SOURCES_START -->
## 参考与延伸阅读

- [S22] [全国人民代表大会：《民法典》](http://www.npc.gov.cn/npc/c2/c30834/202006/t20200602_306457.html) — 2026-11-26 访问。用于核对首段“AI 角色漂，先做角色卡和三视图，再把同一张参考图带进每个镜头。”中的术语与公开背景（肖像、隐私、合同与场地权利的上位法文本）；不替代现场测试。
- [S23] [SMPTE 标准入口](https://www.smpte.org/standards) — 2026-11-26 访问。用于核对首段“AI 角色漂，先做角色卡和三视图，再把同一张参考图带进每个镜头。”中的术语与公开背景（时间码、色彩、影院与信号链标准的机构入口）；不替代现场测试。
- [S02] [WIPO](https://www.wipo.int/en/web/copyright/faq-copyright) — 2026-11-26 访问。用于核对首段“AI 角色漂，先做角色卡和三视图，再把同一张参考图带进每个镜头。”中的术语与公开背景（版权保护对象、经济权利与精神权利）；不替代现场测试。
- [S38] [国家税务总局：官方网站](https://www.chinatax.gov.cn/) — 2026-11-26 访问。用于核对首段“AI 角色漂，先做角色卡和三视图，再把同一张参考图带进每个镜头。”中的术语与公开背景（增值税、跨境服务与代扣代缴的官方政策入口）；不替代现场测试。
<!-- SOURCES_END -->

