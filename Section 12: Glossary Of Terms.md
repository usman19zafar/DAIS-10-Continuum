12. Glossary of Terms
DAIS‑10 — Data Attribute Importance Standard
This glossary defines all terminology used throughout the DAIS‑10 standard.
Each term is written to ensure:

Semantic clarity

Consistent interpretation

Auditability

Domain‑agnostic applicability

Alignment with DAIS‑10’s meaning‑centric philosophy

Terms are grouped by category for ease of reference.

12.1 Core Standard Terms
DAIS‑10 (Data Attribute Importance Standard)
The overarching standard that classifies, scores, and governs data attributes based on their semantic importance, meaning role, and contribution to interpretability.

Meaning‑Centric Architecture
The foundational principle of DAIS‑10: attributes are classified based on the meaning they provide, not their technical type, frequency, or usage.

Attribute
A data field representing a unit of meaning within a dataset. Attributes are the primary objects classified by DAIS‑10.

Meaning Role
The semantic function an attribute plays in defining, enhancing, or extending the meaning of a record.

12.2 Meaning Roles
Meaning‑Defining Attribute
An attribute that establishes the identity or essential meaning of a record.
Mapped to Essential (E) or Semi‑Essential (E‑C) tiers.

Meaning‑Enhancing Attribute
An attribute that provides necessary context for interpreting meaning.
Mapped to Contextual (C) or Semi‑Contextual (C‑N) tiers.

Meaning‑Extending Attribute
An attribute that adds analytical depth but is not required for core meaning.
Mapped to Enrichment (N) tier.

12.3 Tiering Terms
Tier
A categorical classification representing the importance level of an attribute.

Essential (E)
Attributes required for meaning, identity, or core interpretability.

Semi‑Essential (E‑C)
Attributes that are nearly essential but context‑dependent.

Contextual (C)
Attributes required to interpret or understand the record.

Semi‑Contextual (C‑N)
Attributes that provide optional context.

Enrichment (N)
Attributes that add analytical value but are not required for meaning.

12.4 Continuum & Zone Terms
SICM‑10 (Semantic Importance Continuum Model)
The 0–100 scale used to quantify attribute importance.

Continuum Score
A numeric value (0–100) representing the semantic importance of an attribute.

Zone
A range on the continuum representing a tier category (e.g., 0–39, 40–79, 80–100).

Subzone
A finer‑grained segment within a zone, used for infinite‑depth modeling.

Overlap Zone
A transitional region between two zones (e.g., E‑C, C‑N).

12.5 Engine Terms
MCM‑10 (Meaning‑Centric Model)
Defines how meaning roles are determined.

DIFS‑10 (Data Importance Fading System)
Determines how importance fades across the continuum and resolves overlap zones.

QFIM‑10 (Qualitative Fading Importance Model)
Converts numeric continuum scores into qualitative categories and governance intensities.

12.6 Scoring Terms
Weight
A numeric multiplier assigned to each tier for scoring completeness.

Completeness Score
A normalized score representing how complete a record is based on the presence of meaningful attributes.

Weight Band
A qualitative grouping of weights (e.g., high, medium, low).

12.7 Governance Terms
Governance Rule
A rule defining how an attribute must be validated, enforced, or documented.

Enforcement Level
The strictness of validation applied to an attribute based on its tier.

Exception
A documented deviation from standard governance rules.

Rationale
The justification for an attribute’s tier, score, or governance assignment.

12.8 Audit Terms
Audit Evidence
Documentation supporting classification, scoring, or enforcement decisions.

Audit Trail
A chronological record of decisions, changes, and validations.

Compliance Report
A formal document summarizing adherence to DAIS‑10.

12.9 Domain Adaptation Terms
Domain Meaning Driver
A domain‑specific factor that influences meaning (e.g., clinical safety, regulatory compliance).

Domain Governance Profile
A domain‑specific configuration of governance rules.

Domain Weight Adjustment
A modification to scoring weights based on domain requirements.

12.10 Implementation Terms
Attribute Inventory
A complete list of attributes subject to DAIS‑10 classification.

Classification Workflow
The sequence of steps used to assign tiers, scores, and governance rules.

Integration Layer
The technical layer where scoring, enforcement, and governance are implemented.

12.11 Versioning Terms
Change Request (CR)
A formal request to modify the standard.

Semantic Versioning
The versioning model used by DAIS‑10 (MAJOR.MINOR.PATCH).

Structural Change
A change affecting the core logic of the standard.

Functional Change
A change affecting implementation but not core logic.

Documentation Change
A non‑material update.

12.12 Infinite‑Depth Terms
Microgradient
A fine‑grained importance shift within a subzone.

Contextual Layer
A deeper layer of meaning applied to contextual attributes.

Temporal Shift
A change in importance based on time or lifecycle.

Relational Dependency
A meaning dependency between attributes.

End of Section 12 — Glossary of Terms
