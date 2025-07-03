# smart-form-library
A prototype for an open smart form (FHIR SDC Questionnaire) library

## Purpose

As of July 2025, there appear to be limited collections of "smart form" libraries implemented in FHIR SDC, and fewer in an Australian clinical setting.

Respositories:

* LOINC - [LHC Forms](https://lhcforms.nlm.nih.gov/lhcforms) - A component, and connection to the LOINC Forms and Panels. As of LOINC 2.80; there are 5008 "panels" and "forms" available describing questions and answersets. It is unclear how many of these overlap with Australian clinical practice.
  * Includes [standards](https://loinc.org/kb/users-guide/standardized-assessment-measures/)
* [NSQHS PROMS](https://www.safetyandquality.gov.au/our-work/indicators-measurement-and-reporting/patient-reported-outcome-measures/about-proms) - A set of ~300 patient reported outcomes and measures across multiple discplines, documenting licencing status
* AEHRC Smart Forms' - A small collection of test smart forms https://github.com/aehrc/smart-forms/ https://smartforms.csiro.au/dashboard/questionnaires
* National Forms Library - TBC

This repository aims to at least index, similar to the NSQHS PROMS list, assessments and questionaries used in an Australian clinical setting; an indicator of licencing, a *doi* or other stable URL.

A secondary goal would be to host community driven forms, with a quality indicator.

## Contributing

Assessments index

* Open a pull request with the assessment name (short code), description
* Ensure a citation is available - tip, use Pubmed to rapidly generate
* Where possible, include a DOI URL - this is the primary machine readable reference

Assessments

* Indicate FHIR version
* Use https://validator.fhir.org/
* Use https://smartforms.csiro.au/playground and detail your manual testing
* Ensure you include licencing indicators.
* If generative tools used, validate the source assessments are **public domain** or a similarly open licenced publication (ie: CC-0)
* Include citations
