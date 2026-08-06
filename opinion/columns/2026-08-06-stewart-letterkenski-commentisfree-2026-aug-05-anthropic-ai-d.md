---
headline: Anthropic planned to shred the world’s books to extract what authors wrote
publish_date: '2026-08-06'
lede: 'Anthropic’s internal description of “Project Panama” was blunt: “our effort to destructively scan all the books in the world.” The company’s court exhibit advised discretion — “we don’t want it to be known that we are working on this” — and the project involved exactly what the name promised.'
pen_name: stewart-letterkenski
primary_entities: []
primary_themes: []
topic_tags: []
storyline_nexus: []
floor_values_engaged: []
framework_version: 1.1.0
generation_timestamp: '2026-08-05T22:58:21-07:00'
source_cluster_id: cluster_guardian_2026-08-05_commentisfree-2026-aug-05-anthropic-ai-d
gdelt_event_ids: []
consensus_floor_version: v0.3.0
publication_mindspec_version: v0.3.0
license: https://creativecommons.org/publicdomain/zero/1.0/
ai_disclosure: This article was generated algorithmically by Main Street Independent from the public sources listed in its Sources section.
ai_generated: true
sources:
  count: 1
  outlets:
  - The Guardian
  outlet_classes:
  - national_daily
  highest_reliability_tier: 2
  has_originating: true
  has_primary_document: false
figures_aggregate:
  count: 0
  series_ids: []
  sources: []
cross_article_links:
- slug: 2026-08-05-court-filings-show-anthropic-s-vendors-dismantled-books-to-build-ai-training-dat
  relation: extends
  strength: 0.6346
  confidence: high
draft: false
backlog_release: true
---

Anthropic’s internal description of “Project Panama” was blunt: “our effort to destructively scan all the books in the world.” The company’s court exhibit advised discretion — “we don’t want it to be known that we are working on this” — and the project involved exactly what the name promised. Books were sourced, shipped to warehouses, stripped from their bindings, cut into pages, scanned and discarded.

Not every book in the world was destroyed. The record does not establish that. But the documented ambition is bad enough: an AI company treated the physical record of human writing as disposable input material for a training dataset.

The legal backdrop makes the episode worse, not better. In *Bartz v Anthropic PBC*, decided in late July, Judge William Alsup ruled that using lawfully acquired books to train a large language model could qualify as fair use. The digital copy, the court found, “replaced” the original; there was no evidence that it was shown, shared or sold outside the company. In the narrow sense in which courts operate, that reasoning may hold. The digital output was used to create a different kind of product, and the company did not distribute the scanned files.

But the transformation was also literal. Anthropic hired a logistics manager, sourced books from vendors, housed them in a warehouse and found a digitisation company to do the work. Its vendors “stripped the books from their bindings, cut their pages to size, and scanned the books into digital form – discarding the paper originals”.

The engineering requirement was genuine. Claude needed a large, high-quality language dataset, preferably one created before 2022, before AI-generated text began substantially contaminating the contemporary textual record. Books offered what Anthropic wanted: long-form writing, carefully organised information, complex arguments and sustained fictional narratives. The court record describes the attraction as “well-curated facts, well-organized analyses, and captivating fictional narratives” that could help Claude write “as accurately and as compellingly as Authors”.

That requirement describes a data pipeline, not a natural law. A book is acquired; its binding is removed; its pages are cut to a fixed size; images are captured; optical character recognition converts those images into character sequences; the sequences are cleaned, segmented into tokens and filtered for duplication or unwanted material; the resulting corpus is then used to adjust model parameters. Each stage is a management choice. None requires the paper original to be destroyed. Destruction is a property of the acquisition workflow, not of language-model training.

The distinction matters because “the model needs the text” is not a specification. It is an incomplete requirement. A usable training corpus also needs provenance, legibility, quality control, deduplication, stable formatting, storage and a record of what was included or excluded. The physical book is not merely a container around text. It is the source artifact from which the text was extracted, and its destruction removes evidence that could be used to audit the extraction: which edition was scanned, whether pages were missing, whether the scan was altered, and whether the digital file actually corresponds to the purchased object.

Anthropic could have licensed electronic copies. It could have negotiated with publishers and authors. It could have acquired books while retaining them. Instead, it first used pirated sources, a decision that helped produce its $1.5bn out-of-court settlement with authors. When that approach became legally dangerous, the company turned to destructive scanning.

