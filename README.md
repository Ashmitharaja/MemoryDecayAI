# 🧠 Memory Decay Laws for Autonomous AI Agents

<div align="center">

## Learning **What to Forget** Instead of Remembering Everything

A biologically inspired long-term memory architecture for autonomous LLM agents.

---

![Python](https://img.shields.io/badge/Python-3.11-blue)

![Research](https://img.shields.io/badge/Research-AI%20Memory-red)

![Status](https://img.shields.io/badge/Status-Prototype-success)

![License](https://img.shields.io/badge/License-MIT-green)

</div>

---

# Motivation

Current Large Language Model agents suffer from two opposite problems.

✔ Remember everything forever

or

✔ Forget everything abruptly.

Humans do neither.

Human memory gradually decays according to cognitive laws.

This project investigates

> **Can AI agents learn what to forget?**

instead of storing unlimited memories forever.

---

# Research Question

Can adaptive memory decay improve

- Recall accuracy

- Storage efficiency

- Memory scalability

- Hallucination reduction

for long-term autonomous AI agents?

---

# Proposed Architecture

```
Incoming Observation
          │
          ▼
 Importance Scoring
          │
          ▼
 Long-term Memory Store
          │
          ▼
 Time-based Decay
          │
          ▼
 Memory Compression
          │
          ▼
 Retrieval Engine
          │
          ▼
 Autonomous Agent
```

---

# Features

✔ Long-Term Memory Store

✔ Importance-aware Encoding

✔ Exponential Forgetting Curves

✔ Memory Compression

✔ Retrieval Simulation

✔ Multi-week Evaluation

✔ Hallucination Estimation

---

# Mathematical Model

Memory strength follows

```
M(t)=I⋅e−λt
```

where

```
I = Importance

λ = Decay Constant

t = Time
```

Future work replaces the fixed λ with

```
λ=f(context,usage,reward)
```

allowing agents to **learn their own forgetting policy.**

---

# Experimental Results

## Memory Initialization

All memories begin with

```
Strength = 1.0
```

while maintaining different importance scores.

---

## Memory Decay

![Memory Decay](images/memory_decay.png)

Observation

Higher importance memories survive longer while less important memories disappear rapidly.

---

## Recall Accuracy

![Recall](images/recall_accuracy.png)

Observation

Recall decreases sharply after two weeks because of aggressive exponential decay.

---

## Storage Efficiency

![Storage](images/storage_efficiency.png)

Observation

The memory database eventually becomes empty.

Although storage cost approaches zero,

knowledge retention also becomes zero.

---

## Hallucination Reduction

![Hallucination](images/hallucination_reduction.png)

Observation

Removing obsolete memories completely eliminates retrieval hallucinations.

However,

the agent simultaneously loses all useful knowledge.

---

# Experimental Insights

The current implementation demonstrates an important trade-off

```
Higher Forgetting

↓

Lower Storage

↓

Lower Hallucinations

↓

Lower Recall
```

This validates the need for

Adaptive Memory Decay.

---

# Future Work

Instead of

```
Fixed Exponential Decay
```

we propose

```
Learnable Memory Decay Laws
```

using

- Reinforcement Learning

- Meta-learning

- Retrieval Feedback

- Usage Frequency

- Context Similarity

- Emotional Importance

- User Feedback

The agent should learn

**when**

to remember,

**when**

to compress,

and

**when**

to forget.

---

# Applications

Large Language Models

Autonomous AI Agents

Personal AI Assistants

Healthcare AI

Robotics

Long-term Conversational Systems

AI Operating Systems

Scientific Knowledge Bases

Digital Twins

Human-AI Memory Systems

---

# Repository Structure

```
MemoryDecay/

│

├── notebook.ipynb

├── memory.py

├── evaluation.py

├── results/

│     recall.csv

│     storage.csv

│

├── images/

│     memory_decay.png

│     recall_accuracy.png

│     storage_efficiency.png

│     hallucination_reduction.png

│

└── README.md
```

---

# Future Publication

This repository is an initial research prototype for

> **Memory Decay Laws for Autonomous AI Agents**

towards

NeurIPS

ICLR

ICML

AAAI

and Cognitive AI research.

---

# Citation

```
@misc{MemoryDecay2026,

title={Memory Decay Laws for Autonomous AI Agents},

year={2026}

}
```

---

## ⭐ If you find this work useful,

please consider starring the repository.
