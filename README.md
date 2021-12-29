# Analysis in R - Systematic Review of FHIR in Health Reasearch

## Background: 
The standard Fast Healthcare Interoperability Resources (FHIR) is widely used in health information technology. However, its use as a standard for health research is still less prevalent. To use existing data sources more efficiently for health research, data interoperability becomes increasingly important. FHIR provides solutions by offering resource domains such as “Public Health & Research” and “Evidence-Based Medicine” while using already established web technologies. Therefore, FHIR could help to standardize data across different data sources and improve interoperability in health research.

## Objective: 
The aim of our study was to provide a systematic review of existing literature and determine the current state of FHIR implementations in health research and possible future directions.

## Methods: 
We searched PubMed/Medline, EMBASE, Web of Science, IEEE Xplore and the Cochrane Library databases for studies published from 2010 to 2021. Studies investigating the use of FHIR in health research were included. Articles published before 2010, abstracts, reviews, editorials and expert opinions were excluded. We followed the PRISMA guidelines and registered this study with PROSPERO, CRD42021235393. Data synthesis was done in tables and figures.

## Results: 
We identified a total of 674 studies, of which 28 studies were eligible for inclusion.  Most studies covered the domain of clinical research (22/28) while the remaining studies focused on public health/ epidemiology (3/28) or did not specify their research domain (3/28). Studies used FHIR for data capture (11/28), standardization of data (7/28), analysis (4/28), recruitment (4/28) and consent management (2/28). Most studies had a generic approach (15/28) and nine of 13 studies focusing on specific medical specialties (infectious disease, genomics, oncology, environmental health, imaging, pulmonary hypertension) reported their solutions to be conferrable to other use cases. Half of the studies reported using additional data models or terminologies: SNOMED CT (8/14), LOINC (8/14), ICD-10 (6/14), OMOP CDM (3/14) and others (9/14). Only one study used a FHIR resource from the domain “Public Health & Research”. Limitations using FHIR included the possible change in the content of FHIR resources, safety and legal matters and the need for a FHIR server.

## Conclusions: 
Our review found that FHIR can be implemented in health research and that the areas of application are broad and generalizable in most use cases. Implementation of international terminologies was common and other standards such as OMOP CDM could be used complementary with FHIR. Limitations such as change of FHIR content, lack of FHIR implementation, safety and legal matters need to be addressed in future releases to expand the use of FHIR and therefore interoperability in health research.
