# DIKWP TrustPassport OS

Created by Yucong Duan (段玉聪).

DIKWP TrustPassport OS is a GitHub-ready open-source system for provenance, attribution, conformance, and ecosystem certification around DIKWP-based AI products, agent systems, semantic protocols, and industry adapters.

It is deliberately less direct than an implementation gateway. The open-source core does not expose a full industrial control stack. Instead, it creates the layer that is harder for copycats to capture: a public trust passport, conformance scorecard, citation pack, registry entry, signed badge workflow, and partner onboarding path.

## One-sentence positioning

> Make every DIKWP-based project visible, citable, attributable, comparable, and certifiable before it becomes another untraceable fork.

## Why this matters

Open source licenses normally allow use, modification, and redistribution. That is a strength for adoption but also means that code alone is a weak moat. DIKWP TrustPassport OS shifts the value capture layer from code secrecy to origin recognition, official registry, conformance badge, citation metadata, certified partner ecosystem, and commercial services.

## What it produces

Given a project manifest, the system generates:

- `trust_passport.json`
- `trust_scorecard.json`
- `trustmark_badge.svg`
- `public_registry_entry.json`
- `citation_pack.md`
- `attribution_gap_report.json`
- `partner_onboarding_checklist.md`
- `commercial_route_brief.md`

## Install

```bash
pip install -e .
```

## Demo

```bash
dikwp-trustpassport evaluate examples/sample_dikwp_project_manifest.json --out outputs/demo
```

Evaluate a copycat-risk example:

```bash
dikwp-trustpassport evaluate examples/sample_copycat_risk_manifest.json --out outputs/demo/copycat
```

Run static audit:

```bash
dikwp-trustpassport static-audit src --out outputs/demo/static_boundary_audit_report.json
```

## Strategic design

The community edition is open. The scarce value is not the code; it is:

1. Official DIKWP registry identity.
2. Official badge signature.
3. Citation and attribution policy.
4. Conformance benchmark reputation.
5. Certified partner services.
6. Commercial verification API.
7. Public evidence ledger of early adoption.

## Boundary

This project is not legal advice and does not guarantee intellectual property protection. It creates a practical open-source infrastructure for attribution, provenance, conformance, and certification. Formal trademark, copyright, patent, contract, and commercial licensing decisions should be reviewed by qualified professionals.
