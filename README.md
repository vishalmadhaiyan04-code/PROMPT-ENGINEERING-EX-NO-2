# EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

## AIM
To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.

## SCENARIO:
You are part of a content curation team for an educational platform that delivers quick summaries of research papers to undergraduate students. Your task is to summarize a 500-word technical article on "The Basics of Blockchain Technology" using multiple AI platforms and prompting strategies.

Your goal is to determine which combination of prompting technique + platform provides the best summary in terms of:

Accuracy

Coherence

Simplicity

Speed

User experience

## OUTPUT: 
## ZERO SHOT PROMPTS:
PROMPT:WRITE A WELL STRUCTURED, BEGINNER FRIENDLY ARTICLE ON THE BASICS OF BLOCKCHAIN TECHNOLOY FOR 200 WORDS
____________________________________________________________________________________________________________
### CHATGPT 
#### Basics of Blockchain Technology

Blockchain technology is a modern digital system used to record and share information securely. It works as a **distributed ledger**, meaning data is stored across multiple computers (called nodes) instead of a single central server. This structure makes blockchain transparent, secure, and difficult to alter.

A blockchain is made up of **blocks**, where each block contains data, a timestamp, and a cryptographic hash of the previous block. These blocks are linked together in a chain, ensuring data integrity. If someone tries to change information in one block, all following blocks would also need to be changed, which is extremely difficult.

One of the key features of blockchain is **decentralization**. Since no single authority controls the system, it reduces the risk of fraud and increases trust among users. **Consensus mechanisms**, such as Proof of Work and Proof of Stake, are used to validate transactions and ensure all nodes agree on the data.

Blockchain technology offers several advantages, including high security, transparency, and reduced transaction costs. However, it also has limitations such as scalability issues and high energy consumption in some systems.

Today, blockchain is widely used in **cryptocurrencies**, supply chain management, healthcare, banking, and digital identity systems. Its ability to provide secure and reliable data sharing makes it a promising technology for the future.
________________________________________________________________________________________________________________________________________________
### GEMINI:
## Understanding Blockchain: The Digital Ledger

Imagine a shared digital notebook that everyone can read, but no single person can erase or modify. That is the essence of **blockchain technology**.

At its core, a blockchain is a system of recording information in a way that makes it difficult or impossible to change, hack, or cheat the system. It is a **distributed database** shared among the nodes of a computer network.

### How It Works

1. **The Block:** Data (like a transaction) is stored in a container called a "block."
2. **The Chain:** Once a block is filled, it is sealed and linked to the previous block using cryptography. This forms a chronological "chain."
3. **The Network:** Instead of being stored on one central server (like a bank), the ledger is copied across thousands of computers worldwide.

### Why It Matters

* **Decentralization:** No single entity controls the history. It cuts out middlemen.
* **Immutability:** Once data is entered, it is permanent. You cannot go back and "cook the books."
* **Transparency:** Participants can view the history of transactions, creating built-in trust.

While best known for powering cryptocurrencies like Bitcoin, blockchain is currently being adapted for voting systems, supply chain tracking, and secure medical records.
____________________________________________________________________________________________________________________________________________________
### CLAUDE-2:
# Understanding Blockchain Technology: A Beginner's Guide

Blockchain technology is revolutionizing how we store and share information digitally. At its core, a blockchain is a digital ledger that records transactions across multiple computers in a way that makes the data nearly impossible to alter.

## How It Works

Think of a blockchain as a chain of digital blocks, where each block contains a list of transactions. When a new transaction occurs, it's verified by a network of computers and added to a new block. This block is then linked to the previous one, creating an unbreakable chain.

## Key Features

**Decentralization** means no single entity controls the blockchain. Instead, copies exist across thousands of computers worldwide, making it highly secure.

**Transparency** allows anyone to view transactions while maintaining user privacy through encrypted addresses.

**Immutability** ensures that once data is recorded, it cannot be changed without altering all subsequent blocks, which is practically impossible.

## Real-World Applications

While cryptocurrency like Bitcoin made blockchain famous, the technology extends far beyond digital money. Industries use it for supply chain tracking, secure medical records, digital contracts, and voting systems.

Understanding blockchain opens doors to grasping the future of digital trust and security in our increasingly connected world.
_______________________________________________________________________________________________________________________________________________
### COPILOT:

## 🧩 Understanding the Basics of Blockchain Technology  
A Beginner‑Friendly 200‑Word Guide

