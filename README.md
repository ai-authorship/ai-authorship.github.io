# AI authorship labels

This project describes a compact label system for disclosing how people and AI contributed to a piece of text. It is inspired by the clarity of Creative Commons labels: a short code identifies the kind of authorship, review, and language work involved, while a linked page explains what that code means.

The system is designed to be adapted. You may modify it to describe your own ways of generating content with AI, under the terms in [LICENSE](LICENSE). Credit Ludovico Caldara and this project, link to the license, and indicate what you changed.

The labels describe a text’s production process. They are disclosures, not judgments about quality, originality, or whether a text is trustworthy. A label should be chosen to match what actually happened, and readers should not have to infer an unmentioned review step.

## Classification

Labels combine authorship with review and language-processing steps:

- **HA** — Human-authored.
- **AA** — AI-authored.
- **MA** — Mixed-authored: both a human and AI contributed to the writing.
- **HR** — Human-reviewed.
- **AR** — AI-reviewed.
- **AG** — AI grammar and proofreading only.
- **AT** — AI-translated.

The first code indicates the authorship category when one is specified. Following codes describe additional review or translation. **HA** means no AI interaction; add **AG**, **AR**, or **AT** when those AI actions occurred. **AA** by itself does not indicate human review; **HR** explicitly records it. For **AT**, authorship is unspecified. Source language may be included with any translation label, but is always optional.

The labels are process descriptions. They do not certify factual accuracy, detect AI use, or guarantee that a human reviewer made substantial changes. Using a label is optional. A disclosure is a self-reported claim, not a guarantee that the claim is true; its accuracy depends on the author’s honesty in choosing to disclose.

## Labels

### Human-authored

- [HA](labels/HA.md) — Human-authored and human-reviewed, with no AI interaction.
- [HA-AT](labels/HA-AT.md) — Human-authored and human-reviewed; AI only translated the text. Source language is optional.
- [HA-AR](labels/HA-AR.md) — Human-authored and human-reviewed; AI also reviewed it.
- [HA-AR-AT](labels/HA-AR-AT.md) — Human-authored and human-reviewed; AI reviewed and translated it. Source language is optional.
- [HA-AG](labels/HA-AG.md) — Human-authored and human-reviewed; AI only corrected grammar and proofreading issues.
- [HA-AG-AT](labels/HA-AG-AT.md) — Human-authored and human-reviewed; AI corrected grammar in the author’s foreign-language text, then translated it. Source language is optional.

### AI-authored

- [AA](labels/AA.md) — AI-authored, with no human review indicated.
- [AA-HR](labels/AA-HR.md) — AI-authored and human-reviewed.
- [AA-HR-AT](labels/AA-HR-AT.md) — AI-authored and human-reviewed, then AI-translated. Source language is optional.

### Mixed-authored

- [MA](labels/MA.md) — Human and AI both contributed to the writing; the human co-author reviewed it.
- [MA-AT](labels/MA-AT.md) — Mixed-authored; AI only translated the text. Source language is optional.
- [MA-AR](labels/MA-AR.md) — Human and AI both contributed to the writing; the human co-author and AI reviewed it.
- [MA-AR-AT](labels/MA-AR-AT.md) — Mixed-authored and reviewed by both a human and AI, then AI-translated. Source language is optional.
- [MA-AG](labels/MA-AG.md) — Human and AI both contributed to the writing; AI only corrected grammar and proofreading issues.
- [MA-AG-AT](labels/MA-AG-AT.md) — Mixed-authored; AI corrected grammar in the foreign-language text, then translated it. Source language is optional.

### Authorship unspecified

- [AT](labels/AT.md) — AI translation only; authorship is unspecified. Source language is optional. **Source link and author are recommended.**

## Using a label

See the [website embed guide](how-to-use.md) for copyable HTML snippets that link a displayed label to its explanation page. Display the code near the text it describes and link it to the corresponding explanation page. You may include the source language for a translated text, but it is optional for every translation label, including **AT**. If the process does not match a listed combination, do not force it into a code—describe the contributions in plain language.

## License and disclaimer

The original documentation and label descriptions in this repository are licensed under [CC BY 4.0](LICENSE). The labels are optional, self-reported disclosures, not licenses for the text carrying them. See [DISCLAIMER.md](DISCLAIMER.md) for details.
