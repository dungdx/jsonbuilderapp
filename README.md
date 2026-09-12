# JsonAppBuilder

> JsonAppBuilder (https://jsonbuilderapp.com) is a no-code / low-code platform for designing, generating, and deploying full-stack business applications. Users model data, REST APIs, workflows, reports, and pages visually, then generate NestJS + React source ZIP files and deploy to Local Docker, self-hosted servers, Azure, AWS, Kubernetes, or a cloud CDN.

JsonAppBuilder is also known historically as MetaBuilder and Nexa MetaBuilder. The public product name and domain are **JsonAppBuilder** and **jsonbuilderapp.com**.

The platform does not host the customer's production database. Generated apps run on infrastructure the customer provides.

## Official sources

- [Product home](https://jsonbuilderapp.com/): Designer login and workspace
- [Documentation (Vietnamese)](https://jsonbuilderapp.com/docs/): Canonical public docs
- [Documentation (English)](https://jsonbuilderapp.com/docs/en/): English docs
- [Full text for language models](https://jsonbuilderapp.com/docs/llms-full.txt): Complete documentation in one file
- [Getting started](https://jsonbuilderapp.com/docs/bat-dau.html)
- [Concepts](https://jsonbuilderapp.com/docs/khai-niem.html)
- [FAQ](https://jsonbuilderapp.com/docs/faq.html)

## Core concepts

- Application: a deployable app that groups backend modules and frontend pages
- Module: backend building block (entities + REST API); JSON import supported
- Data model: shared schema library; JSON import supported
- Workflow: multi-step visual logic; JSON import supported
- Report template: PDF/HTML templates; JSON import supported
- Page: frontend screen designed in Page Builder; no JSON import
- Generate: export NestJS backend ZIP and React frontend ZIP
- Deploy: package â†’ environment â†’ destination; backend before frontend

## Recommended build order

1. Register or sign in at https://jsonbuilderapp.com/register or /login
2. Create a data model and/or module
3. Optionally add workflows and report templates
4. Create an application, attach modules, design pages
5. Generate backend, then generate frontend
6. Deploy backend, then deploy frontend

## Optional

- [Modules](https://jsonbuilderapp.com/docs/mo-dun.html)
- [Workflows](https://jsonbuilderapp.com/docs/quy-trinh.html)
- [Page Builder](https://jsonbuilderapp.com/docs/thiet-ke-trang.html)
- [Generate and deploy](https://jsonbuilderapp.com/docs/generate-deploy.html)
- [Glossary](https://jsonbuilderapp.com/docs/tu-dien.html)
