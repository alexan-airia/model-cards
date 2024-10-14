# Interrogatory creation

## Model Overview

### Model Name
- **Name:** ft:gpt-4o-2024-08-06:airia:claude-complaint-to-interrogatory-v4:A8YkKSZF
- **Version:** 1.0
- **Date of Release:** 2024-09-17

### Description
- **Summary:** The model is a tool designed to improve lawyers' efficiency in the litigation process, specifically during the discovery phase. It helps generate a first version of interrogatories based on case information and legal documents such as complaints, answers to complaints, financial statements, etc. The model avoids creating simple yes/no questions or asking for specific documents, instead focusing on more detailed and open-ended queries to elicit meaningful information.
- **Architecture:** Fine-tune gpt-4o-2024-08-06.
- **Recommended Temperature:** 0.1

blob:https://airia.atlassian.net/72159ec7-710a-4fd3-b4e5-e166920e1005![image](https://github.com/user-attachments/assets/4eecbe59-b408-4f7a-8a99-8f661cdf3321)


## Intended Use

### Use Cases
- **Primary Use Cases:**
  - Interrogatory creation.
  - Trial preparation
- **Non-intended Use Cases:** This model should not be used for providing final legal advice or in highly sensitive legal contexts without oversight by a human legal professional.

### Target Audience
- **Users:** Litigation attorneys, legal assistants, in-house counsel, law firms, legal tech providers, legal operations teams, government legal departments.

### Sample interaction
- **Sample User Input:** The model generates up to 30 interrogatory questions based on the case info. and legal docs provided by the user.
"Create an interrogatory based on the following complaint = [COMPLAINT]"

- **Sample Assistant Output:** 
```
  1. Question #1
  2. Question #2
  ...
  30. Question #3
```

## Maintenance and Updates

### Version History
| Version Number | Release Date | New Features                  | Bug Fixes                   | Performance Improvements     |
|----------------|--------------|-------------------------------|-----------------------------|------------------------------|
| 1.0            | 2024-09-17   | Initial release               | N/A | N/A |


### Release Notes
#### Version Changes
- **v1.0** (Release Date: 2024-09-17)
  - Initial release.

## Contact Information

### Author(s) / Developers
- **Name(s):** AIRIA LLC

### Contact
- **https://airia.com/learn-more/** 

### License
- **License Type:** Airia Model License
