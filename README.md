# SignAuthority

An open-source project focused on the question: what is the representative authority of a specific individual to bind a given company to a particular legal act—whether acting alone or only jointly with others—under the laws of the country where the company is registered?

## Status

Early draft, 28 October 2026. The repository contains this README, the license, a draft model (docs/model.md) and draft rules for Bulgaria (rules/bg.md) and Germany (rules/de.md). There is no code yet. The drafts were prepared with AI assistance (Claude, Anthropic) and have not been reviewed by the maintainer.

## What it clarifies

For a specific individual, company, and legal act, the model provides one of three possible answers, each accompanied by a rationale and a reference to the relevant legal provision:

- Authorized individual
- Unauthorized individual
- Undetermined (the case requires review by a legal professional)

Example: When a Bulgarian limited liability company (ООД) has several managers, each represents it alone unless the articles of association provide otherwise (Art. 141(2) Commercial Act). The commercial register records the way of representation: together, separately, or in another way (Ordinance No. 1 of 14 February 2007). A German limited liability company (GmbH) with several managers is represented only jointly, unless the articles of association provide otherwise (§ 35(2) Limited Liability Companies Act – GmbHG).

## Scope

In scope: company bodies (acting alone or jointly), procuration (Prokura), and ordinary commercial power of attorney.

Excluded from the scope are: internal restrictions on the powers of a company body, which cannot be invoked against third parties (Article 9, paragraph 2 of Directive (EU) 2017/1132); verification of the validity of signatures; digital wallets and the issuance of certificates; and links to commercial registers.

## Countries

Planned first: Bulgaria and Germany. The Netherlands and Estonia are planned later (no specific date).

## EU Context

Directive (EU) 2025/25 introduces two new elements into Directive (EU) 2017/1132: an EU company certificate (Article 16b) and an EU digital power of attorney (Article 16c). Member States are required to transpose the Directive by July 31, 2027, and to apply its provisions starting from July 31, 2028. The current project does not yet cover either of these documents. The digital power of attorney is intended for procedures under the Directive and is subject to verification in accordance with national law.

## Sources and Methodology

Each rule names the article it rests on and the date it was checked against the official text. Points not yet checked are marked [UNVERIFIED].

Sources:

- Commercial Act (Търговски закон) and Commercial Register and Register of Non-Profit Legal Entities Act (Закон за търговския регистър и регистъра на юридическите лица с нестопанска цел)
- Ordinance No. 1 of 14 February 2007 on the keeping, storage and access to the commercial register and the register of non-profit legal entities
- GmbHG (Gesetz betreffend die Gesellschaften mit beschränkter Haftung — Limited Liability Companies Act): https://www.gesetze-im-internet.de/gmbhg/
- HGB (Handelsgesetzbuch — Commercial Code): https://www.gesetze-im-internet.de/hgb/
- AktG (Aktiengesetz — Stock Corporation Act)
- Directive (EU) 2017/1132 and Directive (EU) 2025/25

## Limitations

Each rule states the date it was checked. The rules reflect the law as of that date. No independent legal review has been carried out. Errors may be reported by creating an "issue" on GitHub.

## License

Licensed under the Apache License 2.0, see LICENSE.
