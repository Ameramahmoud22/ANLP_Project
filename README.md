# ANLP Project: Arabic Question Answering System

## 1. Problem Definition

### Objective
Build an NLP system for **Question Answering (QA)** that:
- Understands natural language questions in Arabic  
- Generates accurate, relevant answers from a given text corpus  
- Demonstrates Natural Language Understanding (NLU) capabilities  

### Domain
- **Natural Language Understanding (NLU)**
- **Information Retrieval**
- **Semantic Analysis**

## 2. Task Description: Question Answering

### Overview
Question Answering (QA) is a core NLP task involving:
1. Automatic response generation to human-language questions  
2. Comprehension of question semantics and context  
3. Information retrieval from text corpora  

### System Requirements
| Capability | Description |
|------------|-------------|
| Understanding | Parse question meaning and intent |
| Retrieval | Search relevant information from corpus |
| Generation | Produce contextually appropriate answers |

### QA Task Types
1. **Extractive QA**  
   - Extracts answer spans directly from source text  
   - Example: Highlighting a sentence in Wikipedia  

2. **Abstractive QA**  
   - Generates novel answers combining multiple sources  
   - Example: Summarizing medical research to answer a patient query  

3. **Open-domain QA**  
   - Searches large, unstructured corpora (e.g., entire Wikipedia)  
   - More challenging than closed-domain QA  

### Key Challenges
```diff
+ Linguistic Complexity: Arabic morphology/dialects
+ Semantic Understanding: Beyond keyword matching
+ Multi-document Reasoning: Combining information across sources
- Ambiguity Resolution: Handling vague/ambiguous questions