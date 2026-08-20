# Fundamental Context Architecture - Agent Instructions

## Scope
- This repository contains the working doctrine and public review material for Fundamental Context Architecture (FCA).
- FCA is vendor-neutral and separate from any one company implementation, vendor stack, platform, or client engagement.
- Version `1.0` is the FCA Founding Edition and first stable public doctrine release. Do not describe FCA as a public standard, proven enterprise framework, certification program, or finished methodology.

## Repository Boundary
- Committed content must be clean doctrine, reviewed guidance, polished comparisons, or intentional public-facing material.
- Raw research, scratch notes, private due diligence, client material, company-private reasoning, and unsanitized implementation records must not be committed unless explicitly sanitized and approved.
- Local ignored folders such as `research/`, `raw_research/`, `notes/`, `scratch/`, `private/`, and `due_diligence_raw/` may exist. Treat them as private working context, not publishable source material.
- Do not copy client-specific, company-private, security-sensitive, credential, financial, legal, or confidential material into committed doctrine.

## First Read
When starting work in this repository:

1. Confirm current working directory and `git status`.
2. Read `README.md`.
3. Read `blueprint.md`.
4. Read `CHANGELOG.md`.
5. Read only the relevant guidance or comparison files needed for the task.

If the working tree is dirty, preserve user changes. Do not overwrite, revert, reformat, or move files you did not intentionally change unless explicitly approved.

## Doctrine Rules
- FCA should remain tool-agnostic and vendor-neutral.
- FCA may define required capabilities, primitives, evidence, and conformance questions, but must not require a specific cloud, database, graph engine, RAG stack, semantic layer, workflow engine, repository system, or AI platform.
- Distinguish clearly between:
  - FCA doctrine;
  - implementation patterns;
  - vendor/product comparisons;
  - private/raw research.
- Do not claim novelty where adjacent disciplines already cover the same ground. Name overlaps and boundaries explicitly.
- Do not turn one implementation into the universal FCA pattern.
- Do not weaken FCA into vague "AI plus context" language. Keep the focus on governed fundamental context, including its operational use, authority, semantics, lifecycle, boundaries, permissions, human approval, actionability, provenance, evidence, and reuse.

## External Comparisons
- Use current, cited sources when comparing FCA to external frameworks, vendors, standards, or market categories.
- Treat TOGAF, NIST AI RMF, Data Mesh, Data Fabric, semantic layers, DDD, MDA/MDE, RAG/GraphRAG, agent orchestration, data governance, and vendor context platforms as serious adjacent work.
- FCA should be positioned by precise contribution, not by pretending adjacent work does not exist.
- Avoid long quoted passages from external sources. Summarize with links and keep citations traceable.

## Writing Style
- Write concise doctrine, not conversation transcripts.
- Use direct language, short sections, and practical definitions.
- Prefer stable terms over marketing slogans.
- Clearly mark status for drafts, comparisons, and public-facing material.
- Do not introduce client-specific material unless it is sanitized and explicitly approved.
- Use ASCII unless a file already clearly uses another character set.

## Versioning
- `1.0` is the Founding Edition and first stable public FCA doctrine.
- `1.x` releases preserve the founding architecture while incorporating accepted corrections, clarifications, and compatible improvements.
- `2.0` is reserved for potential major evolution that may be co-designed with community contributors under explicit governance.

Do not advance version labels without explicit maintainer approval of the release boundary.

## Git Hygiene
- Before committing, run `git status` and `git diff --check`.
- Commit only relevant files for the current task.
- Do not commit ignored/private research folders, credentials, client material, local environment files, generated scratch output, or unrelated user changes.
- If unsure whether a file is publishable, leave it uncommitted and ask.

## Expected Startup Response
When a new agent is started in this repository, it should state:

- current working directory;
- branch and git status;
- files read for initial context;
- whether private ignored research is present but excluded from committed context;
- the proposed next step for the requested task.
