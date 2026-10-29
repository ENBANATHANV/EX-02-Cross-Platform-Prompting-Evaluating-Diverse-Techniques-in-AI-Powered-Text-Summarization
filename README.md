# EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

## AIM
To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.

## Scenario:
You are part of a content curation team for an educational platform that delivers quick summaries of research papers to undergraduate students. Your task is to summarize a 500-word technical article on "The Basics of Blockchain Technology" using multiple AI platforms and prompting strategies.

Your goal is to determine which combination of prompting technique + platform provides the best summary in terms of:

Accuracy

Coherence

Simplicity

Speed

User experience

## ALGORITHM

1. Select a technical article about the basics of blockchain technology.
2. Choose AI platforms such as ChatGPT, Gemini, Claude, and Copilot.
3. Create a basic prompt asking the AI to summarize the article.
4. Improve the prompt by adding role, context, constraints, and output format.
5. Enter the same article and corresponding prompts into each AI platform.
6. Collect and compare the generated summaries.
7. Evaluate the results based on accuracy, coherence, simplicity, speed, and user experience.
8. Identify the most effective prompting technique and AI platform based on the observations.

## PROMPT DESIGN

### 1. Basic Prompt

```text
Summarize the basics of blockchain technology.
```

### 2. Role Prompt

```text
Act as a computer science teacher and summarize blockchain technology for undergraduate students.
```

### 3. Context Prompt

```text
You are preparing educational content for college students who are new to blockchain technology. Summarize the provided article in simple language.
```

### 4. Constraint Prompt

```text
Summarize the provided article about blockchain technology in 150 words. Use simple English, include the main concepts, and avoid unnecessary technical terms.
```

### 5. Output Format Prompt

```text
Summarize the provided article about blockchain technology using the following format:

1. Introduction
2. How Blockchain Works
3. Key Features
4. Applications
5. Conclusion

Use simple English and keep the summary within 150 words.
```

### 6. Final Combined Prompt

```text
Act as a computer science educator creating learning materials for undergraduate students.

Context: Students need to understand the basics of blockchain technology without reading the entire technical article.

Task: Summarize the provided article accurately, covering blockchain, blocks, distributed ledgers, decentralization, security, and real-world applications.

Constraints:
- Use simple English.
- Keep the summary within 150 words.
- Include only information supported by the article.
- Avoid unnecessary technical jargon and repetition.

Output Format:
1. Introduction
2. Working Principle
3. Key Features
4. Applications
5. Conclusion

Ensure that the summary is clear, accurate, coherent, and easy to understand.
```

## EVALUATION CRITERIA

| Criteria | Description | ChatGPT Evaluation | Score (Out of 5) |
|---|---|---|---|
| Accuracy | Correctness of the information in the summary. | Provides relevant blockchain concepts with generally accurate explanations. | 4/5 |
| Coherence | Logical flow and organization of the content. | Presents information in a clear and well-organized sequence. | 3/5 |
| Simplicity | Ease of understanding for undergraduate students. | Uses simple English and explains technical concepts clearly. | 5/5 |
| Speed | Time taken to generate the summary. | Generates summaries quickly with minimal waiting time. | 4/5 |
| User Experience | Readability and usefulness of the generated response. | Provides readable, structured, and student-friendly summaries. | 4/5 |

## RESULT

Different prompting techniques were designed to evaluate their effectiveness in text summarization. The basic prompt provides a general summary, while role-based, context-based, constraint-based, and output-format prompts offer better control over the generated response.

The final combined prompt is expected to produce a more structured, relevant, and student-friendly summary. The best AI platform and prompting technique will be identified by testing the same article across all selected platforms and comparing the actual results.

Prompt engineering improves the quality and consistency of AI-generated summaries by clearly defining the task, context, constraints, and expected output format. The experiment helps identify which prompting technique produces the most accurate, coherent, and understandable summary for undergraduate students.
