# Medical Document Summarization - SOAP Style

## Model Overview

### Model Name
- **Name:**  ft:gpt-4o-2024-08-06:airia:general-soap-summary-2024-10-16:AJ0bIYgQ
- **Version:** 1.0
- **Date of Release:** 2024-10-16

### Description
- **Summary:** Airia's Medical Document Summarization - SOAP Style 4o model provides comprehensive summaries of medical documents, utilizing the SOAP framework (Subjective, Objective, Assessment, Plan) for structured organization. Each section is detailed with well-organized tables that present information along a clear timeline.
- **Architecture:** Fine-tuned gpt-4o-2024-08-06.
- **Recommended Temperature:** 0.1


## Intended Use

### Use Cases
- **Primary Use Cases:**
  - Patient Care Coordination.
  - Patient Handoffs
  - Training and Education
  - Patient Portals

- **Non-intended Use Cases:** This model should not be used for providing final health advice or in highly sensitive health contexts without oversight by a medical professional.

### Target Audience
- **Users:** Patients, healthcare providers, pharmacists, genetic counselors, insurers, researchers, wellness clinics, family members.

### Sample interaction
- **Sample User Input:** 
```
Can you summarize this: [DIVERSE MEDICAL DOCUMENTS]
```

- **Sample Assistant Output:**
```
# Patient Case Summary

## Patient Information
- Name: Jane Doe
- Age: xx years old
- Gender: Female
- Medical Record Number: xxx-xxxxxx
- Date of Birth: mm/dd/yyyy

## Subjective
| Date       | Subjective Information                                      |
|------------|-------------------------------------------------------------|
| mm/dd/yyyy | Confused and lethargic, accidental overdose of medications  |
| mm/dd/yyyy | Feeling less confused, embarrassed about medication mix-up  |
| mm/dd/yyyy  | No complaints of pain or discomfort                        |

## Objective
| Date       | Objective Information                                       |
|------------|-------------------------------------------------------------|
| mm/dd/yyyy | Hypotension, bradycardia, alert but confused                |
| mm/dd/yyyy | BP 110/70, HR 68, RR 16, Temp 98.6°F, O2 Sat 98% on room air|
|            | Alert and oriented x3, lungs clear, heart regular           |
| mm/dd/yyyy | Alert and oriented x3, skin warm and dry, lungs clear       |
|            | Bowel sounds present in all four quadrants                  |

## Assessment
| Date       | Assessment                                                  |
|------------|-------------------------------------------------------------|
| mm/dd/yyyy | Medication overdose (lisinopril and hydrocodone)            |
|            | Hypertension, Osteoarthritis, Type 2 Diabetes               |
| mm/dd/yyyy | Medication overdose improving, hypertension well-controlled |
|            | Type 2 Diabetes stable                                      |
| mm/dd/yyyy | Resolved medication overdose, Hypertension                  |
|            | Type 2 Diabetes, Osteoarthritis                             |
## Plan
| Date       | Plan                                                        |
|------------|-------------------------------------------------------------|
| mm/dd/yyyy | Admit to Medical ICU, IV fluids, hold medications           |
|            | CBC, CMP, toxicology screen, EKG, consult Poison Control    |
| mm/dd/yyyy | Continue IV fluids, restart home meds at 50% dose           |
|            | Endocrinology consult, PT evaluation, discharge planning    |
| mm/dd/yyyy | Monitor vital signs q4h, encourage oral fluid intake        |
|            | Assist with ADLs, reinforce medication safety education     |

## Risks and Suggestions
1. xxxxx
2. xxxxx
3. xxxx
```

## Maintenance and Updates

### Version History
| Version Number | Release Date | New Features                  | Bug Fixes                   | Performance Improvements     |
|----------------|--------------|-------------------------------|-----------------------------|------------------------------|
| 1.0            |  2024-10-16  | Initial release               |  N/A  | N/A |


### Release Notes
#### Version Changes
- **v1.0** (Release Date: 2024-10-16)
  - Initial release.

## Contact Information

### Author(s) / Developers
- **Name(s):** AIRIA LLC

### Contact
- **https://airia.com/learn-more/** 

### License
- **License Type:** Airia Model License
