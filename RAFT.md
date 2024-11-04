# RAFT

## Model Overview

### Model Name

- **Name:**  ft:gpt-4o-2024-08-06:airia:raft-qa-2024-10-31:AOPB3uKB
- **Version:** 1.0
- **Date of Release:** 2024-11-04

### Description

- **Summary:** Airia's RAFT model has been developed to enhance the functionality of RAG applications. In a conventional RAG system, when a query is posed to a model, it retrieves a few documents from a database that are likely to contain the answer. However, some of those documents might be distractors, i.e., they do not contain the correct answer to the question. By fine-tuning with a chain-of-thought approach, our RAFT model learns to recognise and discard irrelevant context before providing an answer. This leads to a model that can be integrated with any RAG pipeline, but with fewer chances of hallucinations caused by the information retrieval process.

- **Recommended Temperature:** 0.1

## Intended Use

### Use Cases

- **Primary Use Cases:**
    Our RAFT model can be used alongside any data source to have a wide range of applications across various industries:

  - **Customer Support**: RAFT-enabled chatbots can provide accurate and contextually relevant responses to customer inquiries by retrieving the latest product information and customer-specific data, improving overall customer satisfaction.
  - **Employee Training**: Our RAFT model is able to enhance onboarding processes by providing new hires with real-time answers to their questions based on a repository of company-specific documents and training materials.
  - **Advanced Question Answering**: Our RAFT model can be integrated with sophisticated question-answering systems that can retrieve precise information from extensive knowledge bases, making it useful in fields like healthcare, legal or finance.

- **Non-intended Use Cases:** This model should not be used for handling sensitive data that could lead to breaches of privacy regulations, especially if personal identifiable information (PII) is exposed.

### Target Audience

- **Users:** Businesses, content creators, educators, students, analysts and anyone interested in QA applications with a set of documents.

### Sample interaction

- **Sample User Input:**

TODO

- **Sample Assistant Output:**

```markdown
TODO
```

## Maintenance and Updates

### Version History

| Version Number | Release Date | New Features                  | Bug Fixes                   | Performance Improvements     |
|----------------|--------------|-------------------------------|-----------------------------|------------------------------|
| 1.0            |  2024-11-04  | Initial release               |  N/A  | N/A |

### Release Notes

#### Version Changes

- **v1.0** (Release Date: 2024-11-04)
  - Model name: ft:gpt-4o-2024-08-06:airia:raft-qa-2024-10-31:AOPB3uKB
  - Initial release

## Contact Information

### Author(s) / Developers

- **Name(s):** AIRIA LLC

### Contact

- **https://airia.com/learn-more/**

### License

- **License Type:** Airia Model License
