# Contract Clause Extraction for Compliance

## Model Overview

### Model Name

- **Name:** ft:gpt-4o-2024-08-06:airia:clause-extraction-compliance-2024-10-09:AGS412xK
- **Version:** 1.0
- **Date of Release:** 2024-10-09

### Description

- **Summary:** Airia's Contract Clause Extraction for Compliance 4o model performs a meticulous examination of a contract to identify and extract all clauses pertaining to compliance with a specific regulation. The model also conducts an evaluation of these extracted clauses, assessing their alignment with the legal requirements of a designated jurisdiction.

- **Architecture:** gpt-4o-2024-08-06 fine-tuned.
- **Recommended Temperature:** 0.1

## Intended Use

### Use Cases

- **Primary Use Cases:**
  - Identify and extract all clauses pertaining to compliance with a specific regulation
  - Assess the alignment of extracted to clause to a specific jurisdiction
  
- **Non-intended Use Cases:** This model should not be used for providing final legal advice or in highly sensitive legal contexts without oversight by a human legal professional.

### Target Audience

- **Users:** Legal teams, contract managers, compliance officers, and risk management teams responsible for monitoring, tracking, and ensuring adherence to contractual obligations across various timelines.

### Sample interaction

- **Sample User Input:**  
  User can ask for something similar to: "Extract clauses from following contract meeting `[REGULATION]` regulation in `[JURISDICTION]` jurisdiction. Contract: `[CONTRACT]`"
  
- **Sample Assistant Output:**

  ```markdown
    ## Relevant Clauses
    1. Compliance with Jurisdiction Laws
      [...]

    2. Regulation Compliance
      [...]
    
    3. Other Specific Clauses
      [...]

    ## Conclusion
      [...]
  ```

## Maintenance and Updates

### Version History

| Version Number | Release Date | New Features                  | Bug Fixes                   | Performance Improvements     |
|----------------|--------------|-------------------------------|-----------------------------|------------------------------|
| 1.0            | 2024-10-09  | Initial release               | N/A | N/A |

### Release Notes

#### Version Changes

- **v1.0** (Release Date: 2024-10-09)
  - Initial release.

## Contact Information

### Author(s) / Developers

- **Name(s):** AIRIA LLC

### Contact

- **<https://airia.com/learn-more/>**

### License

- **License Type:** Airia Model License
