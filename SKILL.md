---
name: text-first-exegesis
description: "Apply a five-layer, text-first method to biblical exegesis with two asymmetric products: (A) a deliberately low-trust AI-only diagnostic reconstruction, and (B) a modernity-weighted current-frontier reconstruction that carries the primary exegetical recommendation and normally prefers well-supported recent revisionist proposals from preferred scholarly ecosystems over older/traditional readings. Use for biblical interpretation, Hebrew/Greek wording, textual criticism, literary analysis, historical context, intertext, commentaries, scholarly debates, theology, sermons, or research. For the Old Testament, keep MT and LXX/Old Greek books as separate whole-book literary objects; for the New Testament, use the NA/ECM initial text."
---

# Text-First Exegesis

Use this evidence hierarchy:

**textual facts > literary facts > historical facts > existing exegetical viewpoints > theology**

- **Textual**: wording and variants.
- **Literary**: language, syntax, discourse/narrative, rhetoric, structure, participants, and lexical networks inside the locked literary object.
- **Historical**: wider language, culture, archaeology, intertexts, other books, textual traditions, composition, redaction, and transmission.
- **Exegetical viewpoints**: scholarly proposals and arguments. Authority is not evidence.
- **Theology**: canonical, biblical-theological, systematic, ecclesial, reception, and pastoral judgments.


## Mandatory dual-track gate

Treat any request that asks what a biblical **word, phrase, clause, verse, passage, or book means**, or asks to **interpret/exegete** it, as substantive exegesis even when the prompt is one line or targets one lexeme. Such requests must run the full protocol and visibly output both **Track A** and **Track B**. The tracks have different epistemic roles: **A is a low-trust AI diagnostic; B is the primary basis for exegetical advice.**

A pure lookup may omit the dual track only when the user asks solely for non-interpretive data such as spelling, parsing, morphology, a manuscript siglum, or a critical-edition reading with no meaning claim.

Before consulting or searching modern secondary scholarship, freeze Track A's actual content. Track A may use primary texts, critical editions, manuscripts, and primary-language corpora as first-order evidence, but no modern commentary conclusion, named scholar, remembered consensus, or secondary-source search result. Cross-book/intertextual material belongs to Track A's **History** step, never its same-object **Literature** step.

A substantive exegetical answer is invalid unless the final response contains, in order: **Object declaration -> A - Independent reconstruction -> B - Current frontier -> Comparison and critique**. Theology is added only when requested. Short prompts shorten each section; they do not remove a track.

## Lock the literary object before Track A

This is a scoping step, not a sixth evidence layer. Keep the object fixed for the whole run.

**Old Testament**
- Study **MT and LXX/Old Greek in parallel** whenever both survive. Each `book x tradition` pair is a separate literary object.
- MT: use BHS as the stable base; consult BHQ where available and normally prefer its fuller apparatus and evaluation.
- LXX/Old Greek: use Goettingen where available; otherwise Rahlfs-Hanhart.
- Add DSS or another ancient tradition when sufficiently relevant and recoverable.
- Cross-tradition comparison is allowed in textual and historical analysis; literary inference stays inside one book and one tradition.

**New Testament**
- Use the target book's **NA/ECM initial text**; prefer ECM where available.
- Material judged secondary or post-compositional by NA/ECM, including Mark 16:9-20 and John 7:53-8:11, is excluded from Layer 2. Record its textual status in Layer 1 and study its editing/transmission in Layer 3 when relevant.
- Sources incorporated before the initial-text book was formed belong to Layer 3 compositional history, not to separate Layer 2 objects inside that run.

For every locked object, the **whole book is both the minimum and maximum synchronic literary object**. A local passage is an analytical window into that whole object.

## Direction of evidence

The hierarchy is directional and non-compensatory. A later layer may refine readings left open by an earlier layer; it may not reverse an earlier result by accumulating later-layer evidence. If later evidence exposes a missed earlier-layer variable, reopen that earlier layer and rerun it with evidence admissible there.

An intertext is historical evidence. Transfer of its referent, chronology, ontology, or function into the target work requires independent support from the target object's literary evidence.

Keep theology and canonical synthesis downstream from historical exegesis.

## Track A - AI diagnostic reconstruction

Treat Track A as a test of the model's unaided reasoning from primary evidence, not as reliable exegetical advice. **Track A is intrinsically low-trust and reference-only.** Its purpose is to expose what the model can reconstruct, what assumptions it makes, and where frontier research later corrects it. A confident-sounding A conclusion does not gain advisory weight from fluency or internal coherence.

Freeze A before any search, retrieval, or consultation of modern exegetical scholarship or Track B.

1. **Text** - Establish the wording of each declared object. Keep OT traditions separate; for NT, record relevant excluded secondary material. Textual criticism does not decide interpretation.
2. **Literature** - Map the whole locked object. State `FORM/SYNTAX`, `MINIMAL OBJECT-INTERNAL SENSE`, and unresolved referent, domain, event type, temporal frame, participant relation, and neighboring ambiguities.
3. **Object-internal testing** - Test controlling variables against the closest comparable uses in the same book and, for OT, the same tradition. Keep disputed dependencies unresolved until independently tested.
4. **Rivals** - When a real dispute exists, construct at least two strong object-internal models and rank them only by evidence that distinguishes them.
5. **History** - Add wider language, intertexts, other books/traditions, culture, archaeology, composition/redaction, and transmission. If this exposes a missed literary variable, rerun Layer 2 inside the same locked object.
6. **Freeze A** - State the conclusion, serious alternatives, unresolved questions, and a compact `TARGET INFERENCE CHAIN`: identify the load-bearing premises and inferential links from evidence to conclusion. Label the product **AI diagnostic / low-trust / reference-only**. Any confidence label describes only the internal fit of A's reconstruction; it does not convert A into a recommended interpretation.

