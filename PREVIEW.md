# About the public preview

LocalFirst-AI helps you give an assistant responsibility for practical work: complete applications, project costings, research, launch packages, documents and media. Hosted or local models use the tools you select, with conversations, notes, tasks and results kept in workspaces.

Read the [V1.0 overview](RELEASE.md) for a feature-led introduction. Published binaries and checksums are listed on the [official Releases page](https://github.com/daemosofchaos/localfirst-ai-preview/releases).

## Available platforms

| Platform | Availability |
|---|---|
| Windows x64 | Installer and portable archive; recommended preview experience. |
| Android | Early sideloaded preview for Android 7.0+ arm64-v8a devices and x86_64 emulators. |
| Web, macOS and iOS | No public package in this release. |

Android requests camera, microphone, foreground location and calendar permissions when their features are invoked. Desktop file, process and application actions are not available on every platform.

## What you can use

- Independent project work with a capable model and the required access: implementation, checking, repair and finished deliverables, not only planning or advice.
- Supervisor workspaces for coordinated assignments, optional nested teams, visible worker results and shared limits.
- Hosted and compatible local/self-hosted text models, with a required Chat profile and optional Utility assignment.
- Guided first-run setup and feature tours, with replay in Tutorials and guides.
- Native Anthropic Claude and Google Gemini profiles, and OpenAI-compatible connections.
- Rooms for assistant roles and workspaces for separate projects.
- Editable notes, tasks, attachments and generated document artifacts.
- Built-in tools with Direct or searchable Gateway routing and Room/Workspace access choices.
- Current web research with a separately configured Brave Search API key.
- Inline charts and comparisons, documents, spreadsheets, presentations and image generation where configured.
- Styled HTML-to-PDF reports on Windows with installed Edge or Chrome.
- Exact conversation-text exports and copies of original artifacts/attachments.
- Specialized profiles for memory, images, speech, transcription and realtime interaction where supported.
- Compatible MCP integrations and backup/restore features.

Availability depends on the installed release, device, model, provider, services and granted access. LocalFirst-AI does not bundle API credits, model-server software or model weights.

Delegation remains within the same Room and cannot expand a worker's inherited tools or file-tool access. Shared request and time allowances are not currency spending caps. Interrupted assignments are not replayed automatically, and cancellation does not undo completed external actions. Read the [Supervisor guide](docs/supervisor-workspaces.md) before starting a team.

[Setup guides](docs/README.md) · [Complete-project examples](docs/use-cases.md) · [Independent assistants](docs/independent-assistants.md)

## Reusable methods and coordinated work

[Skills](docs/skills.md) keep your writing style, research methods and checklists ready to use again. Create your own, import trusted guidance or turn a useful response into a workflow draft. Choose when each Skill applies, keep projects on the version you prefer, and share suitable guidance with specialists.

Teams are easier to follow with separate Active and History views and a Stop control in the message box. The Supervisor can finish a handover after specialists reach their limits, and turning off Supervisor hides the panel without losing saved history. See the updated [Supervisor guide](docs/supervisor-workspaces.md).

Skills support written instructions and text references; bundled scripts are not run. Review important output and imported guidance. Connected models and services may incur charges and receive task information; see [Privacy](PRIVACY.md) and [Billing](TOKEN-USAGE-AND-BILLING.md).

## Preview limitations

Keep backups and review important output.

Key platform and configuration boundaries:

- Use your model and endpoint's supported settings and tool-call format.
- Windows and Android have different device and tool coverage.
- Back up your data before upgrades that change settings or storage formats.
- Local actions and integrations run within available permissions, without an application sandbox.
- Provider billing records remain authoritative; app usage figures are estimates, not spending controls.
- Support is best-effort, as described in [Support](SUPPORT.md).

Begin with a short task and limited access, then configure larger requests and specialized media for your model.

## Your data and accounts

LocalFirst-AI is local-first, not automatically offline. Models and integrations receive the content needed for their requests. A local tool's result can be included in a later remote model request.

You choose the accounts, endpoints, keys, files and integrations used, and are responsible for:

- provider and infrastructure charges, including search and media services;
- monitoring provider quotas, limits and usage;
- deciding which content may be sent to configured services;
- protecting credentials and maintaining backups;
- reviewing consequential operations and important results.

LocalFirst-AI does not include credits, enforce provider budgets, control prices or issue provider refunds. Read [Billing](TOKEN-USAGE-AND-BILLING.md), [Privacy](PRIVACY.md) and [Security](SECURITY.md) before using real data or paid credentials.

## Downloads and terms

Use only the [official website](https://localfirst-ai.com) or this repository's [GitHub Releases](https://github.com/daemosofchaos/localfirst-ai-preview/releases), and verify the published SHA-256 manifest before installing.

The [binary application licence](LICENSE.md) permits personal, professional and commercial use of the unmodified official app, without an application-use fee under that licence version. They are not an open-source licence. This repository contains preview downloads and public documentation, not the application source; any future public source release and licence will be announced separately.

## Help

Start with [Getting started](GETTING-STARTED.md) and [Troubleshooting](docs/troubleshooting.md). For reproducible problems or focused suggestions, follow [Support](SUPPORT.md). Never publish API keys, private endpoints, confidential prompts or sensitive files in an issue.
