# Frontier Search Protocol

Load only for Track B. Its job is to find and qualify live proposals before adjudication.

## 1. Exhaustive candidate census before qualification

Treat Track B discovery as a **bounded exhaustive census**, not a high-recall sample. The bounded universe is modern secondary scholarship inside the rolling frontier window plus older lineage material only when a frontier-eligible work carries it. Do not apply author, venue, method, prestige, or interpretive filters until the candidate census has reached the saturation rule below.

Maintain a discovery ledger with one row per unique work and fields for author, year, title, publication type, venue/series/publisher, target passage/unit, discovery route, access status, and whether its interpretive position has been recovered. Deduplicate by bibliographic identity, not by title wording alone.

### A. Query lattice

Run every applicable family, using spelling/abbreviation variants and the target language where useful:

1. **Exact passage** - passage/range + interpretation, exegesis, debate, reassessment, reading, meaning.
2. **Lexeme/clause** - queried word, construction, decisive clause, neighboring clause, referent, event type, temporal frame, discourse function, semantic role.
3. **Whole containing unit** - paragraph/pericope/prologue/poem/oracle/scene + interpretation, theology, literary function, new reading.
4. **Whole book** - book + target theme/problem + interpretation; for OT add MT/Masoretic and LXX/Septuagint/Old Greek when versions differ materially.
5. **Composition blind spot** - unit/book + composition, source, redaction, original form, literary history, interpolation, edition, transmission; add version-history terms for OT when relevant.
6. **Inference-edge challenge** - use each load-bearing link in A's `TARGET INFERENCE CHAIN` only to generate searches for alternative referent, event type, discourse function, semantic role, temporal frame, clause relation, or competing inference. A supplies queries, never evidence.
7. **Adversarial model search** - each live B-model + alternative, critique, response, reassessment, revision, competing reading.

Repeat productive queries with author names, title phrases, and newly discovered terminology. Escalate from lemma -> clause -> passage -> unit -> book -> researcher network. One empty query never establishes absence.

### B. Technical-commentary census

Enumerate **every frontier-eligible technical commentary or major research commentary directly covering the target book/passage that can be discovered**, regardless of series prior. Search preferred series separately - Hermeneia, EKK, IECOT, AYB, ICC - and also search broadly for other technical series and stand-alone commentaries. For each identified volume:

- add every author/editor responsible for the target passage as a mandatory researcher seed;
- recover authoritative name variants;
- search that scholar by exact passage, containing unit, decisive clause/term, composition, interpretation, and relevant theme;
- inspect the scholar's frontier-window bibliography rather than stopping after one hit.

Coverage cannot close while an identified frontier-eligible commentary author has not received this author-level sweep.

### C. Field-synthesis census

Enumerate all discoverable frontier-eligible handbooks, companions, state-of-research volumes, research guides, and major edited collections directly relevant to the biblical book or dispute. For each:

- treat every editor as a mandatory researcher seed;
- treat every contributor whose chapter intersects the book, unit, method, or disputed theme as a mandatory seed;
- scan the bibliography/reference list for additional frontier-window candidates;
- search each seed's frontier-window bibliography for target-relevant work.

Do not stop after two field hubs when more suitable hubs are discoverable.

### D. Publisher, series, journal, and repository census

Search the target passage/unit/book across the preferred scholarly ecosystems separately: Cambridge, Oxford, Yale, Harvard, Edinburgh, Mohr Siebeck, Brill, T&T Clark/Bloomsbury, De Gruyter, and comparable specialist presses discovered in the field. Search relevant commentary-series catalogs and major field journals when discoverable. Use institutional repositories, author publication lists/CVs, DOI metadata, scholarly indexes, and substantive reviews to recover works missed by general search.

For a mandatory researcher seed, build a **frontier-window author bibliography** from authoritative profiles, CVs, publisher pages, ORCID/DOI metadata, repositories, or equivalent sources, then inspect every plausibly relevant title. Name-based passage queries are a supplement to this bibliography census, not a substitute for it.

### E. Recursive citation closure

For every directly relevant or potentially decisive work:

- trace its frontier-eligible references backward;
- trace frontier-eligible works that cite, adopt, revise, or criticize it forward when discoverable;
- follow directly relevant reviews and review essays;
- add newly discovered authors/works to the ledger;
- run the same author-bibliography and target-query sweeps on each new serious seed.

Repeat this expansion recursively. Discovery is a graph-closure task: new serious nodes reopen the search.

