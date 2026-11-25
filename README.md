# Marcio Carvalho | Security Research

Independent security research focused on web application security, access control, and vulnerability analysis.

Pesquisa independente em segurança de aplicações web, controle de acesso e análise de vulnerabilidades.

---

## English

### About me

I am a Brazilian cybersecurity researcher focused on Offensive Security and Web Application Security, with a background in Linux systems and IT infrastructure.

My work connects vulnerability discovery with root-cause analysis, practical impact validation, and remediation. This repository brings together my published research and technical reports.

### Published research

#### CVE-2026-133202 — Revive Adserver

**Cross-advertiser tracker association exposes tracker metadata**

An access-control flaw allowed a Manager with legitimate access to two advertisers to associate one advertiser’s tracker with the other’s campaign. The association persisted and participated in conversion processing, exposing the tracker’s name and ID in the second advertiser’s restricted report.

- **Classification:** CWE-284 — Improper Access Control
- **Severity:** Medium — CVSS 3.0: 5.4
- **Fix released in:** Revive Adserver 6.1.0
- **Researcher credited by the vendor:** Marcio Carvalho
- **Disclosure coordinated through:** HackerOne

[Read the research](CVE-2026-133202/README.md) ·
[English report](CVE-2026-133202/CVE-2026-133202_Report_en.md) ·
[Download PDF](CVE-2026-133202/CVE-2026-133202_Report_en.pdf)

---

## Português (Brasil)

### Sobre mim

Sou pesquisador brasileiro de segurança cibernética, com foco em Segurança Ofensiva e Segurança de Aplicações Web, e experiência em sistemas Linux e infraestrutura de TI.

Meu trabalho conecta a descoberta de vulnerabilidades à análise da causa técnica, à validação do impacto prático e à correção. Este repositório reúne minhas pesquisas publicadas e relatórios técnicos.

### Pesquisas publicadas

#### CVE-2026-133202 — Revive Adserver

**Associação de tracker entre anunciantes expõe metadados**

Uma falha de controle de acesso permitia que um Manager com acesso legítimo a dois anunciantes associasse o tracker de um à campanha do outro. A associação era persistida e utilizada no processamento de conversões, expondo o nome e o identificador do tracker no relatório restrito do segundo anunciante.

- **Classificação:** CWE-284 — Controle de acesso inadequado
- **Severidade:** Média — CVSS 3.0: 5.4
- **Correção disponibilizada em:** Revive Adserver 6.1.0
- **Pesquisador creditado pelo fornecedor:** Marcio Carvalho
- **Divulgação coordenada pela:** HackerOne

[Conheça a pesquisa](CVE-2026-133202/README.md) ·
[Relatório em português](CVE-2026-133202/CVE-2026-133202_Report_pt-BR.md) ·
[Baixar PDF](CVE-2026-133202/CVE-2026-133202_Report_pt-BR.pdf)

---

## Official references / Referências oficiais

- [Revive Adserver — Security Advisory REVIVE-SA-2026-005](https://www.revive-adserver.com/security/revive-sa-2026-005/)
- [HackerOne — Report #4211442](https://hackerone.com/reports/4211442)
- [Revive Adserver — Fix commit](https://github.com/revive-adserver/revive-adserver/commit/07513dca6)

## Research approach / Abordagem de pesquisa

The published Revive research was conducted in isolated local environments using synthetic accounts and data. Reports distinguish demonstrated behavior from hypotheses and document the limits of the evidence.

A pesquisa publicada sobre o Revive foi conduzida em ambientes locais isolados, com contas e dados sintéticos. Os relatórios distinguem comportamentos demonstrados de hipóteses e documentam os limites das evidências.
