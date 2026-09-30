# Klaus Behnam Shad

**Digital Humanities · Research Software · Oral History · Digital Editions**

I am a postdoctoral researcher and Oral History Coordinator at the Centre for Contemporary and Digital History (C²DH), University of Luxembourg, and Principal Investigator of LIFE. I design research software for digital editions, oral history and interview-based qualitative research. Across these projects, computational proposals, source references and human decisions are documented according to each tool's scope.

[Website](https://behnamshad.com/infrastructure) · [ORCID](https://orcid.org/0000-0002-3601-9024) · [Zenodo](https://zenodo.org/search?q=metadata.creators.person_or_org.name%3A%22Behnam%20Shad%2C%20Klaus%22) · [Teaching](https://behnamshad.com/teaching)

---

## Digital editions and linked data

**[TEI CRM Bridge](https://github.com/klausbehnamshad/tei-crm-bridge)** · research prototype  
Enriches TEI P5 letters with persons, places and organisations. It writes a new TEI file while preserving the reading text and existing markup of the input. Automatically recognised names remain documented candidates. A separate reviewed RDF graph records editorial decisions; accepted candidates additionally receive CIDOC CRM classifications and document references. W3C Web Annotation links mentions to text locations, and PROV-O records their provenance. An evaluation of version 0.2 used 40 letters from the Arthur Schnitzler correspondence edition. The current development branch also contains a CMIF export for correspondence metadata; it does not submit records to correspSearch.

## Oral history infrastructure

**[DINOH](https://github.com/klausbehnamshad/DINOH)** · umbrella project  
Connects a transcript workflow, a metadata model and shared methods. Its evaluation component provides 28 synthetic interview records in seven languages and a scoring procedure. The model backend remains a placeholder, so the published outputs are not model-performance results.

**[OHPIPE](https://github.com/klausbehnamshad/ohpipe)** · experimental public preview  
Versions transcripts and separates descriptive proposals from human decisions. A September 2026 pilot took one transcript through reviewed descriptive proposals; it did not establish export readiness or general model quality.

**[diar2](https://github.com/klausbehnamshad/diar2)** · local transcription tool  
Creates draft speaker-attributed transcripts and a listening review list for two-person interviews on Apple Silicon Macs. It runs offline by default after model setup; accuracy has so far been measured only on synthetic speech.

**[IMM-Core](https://github.com/klausbehnamshad/imm-core)** · published metadata model  
Defines a minimal core for interview-based qualitative research across disciplines: thirteen fields, seven required, specified in DCTAP with documented crosswalks.

## Qualitative analysis

**[AegisQDA](https://github.com/klausbehnamshad/AegisQDA)** · MVP for synthetic inputs  
A local privacy gateway before DigQDA. It detects identifiers, requires complete human review, replaces confirmed identifiers with typed surrogates and performs a second scan. Authorisation for real data is not enabled.

**[DigQDA](https://github.com/klausbehnamshad/DigQDA)** · pre-release  
Provides versioned method contracts and a local reference runner for source-bound coding proposals. Its conformance checks reject quotations or locators that cannot be resolved in the source. The consuming research application remains responsible for authorisation and review.

**[Relational Justice Analysis](https://github.com/klausbehnamshad/relational-justice-analysis)** · published analytical framework  
Makes its theory-guided coding rules and later revisions inspectable. An exploratory reliability study compares human and LLM coders and documents limits, including disagreement about which justice dimensions to assign.

Each repository documents its versions, tests and limitations; archived releases are available through Zenodo where applicable.

---

## Background

I am a social and cultural anthropologist (Dr. phil., Freie Universität Berlin). My research examines human differentiation, migration, citizenship, emotion, AI and society, and oral history. It draws on a socio-cybernetic understanding of society as a recursive system of distinctions reproduced through feedback, institutional routines and cognitive stabilisation. In the software, theoretical assumptions and initial analytical categories are made explicit, revisions are documented, and interpretation remains with the researcher.

I have taught at Freie Universität Berlin and the University of Luxembourg. Recent open-access books: *[The Sorting of Humanity](https://doi.org/10.14361/9783839476130)* and *[Die Sortierung der Menschheit](https://doi.org/10.14361/9783839475973)* (transcript, 2026).