### F. Saturation stop rule for discovery

There is **no candidate quota, minimum-count shortcut, or early pruning rule**. Close the candidate census only after all applicable A-E sweeps have been completed and **two consecutive full expansion rounds** produce no new directly relevant frontier-eligible work, no new serious interpretive cluster, and no new mandatory researcher seed. A full expansion round means rerunning the commentary, field-synthesis, author-bibliography, publisher/series, and citation-network sweeps for all newly added seeds from the previous round.

If access, indexing, language, or tool limits prevent closure, state the concrete limit and describe the census as incomplete. Do not convert practical search limits into a claim of exhaustiveness or consensus.

Only after this census closes may Track B qualify, rank, or prune the candidate set.

## 2. Rolling frontier window

Modern secondary scholarship is frontier-eligible only inside the rolling **15-year window**, inclusive: `current year - 15` through the current year. Primary texts, manuscripts, critical editions, lexical corpora, archaeology, and other first-order evidence are exempt.

A pre-cutoff proposal enters the present frontier only through a recent eligible work that adopts, develops, revises, or criticizes it. Use older work for lineage/background when needed, not to establish current distribution or carry the present conclusion.

## 3. Recover the interpretive payload, not a name or headline thesis

A major proposal counts as mapped only after recovering:
- its headline thesis;
- every **target-relevant subclaim** that could materially change the answer to the user's question;
- the target passage/unit and, for OT, textual tradition/version;
- the primary evidence for those claims;
- the inferential chain from that evidence to the target-relevant conclusion.

For a word- or verse-level question, distinguish **lexical sense** from **contextual referent/function**. A scholar can accept the same dictionary gloss yet directly challenge the target interpretation by reassigning the referent, event type, temporal frame, discourse function, clause relation, literary role, or the meaning of a neighboring clause used to constrain the word. Such a proposal is target-level relevant. Recover those unit-level claims before deciding what the scholar contributes to the target question.

Do not stop at the most visible claim in a title or abstract when the work treats the target unit more broadly. Once an author/work is directly relevant, expand recovery across the containing unit: search the exact passage/range, neighboring decisive clauses, key terms and constructions, and the interpretive categories that distinguish the live models. If accessible full text exists, inspect it and search within it before declaring the position recovered. Metadata, abstracts, publisher descriptions, titles, and isolated review summaries remain discovery aids.

Use a **target-sensitive completeness gate**: ask whether another argument or subclaim in the same work could materially weaken, strengthen, or redirect the answer being given. For every major proposal, record a compact contrastive map: `LEXICAL SENSE (if relevant) -> CONTEXTUAL REFERENT/FUNCTION -> INTERPRETATION OF LOAD-BEARING CLAUSES -> PRIMARY EVIDENCE -> EFFECT ON TARGET INFERENCE`. Mark each A inference link touched by the proposal as `supports`, `challenges`, `redirects`, or `unaddressed`. If these fields cannot yet be filled from the scholar's actual argument, mark the proposal **partially recovered** and continue searching.

When a directly relevant recent commentary is inaccessible, perform a mandatory same-author bridge: search that author within the frontier window for the exact passage and containing unit, then broaden to the decisive semantic/discourse/theme terms emerging from the dispute, and search recent substantive reviews and citation chains of the commentary. A recoverable eligible article, chapter, lecture, or repository text by the same author may carry the relevant argument when it genuinely represents the same view.

For each proposal that could affect the conclusion, also recover its strongest same-object literary case, inferential hinge, treatment of obvious counterevidence when available, and recent direct adoption/criticism. Agreement on a queried word's lexical gloss does not establish agreement on its contextual interpretation. Before saying a proposal leaves the target conclusion unchanged, verify every load-bearing premise or inference it addresses.

## 4. Qualification and discovery priors

Assess serious candidates on six separate fields:
- **recency**;
- **author provenance**;
- **publication ecosystem**;
- **current uptake**;
- **direct relevance**;
- **method compatibility**.

Derive frontier status from recency, provenance, publication ecosystem, uptake, and direct relevance. Method compatibility is an admissibility/audit gate. Direct relevance is required for target-level claims. These fields also feed the project's modernity/revision prior described below.

### Author provenance

Call an author **established-frontier** only with a sustained, field-relevant record of several substantial research monographs/books over time with Cambridge, Oxford, Yale, Harvard, Edinburgh, or genuinely comparable academic presses. One prestigious item, chapters, textbooks, edited-volume contributions, or general-audience books do not suffice by themselves.

