# Project Proposal

## Problem and Solution

Maternal morbidity is associated with worse health outcomes of mothers and infants and high medical cost and length of hospitalization stay. For some factors, it is known how they are associated with maternal morbidity. For example, factors at the individual level (i.e., maternal age, pre-existing medical condition, delivery type) can greatly increase the risk of maternal morbidity. On the other hand, for other factors, their relationship with maternal morbidity is more obscure. For example, despite the fact that the US spends more on maternity care, there has been since 2000, a rise in maternal mortality than in any other developed country. This issue is further exacerbated by racial disparities with Black or African and Indigenous American women having a 3 or 4 times more likelihood of experiencing pregnancy-related death when compared to their white counterparts.

One pertinent driver of this issue is the existence of fragmented and missing data and the lack of interoperability between EHR systems. This situation can be alleviated using FHIR-based computational phenotyping based on structured and unstructured data from multiple healthcare systems.

## Audience

Healthcare systems looking to improve their computerized clinical decision support systems (CDSS) with regards to maternal health. The FHIR-based computational phenotyping can be incorporated into their CDSS and alert providers of high-risk patients prior to the adverse event and mitigate maternal morbidity.

## Desired Features
1. Patient: demographics 
2. Labels: disease or condition
3. Labs: patient IDs and their lab results
4. Medications: patient IDs and their medications
5. Vitals: patient IDs and their vital
6. Clinical Notes: unstructured text for the patients

## Relevant resources in FHIR

* Patient 
* Observation
* Encounter
* MedicationStatement 
* DiagnosticReport
* AdverseEvent
* Procedure
* Condition

## Language

* JSON
* Python
* Regex


## Resources
1. https://effectivehealthcare.ahrq.gov/products/maternal-morbidity-mortality/protocol
2. https://tracs.unc.edu/docs/clark-2-documentation.html#fhir
