# EX-02:Cross Platform Prompting Evaluating Diverse Techniques in AI Powered Text-Summarization

## Name: Shehan Shajahan
## Reg No: 212223240154

## AIM
To evaluate and compare the effectiveness of prompting techniques (Zero-shot, Few-shot, Chain-of-Thought, and Role-based prompting) across different AI platforms such as ChatGPT, Gemini, Claude, and Copilot for the task of text summarization.

---

# SCENARIO

You are part of a content curation team for an educational platform that delivers quick summaries of research papers to undergraduate students. Your task is to summarize a 500-word technical article on **"The Basics of Blockchain Technology"** using multiple AI platforms and prompting strategies.

The goal is to determine which combination of prompting technique and platform provides the best summary in terms of:

- Accuracy
- Coherence
- Simplicity
- Speed
- User Experience

---

# PROMPTING TECHNIQUES USED

## 1. Zero-Shot Prompting

### Description
The AI is directly asked to summarize the article without any examples.

### Prompt
```text
Summarize the following article on "The Basics of Blockchain Technology" in simple language suitable for undergraduate students.
```

### Expected Outcome
- Quick response
- Simple summary
- Less contextual guidance

---

## 2. Few-Shot Prompting

### Description
The AI is given examples before performing the summarization task.

### Prompt
```text
Example:
Input: Artificial Intelligence is the simulation of human intelligence by machines.

Output: AI enables machines to perform tasks that usually require human intelligence.

Now summarize the following article on "The Basics of Blockchain Technology".
```

### Expected Outcome
- Better formatting consistency
- Improved clarity
- More structured summaries

---

## 3. Chain-of-Thought Prompting

### Description
The AI is instructed to think step-by-step before generating the summary.

### Prompt
```text
Read the article carefully.

Identify:
1. Definition of blockchain
2. Key components
3. Working process
4. Advantages
5. Applications

Then create a concise summary suitable for undergraduate students.
```

### Expected Outcome
- Higher accuracy
- Better logical flow
- More detailed summary

---

## 4. Role-Based Prompting

### Description
The AI is assigned a specific role before summarization.

### Prompt
```text
You are a university professor explaining blockchain technology to first-year undergraduate students. Summarize the article in a simple and engaging manner.
```

### Expected Outcome
- More engaging explanation
- Student-friendly language
- Better readability

---

# AI PLATFORMS USED

| Platform | Description |
|---|---|
| ChatGPT | Conversational AI developed by OpenAI |
| Gemini | AI assistant developed by Google |
| Claude | AI assistant focused on safe and natural responses |
| Copilot | AI assistant integrated with Microsoft services |

---

# ARTICLE USED FOR SUMMARIZATION

## Title
**The Basics of Blockchain Technology**

## Main Concepts Covered
- Blockchain is a decentralized digital ledger
- Transactions are grouped into blocks
- Blocks are connected using cryptographic hashes
- Blockchain ensures transparency and security
- Applications include cryptocurrency, banking, healthcare, and supply chain management

---

# EVALUATION CRITERIA

| Criteria | Description |
|---|---|
| Accuracy | Correctness of information in the summary |
| Coherence | Logical flow and readability |
| Simplicity | Ease of understanding for students |
| Speed | Time taken to generate the summary |
| User Experience | Overall interaction quality |

---

# OBSERVATIONS

| Platform | Prompt Technique | Accuracy | Coherence | Simplicity | Speed | User Experience |
|---|---|---|---|---|---|---|
| ChatGPT | Zero-Shot | High | High | Medium | Fast | Excellent |
| ChatGPT | Few-Shot | High | High | High | Fast | Excellent |
| ChatGPT | Chain-of-Thought | Very High | Very High | High | Medium | Excellent |
| ChatGPT | Role-Based | High | Very High | Very High | Fast | Excellent |
| Gemini | Zero-Shot | Medium | High | Medium | Fast | Good |
| Gemini | Few-Shot | High | High | High | Fast | Good |
| Gemini | Chain-of-Thought | High | High | Medium | Medium | Good |
| Gemini | Role-Based | High | Very High | High | Fast | Very Good |
| Claude | Zero-Shot | High | High | High | Medium | Excellent |
| Claude | Few-Shot | Very High | Very High | High | Medium | Excellent |
| Claude | Chain-of-Thought | Very High | Excellent | High | Slow | Excellent |
| Claude | Role-Based | High | Excellent | Very High | Medium | Excellent |
| Copilot | Zero-Shot | Medium | Medium | Medium | Fast | Good |
| Copilot | Few-Shot | High | Medium | High | Fast | Good |
| Copilot | Chain-of-Thought | High | High | Medium | Medium | Good |
| Copilot | Role-Based | High | High | High | Fast | Very Good |

---

# ANALYSIS

## Zero-Shot Prompting
- Fastest technique
- Requires minimal setup
- Suitable for quick summaries
- Sometimes lacks depth and contextual clarity

## Few-Shot Prompting
- Produces more structured summaries
- Improves consistency and formatting
- Helps AI understand expected output style

## Chain-of-Thought Prompting
- Generates highly accurate summaries
- Improves logical explanation and coherence
- Slightly slower due to reasoning steps

## Role-Based Prompting
- Produces engaging and student-friendly summaries
- Enhances readability and simplicity
- Best suited for educational content delivery

---

# OUTPUT

## Best Performing Combinations

| Category | Best Combination |
|---|---|
| Accuracy | Claude + Chain-of-Thought |
| Coherence | ChatGPT + Chain-of-Thought |
| Simplicity | ChatGPT + Role-Based |
| Speed | ChatGPT + Zero-Shot |
| User Experience | ChatGPT + Role-Based |

---

# RESULT

The experiment successfully evaluated different prompting strategies across multiple AI platforms for text summarization tasks.

## Findings
- **Chain-of-Thought prompting** produced the most accurate and coherent summaries.
- **Role-Based prompting** generated the simplest and most engaging explanations for undergraduate students.
- **Few-Shot prompting** improved formatting consistency and clarity.
- **Zero-Shot prompting** provided the fastest responses but with less detailed summaries.

Among the tested platforms, ChatGPT and Claude delivered the best overall performance for educational text summarization.

## Conclusion

The combination of:

> **ChatGPT + Role-Based Prompting**

was identified as the most effective approach for generating clear, accurate, and undergraduate-friendly summaries of technical articles.
