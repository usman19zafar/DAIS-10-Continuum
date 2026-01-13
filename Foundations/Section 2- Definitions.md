2. Definitions & Terminology
DAIS‑10 — Data Attribute Importance Standard
This section defines the core terms used throughout DAIS‑10 and its supporting models. All definitions are meaning‑centric, domain‑agnostic, and aligned with the semantic continuum established by DIFS‑10 and QFIM‑10.

2.1 Attribute Importance
2.1.1 Importance
The qualitative measure of how much an attribute contributes to the meaning, interpretation, or analytical value of a record.

2.1.2 Semantic Importance
Importance determined by the meaning of the attribute rather than its technical characteristics.

2.1.3 Relative Importance
The concept that importance varies by domain, business context, analytical purpose, and temporal conditions.

2.2 Tiers & Zones
2.2.1 Essential (E)
Attributes required to establish the identity, meaning, or fundamental interpretability of a record.

2.2.2 Contextual (C)
Attributes that enrich or clarify the meaning of a record but are not required for basic interpretation.

2.2.3 Enrichment (N)
Attributes that provide specialized analytical value but are not required for meaning or context.

2.2.4 Overlap Zones
Transitional areas where attributes exhibit characteristics of multiple tiers.

E–C Zone: Semi‑Essential

C–N Zone: Semi‑Contextual

N–C Zone: Reverse‑Contextual (domain‑specific)

2.2.5 Sub‑Zones
Finer‑grained divisions within zones that allow infinite depth and semantic precision.

2.3 Continuum & Fading Behavior
2.3.1 Continuum
A 0–100 semantic scale representing the gradual fading of attribute importance.

2.3.2 Fading
The smooth decline of importance across the continuum, governed by DIFS‑10.

2.3.3 Gradient
A measurable slope or transition representing how quickly or slowly importance fades.

2.3.4 Soft Boundary
A non‑rigid threshold between tiers where attributes may partially belong to multiple zones.

2.4 Models & Engines
2.4.1 DAIS‑10
The Data Attribute Importance Standard — the structural framework defining tiers, governance, scoring, and classification rules.

2.4.2 DIFS‑10
The Data Importance Fading System — the behavioral engine describing how importance fades across the continuum.

2.4.3 QFIM‑10
The Qualitative Fading Importance Model — the interpretive model defining how importance decays and how zones overlap.

2.4.4 SICM‑10
The Semantic Importance Continuum Model — the conceptual model mapping importance to the 0–100 scale.

2.4.5 MCM‑10
The Meaning‑Centric Model — the philosophical foundation asserting that meaning drives importance.

2.5 Governance & Scoring
2.5.1 Tier‑Weighted Scoring
A completeness scoring method where Essential attributes carry the highest weight, followed by Contextual and Enrichment.

2.5.2 Critical Failure
A missing Essential attribute that invalidates the meaning of the record.

2.5.3 Interpretability Loss
A reduction in clarity caused by missing Contextual attributes.

2.5.4 Analytical Depth Loss
A reduction in analytical richness caused by missing Enrichment attributes.

2.5.5 Conditional Enforcement
Governance rules applied to overlap‑zone attributes based on business context.

2.6 Classification Concepts
2.6.1 Meaning‑Defining Attribute
An attribute without which the record cannot be understood.

2.6.2 Meaning‑Enhancing Attribute
An attribute that improves interpretability but is not required for identity.

2.6.3 Meaning‑Extending Attribute
An attribute that adds specialized analytical value.

2.6.4 Domain‑Dependent Attribute
An attribute whose importance varies significantly across industries or use cases.

2.6.5 Relational Importance
Importance that changes based on the presence or absence of other attributes.

2.7 Operational Terms
2.7.1 Classification
The process of assigning an attribute to a tier or zone based on semantic importance.

2.7.2 Profiling
The analysis of attribute behavior to support classification and scoring.

2.7.3 Enforcement
The application of rules and validations based on tier importance.

2.7.4 Monitoring
Ongoing observation of attribute behavior to ensure compliance with DAIS‑10.

2.7.5 Auditability
The ability to verify classification decisions through transparent logic and documentation.

2.8 Infinite‑Depth Concepts
2.8.1 Fractal Expansion
The property of DAIS‑10 that allows deeper layers of meaning, sub‑zones, and gradients to emerge as analysis progresses.

2.8.2 Micro‑Gradients
Small, precise shifts in importance within a zone or sub‑zone.

2.8.3 Semantic Layers
Nested levels of meaning that appear as attributes are analyzed more deeply.

2.8.4 Contextual Depth
The degree to which additional attributes enhance interpretability.

End of Section 2 — Definitions & Terminology
