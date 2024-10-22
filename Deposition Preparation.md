# Deposition Preparation

## Model Overview

### Model Name
- **Name:** ft:gpt-4o-2024-08-06:airia:deposition-preparation-2024-10-22:ALF0rEw0
- **Version:** 1.1
- **Date of Release:** 2024-10-22

### Description
- **Summary:** This model is fine-tuned for drafting depositions, this model generates relevant questions based on case details.

- **Architecture:**  gpt-4o-2024-08-06 fine-tuned.
- **Recommended Temperature:** 0.1

## Intended Use

### Use Cases
- **Primary Use Cases:**
  - Document Review and Summary
  - Anticipating Cross-Examination
  - Risk and Consistency Analysis
- **Non-intended Use Cases:** This model is not intended for use in generating legal advice or for handling highly sensitive or classified documents without oversight.

### Target Audience
- **Users:** Legal teams, including attorneys, paralegals, and in-house counsel who are responsible for preparing witnesses for depositions in litigation cases.
  
### Sample interaction
- **Sample User Input**: 
  - Can you describe the events leading up to the incident on [date]?
  - Is it true that you were aware of the contract's termination clause before signing?
  - [link or text of the contract]
- **Sample Assistant Output:**
  - List of mock questions
  - Timeline of events




## Maintenance and Updates

### Version History
| Version Number | Release Date | New Features                  | Bug Fixes                   | Performance Improvements     |
|----------------|--------------|-------------------------------|-----------------------------|------------------------------|
| 1.0            | 2024-09-30  | Initial release               | N/A | N/A |
| 1.1            | 2024-10-22  | System prompt no longer needed. | N/A | N/A |



### Release Notes
#### Version Changes
- **v1.0** (Release Date: 2024-09-30)
  - Initial release with basic deposition creation capabilities for litigation. 
- **v1.1** (Release Date: 2024-10-22)
  - Trained without system prompt.
  - New sections added to the response:
    - Potential areas of witness vulnerability to explore
    - Strategies for handling potential objections
    - Areas to avoid that might strengthen the opposition's case. Format your response using markdown for clear organization.


## Contact Information

### Author(s) / Developers
- **Name(s):** AIRIA LLC

### Contact
- **https://airia.com/learn-more/** 

### License
- **License Type:** Airia Model License
