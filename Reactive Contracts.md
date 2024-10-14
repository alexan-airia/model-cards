# Reactive Contracts

## Model Overview

### Model Name

- **Name:** ft:gpt-4o-2024-08-06:airia:reactive-contract:ACC1zHDF
- **Version:** 1.0
- **Date of Release:** 2024-09-27

### Description

- **Summary:** Airia's Reactive Contracts 4o model is designed to help legal professionals in the event of a data breach (or other reactive situation) to review every contract, understand its content, and determine whether a reaction is required.

- **Architecture:** gpt-4o-2024-08-06 fine-tuned.
- **Recommended Temperature:** 0.1

## Intended Use

### Use Cases

- **Primary Use Cases:**
  - Review Contracts in reactive situations.
  - Identify and list clauses that require action in response to specific events.
  - Summarize actionable obligations that could be relevant in urgent situations.
  
- **Non-intended Use Cases:** This model should not be used for providing final legal advice or in highly sensitive legal contexts without oversight by a human legal professional.

### Target Audience

- **Users:** Legal teams, contract managers, compliance officers, and risk management teams responsible for monitoring, tracking, and ensuring adherence to contractual obligations in reactive situations.

### Sample interaction

- **Sample User Input:**  
  Please analyze this contract and list possible actionable points: `[CONTRACT]`
  
- **Sample Assistant Output:**

  ```markdown
  # Clauses where a Reaction is Necessary
 

    ## 1. Clause 1
        [...]

    ## 2. Clause 2
        [...]

    ## 3. Clause 3
        [...]
  ```

## Maintenance and Updates

### Version History

| Version Number | Release Date | New Features                  | Bug Fixes                   | Performance Improvements     |
|----------------|--------------|-------------------------------|-----------------------------|------------------------------|
| 1.0            | 2024-09-27  | Initial release               | N/A | N/A |

### Release Notes

#### Version Changes

- **v1.0** (Release Date: 2024-09-27)
  - Initial release.

## Contact Information

### Author(s) / Developers

- **Name(s):** AIRIA LLC

### Contact

- **<https://airia.com/learn-more/>**

### License

- **License Type:** Airia Model License
