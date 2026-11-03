# GitHub Copilot Toolbox — MCP & Skills awareness

_Generated: 2026-11-03T22:00:33.381Z_

## How to use this report

- **Saved copy:** This file is **`.github/copilot-toolbox-mcp-skills-awareness.md`** — refreshed whenever the toolbox runs an MCP & Skills scan (including on workspace open when auto-scan is enabled). It is meant for **Copilot workspace context** together with `.github/copilot-instructions.md` (which gets a shorter replaceable summary when auto-merge is on).
- **MCP:** Lists **configured** servers from `mcp.json`. **Live tool use** still requires **Copilot Chat → Agent** with those servers **trusted/started** in the MCP tools UI.
- **Skills:** **On-disk** folders with `SKILL.md`. Copilot does not auto-load them; attach `SKILL.md` or paths in chat when useful.
- **Task routing:** When the user’s request matches a server’s purpose (e.g. Confluence → Confluence/Atlassian MCP), prefer that **server id** from the tables below.

---

## MCP — workspace

Workspace `mcp.json` _(folder: Election)_

- **c:\Users\LENOVO\OneDrive\Metrics\Dashboard\Election\.vscode\mcp.json** — _File missing_

_No active workspace servers in mcp.json._

## MCP — user profile

- **C:\Users\LENOVO\AppData\Roaming\Code\User\mcp.json** — _File exists — servers defined_

| Server id | Kind | Detail |
|-----------|------|--------|
| microsoft/markitdown | stdio | uvx markitdown-mcp@0.0.1a4 |

## Skills (local `SKILL.md` folders)

### Project-scoped

_None found (or no workspace open)._

### User-scoped

- **accidental-data-loss-prevention** — `C:\Users\LENOVO\.copilot\skills\accidental-data-loss-prevention`
  - |

- **bigquery-data-transfer-service** — `C:\Users\LENOVO\.copilot\skills\bigquery-data-transfer-service`
  - Discovers and inspects BigQuery Data Transfer Service (DTS) configurations.

- **building-data-apps** — `C:\Users\LENOVO\.copilot\skills\building-data-apps`
  - |

- **cloud-databases-onboarding** — `C:\Users\LENOVO\.copilot\skills\cloud-databases-onboarding`
  - Guides users through discovering their database requirements, recommends

- **data-autocleaning** — `C:\Users\LENOVO\.copilot\skills\data-autocleaning`
  - Automated data quality and transformation capabilities for Dataform/dbt/BigQuery

- **dataform-bigquery** — `C:\Users\LENOVO\.copilot\skills\dataform-bigquery`
  - Expertise in generating clean, correct, and efficient Dataform pipeline

- **dbt-bigquery** — `C:\Users\LENOVO\.copilot\skills\dbt-bigquery`
  - Expert guidance for creating, modifying, and optimizing dbt pipelines

- **discovering-gcp-data-assets** — `C:\Users\LENOVO\.copilot\skills\discovering-gcp-data-assets`
  - |

- **enforcing-resource-attribution** — `C:\Users\LENOVO\.copilot\skills\enforcing-resource-attribution`
  - Enforces resource attribution for CLI commands. Use this skill whenever

- **gcp-data-pipelines** — `C:\Users\LENOVO\.copilot\skills\gcp-data-pipelines`
  - Primary entry point for building, managing, and orchestrating data pipelines

- **gcp-dataflow** — `C:\Users\LENOVO\.copilot\skills\gcp-dataflow`
  - |

- **gcp-pipeline-orchestration** — `C:\Users\LENOVO\.copilot\skills\gcp-pipeline-orchestration`
  - This skill helps the agent generate or update orchestration pipeline

- **gcp-pipeline-resource-provisioning** — `C:\Users\LENOVO\.copilot\skills\gcp-pipeline-resource-provisioning`
  - |

- **gcp-spark** — `C:\Users\LENOVO\.copilot\skills\gcp-spark`
  - |

- **gcp-spark-observability** — `C:\Users\LENOVO\.copilot\skills\gcp-spark-observability`
  - Monitors, inventories, and assesses Google Cloud Managed Service for

- **gcp-spark-troubleshooting** — `C:\Users\LENOVO\.copilot\skills\gcp-spark-troubleshooting`
  - Provides expert guidance for troubleshooting Google Cloud Spark and Dataproc

- **managing-python-dependencies** — `C:\Users\LENOVO\.copilot\skills\managing-python-dependencies`
  - |

- **ml-best-practices** — `C:\Users\LENOVO\.copilot\skills\ml-best-practices`
  - |

- **notebook-guidance** — `C:\Users\LENOVO\.copilot\skills\notebook-guidance`
  - |-

- **schema-mapping** — `C:\Users\LENOVO\.copilot\skills\schema-mapping`
  - Guides the process of analyzing, mapping, and documenting transformations

- **skill-repair** — `C:\Users\LENOVO\.copilot\skills\skill-repair`
  - |

- **autobuild** — `C:\Users\LENOVO\.claude\skills\autobuild`
  - Autonomous scheduled build workflows and pipelines. Trigger on "/autobuild schedule", "run workflow", "automate build", or "schedule task".

