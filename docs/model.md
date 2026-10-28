# Model

> Draft prepared with AI assistance (Claude, Anthropic), 28 October 2026. Not yet reviewed by the maintainer.

## Question

Can a named person bind a given company to a specific legal act, alone or only together with others, under the law of the country where the company is registered?

## Inputs

- the person;
- the company and its country of registration;
- the legal act;
- what the commercial register shows about the company's representatives and their way of representation;
- any procuration or power of attorney the person relies on.

This draft defines no data formats and no software interfaces.

## Types of representative

1. Body of the company (manager, board of directors, management board), acting alone or jointly.
2. Procurator (Prokura / прокура), who may act separately or jointly.
3. Commercial attorney under an ordinary commercial power of attorney.

## Outcomes

Each outcome comes with a reason and the legal provision it rests on:

- Authorized: the authority to represent and any required joint signatures are confirmed.
- Unauthorized: the authority is missing, or a required joint signature is absent.
- Undetermined: the case needs review by a legal professional.

## Principles

1. Limits on the powers of company bodies that come from the articles or from decisions of company bodies cannot be invoked against third parties (Art. 9(2) Directive (EU) 2017/1132). The model does not apply such internal limits. Checked 20 October 2026.
2. Joint representation under the articles can be invoked against third parties only where national law allows it (Art. 9(3) Directive (EU) 2017/1132). This is a choice of each Member State. Checked 20 October 2026.
3. National rules are recorded per country in the rule files, each rule with its provision and the date it was checked.

## Out of scope

Internal restrictions on the powers of company bodies; verification of the validity of signatures; digital wallets and the issuance of certificates; connections to commercial registers; EU Inc.
