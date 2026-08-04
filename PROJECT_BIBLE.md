# PROJECT BIBLE

This document is the single source of truth for the project.

Whenever confused,
read this document before writing code.

---

# Mission

Do NOT build another Enterprise Chatbot.

Build a system that intelligently decides HOW retrieval should happen before asking the LLM to generate an answer.

---

# Core Philosophy

Traditional RAG

Question

↓

Retrieve

↓

Generate

Our Framework

Question

↓

Understand

↓

Plan

↓

Retrieve

↓

Verify

↓

Generate

↓

Evaluate

Always remember this.

---

# The Seven Questions

Every module answers ONE question.

## Module 1

Document Processing

Question

How do I convert enterprise PDFs into searchable knowledge?

Output

Knowledge Base

---

## Module 2

Query Understanding

Question

What exactly is the user asking?

Output

Intent

Complexity

Answer Type

---

## Module 3

Adaptive Retrieval Planner

Question

How should retrieval happen?

Output

Retrieval Plan

---

## Module 4

Retrieval Executor

Question

Which enterprise documents are relevant?

Output

Relevant Context

---

## Module 5

Evidence Verification

Question

Did retrieval collect enough information?

Output

Verified Context

---

## Module 6

Prompt Builder

Question

How should I communicate with the LLM?

Output

Optimized Prompt

---

## Module 7

Evaluation

Question

Did the system perform well?

Output

Metrics

---

# Mental Workflow

Never think

Question

↓

Answer

Always think

Question

↓

Understand

↓

Plan

↓

Retrieve

↓

Verify

↓

Generate

↓

Evaluate

---

# Development Roadmap

Phase 1

Document Processing

Deliverable

Searchable Knowledge Base

Done?

[]

---

Phase 2

Baseline RAG

Deliverable

Working Enterprise Chatbot

Done?

[]

---

Phase 3

Query Understanding

Deliverable

Intent Detection

Complexity Estimation

Done?

[]

---

Phase 4

Adaptive Retrieval Planner

Deliverable

Dynamic Retrieval Planning

Done?

[]

---

Phase 5

Adaptive Retrieval

Deliverable

Hybrid Retrieval

Re-ranking

Done?

[]

---

Phase 6

Evidence Verification

Deliverable

Confidence Estimation

Coverage

Iteration

Done?

[]

---

Phase 7

Prompt Builder

Deliverable

Optimized Prompt

Done?

[]

---

Phase 8

Evaluation

Deliverable

Experimental Results

Done?

[]

---

# Research Contribution

Our novelty is NOT

Enterprise Chatbot

Our novelty IS

Adaptive Retrieval Intelligence Framework

This includes

Query Understanding

↓

Adaptive Planning

↓

Adaptive Retrieval

↓

Evidence Verification

↓

Retrieval Refinement

---

# Whenever You Get Lost

Ask yourself

Am I

Building the Knowledge Base?

Understanding the Query?

Planning Retrieval?

Retrieving?

Verifying?

Generating?

Evaluating?

One of these seven is always your current task.

---

# Coding Rule

Every module should

Take one input.

Produce one output.

Do one job only.

Never mix responsibilities.

---

# Experiment Rule

Every improvement must be compared with

Baseline RAG

Never claim improvement without comparison.

---

# Paper Rule

Every chapter should answer one question.

Introduction

Why is this problem important?

Literature Review

What has already been done?

Methodology

What are we proposing?

Experiments

How was it tested?

Results

Did it work?

Conclusion

What was learned?

---

# Golden Rule

If a feature does not improve

- Retrieval Quality

or

- Latency

or

- Hallucination Reduction

or

- Enterprise Usability

it probably does not belong in this project.

Stay focused.

Research first.

Engineering second.