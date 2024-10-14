# Contract Redlining

## Model Overview

### Model Name

- **Name:** ft:gpt-4o-2024-08-06:airia:redlining-contracts:ACtXD9KN
- **Version:** 1.0
- **Date of Release:** 2024-09-29

### Description

- **Summary:** This model is designed to assist legal teams in contract redlining. Prepared with a playbook, the model can identify problematic clauses, rewrite them, and even add missing or required clauses, leaving just the final review up to lawyers.
- **Architecture:** gpt-4o-2024-08-06 fine-tuned.
- **Recommended Temperature:** 0.1

## Intended Use

### Use Cases

- **Primary Use Cases:**
  - Identify problematic clauses and rewrite them.
  - Add missing or required clauses.
  
- **Non-intended Use Cases:** This model should not be used for providing final legal advice or in highly sensitive legal contexts without oversight by a human legal professional.

### Target Audience

- **Users:** Legal teams, contract managers, business executives, and procurement teams responsible for quickly reviewing and apporving contracts accross different sectors.

### Sample interaction

- **Sample User Input:**  
  No need to ask for redlining (e.g. can you please redline this), given a playbook and a contract it automatically will redline one according to the other.
  
- **Sample Assistant Output:**

  ```markdown
  # Redline Analysis: [name/type of document analyzed]

  Here's a **redline analysis** of the provided [agreement name] based on the provided [playbook name]:

  ---

  ## 1. Party Definition

  **[citation from playbook]**

  **Analysis**: [analysis confirming the document satifies the citation from playbook above]


  ## 2. Termination Conditions

  **[citation from playbook]**

  **Excerpt**:

  [document excerpt]

  **Suggested Improvement**:

  [suggested improvement for document excerpt]

  **Reason**: [reason for suggestion]
  
  [...]
  ```

## Maintenance and Updates

### Version History

| Version Number | Release Date | New Features                  | Bug Fixes                   | Performance Improvements     |
|----------------|--------------|-------------------------------|-----------------------------|------------------------------|
| 1.0            | 2024-09-29  | Initial release               | N/A | N/A |

### Release Notes

#### Version Changes

- **v1.0** (Release Date: 2024-09-29)
  - Initial release.

## Contact Information

### Author(s) / Developers

- **Name(s):** AIRIA LLC

### Contact

- **<https://airia.com/learn-more/>**

### License

- **License Type:** Airia Model License
