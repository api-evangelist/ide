# IDE (ide)
An index and topic collection covering integrated development environments (IDEs), code editors, and cloud workspaces with APIs. This topic captures the editors, IDEs, and developer workspaces that expose programmable surfaces, including local desktop IDEs (Visual Studio, JetBrains IDEs, Eclipse), modern AI-first editors (Cursor, Windsurf), agentic coding assistants (Aider, Cline, Continue, GitHub Copilot, Amazon Q Developer, Tabnine), notebook environments (Jupyter, JupyterLab, JupyterHub, Google Colab), cloud development platforms (Replit), plugin marketplaces (JetBrains Marketplace), and editor extension APIs (Visual Studio Code). This collection is distinct from API client tooling (HTTP request testing) and focuses on the surface where developers write, edit, debug, and run code.

**URL:** [https://apievangelist.com](https://apievangelist.com)

## Tags:

 - IDE, Code Editor, Cloud IDE, Developer Tools, Workspaces

## Timestamps

- **Created:** 2026-05-19
- **Modified:** 2026-05-19

## Common Properties

- [Portal](https://apievangelist.com)
- [GitHubOrganization](https://github.com/api-evangelist)
- [JSONSchema - Workspace Schema](https://raw.githubusercontent.com/api-evangelist/ide/refs/heads/main/json-schema/ide-workspace-schema.json)
- [JSONSchema - Extension Schema](https://raw.githubusercontent.com/api-evangelist/ide/refs/heads/main/json-schema/ide-extension-schema.json)
- [JSON-LD](https://raw.githubusercontent.com/api-evangelist/ide/refs/heads/main/json-ld/ide-context.jsonld)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/ide/refs/heads/main/vocabulary/ide-vocabulary.yaml)

## Features

| Name | Description |
|------|-------------|
| Extension and Plugin APIs | IDEs expose extension APIs that let third-party developers add commands, views, language support, debuggers, and integrations. Examples include the VS Code Extension API, JetBrains Platform SDK, and Eclipse Platform APIs. |
| Language Server Protocol (LSP) | LSP is a JSON-RPC protocol that standardizes how editors communicate with language tooling (completion, hover, diagnostics, references) across VS Code, Neovim, JetBrains, and Eclipse Theia. |
| Workspace and Project APIs | Editors expose workspace, project, and file-system APIs that extensions and remote clients use to read, write, and watch source files, including multi-root workspaces and remote workspace orchestration. |
| AI Completion and Chat APIs | Modern editors and assistants (Copilot, Cursor, Windsurf, Tabnine, Continue, Cline, Aider, Amazon Q Developer) expose inline completion, chat, and agentic edit APIs that integrate LLMs into the developer loop. |
| Plugin and Extension Marketplaces | Marketplaces like the VS Code Marketplace and JetBrains Marketplace host millions of extensions and expose APIs for publishing, searching, and managing plugin metadata, downloads, and reviews. |
| Notebook and Kernel APIs | Jupyter and JupyterLab expose REST APIs and a WebSocket-based messaging protocol for managing kernels, sessions, contents, and terminals, powering notebook computing in Colab and JupyterHub. |
| Cloud Workspaces and Remote Development | Cloud-based IDEs like Replit and remote-development backends provide APIs for provisioning ephemeral workspaces, managing containers, and streaming editor sessions to browsers. |
| Debugger and Test Adapter Protocols | Standards like the Debug Adapter Protocol (DAP) and Test Adapter Protocol let editors integrate with debuggers and test runners across many languages through a single, portable interface. |

## Use Cases

| Name | Description |
|------|-------------|
| Building AI Coding Assistants | Developers integrate LLM-backed completion and agentic editing into IDEs through extension APIs and editor-side hooks. |
| Custom Internal Developer Tooling | Engineering platform teams build internal extensions for VS Code, JetBrains, and Eclipse to embed company-specific scaffolding, deployment, and code-review tooling. |
| Notebook-Driven Data Science Workflows | Data teams use Jupyter, JupyterLab, JupyterHub, and Google Colab APIs to automate notebook execution and manage shared kernels. |
| Cloud-Native Onboarding and Ephemeral Environments | Platforms like Replit use APIs to spin up pre-configured cloud IDEs for tutorials, interviews, and short-lived environments. |
| Plugin Distribution and Marketplace Automation | ISVs publish, version, and analyze extensions via the JetBrains Marketplace and Visual Studio Marketplace APIs. |
| Game and Real-Time Editor Tooling | Engines like Unity expose editor APIs and packages that integrate live services directly into the editor. |
| Standardized Language Tooling Across Editors | Tooling authors implement Language Server Protocol once and expose features across every LSP-capable editor. |

## Integrations

| Name | Description |
|------|-------------|
| Visual Studio Code | The dominant open-source code editor with the VS Code Extension API, LSP and DAP implementations, and a marketplace of 60,000+ extensions. |
| JetBrains IDEs | A family of professional IDEs (IntelliJ IDEA, PyCharm, GoLand, WebStorm, PhpStorm, RubyMine, Rider) built on the JetBrains Platform SDK. |
| Cursor | AI-first code editor forked from VS Code with deep agentic editing and codebase-aware chat. |
| Windsurf | AI-native editor (formerly Codeium) featuring the Cascade autonomous agent and enterprise APIs for analytics and team management. |
| GitHub Copilot | AI pair programmer integrated into VS Code, Visual Studio, JetBrains, Neovim, and the GitHub web UI, with Copilot Chat and agent APIs. |
| Jupyter / JupyterLab | Interactive computing platform exposing REST APIs and a WebSocket messaging protocol for kernels, sessions, contents, and terminals. |
| Replit | Cloud development platform offering instant containerized workspaces, multiplayer editing, and APIs for managing Repls and deployments. |
| Eclipse Foundation | Open-source community behind the Eclipse IDE, Eclipse Theia, Eclipse Che, and a wide ecosystem of editor and language tooling projects. |

## Artifacts

Machine-readable API specifications organized by format.

### JSON Schema

- [Workspace Schema](json-schema/ide-workspace-schema.json)
- [Extension Schema](json-schema/ide-extension-schema.json)

### JSON Structure

- [Workspace Structure](json-structure/ide-workspace-structure.json)
- [Extension Structure](json-structure/ide-extension-structure.json)

### JSON-LD

- [IDE Context](json-ld/ide-context.jsonld)

## Vocabulary

- [IDE Vocabulary](vocabulary/ide-vocabulary.yaml) — Unified taxonomy covering resources, actions, workflows, and personas across IDEs, code editors, plugin marketplaces, notebook environments, and cloud workspaces

## Network

This index references the following IDE, code editor, and cloud workspace repositories:

- [Aider](https://github.com/api-evangelist/aider)
- [Amazon Q](https://github.com/api-evangelist/amazon-q)
- [Cline](https://github.com/api-evangelist/cline)
- [Continue](https://github.com/api-evangelist/continue-dev)
- [Cursor](https://github.com/api-evangelist/cursor)
- [Cursor Rules](https://github.com/api-evangelist/cursorrules)
- [Eclipse Foundation](https://github.com/api-evangelist/eclipse)
- [GitHub Copilot](https://github.com/api-evangelist/github-copilot)
- [Google Colab](https://github.com/api-evangelist/google-colab)
- [Google Flutter](https://github.com/api-evangelist/google-flutter)
- [Integrated Development Environment](https://github.com/api-evangelist/integrated-development-environment)
- [JetBrains](https://github.com/api-evangelist/jetbrains)
- [JetBrains Marketplace](https://github.com/api-evangelist/jetbrains-plugin)
- [Jupyter](https://github.com/api-evangelist/jupyter)
- [JupyterHub](https://github.com/api-evangelist/jupyterhub)
- [Jupyter Hub](https://github.com/api-evangelist/jupyter-hub)
- [Jupyter Notebook](https://github.com/api-evangelist/jupyter-notebook)
- [Jupyter Server](https://github.com/api-evangelist/jupyter-server)
- [JupyterLab](https://github.com/api-evangelist/jupyterlab)
- [Microsoft Visual Studio](https://github.com/api-evangelist/microsoft-visual-studio)
- [Replit](https://github.com/api-evangelist/replit)
- [Tabnine](https://github.com/api-evangelist/tabnine)
- [Unity](https://github.com/api-evangelist/unity)
- [Visual Studio](https://github.com/api-evangelist/visual-studio)
- [Visual Studio Code](https://github.com/api-evangelist/visual-studio-code)
- [Windsurf](https://github.com/api-evangelist/windsurf)
- [Windsurf Rules](https://github.com/api-evangelist/windsurfrules)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
