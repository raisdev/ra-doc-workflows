# ra-doc-workflows

Document-processing workflows for research administration. The worklows extract structured metadata from the varied documents that research administrators handle, such as award notices, proposal attachments, and sponsor-specific templates.

The workflows run on [Vandalizer](https://github.com/ui-insight/vandalizer), the open-source document extraction platform developed by the University of Idaho's AI4RA team. They are designed for Cornell's research administration system (RASS) but written to be reusable at other institutions.

## Background

Research administration offices process large volumes of documents that arrive in inconsistent formats. Templates and conventions differ across sponsors and organizations, so staff spend significant time on manual review and data entry. This repo explores whether AI-assisted extraction can reduce that burden while keeping every extracted field traceable to its source in the document.

The project is part of *The Fellowship of AI4RA*, a Cornell sub-award under NSF Grant #2427549 (University of Idaho prime). It is developed by Cornell's Research Administration Information Services (RAIS) with Cornell MEng Student Team Projects participants.

## Goals

1. Inventory the document types research administrators handle and how each is used.
2. Build a Vandalizer workflow for each priority document category, with source-tracked field extraction.
3. Pilot the workflows with a small group of research administration staff before any broader rollout.
4. Measure cost, speed, and output quality, along with time on task and user satisfaction.
5. Contribute the workflows and lessons back to the AI4RA community as open source.

## Scope

In scope are workflow definitions, extraction schemas, evaluation scripts and test sets, and documentation of document types and design decisions. Out of scope for now are production deployment (a stretch goal), the UDM-based RASS agent (a separate track), and Weill Cornell Medicine data.

## Data and security

This repo contains no real institutional data. Only synthetic or fully de-identified sample documents may be committed. Work on real documents happens only in approved Cornell environments, after the security and compliance review.

## License

GPL-3.0

## Contributors

See the [contributors list](https://github.com/raisdev/ra-doc-workflows/graphs/contributors).