The reported description of copyright management as a “legal/practice/business slog” is revealing. It captures the company’s apparent view of negotiating over the works it wanted to use: not as the ordinary cost of building a commercial dataset, but as an obstacle to be avoided. In engineering terms, Anthropic selected a system architecture that removed the rights-holder from the data-ingestion path. The company did not solve the permission problem. It routed around the person who could grant permission.

That is the central technical fact of this case. Anthropic needed human writing badly enough to build warehouses around it, yet treated the physical source and the people who made it as friction in the pipeline. The company separated content from provenance, then treated the separation as efficiency.

The law helped make that separation possible. Fair use recognises the use of copyrighted expression in certain transformative circumstances. But the doctrine is concerned primarily with the text and its economic use, not with whether the extraction architecture preserved the source artifact. The court’s “replacement” reasoning describes a digital file taking the functional place of a paper book inside Anthropic’s system. It does not establish that the paper object was technically irrelevant before the system consumed it.

A printed book is also a binding, a typeface, a paper object, a record of manufacture and ownership, and sometimes a surviving witness to a particular moment. Those features are not all represented in a token sequence. When the binding is cut away and the pages are fed into a scanner, the model receives one representation of the work and the public loses another. The loss is not repaired by saying that the model’s input layer never represented it.

The record notes that US law contains few provisions governing the treatment of books as cultural objects. That absence matters. There is no endangered-species list for printed works and no clear rule declaring that a book’s physical survival has value independent of the information extracted from it. A company can therefore describe a project in terms of scanning “all the books in the world” while the law asks a narrower question: what happened to the digital copy?

The engineering version of the question is more exact: what information did the pipeline preserve, what information did it discard, and who had authority to decide? The answer is not “the algorithm”. Staff, vendors and managers chose the acquisition method, the cutting process, the scanning equipment, the quality thresholds, the retention policy and the disposal procedure. The model did not decide that the source should be destroyed. The architecture was designed around that choice.

This is not an argument that every printed book must be preserved forever. It is an argument against allowing the company that wants the words to define the minimum information worth keeping. If a source can be replaced by a digital copy, the replacement should be demonstrated rather than asserted. A proper system would retain provenance records, preserve representative physical copies, document the scanning process, record rejected or damaged pages and make the destruction decision auditable. “No evidence that the digital copy was shown, shared or sold” does not answer whether the acquisition process itself was accountable.

Anthropic’s future research-library ambitions may present the company as a preserver, but preservation after extraction is not the same as preservation before extraction. A library is not simply a server with shelves attached. It maintains objects, catalogues their histories and preserves the conditions under which later readers can inspect them. A private corpus optimised for model training has a different objective function: maximise useful language signal while minimising cost and legal exposure. Confusing those objectives is how a warehouse becomes a library in the company’s public description.

The earlier [collision between Anthropic’s IPO ambitions and political backlash over AI risks](/articles/2026-06-20-anthropic-s-ipo-ambitions-collide-with-political-backlash-over-ai-risks/) showed how quickly the company’s public legitimacy can become part of the business problem. The book case exposes a deeper legitimacy problem: the company wants the authority and cultural power of human writing while resisting the obligations that come with relying on human writers.

Judge Alsup wrote that “for centuries, we have read and re-read books. We have admired, memorized, and internalized their sweeping themes, their substantive points, and their stylistic solutions to recurring writing problems.” The quotation also describes the dataset’s intended function, but with one important difference. Human readers encounter a book through a social and physical process that includes ownership, lending, memory and interpretation. A training pipeline converts the work into numerical representations whose value is measured by what they do to model loss during optimisation. Reading is not the same as parameter adjustment, and learning from a book is not the same as acquiring the right to decide that its physical form no longer matters.

Anthropic’s demand for a large, high-quality training dataset exposed a conflict between the company’s data practices and a copyright system not built for this kind of industrial-scale use. The answer cannot be to pretend that the physical book is irrelevant because the model only needs the text. Nor can it be to treat payment to authors as an avoidable administrative burden.

Training systems built on human writing should pay for that writing. Companies that destroy books should account for what they destroyed, why they destroyed it, which alternatives were evaluated and which records remain available for independent inspection. The remedy is not a decorative preservation promise after the fact. It is a data-governance requirement attached to the acquisition pipeline itself.

The question is not whether Anthropic destroyed every book in the world. It did not. The question is why a company seeking to build machines that write like authors found it easier to destroy books than to deal with the people who wrote them.

## Sources

### src_001 — The Guardian, national_daily, Tier 2, originating
**Publication date:** 2026-08-05
**Title:** Why is Anthropic destroying books? | Kathryn James
**URL:** https://www.theguardian.com/commentisfree/2026/aug/05/anthropic-ai-destroying-books
