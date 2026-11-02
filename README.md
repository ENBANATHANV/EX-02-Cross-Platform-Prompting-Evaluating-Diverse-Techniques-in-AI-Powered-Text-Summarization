## EX-02-Cross-Platform Prompting: Evaluating Diverse Prompt Engineering Techniques in AI-Powered Applications

#### NAME : ENBANATHAN V
#### REG NO : 212224220027

## AIM

To design and evaluate different prompt structures, including Basic Prompting, Role-Based Prompting, Context-Based Prompting, Constraint-Based Prompting, and Output Format Prompting, across multiple AI platforms for text summarization.

The experiment aims to identify how different prompt structures influence the accuracy, coherence, simplicity, speed, and user experience of AI-generated summaries.

---

## SCENARIO

You are a content development assistant for an online educational platform that provides simplified technical summaries to undergraduate students.

The task is to summarize a 500-word technical article titled **"The Basics of Blockchain Technology"** using different prompt structures across ChatGPT, Gemini, Claude AI, and Microsoft Copilot.

The generated summaries are evaluated based on:

- Accuracy
- Coherence
- Simplicity
- Speed
- User Experience

---

## INPUT ARTICLE

### The Basics of Blockchain Technology

Blockchain is a distributed digital ledger technology that stores information securely across multiple computers. It allows transactions and data to be recorded without depending on a central authority. Blockchain is widely used in cryptocurrencies, supply chain management, healthcare, and digital identity systems.

A blockchain consists of a series of blocks connected in chronological order. Each block contains transaction data, a timestamp, and a cryptographic hash of the previous block. A cryptographic hash is a unique digital fingerprint generated from the data. If the information in a block is changed, its hash also changes, making unauthorized modifications easy to detect.

Blockchain operates through a network of computers called nodes. When a user initiates a transaction, it is broadcast to the network. The nodes verify the transaction according to predefined rules. Once the transaction is validated, it is grouped with other transactions into a block. The network uses a consensus mechanism to agree on the validity of the block before adding it to the blockchain.

Two common consensus mechanisms are Proof of Work (PoW) and Proof of Stake (PoS). Proof of Work requires computers to solve computational puzzles to validate blocks. Proof of Stake selects validators based on the cryptocurrency they lock as a stake. Proof of Stake generally consumes less energy than Proof of Work.

Blockchain has several important features. Decentralization means that data is maintained by multiple participants rather than a single organization. Transparency allows participants to verify recorded transactions. Immutability makes confirmed records difficult to modify. Cryptographic security helps protect data and verify transactions.

There are different types of blockchain networks. Public blockchains allow anyone to participate, while private blockchains restrict access to authorized users. Consortium blockchains are managed by a group of organizations. Hybrid blockchains combine features of public and private networks.

Blockchain technology has many real-world applications. In finance, it supports cryptocurrency transactions and cross-border payments. In supply chain management, it helps track products from manufacturers to customers. In healthcare, it can improve the secure sharing of medical records. Smart contracts are programs stored on a blockchain that automatically execute agreements when specified conditions are met.

Despite its advantages, blockchain faces challenges such as scalability, energy consumption, regulatory uncertainty, and implementation costs. Some blockchain networks process transactions more slowly than traditional centralized systems.

In conclusion, blockchain is an innovative technology that provides secure, transparent, and decentralized data management. Understanding its working principles, features, applications, and limitations helps students understand its growing importance in modern digital systems.

---

## PROMPT STRUCTURES USED

### 1. Basic Prompt

**Prompt Used:**

```text
Summarize the following article about blockchain
technology in approximately 120 words.

Include the main ideas and preserve the original meaning.


```

**Purpose:** To generate a general summary without providing additional instructions or background information.

### 2. Role-Based Prompt

**Prompt Used:**

```text
Act as a computer science professor explaining
blockchain technology to first-year engineering students.

Summarize the following article using simple language
and explain the important concepts clearly.

```

**Purpose:** To evaluate whether assigning an educational role improves clarity and explanation.

### 3. Context-Based Prompt

**Prompt Used:**

```text
You are preparing revision material for undergraduate
students who are new to blockchain technology.

Summarize the article by highlighting its basic
concepts, working process, and real-world applications.

```

**Purpose:** To improve the relevance of the summary by providing the target audience and learning objective.

### 4. Constraint-Based Prompt

**Prompt Used:**

```text
Summarize the following blockchain article using
these conditions:

- Limit the summary to 100–120 words.
- Use simple English.
- Include the working principle and applications.
- Avoid unnecessary technical details.
- Do not introduce unsupported information.

```

**Purpose:** To control the length, language complexity, and factual accuracy of the summary.

### 5. Output Format Prompt

**Prompt Used:**

```text
Summarize the following blockchain article using
the format below:

Title:
Overview:
Working Principle:
Key Features:
Applications:
Conclusion:

Use simple English and keep the summary within
150 words.

```

**Purpose:** To improve the organization, readability, and presentation of the generated summary.

---

## CROSS-PLATFORM AI EVALUATION

### 1. ChatGPT — Basic Prompt

**Prompt Used:**

```text
Read the blockchain article and identify its central
message, important concepts, and major applications.

Write a concise summary suitable for undergraduate
students using approximately 120 words.
```

**Summary Generated:**

