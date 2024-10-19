# Medical Document Summarization - POMR Style

## Model Overview

### Model Name
- **Name:**  ft:gpt-4o-2024-08-06:airia:medical-documents-summarization-pomr-2024-10-17:AJWkCg1y
- **Version:** 1.0
- **Date of Release:** 2024-10-17

### Description
- **Summary:** Airia's Medical Document Summarization - POMR Style 4o model provides comprehensive summaries of medical documents, utilizing the POMR framework (Problem-Oriented Medical Record) for structured organization. Each section is detailed with well-organized tables that present information along a clear timeline.
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
- **Users:** Patients, healthcare providers, pharmacists, insurers, researchers, wellness clinics, family members.

### Sample interaction
- **Sample User Input:** 
```
Can you summarize this: [DIVERSE MEDICAL DOCUMENTS]
```

- **Sample Assistant Output:**
```
# Patient Case Summary: Daniel Williams

## 1. Patient Information

- Name: Daniel Williams
- Age: 77
- Gender: Male
- Medical Record Number: MRN-xxxxxxxx

## 2. Problem List

| No. | Problem                     | Date Identified    |
|-----|-----------------------------| ------------------ |
| 1   | Right femoral neck fracture |    mm/dd/yyyy      |
| 2   | Hypertension                | Prior to admission |
| 3   | Type 2 Diabetes             | Prior to admission |
| 4   | Osteoarthritis              | Prior to admission |

## 3. Database

| Date       | Information                                                |
|------------|------------------------------------------------------------|
| mm/dd/yyyy | - Fall from 6-foot ladder while cleaning gutters           |
|            | - Severe right hip pain, unable to bear weight             |
|            | - X-ray: Displaced right femoral neck fracture             |
|            | - Labs: WBC 9.2, Hgb 13.5, Plt 210, Cr 1.1, INR 1.1        |
| mm/dd/yyyy | - Persistent right hip pain, slightly improved with meds   |

## 4. Initial Plans

| Date       | Plan                                                       |
|------------|------------------------------------------------------------|
| mm/dd/yyyy | 1. X-ray of right hip and pelvis                           |
|            | 2. CBC, BMP, PT/INR                                        |
|            | 3. Pain management with IV morphine                        |
|            | 4. Orthopedic consultation                                 |
|            | 5. Admit for further management and likely surgery         |
| mm/dd/yyyy | 1. Continue pain management                                |
|            | 2. NPO status in preparation for surgery                   |
|            | 3. Orthopedic surgery scheduled for next morning           |
|            | 4. DVT prophylaxis with enoxaparin                         |

## 5. Progress Notes

| Date       | Progress                                                   |
|------------|-----------------------------------------------------------|
| mm/dd/yyyy | - Pain slightly improved with medication                   |
|            | - Pre-operative clearance obtained                         |
| mm/dd/yyyy | - Right hip hemiarthroplasty performed successfully        |
|            | - Estimated blood loss: 250 mL                             |
|            | - No complications during surgery                          |
| mm/dd/yyyy | - Pain well-managed (3-6/10)                               |
|            | - Surgical site clean and dry, no signs of infection       |
|            | - Ambulated 10 feet with walker assistance                 |
|            | - Taking oral fluids well                                  |

## 6. Risks and Suggestions

1. [...]
2. [...]
3. [...]
```

## Maintenance and Updates

### Version History
| Version Number | Release Date | New Features                  | Bug Fixes                   | Performance Improvements     |
|----------------|--------------|-------------------------------|-----------------------------|------------------------------|
| 1.0            |  2024-10-17  | Initial release               |  N/A  | N/A |


### Release Notes
#### Version Changes
- **v1.0** (Release Date: 2024-10-17)
  - Initial release.

## Contact Information

### Author(s) / Developers
- **Name(s):** AIRIA LLC

### Contact
- **https://airia.com/learn-more/** 

### License
- **License Type:** Airia Model License
