# SignAuthority
An open-source project focused on the question: what is the representative authority of a specific individual to bind a given company to a particular legal act—whether acting alone or only jointly with others—under the laws of the country where the company is registered?

# Status
Early draft, October 28, 2026.
The repository contains a model and a draft set of rules for Bulgaria and Germany. As of now, there is no complete, functional software code. The rules do not constitute legal advice and have not been reviewed by a legal professional.

# What it clarifies
For a specific individual, company, and legal act, the model provides one of three possible answers, each accompanied by a rationale and a reference to the relevant legal provision:
*Authorized individual
*Unauthorized individual
*Undetermined (the case requires review by a legal professional)
Example from the draft rules: Where a company has multiple registered managers, each manager may represent a Bulgarian limited liability company (OOD) either individually or jointly, unless the articles of association provide otherwise (Art. 141, para. 2 of the Commercial Act). In the case of a German limited liability company (GmbH) with multiple managers, representation can only be exercised jointly, unless the articles of association provide otherwise (§ 35, para. 2 of the Limited Liability Companies Act – GmbHG). Scope
The scope includes: company bodies (acting individually or jointly), *prokura* (commercial power of attorney), and other types of commercial powers of attorney.

Excluded from the scope are: internal restrictions on the powers of a company body, which cannot be invoked against third parties (Article 9, paragraph 2 of Directive (EU) 2017/1132); verification of the validity of signatures; digital wallets and the issuance of certificates; and links to commercial registers.

# Countries
Currently included are: Bulgaria and Germany. The Netherlands and Estonia are set to be included (no specific date provided).

# EU Context
Directive (EU) 2025/25 introduces two new elements into Directive (EU) 2017/1132: an EU company certificate (Article 16b) and an EU digital power of attorney (Article 16c). Member States are required to transpose the Directive by July 31, 2027, and to apply its provisions starting from July 31, 2028. The current project does not yet cover either of these documents. The digital power of attorney is intended for procedures under the Directive and is subject to verification in accordance with national law.

# Sources and Methodology
Each rule cites a specific article, which has been verified against the official text as of the date indicated within the rule itself; points that have not been verified are marked as [UNVERIFIED]. Commercial Act (CA) and the Commercial Register and the Register of Non-Profit Legal Entities Act (CRRNPLEA)
GmbHG (Gesetz betreffend die Gesellschaften mit beschränkter Haftung — Limited Liability Companies Act), HGB (Handelsgesetzbuch — Commercial Code), AktG (Aktiengesetz — Stock Corporation Act): https://www.gesetze-im-internet.de/gmbhg/ , https://www.gesetze-im-internet.de/hgb/
Directive (EU) 2017/1132 and Directive (EU) 2025/25

# Limitations
The rules reflect the legal framework as of the version specified for each of them. The German rules have not yet undergone an independent legal review. Errors may be reported by creating an "issue" on GitHub.
