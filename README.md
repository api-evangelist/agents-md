# AGENTS.md (agents-md)
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
