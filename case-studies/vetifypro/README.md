# VetifyPro / Nova Vet Family — AI-Assisted Veterinary Product Platform

**Status:** Production environment and release workflow documented | **Access:** Restricted application; public marketing/product entry is not an unrestricted demo.

**Core technologies:** Python, Django / DRF, Next.js, NestJS, TypeScript, gRPC, Docker, CircleCI, Kestra.

[← Back to the project showcase](../../README.md)

## A working software product, not an architecture mock-up

VetifyPro is part of a veterinary practice-management product ecosystem that includes a web experience, a backend-for-frontend, an AI service, and data-ingestion workflows. The software is organized into independently deployable components rather than being a single static demonstration.

### What the software does

- Provides application workflows for veterinary teams through a Next.js web frontend.
- Exposes language-model generation and transcription capabilities through a Python/Django AI service.
- Connects the web product to its underlying practice-management services through a NestJS backend-for-frontend and environment-specific gRPC interfaces.
- Ingests practice-management exports through a separate pipeline for clinic and business information.
- Keeps development, staging, and production release paths separate.

## Operational evidence

| Evidence | What it establishes |
| --- | --- |
| Documented production environment and release branch | A production release path exists for the application; not just a local design |
| CircleCI release pipelines and per-component container builds | Software components are built and published through an operational release process |
| Manual approval before production releases | Release authority is controlled rather than assumed from a successful build |
| Backend and QA documentation | The Python AI service, ingestion pipeline, and browser-testing workflows have implementation and test instructions |

**Scope of verification:** Repository documentation describes this delivery process and production environment. This public case study does not independently attest to current production uptime, customer adoption, or a particular deployed revision.

## Engineering work

- Full-stack integration between frontend interfaces, API/BFF services, and AI-backed capabilities.
- AI application boundaries for transcription and language-model workflows.
- Integration with external core practice-management services without reproducing their proprietary internals.
- Environment-specific configurations, automated QA, and release-aware software delivery.

## My contribution

My engineering work includes AI-service integration, product and full-stack development, architecture, testing, debugging, and delivery coordination. This case study does not claim authorship of third-party platform components.

## Source code and privacy

The implementation is private. No source code, infrastructure credentials, patient records, private service endpoints, deployment configuration, or customer information is published in this case study.
