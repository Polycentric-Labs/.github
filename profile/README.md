<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Polycentric-Labs/.github/main/profile/assets/logo-white.png">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Polycentric-Labs/.github/main/profile/assets/logo-black.png">
    <img alt="Polycentric Labs" src="https://raw.githubusercontent.com/Polycentric-Labs/.github/main/profile/assets/logo-black.png" width="440">
  </picture>

  <p><em>Dimidium scientiae — &ldquo;the half of knowledge is to know where to find knowledge.&rdquo;</em></p>
</div>

---

We build software for problems where being wrong is expensive — compliance, regulated AI, and the research that underpins both. Everything here is open source, and everything is built to be **verified, not trusted**: signed artifacts, traceable provenance, and a refusal to assert anything we can't trace to a primary source.

That principle is the through-line. Our platforms enforce it for the people who use them; our tooling enforces it on ourselves.

## What we build

### Compliance &amp; governance infrastructure

**[Evidentia](https://github.com/Polycentric-Labs/evidentia)** — *compliance as code, signed and provable.*
An open-source, OSCAL-native GRC engine: gap analysis, AI risk statements, and a broad library of bundled frameworks (NIST 800-53, FedRAMP, CMMC, SOC 2, HIPAA, GDPR, and more). Every piece of evidence is cryptographically signed (Sigstore + GPG) and shipped with CycloneDX SBOMs, SLSA build provenance, and PEP 740 attestations — so an auditor can verify the chain instead of taking your word for it. Runs fully offline for sovereign-cloud and air-gapped deployments. Python-first, CLI-first, CI-native.

**[RegRails](https://github.com/Polycentric-Labs/regrails)** — *deterministic guardrails that decide before the model speaks.*
Policy-as-code for FERPA and Title IV. RegRails makes a risk-tiered, citation-faithful decision *before* any LLM responds, so the guarantee never depends on the model behaving. Ships with an MCP server, OSCAL/SARIF exports, a GitHub Action, and a live web demo.

### Research &amp; engineering discipline

The instruments we use to keep our own work honest — open-sourced because the discipline travels.

**[Labcoat](https://github.com/Polycentric-Labs/labcoat)** — *a hard-skeptic, multi-model research engine.*
Fans a question across a live fleet of models, then kills every finding it can't trace to a primary source, validates three times, and ranks what survives. A Claude Code skill and a standalone Python runner. *MIT.*

**[sonar-router](https://github.com/Polycentric-Labs/sonar-router)** — *route to the right research tool, not the loudest one.*
A decision-matrix skill and classifier that picks the right web-research method for a query and routes away from deep-research models when they would hallucinate. *MIT.*

**[pre-release-review](https://github.com/Polycentric-Labs/pre-release-review)** — *a methodical, user-in-the-loop pre-tag review.*
A portable release-gate skill aligned to SLSA L3, OpenSSF Best Practices, and the OSPS Baseline — the checklist that stands between &ldquo;it builds&rdquo; and &ldquo;it ships.&rdquo;

**[Voidseal](https://github.com/Polycentric-Labs/voidseal)** — *untrusted code runs behind a sealed door or not at all.*
A risk-tiered Hyper-V sandbox provisioner: inject a workload, seal the VM to the isolation tier it demands — network-restricted to fully air-gapped — behind a fail-closed, host-verified gate, capture results across a one-way boundary, and tear it down. For agent loops, unvetted plugins, and code you'd rather not trust. *MIT.*

## How we work

- **Open by default.** Apache-2.0 and MIT. Read the code, fork it, build on it.
- **Verifiable, not trust-me.** Signed evidence, build provenance, primary-source discipline. If we claim it, you can check it.
- **CLI-first, library-first, CI-native.** Tools that drop into a terminal, import as a library, and run on every pull request.
- **Built for hard environments.** Regulated industries, offline and air-gapped deployments, and reviewers who read the source.

## Get involved

We build in the open, and we're looking for developers who care about correctness. Star a project, open an issue, or send a pull request — each repo has its own contributing guide and good first issues. If a framework, integration, or guardrail you need is missing, that's a great place to start.

✉️ contact@polycentriclabs.com

---

<sub>This organization's projects are developed alongside AI platforms. See the [AI-assistance policy](https://github.com/Polycentric-Labs/.github/blob/main/AI_POLICY.md) and each project's `docs/ai-assistance.md` for the tools in use.</sub>
