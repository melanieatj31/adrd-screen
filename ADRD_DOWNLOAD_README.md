# ADRD supporting-sheet correction — version3

The user confirmed the data is synthetic and authorized upload. This version fixes missing clinical supporting records in the latest eight uploaded workbooks and supersedes the previous ZIP.

[Download all corrected files](https://github.com/melanieatj31/adrd-screen/raw/refs/heads/adrd-download-package/ADRD_All_Files.zip)

On a Mac, download in Safari and double-click the ZIP in Finder → Downloads. Open the workbooks in the `inputs` folder.

## Completed supporting tabs

| Workbook | Applicants | Diagnoses coverage | Medications coverage | Surgery-history coverage |
|---|---:|---:|---:|---:|
| Eligibility |58|58|58|58|
| Ineligibility |13|13|13|13|
| Followup |17|17|17|17|
| Wait |13|13|13|13|

The previous tabs represented only the50added prior-list applicants. The49original applicants' inline histories are now split into structured rows, preserving diagnosis/date, medication/start/duration and surgery/plan alignment. Marcus Hill(MC-00H) and Henry Brown(MC-00D) were restored from the user's supplied baseline table. Peta Nguyen, Sharon Bell and Beatrice James already existed and were not duplicated.

The package now retains351applicants:250currentMC plus101prior-list people. All original applicant entries and existing supporting records remain present. Call updates and source clinical discrepancies remain available for the screening exercise; existing people were not moved between lists during this synchronization.

Marcus and Henry's additional baseline clinical details were not supplied. Nine supporting-field values are explicitly marked `not supplied`; no diagnoses, medicines, dates or negative medical histories were invented. Henry's tamsulosin is included because the supplied note names it. See `reviewer/EXPLICIT_UNKNOWNS.csv`.

All136validation checks passed. The reviewer folder contains a coverage report, source-to-record audit, ID crosswalk, restoration report, complete review workbook and validation results. All381original MC clinical formulas are preserved. The original uploads are archived unchanged in `original_sources`; they are source snapshots, not additional applicants to import.

The revised study manuals, source-date assumptions and external-reference verification limitations remain documented in the package. Scheduling examples are reviewer examples only, not bookings.

Archive:39files;3,923,843bytes.
SHA-256:`b4401740bca74bd76248dd436965eec262780a1f0785d178b1b62745e3ab437f`
