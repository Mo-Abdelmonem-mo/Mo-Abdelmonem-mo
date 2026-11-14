# VetifyPro / Nova Vet Family — AI-Assisted Veterinary Product Platform

**Operational status:** Working AI-assisted veterinary software platform with documented development, staging, and production environments. Access is restricted.

**Technology:** Python · Django/DRF · Next.js · NestJS · TypeScript · gRPC · Docker · CI/CD

VetifyPro combines an interactive veterinary product, Python-based AI services, APIs, and practice-data processing. Its AI services support language-model and transcription workflows; its web application connects through backend APIs to the wider practice-management platform.

[← Back to the project showcase](../../README.md)

### What the software does

- Provides application workflows for veterinary teams through a Next.js web frontend.
- Exposes language-model generation and transcription capabilities through a Python/Django AI service.
- Connects the web product to its underlying practice-management services through a NestJS backend-for-frontend and environment-specific gRPC interfaces.
- Ingests practice-management exports through a separate pipeline for clinic and business information.
- Keeps development, staging, and production release paths separate.


## Engineering work

- Full-stack integration between frontend interfaces, API/BFF services, and AI-backed capabilities.
- AI application boundaries for transcription and language-model workflows.
- Integration with external core practice-management services without reproducing their proprietary internals.
- Environment-specific configurations, automated QA, and release-aware software delivery.

## My contribution

My engineering work includes AI-service integration, product and full-stack development, architecture, testing, debugging, and delivery coordination. This case study does not claim authorship of third-party platform components.

## Source code and privacy

The implementation is private. No source code, infrastructure credentials, patient records, private service endpoints, deployment configuration, or customer information is published in this case study.
