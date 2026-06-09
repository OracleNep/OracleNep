# OracleNep

Java security, AppSec automation, and open-source code audit tooling.

I focus on Java/Spring code audit, vulnerability research, security tooling, and AI-assisted review workflows. My current work is centered on turning manual audit steps into reproducible tools: attack-surface extraction, heuristic SAST rules, report generation, human-in-the-loop AI triage, and responsible disclosure materials.

## Focus Areas

- Java / Spring / Shiro / Dubbo code audit
- AppSec, SDL, SAST rules, SARIF reports, and CI workflows
- Web vulnerability research: SSRF, XXE, SpEL/OGNL/JNDI, path traversal, file upload, authorization bypass
- Open-source security tooling and upstream collaboration
- AI-assisted code review, Agent tool-call security, and MCP security baselines

## Selected Work

### JavaSecAtlas

[JavaSecAtlas](https://github.com/Team-intN18-SoybeanSeclab/JavaSecAtlas) is a lightweight Java white-box audit workspace for Java/Spring projects. It connects attack-surface extraction, heuristic SAST rules, report generation, a local browser GUI, and OpenAI-compatible Agent review into a reproducible workflow.

- Public release: [v0.1.0-alpha](https://github.com/Team-intN18-SoybeanSeclab/JavaSecAtlas/releases/tag/v0.1.0-alpha)
- Extracts Spring routes and common Shiro / Spring Security permission annotations
- Includes heuristic rules for SSRF, XXE, SpEL, path traversal, and file upload risks
- Generates JSON, Markdown, HTML, and SARIF reports
- Provides a local GUI and AI-assisted review with source-context retrieval
- Demo result: 2 Java files, 5 Spring routes, 14 audit findings, 4 unit tests passed

Project material:

- [Project brief](https://github.com/Team-intN18-SoybeanSeclab/JavaSecAtlas/blob/main/docs/project-brief.md)
- [Demo results](https://github.com/Team-intN18-SoybeanSeclab/JavaSecAtlas/blob/main/docs/demo-results.md)
- [5-minute walkthrough](https://github.com/Team-intN18-SoybeanSeclab/JavaSecAtlas/blob/main/docs/project-walkthrough.md)
- [Screenshots](https://github.com/Team-intN18-SoybeanSeclab/JavaSecAtlas/tree/main/docs/assets)

Current boundary: JavaSecAtlas is an audit-assistance and rule-prototyping tool. It does not claim full interprocedural taint analysis or automatic exploit confirmation.

### PHP php-src Contributor

I contribute to the official [php/php-src](https://github.com/php/php-src) repository, with current work around HTTP request-body parsing behavior and internationalization extension documentation.

- [php-src #22223](https://github.com/php/php-src/pull/22223): aligns `request_parse_body()` handling of `max_input_vars` with INI behavior for negative input, with PHPT regression coverage, NEWS, and UPGRADING notes. Current status should be checked before formal use because the PR is still under upstream review.
- [php-src #22261](https://github.com/php/php-src/pull/22261): merged documentation and test-comment maintenance for `ext/intl` error conventions.

This work covers upstream synchronization, minimal patch design, PHPT tests, CI validation, compatibility notes, and maintainer review.

### Browser-Side Web Asset Analysis

I also maintain and productize browser-extension based workflows for authorized SRC and Web asset analysis. The focus is page asset discovery, API extraction, sensitive-information detection, scope control, export formats, and compliance boundaries.

Public details and repository links will be added after the current documentation and release materials are cleaned up.

## Responsible Security Work

Some vulnerability research, SRC submissions, and authorized exercise materials are intentionally not public. When shared, they are redacted to protect affected systems and respect responsible disclosure boundaries.

Areas I can discuss in interviews or private review:

- Java/Web vulnerability reproduction and root-cause analysis
- Source/sink reasoning, exploit prerequisites, and remediation design
- Authorized attack-and-defense exercise review
- CTF and challenge writeups focused on Web/Java and code-audit methodology
- Converting recurring vulnerability patterns into rules, checklists, and regression samples

## Current Roadmap

The public work I am currently consolidating:

- Apache Shiro / Dubbo read-only audit notes and attack-surface maps
- JavaSecAtlas v0.2 roadmap: SARIF import, configurable source/sink rules, better Java parsing, and finding-status workflow
- MCP-Security-Lab: Agent / MCP tool-permission checks, Prompt Injection cases, and report templates
- JavaVulnRegression: vulnerable/fixed Java samples for rule validation
- Browser-extension security workflow documentation and release packaging

## Tooling

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)
![SARIF](https://img.shields.io/badge/SARIF-Code_Scanning-2D6CDF?style=flat-square)
![AppSec](https://img.shields.io/badge/AppSec-Code_Audit-0A7B83?style=flat-square)

## GitHub

![GitHub stats](https://github-readme-stats.vercel.app/api?username=OracleNep&show_icons=true&theme=transparent)

Team: [Team-intN18-SoybeanSeclab](https://github.com/Team-intN18-SoybeanSeclab)