> Blockchain is a distributed digital ledger that records information across multiple computers without requiring a central authority. Data is organized into blocks connected through cryptographic hashes, making unauthorized changes difficult to perform. Transactions are verified by network participants using consensus mechanisms such as Proof of Work and Proof of Stake. Blockchain offers decentralization, transparency, security, and immutability. It is used in cryptocurrency, financial services, healthcare, supply chain management, and smart contracts. However, blockchain technology faces challenges related to scalability, energy consumption, and transaction speed. Its ability to provide reliable and transparent records makes it an important technology for modern digital systems.

**Evaluation:**

| Criterion | Observation |
|---|---|
| Accuracy | Very Good |
| Coherence | Excellent |
| Simplicity | Excellent |
| Speed | Very Fast |
| User Experience | Excellent |

### 2. Gemini — Role-Based Prompt

**Prompt Used:**

```text
Act as a blockchain technology instructor.

Explain the main ideas of the article to undergraduate
students using a short and informative summary.

Focus on how blockchain works, why it is useful,
and where it is applied.
```

**Summary Generated:**

> Blockchain is a technology that maintains a shared digital record across multiple computers. Instead of depending on a single organization, transactions are verified by participants in the network. Information is grouped into blocks and connected using cryptographic techniques. Consensus mechanisms help participants agree on valid transactions. Blockchain provides transparency, decentralization, and protection against unauthorized changes. Its applications include digital payments, product tracking, healthcare information management, and automated agreements through smart contracts. Although blockchain improves trust and data sharing, its adoption is affected by transaction speed, scalability, and energy requirements. Understanding these concepts helps students recognize the role of blockchain in developing secure digital systems.

**Evaluation:**

| Criterion | Observation |
|---|---|
| Accuracy | Excellent |
| Coherence | Excellent |
| Simplicity | Very Good |
| Speed | Fast |
| User Experience | Very Good |

### 3. Claude AI — Context-Based Prompt

**Prompt Used:**

```text
You are preparing introductory revision material for
engineering students who are studying blockchain
technology for the first time.

Summarize the article by connecting its basic principles
with its real-world applications.

Make the summary informative, logically organized,
and suitable for quick revision.
```

**Summary Generated:**

> Blockchain is a decentralized record-keeping system that enables multiple participants to maintain and verify shared information. Transactions are collected into blocks, which are linked using cryptographic hashes. Network participants validate transactions through consensus mechanisms before new blocks are added. This process supports transparency, security, and resistance to unauthorized modifications. Public, private, consortium, and hybrid blockchains provide different levels of participation and control. Applications include cryptocurrency, supply chain tracking, healthcare data sharing, and smart contracts. Despite its potential, blockchain must address challenges such as scalability, energy usage, and implementation costs. Its importance lies in providing a shared and verifiable method of managing digital information.

**Evaluation:**

| Criterion | Observation |
|---|---|
| Accuracy | Excellent |
| Coherence | Excellent |
| Simplicity | Very Good |
| Speed | Moderate |
| User Experience | Excellent |

### 4. Microsoft Copilot — Constraint-Based Prompt

**Prompt Used:**

```text
Summarize the blockchain article for first-year
engineering students.

Use simple English and a maximum of 120 words.

Include the definition, working principle, two
applications, and one major limitation.

Avoid unnecessary technical terminology.
```

**Summary Generated:**

> Blockchain is a digital record system that stores information across multiple computers. Data is organized into connected blocks, and transactions are verified by network participants before being recorded. Cryptographic techniques help protect the information from unauthorized changes. Blockchain reduces dependence on central authorities and improves transparency. It is used in cryptocurrency transactions and supply chain tracking. Smart contracts also allow agreements to execute automatically when specified conditions are met. However, blockchain technology faces challenges such as slow transaction processing and high energy consumption in some networks. Despite these limitations, blockchain provides a useful approach to secure and shared digital record management.

**Evaluation:**

| Criterion | Observation |
|---|---|
| Accuracy | Very Good |
| Coherence | Very Good |
| Simplicity | Excellent |
| Speed | Very Fast |
| User Experience | Very Good |

---

## COMPARISON TABLE

| AI Platform | Prompt Structure | Accuracy | Coherence | Simplicity | Speed | User Experience |
|---|---|---|---|---|---|---|
| ChatGPT | Basic Prompt | Very Good | Excellent | Excellent | Very Fast | Excellent |
| Gemini | Role-Based | Excellent | Excellent | Very Good | Fast | Very Good |
| Claude AI | Context-Based | Excellent | Excellent | Very Good | Moderate | Excellent |
| Microsoft Copilot | Constraint-Based | Very Good | Very Good | Excellent | Very Fast | Very Good |

---

## OVERALL FINDINGS

| AI Platform | Key Strength | Limitation |
|---|---|---|
| ChatGPT | Produces concise and readable summaries with a good balance of important concepts. | May omit some secondary technical details in shorter summaries. |
| Gemini | Provides clear educational explanations and effectively covers practical applications. | May include more explanation than required for a very short summary. |
| Claude AI | Produces logically connected summaries and includes useful conceptual details. | The output may require additional simplification for beginners. |
| Microsoft Copilot | Generates concise summaries and follows explicit constraints effectively. | Strict word limits may reduce the amount of technical information included. |

---

## RESULT

The experiment demonstrated that different prompt structures influence the quality of AI-generated text summaries. Role-Based and Context-Based Prompting improved educational relevance, while Constraint-Based Prompting controlled length and simplicity. Output Format Prompting enhanced readability and organization. 

---


