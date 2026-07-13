# Steve Seifert

Business Analyst with 12+ years in banking operations, application support, and fraud systems, now focused on scoping and evaluating how AI actually fits into regulated financial institution technology — where it adds real value, and where it doesn't.

I build hands-on AI projects to understand these systems from the inside, not to become a software engineer — but because a BA who has actually built a RAG pipeline or a classification tool writes better requirements, asks sharper vendor questions, and can tell the difference between a demo and something production-ready. Every project here is designed the way it would actually need to work in a regulated financial institution: grounded outputs, audit trails, human-in-the-loop checkpoints, and honest acknowledgment of what production requires beyond the prototype.

## Background

Banking operations, business analysis, RPA, application support, fraud systems, and core banking — Kansas City-area fintech professional with deep domain knowledge in Reg E, Reg CC, BSA/AML compliance, and commercial loan servicing. Currently building hands-on technical fluency in AI systems so I can scope, evaluate, and write requirements for AI initiatives from a position of understanding, not just translation.

## Featured Projects

### [Reg Compliance Assistant](https://github.com/seifertlogan/Reg-Compliance-Assistant)
A RAG chatbot that answers Reg E and Reg CC questions using retrieved regulation text with section-level citations — not a model's general knowledge. Runs free and local by default (Ollama), with a one-line swap to the Claude API for production-quality answers.

**Why it matters for the business:** shows what "grounded, citable answers" requires under the hood — the kind of requirement a BA needs to write and defend when scoping a compliance-facing AI tool. Built to understand retrieval-augmented generation, vector search, and section-aware chunking well enough to evaluate a vendor's claims about them.

### [Fraud Alert Extraction](https://github.com/seifertlogan/fraud-alert-extraction)
Extracts structured JSON (transaction type, amount, fraud indicators, SAR recommendation) from unstructured fraud narratives. Originally built on OpenAI fine-tuning; rebuilt on Claude few-shot prompting after OpenAI discontinued self-serve fine-tuning mid-project — a real platform deprecation, diagnosed and solved, not a hypothetical.

**Why it matters for the business:** the kind of vendor-dependency risk a BA should be flagging in any build-vs-buy conversation. Living through a platform deprecation mid-build is exactly the kind of risk a requirements document should anticipate.

### [Loan Servicing Note Classifier](https://github.com/seifertlogan/loan-servicing-note-classifier)
Classifies commercial loan servicing notes into 8 operational categories (covenant breach, payment dispute, escrow inquiry, etc.) using few-shot prompting. 100% accuracy on held-out test cases covering all 8 categories.

**Why it matters for the business:** demonstrates how to define success criteria and evaluation design for a classification tool before it touches operational workflows — the step that's easy to skip and expensive to skip.

## What connects these projects

Every project here started from an actual operational pain point I've seen in banking, not a tutorial. Each README leads with the business problem before the tech. Each one documents what it would actually take to run in production — monitoring, drift detection, audit trails, human review — because that's the gap between a demo and something a bank's risk and compliance functions would actually sign off on deploying.

## Currently

Actively looking for Business Analyst / AI-adjacent roles in fintech where deep banking domain knowledge and hands-on technical fluency in AI systems combine to scope initiatives correctly the first time.