Track A may not use named scholars, remembered consensus, commentary conclusions, or Track B as premises.

## Track B - current-frontier reconstruction

Treat Track B as the primary evidential product and the main basis for any actual exegetical recommendation. It remains fallible, but it normally has **substantially greater epistemic weight than Track A** because it recovers and adversarially tests the current scholarly frontier. Track B also uses an explicit **modernity/revision prior**: among serious method-compatible proposals with adequate primary-evidence support, give a default advantage to the newer substantive revision when it comes from the project's preferred scholarly ecosystem and survives the rebuttal burden.

Begin only after A is frozen. Read `references/frontier-search.md` and follow it as the Track B search and qualification protocol. Treat candidate discovery as an **exhaustive census within the defined 15-year research universe**, not a representative sample. Do not rank or prune proposals until the census reaches the protocol's saturation stop rule.

Track B must:
- enforce the rolling **15-year** window for modern secondary scholarship while exempting primary/first-order evidence;
- enumerate the recoverable candidate universe across direct searches, technical commentaries, field syntheses, author bibliographies, publisher/series catalogs, and recursive citation networks; a candidate quota or a few agreeing results never closes discovery;
- recover each major proposal's **target-relevant interpretive payload**: headline thesis, every subclaim that could materially change the answer to the user's target question, the relevant unit/tradition, primary evidence, and the decisive inference connecting them; for word-level questions, separate lexical sense from contextual referent/function and treat a proposal that changes either the referent/function or a load-bearing neighboring clause as target-level relevant;
- treat author provenance, publisher/series reputation, recency, and uptake as **meta-epistemic priors** for frontier ranking, while keeping them distinct from textual/literary/historical evidence; they may break or tilt a live contest but may not rescue a proposal with a clear Layer 1-3 failure;
- steelman every major method-compatible proposal that could affect the conclusion, including its strongest same-object evidence and response to obvious counterevidence when recoverable;
- decompose decisive proposals into textual, literary, historical, exegetical, and theological/canonical components, then re-adjudicate them in that order;
- report influential method-incompatible views fairly, identify the backflow/category error, and retest their remaining earlier-layer case;
- preserve tension between incompatible live models; produce a synthesis only when frontier-eligible scholarship actually argues for that synthesis from admissible evidence;
- when a newer revisionist proposal from a preferred scholarly ecosystem directly challenges an older/traditional reading and survives the rebuttal burden, **prefer the newer proposal as Track B's recommendation**, even if the older reading remains more familiar or historically widespread;
- leave the compatible frontier unresolved only when no proposal earns preference under the evidence hierarchy plus the modernity/revision prior.

Use A's `TARGET INFERENCE CHAIN` only to generate adversarial searches and to audit coverage; never use A as evidence for B. Freeze B only after every load-bearing A link that frontier scholarship materially challenges has been recovered and classified.

## Compare only after both freezes

Treat **A/B divergence as ordinary and expected**, especially on disputed questions. Do not seek convergence or harmonize the tracks for presentation. State where they agree and conflict, then let B audit A for missed live models, omitted or misweighted evidence, loaded assumptions, and overconfidence. Keep A frozen so the diagnostic failure remains visible. Agreement between A and B is descriptive, not an independent confirmation of B. Within B, keep genuinely incompatible frontier models visibly separate; avoid compromise language that blurs the claim each model actually makes.

When A and B conflict, the user-facing exegetical recommendation normally follows **B**, subject to B's own stated uncertainty, coverage limits, and unresolved frontier disputes. A does not override B. A literary ranking may be corrected only by a stronger **same-object literary** case recovered in B; historical/intertextual evidence may trigger that rerun but cannot substitute for it.

## Output

0. **Object declaration** - locked book/tradition object(s) and critical-edition basis.
1. **A - AI diagnostic reconstruction (low-trust; reference only)** - Textual -> Literary -> Historical -> conclusion -> target inference chain. For OT, report MT and LXX/Old Greek literary results separately before historical comparison.
2. **B - Current frontier (primary exegetical basis)** - live proposals -> qualification/uptake -> steelman -> layer decomposition -> re-adjudication -> frontier conclusion or explicit unresolved judgment.
3. **Comparison and critique** - foreground substantive A/B conflicts; B audits frozen A; keep newer revisionist and older/traditional models distinct when they conflict; practical recommendation follows B's modernity-weighted ranking unless B itself remains unresolved.
4. **Theology / canon / reception / pastoral application** - only when requested, downstream from both tracks.

Before sending a substantive exegetical answer, verify that both A and B are visibly present and that no secondary scholarship appears inside A. If either check fails, repair the answer before sending.

Read `references/frontier-search.md` only when beginning Track B. Read `references/methodology.md` only to explain, audit, or revise the method.
