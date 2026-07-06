# Knowledge Foundry Specification (KFS)

> Build knowledge that thinks.

## Status

This project is in **Sprint 0: Foundation**.

The Knowledge Foundry Specification is an open specification for building living knowledge systems that are durable, explainable, versioned, and grounded in evidence.

KFS is not a note-taking app, an Obsidian vault, a database schema, or a single tool. It is a specification for how knowledge systems should represent evidence, facts, entities, relationships, activities, provenance, confidence, and change over time.

## Founding Principle

**The repository is the source of truth. Humans are the owners. AI is a collaborator.**

Conversations generate ideas. Repositories preserve decisions. Nothing is part of KFS until it is recorded, reviewed, and accepted in this repository.

## Why KFS Exists

Organizations, teams, families, researchers, and individuals accumulate knowledge across email, documents, conversations, meetings, files, applications, and memory. Over time, that knowledge becomes fragmented, stale, undocumented, and difficult to trust.

KFS exists to define a durable pattern for turning scattered information into maintained, connected, explainable knowledge.

## Design Goals

- Preserve provenance.
- Separate evidence from understanding.
- Make confidence explicit.
- Preserve history instead of overwriting it.
- Support human knowledge without pretending all knowledge has equal evidence.
- Remain implementation-agnostic.
- Treat knowledge as an engineered system.
- Build knowledge that outlives tools.

## Non-Goals

KFS does not aim to define a single application, storage backend, note-taking workflow, AI model, or user interface.

Reference implementations may use Markdown, Obsidian, Git, databases, graph stores, or other tools. The specification should remain useful even when those tools change.

## Project Structure

- `governance/` — project principles and decision rules.
- `kfd/` — Knowledge Foundry Design documents.
- `specification/` — the eventual formal specification.
- `implementations/` — reference implementation notes.
- `tooling/` — future tooling plans and placeholders.

## Current Roadmap

1. Sprint 0: foundation and governance.
2. Phase 1: core information model.
3. Phase 2: evidence and provenance model.
4. Phase 3: reference implementation.
5. Phase 4: tooling and validators.
6. Phase 5: reference deployments.