- **doc-writer** — `C:\Users\LENOVO\.claude\skills\doc-writer`
  - Keeps user-facing docs in sync with public-API changes. Triggered by /persona doc-writer and auto-dispatched on a task_complete whose diff touches a public API (exported types, command contributions, MCP tools, CLI flags

- **intelligence** — `C:\Users\LENOVO\.claude\skills\intelligence`
  - Local-first intelligence layer that learns from past AI coding sessions, does RAG over your codebase, and cuts token waste. Trigger on "learn from my sessions", "index my code", "retrieve context", "/learn", "/index-code

- **kdream** — `C:\Users\LENOVO\.claude\skills\kdream`
  - Persistent always-on background agent with automatic memory consolidation. Trigger on "start background agent", "enable kdream", "/kdream start", "persistent daemon", or "auto-dream memory".

- **mateam** — `C:\Users\LENOVO\.claude\skills\mateam`
  - Multi-agent coordinator that spawns specialized sub-agents working in parallel. Trigger on "/mateam launch", "spawn agents", "multi-agent", or "coordinate team".

- **orchestrate** — `C:\Users\LENOVO\.claude\skills\orchestrate`
  - Multi-agent parallel development orchestrator. Reads task manifests, builds dependency DAGs, generates sprint plans, assigns scoped work to parallel agents, and coordinates review gates. Trigger on "/orchestrate", "plan 

- **security-auditor** — `C:\Users\LENOVO\.claude\skills\security-auditor`
  - Audits a target module for security defects against a seeded pattern set, writes a structured finding report with severity + disposition, and gates security-tier merges. Triggered by /persona security-auditor, by /sprint

- **skill-creator** — `C:\Users\LENOVO\.claude\skills\skill-creator`
  - Create new skills, modify and improve existing skills. Use when users want to create a skill from scratch, edit, or optimize an existing skill.

- **automate** — `C:\Users\LENOVO\.agents\skills\automate`
  - Use this skill to create Codex Automations.

- **autopilot** — `C:\Users\LENOVO\.agents\skills\autopilot`
  - >-

- **canvas** — `C:\Users\LENOVO\.agents\skills\canvas`
  - >-

- **create-hook** — `C:\Users\LENOVO\.agents\skills\create-hook`
  - >-

- **create-rule** — `C:\Users\LENOVO\.agents\skills\create-rule`
  - >-

- **create-skill** — `C:\Users\LENOVO\.agents\skills\create-skill`
  - >-

- **create-subagent** — `C:\Users\LENOVO\.agents\skills\create-subagent`
  - >-

- **deploy-with-vercel** — `C:\Users\LENOVO\.agents\skills\deploy-with-vercel`
  - >-

- **goal** — `C:\Users\LENOVO\.agents\skills\goal`
  - Set a goal that Codex will pursue to completion.

- **loop** — `C:\Users\LENOVO\.agents\skills\loop`
  - >-

- **microsoft-foundry** — `C:\Users\LENOVO\.agents\skills\microsoft-foundry`
  - Build, deploy, evaluate, optimize, fine-tune, and manage Microsoft Foundry agents, models, and resources end to end. USE FOR: foundry, azd ai agent, azd provision/deploy, hosted agent scaffold/develop/run/deploy/troubles

- **migrate-to-skills** — `C:\Users\LENOVO\.agents\skills\migrate-to-skills`
  - >-

- **new-repo** — `C:\Users\LENOVO\.agents\skills\new-repo`
  - >-

- **onboard** — `C:\Users\LENOVO\.agents\skills\onboard`
  - >-

- **origin** — `C:\Users\LENOVO\.agents\skills\origin`
  - >-

- **rename-chat** — `C:\Users\LENOVO\.agents\skills\rename-chat`
  - >-

- **review** — `C:\Users\LENOVO\.agents\skills\review`
  - Review code changes with the Bugbot or Security Review subagent.

- **review-bugbot** — `C:\Users\LENOVO\.agents\skills\review-bugbot`
  - Review code changes with Bugbot subagent.

- **review-security** — `C:\Users\LENOVO\.agents\skills\review-security`
  - Review code changes with Security Review subagent.

- **sdk** — `C:\Users\LENOVO\.agents\skills\sdk`
  - >-

- **share** — `C:\Users\LENOVO\.agents\skills\share`
  - >-

- **shell** — `C:\Users\LENOVO\.agents\skills\shell`
  - >-

- **split-to-prs** — `C:\Users\LENOVO\.agents\skills\split-to-prs`
  - >-

- **statusline** — `C:\Users\LENOVO\.agents\skills\statusline`
  - >-

- **update-cli-config** — `C:\Users\LENOVO\.agents\skills\update-cli-config`
  - >-

- **update-cursor-settings** — `C:\Users\LENOVO\.agents\skills\update-cursor-settings`
  - >-

- **visualize** — `C:\Users\LENOVO\.agents\skills\visualize`
  - >-

---

## Suggested next steps

- **MCP:** Command Palette → `MCP: List Servers` (or this extension’s hub **MCP** tab) → start/trust servers in **Copilot Chat → Agent → tools**.
- **Edit config:** `MCP: Open Workspace Folder MCP Configuration` / `MCP: Open User Configuration`.
- **Refresh this report:** run **Intelligence — scan MCP & Skills awareness** again after changing `mcp.json` or adding skills.

_Report from GitHub Copilot Toolbox extension._
