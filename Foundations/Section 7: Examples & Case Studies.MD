7. Examples & Case Studies
DAIS‑10 — Data Attribute Importance Standard
This section provides practical examples and case studies demonstrating how DAIS‑10 classifies attributes, applies the semantic continuum, and enforces tier‑weighted governance across real‑world datasets. Examples are domain‑agnostic and illustrate the meaning‑centric logic of DAIS‑10, including Essential, Contextual, Enrichment tiers and their overlap zones.

7.1 Purpose of Examples & Case Studies
The examples in this section serve to:

Demonstrate how DAIS‑10 applies to real datasets

Show how meaning determines tier classification

Illustrate the fading importance continuum

Provide reference patterns for practitioners

Support governance, training, and auditability

Each example includes:

Dataset description

Attribute list

Tier classification

Continuum score (0–100)

Rationale

Scoring and enforcement implications

7.2 Case Study 1 — Customer Dataset
Dataset Description
A retail customer master dataset used for identity, segmentation, and analytics.

Attribute	        Tier	      Continuum Score	    Rationale
Customer_ID	      Essential	    98	            Defines identity of the customer
First_Name	      Essential	    85	            Required for customer facing operations
Last_Name	        Essential	    88	            Required for identity and communication
Email	            E–C	          78	            Essential for digital workflows,                                                         contextual otherwise
Phone_Number	    E–C	          72	            Required in some workflows, optional in                                                  others
Age	              Contextual	  65	            Enhances segmentation and interpretation
Gender	          Contextual	  58	            Supports analytics but not identity
Region	          Contextual	  60	            Required for interpretation and routing
Loyalty_Score	    Enrichment	  30	            Analytical depth only
Preferred_Channel	  C–N	        45	            Contextual for marketing, enrichment                                                     otherwise

Scoring Implications

Missing Customer_ID → Critical failure

Missing Email → Conditional failure (digital workflows)

Missing Age → Interpretability loss

Missing Loyalty_Score → Minimal penalty

Governance Notes

Essential attributes require strict enforcement

E–C attributes require conditional enforcement

Contextual attributes require soft validation

Enrichment attributes require monitoring only

7.3 Case Study 2 — Product Dataset
Dataset Description
A product catalog used for inventory, pricing, and analytics.

Attribute Classification Table
Attribute	        Tier	          Continuum Score	      Rationale
SKU	              Essential	      100	                  Defines product identity
Product_Name	    Essential	      92	                  Required for all business                                                                functions
Brand	            E–C	            75	                  Essential in retail, contextual                                                          in logistics
Category	        Contextual	    70	                  Required for classification and                                                          analytics
Subcategory	      Contextual	    62	                  Enhances interpretability
Price	            Essential	      90	                  Required for transactions
Cost	            C–N	            48	                  Contextual for finance,                                                                  enrichment for analytics
Color	            Enrichment    	25	                  Analytical depth only
Weight	          Contextual	    55	                  Required for shipping and                                                                logistics
Rating	          Enrichment	    20	                  Optional analytical attribute


Scoring Implications

Missing SKU → Critical failure

Missing Brand → Conditional penalty

Missing Category → Moderate penalty

Missing Rating → Minimal penalty

Governance Notes
SKU and Price require strict enforcement

Brand requires domain‑specific enforcement

Color and Rating require monitoring only

7.4 Case Study 3 — Financial Transaction Dataset
Dataset Description
A financial transaction dataset used for compliance, reporting, and fraud detection.

Attribute Classification Table
Attribute	        Tier	        Continuum Score	        Rationale
Transaction_ID	  Essential	    100	                  Defines transaction identity
Account_ID	      Essential	    95	                  Required for linking to customer
Transaction_Date	Essential	    90	                  Required for compliance
Amount	          Essential	    98	                  Required for financial reporting
Currency	        Contextual	  70	                  Required for interpretation
Merchant_Category	Contextual	  60	                  Supports analytics and fraud                                                             detection
Device_ID	        C–N	          40	                  Enrichment for fraud, 
                                                      contextual for risk
Geo_Location	    C–N	          45	                  Contextual for fraud, 
                                                      enrichment otherwise
Risk_Score	      Enrichment	  30	                  Analytical depth only
Notes	            Enrichment	  10	                  Optional free‑text field


Scoring Implications
Missing Amount → Critical failure

Missing Currency → Interpretability loss

Missing Device_ID → Minor penalty

Missing Notes → No penalty

Governance Notes
Essential attributes require strict enforcement

Contextual attributes require soft validation

Enrichment attributes require monitoring only

7.5 Case Study 4 — HR Employee Dataset
Dataset Description
An HR dataset used for payroll, compliance, and workforce analytics.

Attribute Classification Table
Attribute	Tier	Continuum Score	Rationale
Employee_ID	Essential	100	Defines employee identity
First_Name	Essential	85	Required for HR operations
Last_Name	Essential	88	Required for identity
Date_of_Birth	Essential	90	Required for compliance
Department	Contextual	70	Required for interpretation
Job_Title	Contextual	65	Enhances interpretability
Salary	Essential	95	Required for payroll
Manager_ID	C–N	50	Contextual for org charts, enrichment otherwise
Performance_Score	Enrichment	30	Analytical depth only
Skills	Enrichment	20	Optional analytical attribute
Scoring Implications
Missing Salary → Critical failure

Missing Department → Moderate penalty

Missing Performance_Score → Minimal penalty

7.6 Case Study 5 — Healthcare Patient Dataset
Dataset Description
A patient dataset used for clinical operations, reporting, and analytics.

Attribute Classification Table
Attribute	Tier	Continuum Score	Rationale
Patient_ID	Essential	100	Defines patient identity
Date_of_Birth	Essential	95	Required for clinical decisions
Gender	Contextual	60	Required for interpretation
Diagnosis_Code	Essential	90	Required for treatment
Procedure_Code	E–C	75	Essential in surgical workflows
Medication	Contextual	65	Enhances interpretability
Allergies	Essential	92	Required for safety
Risk_Factor_Score	Enrichment	30	Analytical depth only
Visit_Notes	Enrichment	15	Optional free‑text
Scoring Implications
Missing Allergies → Critical failure

Missing Medication → Interpretability loss

Missing Risk_Factor_Score → Minimal penalty

7.7 Cross‑Case Insights
Across all case studies:

7.7.1 Essential attributes define meaning
Identity, compliance, and core business logic always anchor the Essential tier.

7.7.2 Contextual attributes enhance interpretability
They are important but not meaning‑defining.

7.7.3 Enrichment attributes extend analytical depth
They support advanced analytics but do not affect core meaning.

7.7.4 Overlap zones reflect real‑world ambiguity
Attributes like Email, Brand, Device_ID, and Manager_ID behave differently across contexts.

7.7.5 Scoring reflects semantic importance
Missing values impact completeness proportionally to their tier.

End of Section 7 — Examples & Case Studies
