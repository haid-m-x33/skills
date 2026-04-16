---
name: explain-in-depth
description: Use when the user asks for an explanation of a term, concept, technology, or topic. Best for in-depth explanations with a cybersecurity-first bias, grounded in authoritative sources and structured into Plain Understanding and Root Understanding.
---

# Explain In Depth

Use this skill when the user asks for an explanation of a term, concept, framework, protocol, attack, defense, technology, or topic.

This is a general-purpose explanation skill with a cybersecurity-first bias. It is especially useful for cybersecurity terminology and CompTIA Security+ preparation, but it can also be used for non-cyber topics when the user wants a structured, deep explanation.

Do not require the exact phrase `Explain to me`. Activate this skill for any clear explanation intent.

Keep the skill instructions and your internal reasoning in English.

## Source Policy

Before answering, do a brief web search to ground the explanation.

Prefer authoritative sources that match the topic. For cybersecurity topics, prefer these first when relevant:

- CompTIA Security+ pages and objectives
- NIST CSRC and NIST publications
- NIST NVD
- MITRE ATT&CK
- MITRE CWE
- OWASP
- CISA

Wikipedia may be used as a supporting source, but it should not be the main source when stronger authoritative sources are available.

Use 1-3 strong sources when possible. Prefer source quality over source count.

If the topic is ambiguous or overloaded, state which meaning you are explaining.

## Workflow

1. Identify the exact term or topic the user wants explained.
2. Disambiguate the meaning if the term has multiple common uses.
3. Perform a brief web search before answering.
4. Pick the most relevant authoritative sources for the topic.
5. Build the answer using the two explanation principles below.
6. Include links to the sources used.
7. Add a short `Security+ Relevance` section when the topic is relevant to cybersecurity or CompTIA Security+.

## Explanation Principles

Every response must include both sections below in this exact order.

### Plain Understanding

This section should be more technical and more concrete.

It must include:

- Term
- Plain meaning
- Why it exists
- Simple example
- What it is not

### Root Understanding

This section should be broader and less strictly technical. It should explain why the concept matters in a wider, more intuitive way.

It must answer these five questions:

1. What problem is this trying to solve?
2. What bad thing happens without it?
3. What is the simplest real example?
4. What is it often confused with?
5. How would I explain it to a normal person in 2 sentences?

## Output Requirements

Use this structure:

## Topic

State what is being explained.

## Plain Understanding

- Term: ...
- Plain meaning: ...
- Why it exists: ...
- Simple example: ...
- What it is not: ...

## Root Understanding

1. What problem is this trying to solve?
2. What bad thing happens without it?
3. What is the simplest real example?
4. What is it often confused with?
5. How would I explain it to a normal person in 2 sentences?

## Security+ Relevance

Include this section only when the topic is relevant to cybersecurity or CompTIA Security+.

## Sources

List the links used for the explanation.

## Quality Bar

- Write in clear English.
- Prefer plain language over jargon.
- If technical terms are necessary, define them briefly.
- Be accurate first, then simple.
- Prefer practical examples over abstract descriptions.
- For cybersecurity topics, connect the explanation to real defensive thinking and exam relevance when useful.
- If authoritative sources use context-specific definitions, say that clearly.