Blockchain technology is often described as complex, but its core idea is surprisingly simple. At its heart, a blockchain is a **digital ledger**—a record of transactions—that is shared across a network of computers. Instead of being stored in one place, copies of this ledger exist on many machines, making it **transparent, secure, and difficult to tamper with**.

Each record on a blockchain is stored in a “block.” These blocks are linked together in chronological order, forming a **chain**. Once information is added to a block and confirmed by the network, it becomes extremely hard to change. This feature is what gives blockchain its strong reputation for security.

A key concept behind blockchain is **decentralization**. Unlike traditional systems controlled by banks or companies, a blockchain is maintained by many participants. This reduces the risk of fraud and makes the system more trustworthy.

Blockchain first became popular through cryptocurrencies like Bitcoin, but its uses go far beyond digital money. Today, it’s being explored for **supply chain tracking**, **secure voting**, **healthcare records**, and even **digital identity**.

For beginners, the most important takeaway is this: blockchain is a secure, transparent way to store and share information without relying on a central authority. Its potential is vast, and understanding the basics opens the door to many exciting innovations.
__________________________________________________________________________________________________________________________________________________
__________________________________________________________________________________________________________________________________________________
## FEW SHOT PROMPTING:
PROMPT:
Example 1:
Topic: Basics of Artificial Intelligence
Output:
Artificial Intelligence (AI) refers to the ability of machines to perform tasks that normally require human intelligence. It includes learning, reasoning, and problem-solving. AI is widely used in applications such as virtual assistants, recommendation systems, and autonomous vehicles. Its benefits include automation and improved efficiency, but it also raises ethical and security concerns.

Example 2:
Topic: Basics of Cloud Computing
Output:
Cloud computing is a technology that allows users to store and access data over the internet instead of local computers. It offers services such as storage, servers, and software on demand. Common cloud models include public, private, and hybrid clouds. Cloud computing provides scalability and cost efficiency, though it depends heavily on internet connectivity.

Now generate:
Topic: Basics of Blockchain Technology WITH 200 WORDS
_______________________________________________________________________________________________________________________________________________________
### CHATGPT:
**Basics of Blockchain Technology**

Blockchain technology is a decentralized digital system used to record transactions in a secure and transparent manner. Instead of storing data in a single central server, blockchain distributes information across a network of computers called nodes. Each transaction is grouped into a block, and these blocks are linked together in chronological order, forming a chain. Once data is recorded on a blockchain, it is extremely difficult to alter, which ensures data integrity and trust.

One of the key features of blockchain is decentralization, which removes the need for intermediaries such as banks or clearing agencies. Another important feature is transparency, as all participants in the network can view the transaction history. Blockchain also uses cryptographic techniques to secure data and validate transactions through consensus mechanisms like Proof of Work and Proof of Stake.

Blockchain technology is best known for supporting cryptocurrencies such as Bitcoin and Ethereum, but its applications go far beyond digital currency. It is widely used in supply chain management, healthcare, digital identity verification, and smart contracts. By improving security, reducing fraud, and increasing efficiency, blockchain has the potential to transform many industries, although challenges like scalability, energy consumption, and regulatory concerns still exist.
_______________________________________________________________________________________________________________________________________________________
### GEMINI:
Here is an overview of the basics of Blockchain Technology.

### The Basics of Blockchain Technology

At its core, **Blockchain** is a distributed ledger technology (DLT) that records transactions securely and transparently across a network of computers. Unlike traditional databases managed by a single central authority (like a bank or government), blockchain operates on a **decentralized** peer-to-peer network.

**How It Works**
Information is stored in groups known as **blocks**. When a block is filled with data, it is chemically linked to the previous block using a unique cryptographic code called a **hash**.  This process forms a chronological "chain." Because every block is mathematically anchored to the one before it, altering historical data is virtually impossible, ensuring **immutability**.

**Key Characteristics**

* **Decentralization:** Data is stored across thousands of nodes, eliminating single points of failure.
* **Transparency:** In public blockchains, the transaction history is visible to all participants.
* **Security:** Cryptography makes the ledger resistant to fraud and unauthorized changes.

**Applications**
While most famous as the underlying technology for cryptocurrencies like **Bitcoin**, blockchain has vast utility. It is used for **Smart Contracts** (self-executing agreements), **Supply Chain Management** (tracking product origins), and securing **Digital Identities**. It effectively shifts trust from institutions to code.
___________________________________________________________________________________________________________________________________________________________
### CLAUDE-2:
**Basics of Blockchain Technology**

