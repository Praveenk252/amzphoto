# amzphoto

A product-agnostic Codex skill for planning, generating, and auditing Amazon product listing image galleries and A+ Content.

The skill uses supplied product evidence to protect product identity, dimensions, claims, package contents, variants, and explicit visual constraints. It builds a complete checklist, asks focused questions only when missing facts materially affect accuracy, and supports separate image files for every applicable, supported slot when the user requests a full set. A+ support includes module planning, copy, image assets, and a responsive offline HTML preview with a Seller Central handoff.

## Contents

- `SKILL.md` — complete workflow, image checklist, accuracy rules, and A+ Content procedure
- `agents/openai.yaml` — Codex skill display metadata

## Install

Copy this folder into your Codex skills directory as `amzphoto`, then invoke it with `$amzphoto`.

AI-generated product renderings remain drafts until checked against the actual item. The skill does not guarantee Amazon approval or sales results.

## Explainer

See [WHAT-AMZPHOTO-CAN-DO.md](WHAT-AMZPHOTO-CAN-DO.md) for a 2,000-word overview of the skill's product-agnostic workflow, gallery image checklist, image generation, A+ Content, HTML previews, and accuracy review.

