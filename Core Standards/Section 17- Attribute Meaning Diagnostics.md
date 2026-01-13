17. Attribute Meaning Diagnostics (AMD‑10)
DAIS‑10 — Data Attribute Importance Standard
AMD‑10 is the diagnostic subsystem of DAIS‑10.
It provides a structured set of tests, indicators, and validation mechanisms used to verify whether an attribute has been classified correctly according to:

Meaning role

Tier

Continuum score

Fading behavior

Qualitative interpretation

Governance intensity

AMD‑10 ensures that DAIS‑10 classification is:

Accurate

Consistent

Defensible

Auditable

Domain‑aligned

It is the quality assurance engine of the standard.

17.1 Purpose of AMD‑10
AMD‑10 exists to:

Validate meaning‑centric classification

Detect misclassifications

Identify ambiguous attributes

Support governance and audit teams

Provide diagnostic evidence for certification

Strengthen semantic integrity across datasets

AMD‑10 is mandatory for:

Certification audits

Annual reviews

Domain adaptation reviews

High‑risk datasets

17.2 Diagnostic Categories
AMD‑10 defines five diagnostic categories:

Meaning Diagnostics

Tier Diagnostics

Continuum Diagnostics

Governance Diagnostics

Scoring Diagnostics

Each category contains multiple diagnostic tests.

17.3 Meaning Diagnostics
Meaning diagnostics validate whether the attribute’s meaning role is correct.

17.3.1 Meaning‑Defining Test
Checks whether the attribute is required for identity or core meaning.

17.3.2 Meaning‑Enhancing Test
Checks whether the attribute is required for interpretation.

17.3.3 Meaning‑Extending Test
Checks whether the attribute adds analytical depth only.

17.3.4 Meaning Ambiguity Indicator
Flags attributes that could belong to multiple meaning roles.

17.3.5 Domain Meaning Alignment Test
Ensures meaning role matches domain meaning drivers.

17.4 Tier Diagnostics
Tier diagnostics validate whether the assigned tier is correct.

17.4.1 Tier Boundary Test
Checks whether the attribute sits near a tier boundary (E‑C or C‑N).

17.4.2 Tier Consistency Test
Ensures tier assignment matches meaning role.

17.4.3 Tier Conflict Indicator
Flags attributes whose tier contradicts domain logic.

17.4.4 Tier Drift Test
Detects changes in meaning over time that may require reclassification.

17.5 Continuum Diagnostics
Continuum diagnostics validate the numeric importance score.

17.5.1 Continuum Range Test
Ensures score is within the correct zone.

17.5.2 Continuum Justification Test
Checks whether rationale supports the numeric score.

17.5.3 Continuum Stability Test
Detects attributes whose importance changes over time.

17.5.4 Overlap Zone Test
Validates EC and CN transitional assignments.

17.5.5 Microgradient Test
Ensures subzone assignments are justified.

17.6 Governance Diagnostics
Governance diagnostics validate enforcement and documentation.

17.6.1 Enforcement Alignment Test
Ensures enforcement level matches tier.

17.6.2 Documentation Completeness Test
Checks whether rationale, rules, and exceptions are documented.

17.6.3 Exception Validity Test
Ensures exceptions are justified and approved.

17.6.4 Governance Drift Indicator
Detects governance rules that no longer match meaning.

17.7 Scoring Diagnostics
Scoring diagnostics validate completeness scoring.

17.7.1 Weight Accuracy Test
Ensures weight matches tier and QFIM‑10 category.

17.7.2 Score Contribution Test
Validates attribute’s contribution to completeness.

17.7.3 Scoring Threshold Test
Checks whether thresholds are appropriate for the domain.

17.7.4 Scoring Stability Test
Detects scoring inconsistencies across datasets.

17.8 AMD‑10 Diagnostic Matrix
The AMD‑10 matrix provides a structured view of all diagnostics.

Diagnostic Category	Diagnostic Tests	Purpose
Meaning	5 tests	Validate meaning role
Tier	4 tests	Validate tier assignment
Continuum	5 tests	Validate numeric score
Governance	4 tests	Validate enforcement & documentation
Scoring	4 tests	Validate completeness scoring
Total: 22 diagnostic tests

17.9 AMD‑10 Diagnostic Workflow
Attribute selected for review

Meaning diagnostics applied

Tier diagnostics applied

Continuum diagnostics applied

Governance diagnostics applied

Scoring diagnostics applied

Diagnostic report generated

Reclassification (if required)

Governance approval

Audit logging

17.10 Diagnostic Output Requirements
Each diagnostic must produce:

Diagnostic result (Pass / Fail / Warning)

Explanation

Evidence

Recommended action

Reviewer identity

Review date

17.11 Diagnostic Severity Levels
Critical
Meaning role incorrect

Tier incorrect

Essential attribute misclassified

Major
Continuum score unjustified

Governance rule incorrect

Minor
Documentation incomplete

Scoring threshold misaligned

Informational
No action required

17.12 AMD‑10 Annual Diagnostic Review
Every dataset must undergo:

Full AMD‑10 diagnostic review

Reclassification (if needed)

Governance updates

Scoring recalibration

Audit verification

This ensures long‑term semantic integrity.

End of Section 17 — Attribute Meaning Diagnostics (AMD‑10)