Blockchain is a distributed digital ledger technology that records transactions across multiple computers in a secure and transparent manner. Each transaction is stored in a "block," and these blocks are linked together chronologically to form a "chain." This structure makes it extremely difficult to alter past records without detection.

The technology operates on a decentralized network, meaning no single authority controls the data. Instead, all participants in the network maintain copies of the ledger, which are updated simultaneously when new transactions occur. This decentralization enhances security and eliminates the need for intermediaries.

Key features of blockchain include immutability, where recorded data cannot be changed retroactively; transparency, allowing all network participants to view transactions; and cryptographic security, which protects data from unauthorized access.

Blockchain gained prominence through cryptocurrencies like Bitcoin, but its applications extend far beyond digital currencies. Industries use blockchain for supply chain management, healthcare record keeping, smart contracts, digital identity verification, and voting systems.

The benefits of blockchain include enhanced security, reduced costs by removing intermediaries, faster transaction processing, and increased trust through transparency. However, challenges exist, including high energy consumption, scalability issues, regulatory uncertainty, and the need for widespread adoption.

Understanding blockchain is increasingly important as this transformative technology continues reshaping how we store, share, and verify information across various sectors.
_________________________________________________________________________________________________________________________________________________________________
### COPILOT:
## 🧩 Basics of Blockchain Technology

Blockchain technology is a decentralized digital ledger system designed to securely record and verify transactions across a distributed network of computers. Instead of relying on a central authority, blockchain stores data in **blocks**, each containing information such as transactions, timestamps, and a unique cryptographic hash. Every block is linked to the previous one, forming an immutable **chain** that makes tampering extremely difficult.

A key feature of blockchain is **decentralization**. Copies of the ledger are maintained across multiple nodes in the network, and any new transaction must be validated by a majority of participants. This consensus mechanism ensures transparency, trust, and resistance to fraud or unauthorized changes. Because data is stored in a distributed manner, no single entity can manipulate the information, making blockchain highly secure.

Although blockchain is widely known for powering cryptocurrencies like Bitcoin, its applications extend far beyond digital money. Industries such as supply chain, healthcare, finance, and government use blockchain to ensure data integrity, track assets, and automate processes through smart contracts. Its immutability and transparency make it ideal for environments where trust and verification are essential.

Overall, blockchain represents a transformative technology that enhances security, transparency, and efficiency in digital interactions.
_________________________________________________________________________________________________________________________________________________________________
_________________________________________________________________________________________________________________________________________________________________
## CHAIN OF THOUGHT PROMPTS:
PROMPT: EXPLAIN THE BASICS OF BLOCKCHAIN TECHNOLOGY  IN 200 WORDS, GIVE ME A STEP BY STEP EXPLANATION
_________________________________________________________________________________________________________________________________________________________________
### CHATGPT:
Here is a **clear, step-by-step explanation of the basics of Blockchain Technology** in **about 200 words**, written in a beginner-friendly way:

### Step-by-Step Explanation of Blockchain Technology

**Step 1: What is Blockchain?**
Blockchain is a digital system used to record information securely and transparently. Instead of storing data in one central place, it stores data across a network of computers.

**Step 2: Blocks and Chains**
Data is stored in units called *blocks*. Each block contains transaction data, a timestamp, and a unique code called a *hash*. Blocks are linked together using these hashes, forming a *chain*.

**Step 3: Decentralization**
Unlike traditional databases controlled by a single authority, blockchain is decentralized. Every participant (node) in the network has a copy of the blockchain, making it more secure and reliable.

**Step 4: Transaction Verification**
When a transaction is made, it is verified by multiple nodes using consensus mechanisms such as Proof of Work or Proof of Stake. Only verified transactions are added to the blockchain.

**Step 5: Security and Immutability**
Once data is added to the blockchain, it cannot be changed or deleted. Cryptographic techniques ensure data integrity and protect against tampering.

**Step 6: Applications**
Blockchain is widely used in cryptocurrencies, supply chain management, healthcare, voting systems, and smart contracts due to its transparency and security.
____________________________________________________________________________________________________________________________________________________________________
### GEMINI:
Here is a simplified, step-by-step explanation of how blockchain works.

### 1. The Transaction Request

A user requests a transaction, such as sending cryptocurrency or recording a contract. This request is broadcast to a peer-to-peer network consisting of computers, known as **nodes**.

### 2. Verification