A live proposal from a less-established author may enter through demonstrated recent uptake by established-frontier scholars or multiple high-level recent treatments. Label the proposal emerging/live without upgrading the author.

### Preferred scholarly ecosystem

Use venue and author provenance as a **meta-epistemic prior** after a proposal has cleared direct-relevance and method-compatibility gates. They do not become textual, literary, or historical evidence, but they may affect which live proposal Track B recommends.

Preferred publication signals:
- sustained specialist work with **Cambridge, Oxford, Yale, Harvard, Edinburgh**, or genuinely comparable academic presses;
- **Hermeneia, EKK, IECOT** - strong positive prior;
- **AYB** - positive prior;
- a **recent ICC** volume - positive prior when the author has strong field provenance and the volume directly treats the target passage;
- Mohr Siebeck, Brill, T&T Clark/Bloomsbury, De Gruyter, and comparable specialist presses may count positively when the work is technical, directly relevant, and carried by an established field researcher.

Venue never repairs a clear Layer 1-3 error. Directly relevant recent research can outrank an adjacent prestigious book.

### Modernity / revision prior

Track B deliberately prefers current revision over inherited familiarity when the newer proposal is serious. Apply this after recovering the actual arguments:

- Treat **recency as an affirmative prior inside the 15-year frontier window**, with the latest substantial statement of a live position preferred over an older statement when they conflict.
- Give a **newer revisionist proposal** a default ranking advantage when it is directly relevant, method-compatible, supported by admissible primary evidence, and carried by the preferred scholarly ecosystem.
- Historical longevity, traditional familiarity, and sheer inherited majority do not cancel that advantage. Current uptake still helps establish that a proposal is live, but the older reading needs a substantive same-layer rebuttal to displace a qualifying newer revision.
- If the newer proposal survives the rebuttal burden, recommend it distinctly. Keep the older/traditional reading as a serious alternative when warranted; do not average the two into a middle position.
- Use synthesis only when frontier-eligible scholarship itself proposes and argues for a synthesis from admissible evidence.

## 5. Citation-network and rebuttal pass

For each major directly relevant proposal:
- trace recent backward/forward citations and the author's later work;
- identify rival proposals and direct critiques;
- search for the author's or defenders' response to the strongest apparent objection;
- keep OT claims tied to the textual tradition actually interpreted.

A method-compatible frontier proposal may be ranked below a rival only when either:
1. eligible method-compatible scholarship supplies a stronger direct same-layer rebuttal to its decisive argument; or
2. there is a clear, independently checkable Layer 1-3 error, and recent defenders do not adequately answer it.

When a **newer revisionist proposal from the preferred scholarly ecosystem** challenges an older/traditional reading, apply that burden asymmetrically: the older reading regains priority only through a substantive same-layer rebuttal or a clear Layer 1-3 failure in the revision. Familiarity, longevity, broader historical uptake, or Track A do not meet this burden. If the response to an objection cannot be recovered, report the gap instead of treating the objection as decisive.

## 6. Method audit and stop rule

For each decisive proposal, separate:

```text
TEXTUAL EVIDENCE
LITERARY EVIDENCE
HISTORICAL EVIDENCE
EXEGETICAL INFERENCES
THEOLOGICAL / CANONICAL INFERENCES
```

Re-adjudicate in that order. Keep OT traditions separate at the literary layer; keep NT post-compositional additions outside the NA/ECM initial-text literary corpus. Historical/intertextual evidence may refine surviving literary models or trigger a same-object literary rerun, but may not directly reverse a literary result.

Freeze B only after the **candidate census has closed under the two-round saturation rule** (or a concrete access/indexing limit has been recorded), every major candidate has undergone proposal recovery and qualification, the citation/rebuttal pass and method audit are complete, and further recursive expansion is producing no new directly relevant work, serious live model, mandatory researcher seed, or rebuttal that changes the dispute. Every load-bearing A inference edge must have received an adversarial search pass, and every major proposal that challenges or redirects one of those edges must have its inferential effect stated explicitly. A major directly relevant proposal may remain **partially recovered** only when a concrete access limit is reported; missing recovery supplies no evidence about the scholar's target-relevant position.

Claim consensus only when distribution has been independently established. Consensus is descriptive rather than a requirement for recommendation: a qualifying newer revision may be Track B's preferred reading before it becomes the majority view. Otherwise describe the mapped frontier and its uncertainty.
