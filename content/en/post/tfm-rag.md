---
date: 2024-09-01T10:00:00+02:00
featured_image: "/images/rag-tfm.jpg"
title: "Intelligent RAG search system for MBA documentation"
summary: "Master's thesis: a RAG system for finding and synthesising knowledge across business-management documents."
tags: ["RAG", "LLM", "NLP", "Python", "Semantic search"]
---

**Goal.** Design an intelligent search system that lets users query a collection of business-management documents in natural language and receive answers grounded in the available sources.

**Proposed solution.** The project defines a Retrieval-Augmented Generation (RAG) architecture. Documents are processed into semantic chunks and indexed through vector representations. For every question, the system retrieves the most relevant context before a language model generates an evidence-backed answer.

**Design criteria.** The proposal focuses on answer traceability, retrieval quality, context management and evaluating practical use cases: finding concepts, comparing management frameworks and synthesising information spread across several sources.

**Intended value.** Compared with conventional keyword search, the system aims to reduce the time required to find relevant knowledge while preserving the link to the original documentation. This is my Master's thesis for the Master's Degree in Data Science at Universitat de València. This is a draft description and will be updated with implementation details and final results.
