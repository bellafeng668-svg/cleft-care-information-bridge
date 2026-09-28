# Cleft Care Information Bridge — Final

A bilingual, source-traceable public-information project for cleft care in China.

## Dataset
- 50 source-traceable records as of 28 September 2026.
- Coverage expanded across national guidance, specialist-care sources, charitable assistance, and local medical-assistance examples.
- Records retain official source URLs, source dates, last-verified dates, service type, care stage, assistance, scope, and bilingual fields.
- A 0–2 coding protocol is applied consistently to findability, completeness, reliability, and actionability.
- Coding is for research organization and does not rank hospitals, foundations, programs, or policies.

## Language
- Chinese mode contains Chinese user-facing text; necessary technical file-format terms such as CSV/JSON remain unchanged.
- English mode contains English user-facing text; original document titles and proper names are preserved only where necessary for source identification.

## Data files
- `cleft_care_resources_BILINGUAL.csv`: spreadsheet-friendly structured data.
- `cleft_care_resources_BILINGUAL.xlsx`: spreadsheet version.
- `data.json`: machine-readable web/developer format.

## Important boundary
This is a research dataset, not an exhaustive national directory and not individualized medical advice. Time-bound local programs are labeled as local or event-specific. Users should verify current eligibility, appointment rules, funding availability, and medical suitability with the relevant official source before acting.

## Final QA
- Dataset count cross-checked across HTML, JSON, CSV, and XLSX: 50 records.
- IDs CCIB-001 through CCIB-050 are unique.
- Every record has an official source URL and a last-verified date.
- English-only spans were checked for Chinese text; Chinese/English content is separated except for necessary technical terms and source-identifying proper names.
- Local/event-specific assistance records are explicitly labeled to avoid implying permanent or nationwide eligibility.


## V8 research update
- Fixed oversized `.section-desc` typography that caused the About/Research card body text to render excessively large.
- Added a descriptive-analysis section to `research.html` based on the 50-record dataset.
- Added dataset-composition bars and 0–2 information-friction summary statistics.
- Added external literature context on cleft-care access and healthcare information accessibility.
