3. Tier Structure & Zone Definitions
DAIS‑10 — Data Attribute Importance Standard
DAIS‑10 classifies data attributes into a structured tiering system that reflects their semantic importance, business utility, and analytical contribution. The tier structure is built on three primary zones—Essential, Contextual, and Enrichment—supported by overlapping transitional zones that capture the natural fading of importance across the semantic continuum defined by DIFS‑10 and QFIM‑10.

This tiering system is meaning‑centric, domain‑agnostic, and designed for infinite depth through sub‑zones and semantic gradients.

3.1 Overview of Tiering Structure
DAIS‑10 defines three primary tiers:

Essential (E) — Meaning‑defining attributes

Contextual (C) — Meaning‑enhancing attributes

Enrichment (N) — Meaning‑extending attributes

Between these tiers exist overlap zones that reflect transitional importance states:

E–C Zone — Semi‑Essential

C–N Zone — Semi‑Contextual

N–C Zone — Reverse‑Contextual (domain‑specific)

The entire structure sits on a 0–100 semantic continuum, where importance fades gradually rather than shifting abruptly.

3.2 Essential Tier (E)
Definition
Attributes that define the identity, meaning, or fundamental interpretability of a record.

Characteristics
Required for the record to exist meaningfully

Missing values constitute a critical failure

High semantic density

High business dependency

High analytical dependency

Examples (generic)
Customer ID

Country Code

Product SKU

Transaction Date

Continuum Range (typical)
80–100 on the semantic importance scale.

3.3 Contextual Tier (C)
Definition
Attributes that enrich or clarify the meaning of a record but are not required for basic interpretation.

Characteristics
Improve interpretability

Missing values reduce clarity but do not invalidate the record

Medium semantic density

Medium business dependency

Medium analytical dependency

Examples (generic)
Customer Age

Product Category

Region

Payment Method

Continuum Range (typical)
40–79 on the semantic importance scale.

3.4 Enrichment Tier (N)
Definition
Attributes that extend analytical depth but are not required for meaning or context.

Characteristics
Provide specialized insights

Missing values reduce analytical richness

Low semantic density

Low business dependency

High variability across domains

Examples (generic)
Customer Loyalty Score

Product Review Text

Derived Metrics

Behavioral Indicators

Continuum Range (typical)
0–39 on the semantic importance scale.

3.5 Overlap Zones (Transitional Tiers)
Overlap zones represent transitional states where attributes exhibit characteristics of multiple tiers. These zones are essential to the fading model of DAIS‑10 and reflect the natural ambiguity of real‑world data.

3.5.1 Essential–Contextual Zone (E–C)
Definition
Attributes that are not strictly Essential but behave as Essential in certain business or analytical contexts.

Characteristics
High semantic density

Conditional enforcement

Often required for specific workflows

Examples
Customer Email (Essential for digital workflows, Contextual otherwise)

Product Brand (Essential in retail, Contextual in logistics)

Continuum Range
70–85

3.5.2 Contextual–Enrichment Zone (C–N)
Definition
Attributes that provide context in some scenarios and enrichment in others.

Characteristics
Medium semantic density

Flexible governance

Often domain‑dependent

Examples
Customer Income Bracket

Product Color

Device Type

Continuum Range
30–50

3.5.3 Enrichment–Contextual Zone (N–C)
Definition
Attributes that are typically Enrichment but become Contextual under specific analytical conditions.

Characteristics
Low semantic density

High analytical variability

Often used in advanced analytics

Examples
Sentiment Score

Derived Risk Index

Behavioral Frequency Metrics

Continuum Range
20–45

3.6 Sub‑Zones (Infinite Depth Layer)
DAIS‑10 supports infinite refinement through sub‑zones, which allow practitioners to classify attributes with greater precision.

Examples of Sub‑Zones
E‑High, E‑Mid, E‑Low

C‑High, C‑Mid, C‑Low

N‑High, N‑Mid, N‑Low

E–C‑High, E–C‑Low

C–N‑High, C–N‑Low

Sub‑zones are optional but recommended for advanced governance and analytical environments.

3.7 Semantic Gradients
A semantic gradient is the slope of importance change across a zone or sub‑zone.

Gradient Types
Steep Gradient: Rapid change in importance

Shallow Gradient: Slow, smooth transition

Variable Gradient: Context‑dependent slope

Gradients allow DAIS‑10 to model complex, real‑world importance behavior.

3.8 Tiering Rules Summary
Tier / Zone	Meaning Role	Governance	Importance Range	Behavior
E	Meaning‑defining	Strict	80–100	Required
E–C	Semi‑Essential	Conditional	70–85	Context‑dependent
C	Meaning‑enhancing	Soft	40–79	Recommended
C–N	Semi‑Contextual	Flexible	30–50	Optional
N	Meaning‑extending	Monitoring	0–39	Analytical
End of Section 3 — Tier Structure & Zone Definitions
