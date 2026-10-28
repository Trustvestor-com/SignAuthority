# SignAuthority
An open-source library for the digital verification of the representative authority of individuals signing documents on behalf of a commercial company: can the signatory bind the company to the specific action under the laws of the country where the company is registered?

# What the application does:
  *Legal Validation: Verifies, analyzes, and certifies the signatory authority of individuals—including whether such authority is exercised independently or jointly—in accordance with the laws of the country of registration (e.g., the Commercial Code, BW, GmbHG, Äriseadustik, etc.).
  *Digital Evidence: Processes structured data from commercial registers (including EU company certificates issued under Directive (EU) 2025/25) as well as digital powers of attorney.
  *Deterministic Outcome: Provides a clear status:
  A) Authorized;
  B) Unauthorized (lacks signatory authority);
  C) Undefined (referred for manual review by a legal expert).

# Why it is useful:

The project removes key administrative and legal barriers to business digitalization within the EU:
  *Eliminates manual, time-consuming tasks: Replaces the physical review of paper documents, translations, apostilles, and manual registry checks with an automated digital verification process that takes only seconds.
  *Ensures legal certainty: Eliminates the risk of errors regarding joint signatory authority and accelerates deal execution as well as KYB (Know Your Business) and onboarding processes. 
  *Compliance with EU Standards: Works directly with the EU Company Certificate, the Digital Power of Attorney (Directive (EU) 2025/25), and the EUDI Wallet;*

# How it works
  1. Input Data: The user (or an integrated system) submits an electronically signed document (or a draft thereof), along with a digital certificate of representation (*EU Company Certificate* / *EAA token*).
  2. Automated Verification: The module validates the submitted digital evidence and applies deterministic legal rules based on the country where the company is registered.
  3. Result: The application returns an immediate status:
    "Authorized" - the authority to represent and the required signatures have been confirmed. 
    "Unauthorized" - the authority to represent is missing, or a required joint signature is absent. 
    "Undefined" - the case requires further manual review by a legal expert.

# Help and Support
Users can obtain assistance and technical support via the developer’s helpdesk at: https://trustvestor.com/helpdesk
The project is maintained, developed, and administered by Trustvestor Ltd.



