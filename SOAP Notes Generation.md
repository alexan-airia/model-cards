# SOAP Notes Generation

## Model Overview

### Model Name

- **Name:**  ft:gpt-4o-2024-08-06:airia:soap-notes-generation-2024-10-14:AIN6c4hL
- **Version:** 1.0
- **Date of Release:** 2024-10-14

### Description

- **Summary:** Airia’s SOAP Notes Generation 4o model efficiently converts brief medical visit notes into comprehensive SOAP (Subjective, Objective, Assessment, Plan) format documentation. The model ensures all relevant patient data, exam findings, diagnostic reasoning, and treatment plans are captured and organized coherently, expanded on key details, and structured into standard SOAP sections.
- **Architecture:** Fine-tuned gpt-4o-2024-08-06.
- **Recommended Temperature:** 0.1

## Intended Use

### Use Cases

- **Primary Use Cases:**
  - Convert brief medical notes into comprehensive SOAP documentation

- **Non-intended Use Cases:** This model should not be used for providing final health advice or in highly sensitive health contexts without oversight by a medical professional.

### Target Audience

- **Users:** Healthcare Professionals, Healthcare Organizations, Medical Educators and Students, Researchers

### Sample interaction

- **Sample User Input:**

Generate SOAP Note from this visit summary: `[MEDICAL VISIT SUMMARY]`

- **Sample Assistant Output:**

```markdown
# SOAP Note

## Subjective
[...]

## Objective
[...]

## Assessment
[...]

## Plan
[...]
```

## Maintenance and Updates

### Version History

| Version Number | Release Date | New Features                  | Bug Fixes                   | Performance Improvements     |
|----------------|--------------|-------------------------------|-----------------------------|------------------------------|
| 1.0            |  2024-10-14  | Initial release               |  N/A  | N/A |

### Release Notes

#### Version Changes

- **v1.0** (Release Date: 2024-10-14)
  - Model name: ft:gpt-4o-2024-08-06:airia:soap-notes-generation-2024-10-14:AIN6c4hL
  - Initial release

## Contact Information

### Author(s) / Developers

- **Name(s):** AIRIA LLC

### Contact

- **https://airia.com/learn-more/**

### License

- **License Type:** Airia Model License