The network of nodes uses algorithms to validate the transaction and the user's status. They ensure the user has the funds or authority to make the change. No central authority (like a bank) is involved; the trust is decentralized.

### 3. Block Creation

Once verified, the transaction is combined with other recent transactions to create a new block of data.

### 4. Hashing and Chaining

The new block is given a unique cryptographic code called a **hash**. It also contains the hash of the previous block. This connects the blocks together in a specific order, forming a "chain."

### 5. The Permanent Record

The new block is added to the existing blockchain in a way that is permanent and unalterable. Because every block is connected to the one before it, changing one block would require changing every subsequent block, which is virtually impossible. The transaction is now complete and recorded on a public ledger.
______________________________________________________________________________________________________________________________________________________________________
### CLAUDE-2:
# Blockchain Technology: A Step-by-Step Explanation

**Step 1: Transaction Initiation**
A user requests a transaction, such as transferring cryptocurrency or recording data. This transaction is created and broadcast to the network.

**Step 2: Broadcasting to Network**
The transaction is transmitted to all computers (called nodes) participating in the blockchain network worldwide.

**Step 3: Verification Process**
Network nodes validate the transaction using predetermined rules and cryptographic algorithms. They check if the sender has sufficient resources and proper authorization.

**Step 4: Creating a Block**
Once verified, the transaction is combined with other approved transactions to form a new block of data. Each block contains transaction details, a timestamp, and a unique code called a hash.

**Step 5: Block Validation**
Nodes compete to solve complex mathematical puzzles to validate the new block. This process, called mining in cryptocurrency systems, ensures security.

**Step 6: Adding to Chain**
After validation, the new block is added to the existing blockchain. It's linked to the previous block through cryptographic hashes, creating an unbreakable chain.

**Step 7: Distribution**
The updated blockchain is distributed across the entire network. Every node receives the same copy, maintaining decentralization and transparency.

**Step 8: Transaction Complete**
The transaction is now permanently recorded and cannot be altered, ensuring security and trust without intermediaries.
_______________________________________________________________________________________________________________________________________________________
### COPILOT:
1. **Definition:**  
Blockchain is a digital ledger that records transactions in a secure, transparent, and tamper-resistant way. It is shared across many computers instead of being stored in one central place.

2. **Blocks:**  
Data (like transactions) is grouped into units called blocks. Each block contains a list of transactions, a timestamp, and a unique code called a hash.

3. **Hashing:**  
A hash is a cryptographic fingerprint of a block. If any data inside the block changes, the hash changes, which helps detect tampering.

4. **Chaining blocks:**  
Each block stores the hash of the previous block, forming a chain. This linking makes it extremely hard to alter past data without changing all following blocks.

5. **Decentralization:**  
The blockchain is stored on many computers (nodes) in a network. Every node has a copy of the entire ledger, increasing transparency and reliability.

6. **Consensus mechanism:**  
Before adding a new block, nodes agree that the transactions are valid using rules (like Proof of Work or Proof of Stake).

7. **Immutability:**  
Once data is added and accepted by the network, it is very difficult to change, ensuring trust.

8. **Applications:**  
Beyond cryptocurrencies, blockchain is used in supply chains, voting systems, identity management, and more.
_______________________________________________________________________________________________________________________________________________________
_______________________________________________________________________________________________________________________________________________________
## ROLE BASED PROMPTING:
PROMPT:YOU ARE A BLOCKCHAIN EXPERT, GIVE ME AN ARTICLE ABOUT BASICS OF BLOCKCHAIN TECHNOLOGY IN 200 WORDS
_______________________________________________________________________________________________________________________________________________________
### CHATGPT:
**Basics of Blockchain Technology**

Blockchain technology is a decentralized digital system used to record transactions securely and transparently. Instead of relying on a central authority, such as a bank or server, blockchain operates on a distributed network of computers called nodes. Each node maintains a copy of the blockchain, ensuring trust through consensus rather than intermediaries.

A blockchain consists of a series of blocks, where each block stores a group of transactions, a timestamp, and a cryptographic hash of the previous block. This hash links the blocks together, forming a chain. Once data is recorded in a block and added to the chain, it becomes extremely difficult to alter, making blockchain tamper-resistant and reliable.

Transactions on a blockchain are validated using consensus mechanisms such as Proof of Work (PoW) or Proof of Stake (PoS). These mechanisms ensure that all participants agree on the validity of transactions before they are permanently recorded. Cryptography plays a key role by securing transaction data and verifying user identities through digital signatures.

