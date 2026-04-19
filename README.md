# Activepieces (activepieces)
Activepieces is an open-source, no-code automation platform that enables users to streamline workflows by connecting various applications and automating tasks. It supports over 400 MCP servers and integrations, allowing developers to build custom TypeScript-based pieces. The platform offers AI agents, MCPs, and workflow automation capabilities with both cloud and self-hosted deployment options.

**URL:** [https://www.activepieces.com/](https://www.activepieces.com/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Automation, No-Code, Open Source, Workflow, AI Agents, MCP

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Activepieces API
The Activepieces API provides programmatic access to the automation platform, enabling management of flows, connections, projects, users, folders, pieces, templates, and execution monitoring. Uses Bearer token authentication.

**Human URL:** [https://www.activepieces.com/docs/endpoints/overview](https://www.activepieces.com/docs/endpoints/overview)

#### Tags:

 - Automation, Workflow, No-Code

#### Properties

- [Documentation](https://www.activepieces.com/docs/endpoints/overview)
- [OpenAPI](openapi/activepieces.json)
- [JSONSchema - Flow](json-schema/activepieces-flow-schema.json)
- [JSONSchema - Flow Run](json-schema/activepieces-flow-run-schema.json)
- [JSONSchema - Connection](json-schema/activepieces-connection-schema.json)
- [JSONSchema - Project](json-schema/activepieces-project-schema.json)
- [JSONStructure - Flow](json-structure/activepieces-flow-structure.json)
- [Example - Flow](examples/activepieces-flow-example.json)

## Common Properties

- [Portal](https://www.activepieces.com/)
- [Documentation](https://www.activepieces.com/docs/)
- [Pricing](https://www.activepieces.com/pricing)
- [GitHubOrganization](https://github.com/activepieces)
- [GitHubRepository](https://github.com/activepieces/activepieces)

## Features

| Name | Description |
|------|-------------|
| Visual Flow Builder | No-code drag-and-drop interface for building automation workflows with triggers and actions. |
| 400+ Integration Pieces | Over 400 pre-built integrations (pieces) written in TypeScript, available as MCP servers for AI agents. |
| AI Agents | Native AI agent creation and orchestration within automation workflows. |
| MCP Servers | Every piece automatically becomes an MCP server for use with AI agents and LLMs like Claude. |
| Custom Pieces | Build custom TypeScript-based integration pieces and publish them to npm. |
| Flow Versioning | Version control for flows with publish/draft states and rollback capabilities. |
| Self-Hosting | Deploy on Docker, Kubernetes, AWS, GCP, or any cloud provider with full data control. |
| Git Sync | Synchronize flows with Git repositories for version control and CI/CD integration. |

## Use Cases

| Name | Description |
|------|-------------|
| Marketing Automation | Automate lead capture, email sequences, and CRM updates from marketing platforms. |
| Sales Operations | Sync contacts, deals, and activities between CRM, email, and communication tools. |
| AI Agent Orchestration | Use Activepieces as an MCP server to give AI agents access to 400+ integrations. |
| IT Automation | Automate user provisioning, notifications, and system integrations. |
| Developer Integration Platform | Embed Activepieces as a white-label automation platform in SaaS products. |

## Integrations

| Name | Description |
|------|-------------|
| GitHub | Trigger workflows on GitHub events and automate repository operations. |
| Gmail | Send emails, parse inbound mail, and automate email workflows. |
| Slack | Send notifications, create channels, and respond to Slack events. |
| OpenAI | Integrate GPT models for AI-powered automation and content generation. |
| Google Sheets | Read and write data to Google Sheets for data synchronization workflows. |
| Salesforce | Create and update Salesforce records from automation workflows. |
| Stripe | Trigger flows on payment events and automate billing operations. |

## Solutions

| Name | Description |
|------|-------------|
| Community Edition | Free, open-source self-hosted deployment with unlimited flows and no task limits. |
| Plus | Cloud plan at $25/mo with 10 active flows, AI agents, and 500 AI credits. |
| Business | Cloud plan at $150/mo with 50 active flows, team collaboration, and 1,000 AI credits. |
| Enterprise | Custom pricing with unlimited flows, SSO, audit logs, and custom AI model support. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Activepieces API](openapi/activepieces.json)

### JSON Schema

- [Flow](json-schema/activepieces-flow-schema.json)
- [Flow Run](json-schema/activepieces-flow-run-schema.json)
- [Connection](json-schema/activepieces-connection-schema.json)
- [Project](json-schema/activepieces-project-schema.json)
- [User](json-schema/activepieces-user-schema.json)
- [Folder](json-schema/activepieces-folder-schema.json)
- [Piece](json-schema/activepieces-piece-schema.json)
- [Template](json-schema/activepieces-template-schema.json)

### JSON Structure

- [Flow](json-structure/activepieces-flow-structure.json)
- [Flow Run](json-structure/activepieces-flow-run-structure.json)
- [Connection](json-structure/activepieces-connection-structure.json)
- [Project](json-structure/activepieces-project-structure.json)

### JSON-LD

- [Activepieces Context](json-ld/activepieces-context.jsonld)

### Examples

- [Flow](examples/activepieces-flow-example.json)
- [Flow Run](examples/activepieces-flow-run-example.json)
- [Connection](examples/activepieces-connection-example.json)
- [Project](examples/activepieces-project-example.json)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Activepieces API](capabilities/shared/activepieces.yaml) — 9 operations for flows, flow runs, connections, and projects

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Workflow Automation](capabilities/workflow-automation.yaml) | Activepieces API | 8 | Developer, No-Code Builder, Operations Engineer |

## Vocabulary

- [Activepieces Vocabulary](vocabulary/activepieces-vocabulary.yaml) — Unified taxonomy mapping 8 resources, 6 actions, 1 workflow, and 3 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [activepieces-spectral-rules.yml](rules/activepieces-spectral-rules.yml) — 25 rules across 8 categories enforcing Activepieces API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
