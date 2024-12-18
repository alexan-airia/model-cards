# Testimony search

## Model Overview

### Model Name
- **Name:** ft:gpt-4o-2024-08-06:airia:testimony-search-2024-10-22:ALAsroEx
- **Version:** 1.1
- **Date of Release:** 2024-09-29

### Description
- **Summary:** Airia's Testimony search 4o model provides targeted questions and answers, highlighting crucial case details. The strategy review includes winning strategies for success and counterpart strategies that anticipate opposing tactics. The similar cases section lists the top five relevant cases, offering useful precedents. This concise structure saves time, sharpens focus, and strengthens legal strategy.
- **Architecture:** Fine-tune gpt-4o-2024-08-06.
- **Recommended Temperature:** 0.1


## Intended Use

### Use Cases
- **Primary Use Cases:**
  - Automating the search for relevant testimonies to develop compelling legal strategies and prepare for witness examination.
  - Reviewing document transcripts to identify inconsistencies or corroborate details, crucial for shaping arguments or cross-examinations.
  - Enhancing the discovery phase by efficiently locating key witness statements that strengthen or weaken a case's legal position.

- **Non-intended Use Cases:** This model should not be used for providing final legal advice or in highly sensitive legal contexts without oversight by a human legal professional.

### Target Audience
- **Users:** Litigating attorneys, paralegals, law firms, in-house legal teams, judicial clerks, legal consultants, investigators, litigation finance firms.

### Sample interaction
- **Sample User Input:** The user must request a testimony search based on legal documents such as depositions and trial transcriptions that could lead to implement a testimony search process. For example:
  "Please do a testimony search with the following case details: [CASE DETAILS], [DEPOSITION TRANSCRIPT]".
- **Sample Assistant Output:**
```
<testimony_search>
A list of with questions and answers reflecting the nuances of the case.
</testimony_search>
<strategy_review>
<winning_strategies>
A list with possible strategies to win the case.
</winning_strategies>
<counterpart_strategies>
Identify trends or paths that could be used by the counterpart.
</counterpart_strategies>
</strategy_review>
<similar_cases>
A list eith the top 5 most similar cases, with relevant information about them.
</similar_cases>
```

## Maintenance and Updates

### Version History
| Version Number | Release Date | New Features                  | Bug Fixes                   | Performance Improvements     |
|----------------|--------------|-------------------------------|-----------------------------|------------------------------|
| 1.0            | 2024-09-29   | Initial release               |  N/A  | N/A |
| 1.1            | 2024-10-22   | System prompt no longer needed               |  N/A  | N/A |


### Release Notes
#### Version Changes
- **v1.0** (Release Date: 2024-09-29)
  - Initial release.
- **v1.1** (Release Date: 2024-10-22)
  - This model was trained without system prompt.

## Contact Information

### Author(s) / Developers
- **Name(s):** AIRIA LLC

### Contact
- **https://airia.com/learn-more/** 

### License
- **License Type:** Airia Model License
