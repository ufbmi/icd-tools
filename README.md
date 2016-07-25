The goal of this repository is to help developers in their work with ICD/HCPCS
and other coding schemes.

# CPT Category II (CDM - C2)

From [health-information.advanceweb.com](http://health-information.advanceweb.com/Article/Understand-the-Three-CPT-Code-Categories-2.aspx)

Category II codes are supplemental tracking codes that are intended to be used
for performance measurement. In compliance with ongoing changes being made
because of HIPAA regulations, these codes provide a method for reporting
performance measures. The Category II codes are intended to facilitate the
collection of information about the quality of care delivered by coding a
number of services or test results that support performance measures. These
performance measures have been agreed upon as contributing to good patient
care.

The Category II Codes are alphanumeric and consist of four digits followed by
the alpha character 'F.' The use of these codes is optional and are not a
substitute for Category I codes.

CPT Category II codes will be arranged according to the following categories:

- Composite Measures 0001F
- Patient Management 0500F-0503F
- Patient History 1000F-1002F
- Physical Examination 2000F
- Diagnostic/Screening Processes or Results 3000F
- Therapeutic, Preventive or Other Interventions 4000F-4011F
- Follow-up or Other Outcomes 5000F
- Patient Safety 6000F


# CPT Category III (CDM - C3)

Category III codes represent temporary codes for new and emerging technologies.
They have been created to allow for data collection and utilization tracking
for new procedures or services. Category III codes are different from Category
I CPT codes in that they identify services that may not be performed by many
health care professionals across the country, do not have FDA approval, nor
does the service/procedure have proven clinical efficacy. To be eligible for a
Category III code, the procedure or service must be involved in ongoing or
planned research. The rationale behind these codes is to help researchers track
emerging technology and services to substantiate widespread usage and clinical
efficacy. In the past, researchers have been hindered by the length and
requirements of the current CPT approval process.

The Category III codes are five characters long, with four digits followed by
the letter 'T' in the last field (e.g. 0002T). The codes are intended to be
temporary and will be retired if the procedure or service is not accepted as a
Category I code within five years. In some instances Category III codes may
replace temporary local codes (HCPCS Level III) assigned by carriers and
intermediaries to describe new procedures or services. If a Category III code
is available it must be used instead of the unlisted Category I code. The use
of the unlisted code does not offer the opportunity for collection of specific
data.


# HCPCS Level I (CDM - C4, aka CPT-4, aka CPT Category I)

CPT-4 codes (5 digits) are copyrighted by AMA -- a license is needed for usage.

Note: you can download the
[`current_lmrp.zip`](https://downloads.cms.gov/medicare-coverage-database/downloads/exports/current_lmrp.zip)
file and extract the `hcpc_code_lookup.csv` file to lookup codes.


# HCPCS Level III (CDM - H3)

From [wikipedia](https://en.wikipedia.org/wiki/Healthcare_Common_Procedure_Coding_System):

HCPCS-L3 cdes, also called local codes, were developed by state Medicaid agencies,
Medicare contractors, and private insurers for use in specific programs and
jurisdictions. The Health Insurance Portability and Accountability Act of 1996
(HIPAA) instructed CMS to adopt a standard coding systems for reporting medical
transactions. The use of Level III codes was discontinued on December 31, 2003,
in order to adhere to consistent coding standards.


# Alpha-Numeric HCPCS Level II (CDM - HC)

From [www.cms.gov](https://www.cms.gov/Medicare/Coding/HCPCSReleaseCodeSets/Alpha-Numeric-HCPCS-Items/2016-Alpha-Numeric-HCPCS-File.html)
the following archive was downloaded:
[2016 Alpha-Numeric HCPCS File (ZIP, 978KB)](https://www.cms.gov/Medicare/Coding/HCPCSReleaseCodeSets/Downloads/2016-Alpha-Numeric-HCPCS-File.zip)

It contains the following files:

- [`HCPC2016_CONTR_ANWEB.txt`](hcpcs-2016/HCPC2016_CONTR_ANWEB.txt)
- [(!) `HCPC2016_CONTR_ANWEB.xlsx`](hcpcs-2016/HCPC2016_CONTR_ANWEB.xlsx)
- [`HCPC2016_README.txt`](hcpcs-2016/HCPC2016_README.txt)
- [`HCPC2016_TransactionReport_Alpha.xlsx`](hcpcs-2016/HCPC2016_TransactionReport_Alpha.xlsx)
- [`HCPC2016_TransReport_Changes_by_Action_Code.txt`](hcpcs-2016/HCPC2016_TransReport_Changes_by_Action_Code.txt)
- [`HCPC2016_TransReport_Changes_by_HCPCS_Code.txt`](hcpcs-2016/HCPC2016_TransReport_Changes_by_HCPCS_Code.txt)
- [`HCPCS2016_recordlayout.txt`](hcpcs-2016/HCPCS2016_recordlayout.txt)
- [`proc_notes_2016.txt`](hcpcs-2016/proc_notes_2016.txt)

@see [`https://en.wikipedia.org/wiki/HCPCS_Level_2`](https://en.wikipedia.org/wiki/HCPCS_Level_2)

# HCPCS modifiers

From [www.codingahead.com](http://www.codingahead.com/2009/08/list-of-modifiers.html):

Modifier - as the name implies a modifier will modify a service / procedure or
an item under certain circumstances for appropriate reimbursement. Modifiers
may add information or change the description according to the physician
documentation to give more specificity for the service or procedure rendered.
Appending of an appropriate modifier will effectively respond to reimbursement.


1. Level I Modifiers: Normally known as CPT Modifiers and consists of two
   numeric digits and are updated annually by AMA - American Medical Association.
2. Level II Modifiers: Normally known as HCPCS Modifiers and consists of two
   digits (Alpha / Alphanumeric characters) in the sequence AA through VP.

These modifiers are annually updated by CMS (Center for Medicare and Medicaid Services)


# ICD-9-CM

Diagnosis and Procedure Codes: Abbreviated and Full Code Titles

From the [www.cms.gov](https://www.cms.gov/medicare/coding/ICD9providerdiagnosticcodes/codes.html)
the following archive was downloaded:
[ICD-9-CM-v32-master-descriptions.zip](https://www.cms.gov/Medicare/Coding/ICD9ProviderDiagnosticCodes/Downloads/ICD-9-CM-v32-master-descriptions.zip)

It contains the following files:

- [`CMS32_DESC_LONG_DX.txt`](icd-9-cm-v32/CMS32_DESC_LONG_DX.txt)
- [`CMS32_DESC_LONG_SG.txt`](icd-9-cm-v32/CMS32_DESC_LONG_SG.txt)
- [`CMS32_DESC_LONG_SHORT_DX.xlsx`](icd-9-cm-v32/CMS32_DESC_LONG_SHORT_DX.xlsx)
- [`CMS32_DESC_LONG_SHORT_SG.xlsx`](icd-9-cm-v32/CMS32_DESC_LONG_SHORT_SG.xlsx)
- [`CMS32_DESC_SHORT_DX.txt`](icd-9-cm-v32/CMS32_DESC_SHORT_DX.txt)
- [`CMS32_DESC_SHORT_SG.txt`](icd-9-cm-v32/CMS32_DESC_SHORT_SG.txt)


Notes:

- **DX** stands for Diagnosis
- **SG** stands for Procedures



# ICD-10

There are two types: CM (diagnosis) and PCS (procedures)

## ICD-10-CM (Clinical Modification - are these used in CDM?) 

- [2016-Code-Descriptions-in-Tabular-Order.zip (2MB)](https://www.cms.gov/Medicare/Coding/ICD10/Downloads/2016-Code-Descriptions-in-Tabular-Order.zip)
- [2016-General-Equivalence-Mappings.zip (1MB))](https://www.cms.gov/Medicare/Coding/ICD10/Downloads/2016-General-Equivalence-Mappings.zip)


## ICD-10-PCS (Procedure Coding System)

From the [www.cms.gov](https://www.cms.gov/Medicare/Coding/ICD10/2016-ICD-10-PCS-and-GEMs.html)
the following archives have been downloaded:

- [2016-PCS-Code-Tables.zip (7MB)](https://www.cms.gov/Medicare/Coding/ICD10/Downloads/2016-PCS-Code-Tables.zip)
- [201a-ProcedureGEMs.zip (1MB)](https://www.cms.gov/Medicare/Coding/ICD10/Downloads/2016-ProcedureGEMs.zip)
