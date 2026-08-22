# AGENTS.md (agents-md)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

AGENTS.md is an open standard file format that provides context and instructions to AI coding agents working on software projects. Like a README for agents, an AGENTS.md file lives in the project repository and tells AI agents how to build, test, and contribute code — including coding standards, build commands, testing procedures, and development conventions. Supported by over 60,000 open-source projects and major platforms including OpenAI Codex, Google Jules, Cursor, Devin, Windsurf, GitHub Copilot, and goose. Stewarded by the Agentic AI Foundation under the Linux Foundation.

**URL:** [https://agents.md/](https://agents.md/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - AI Agents, AI Copilot, Coding Standards, Developer Workflow, Open Standard, Documentation

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-04-19

## APIs

### AGENTS.md Specification
The AGENTS.md specification defines a standard Markdown file format for providing project context, build instructions, coding standards, and testing procedures to AI coding agents.

**Human URL:** [https://agents.md/](https://agents.md/)

#### Tags:

 - Open Standard, AI Agents, Developer Workflow, Specification

#### Properties

- [Documentation](https://agents.md/)
- [GitHubRepository](https://github.com/openai/agents.md)

## Common Properties

- [Portal](https://agents.md/)
- [Documentation](https://agents.md/)
- [GitHubOrganization](https://github.com/agentic-ai-foundation)
- [JSONSchema - AGENTS.md File Schema](https://raw.githubusercontent.com/api-evangelist/agents-md/refs/heads/main/json-schema/agents-md-file-schema.json)
- [JSON-LD](https://raw.githubusercontent.com/api-evangelist/agents-md/refs/heads/main/json-ld/agents-md-context.jsonld)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/agents-md/refs/heads/main/vocabulary/agents-md-vocabulary.yaml)

## Features

| Name | Description |
|------|-------------|
| Project Context for AI Agents | Provides AI agents with structured information about the project including its purpose, architecture, and key concepts. |
| Build and Test Instructions | Documents the exact commands needed to build, test, lint, and deploy the project so AI agents can execute them correctly. |
| Coding Standards | Specifies coding conventions, style guides, naming patterns, and best practices that AI agents should follow when generating code. |
| Monorepo Support | Supports nested AGENTS.md files in monorepo subdirectories, allowing different projects to have tailored agent instructions with closest-file-wins precedence. |
| Open Standard with No Required Fields | The format uses standard Markdown with no mandatory fields, giving teams flexibility to include only the context their agents need. |
| Broad Tool Support | Supported by 60+ AI coding tools and editors including OpenAI Codex, Google Jules, Cursor, Devin, GitHub Copilot, Windsurf, and goose. |

## Use Cases

| Name | Description |
|------|-------------|
| AI-Assisted Code Review | Provide AI coding agents with project conventions and standards so their generated code passes review without needing manual style corrections. |
| Autonomous Feature Development | Enable AI agents to independently implement features by giving them the context needed to set up the development environment, run tests, and validate their work. |
| Onboarding AI Agents to Existing Projects | Accelerate AI agent productivity on legacy codebases by documenting the context that would normally come from exploring the project. |
| Consistent Multi-Agent Workflows | Ensure all AI agents working on a project operate from the same context, reducing inconsistencies when multiple agents collaborate. |
| Security-Aware AI Development | Document security considerations and sensitive file locations so AI agents avoid introducing vulnerabilities or accidentally exposing credentials. |

## Integrations

| Name | Description |
|------|-------------|
| OpenAI Codex | Native AGENTS.md support for AI coding tasks via OpenAI's coding agent. |
| Google Jules | AGENTS.md context ingestion in Google's AI coding agent for autonomous development tasks. |
| Cursor | AGENTS.md file discovery and context loading in Cursor's AI-assisted editor. |
| Devin (Cognition) | AGENTS.md support in Cognition's autonomous coding agent Devin. |
| GitHub Copilot | AGENTS.md integration in GitHub Copilot for project-aware AI code suggestions. |
| goose (AAIF) | AGENTS.md context loading in Block's open-source goose AI agent, now under the Agentic AI Foundation. |
| Windsurf | AGENTS.md support in Windsurf's AI-powered development environment. |
| JetBrains Junie | AGENTS.md discovery in JetBrains' AI coding assistant Junie. |

## Artifacts

Machine-readable API specifications organized by format.

### JSON Schema

- [AGENTS.md File Schema](json-schema/agents-md-file-schema.json)

### JSON Structure

- [AGENTS.md File Structure](json-structure/agents-md-file-structure.json)

### JSON-LD

- [AGENTS.md Context](json-ld/agents-md-context.jsonld)

## Vocabulary

- [AGENTS.md Vocabulary](vocabulary/agents-md-vocabulary.yaml) — Unified taxonomy mapping 4 resources, 5 actions, 2 workflows, and 2 personas across the AGENTS.md standard and AI coding tool ecosystem

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