Blockchain technology offers several benefits, including transparency, enhanced security, reduced fraud, and improved efficiency. It is widely known for powering cryptocurrencies like Bitcoin and Ethereum, but its applications extend beyond finance. Blockchain is increasingly used in supply chain management, healthcare, voting systems, and digital identity verification. Overall, blockchain provides a trustworthy and innovative approach to managing data in the digital age.
__________________________________________________________________________________________________________________________________________________________
### GEMINI:
## ⛓️ The Foundation: Understanding Blockchain Technology

Blockchain is a revolutionary, decentralized, and distributed digital ledger.

In its simplest form, it's a chain of **blocks**, where each block contains a list of verified **transactions**. Once a block is filled, it's sealed with a cryptographic **hash** (a unique digital fingerprint) and linked to the previous block, creating an immutable and chronological chain. This linkage is what makes the ledger secure and tamper-proof.

The entire ledger is replicated and shared across a network of computers (nodes). This **decentralized** structure means no single entity controls the data, eliminating the need for a central authority like a bank.

Consensus mechanisms, such as **Proof-of-Work (PoW)** or **Proof-of-Stake (PoS)**, ensure that all copies of the ledger are synchronized and agree on the validity of new transactions. While famously underpinning cryptocurrencies like Bitcoin, blockchain’s utility extends to supply chain management, voting, and healthcare, offering unprecedented transparency and security.
__________________________________________________________________________________________________________________________________________________________________
### CLAUDE-2:
# Blockchain Technology: An Expert's Perspective

As a blockchain expert, I can tell you that blockchain represents a paradigm shift in distributed systems architecture. It's a cryptographically secured, append-only data structure that achieves Byzantine fault tolerance through consensus mechanisms.

**Core Architecture**

Blockchain utilizes a peer-to-peer network where each node maintains an identical copy of the ledger. Transactions are bundled into blocks, cryptographically hashed, and linked using Merkle trees. This creates an immutable chain where altering historical data requires recalculating all subsequent block hashes—computationally infeasible in established networks.

**Consensus Mechanisms**

Networks employ various consensus algorithms: Proof of Work (PoW) requires computational puzzle-solving, while Proof of Stake (PoS) validates based on token ownership. These mechanisms prevent double-spending and maintain network integrity without central authority.

**Cryptographic Foundation**

Public-key cryptography enables secure, pseudonymous transactions. Digital signatures authenticate ownership, while hash functions ensure data integrity. This cryptographic layer provides security superior to traditional centralized databases.

**Technical Applications**

Beyond cryptocurrency, blockchain enables smart contracts—self-executing code on platforms like Ethereum. Distributed applications (DApps) leverage blockchain for trustless operations across finance, supply chains, and decentralized identity systems.

**Scalability Challenges**

Current limitations include transaction throughput constraints and storage requirements. Layer-2 solutions and sharding technologies are emerging to address these bottlenecks while maintaining decentralization and security—the fundamental blockchain trilemma.
_______________________________________________________________________________________________________________________________________________________________________
### COPILOT:
## 🧩 Basics of Blockchain Technology (200 Words)

Blockchain technology is a decentralized digital ledger system designed to record transactions securely, transparently, and permanently. Instead of relying on a central authority, blockchain distributes identical copies of its ledger across a network of computers, known as nodes. This decentralization increases trust because no single entity controls the data.

A blockchain is made up of blocks, each containing a list of transactions, a timestamp, and a unique cryptographic hash. Every block also stores the hash of the previous block, creating a linked chain. If someone attempts to alter data in a block, its hash changes, breaking the chain and alerting the network. This structure makes blockchain highly tamper‑resistant.

Before a new block is added, participants must validate transactions through a consensus mechanism such as Proof of Work or Proof of Stake. This ensures accuracy and prevents fraud without needing intermediaries.

Although blockchain is widely associated with cryptocurrencies like Bitcoin, its applications extend far beyond digital money. Industries such as supply chain, healthcare, finance, and government use blockchain to enhance transparency, track assets, and automate processes through smart contracts. Overall, blockchain provides a secure, efficient, and trustworthy way to manage digital information in a rapidly evolving technological world.
________________________________________________________________________________________________________________________________________________________________________
________________________________________________________________________________________________________________________________________________________________________

## RESULT:
Considering the above prompts and outputs, ChatGPT provides the best summary in terms of accuracy,Coherance, Simplicity, Speed, User experience.
