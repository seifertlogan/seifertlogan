# Steve Seifert

AI Engineer transitioning from 12+ years in banking operations, application
support, and fraud systems into AI/ML engineering roles in fintech.

I build AI tools that solve real banking operations problems — not tech
demos, but things designed the way they'd actually need to work in a
regulated financial institution: grounded outputs, audit trails, human-in-
the-loop design, and honest acknowledgment of what production would
require beyond the prototype.

## Background

Banking operations, business analysis, RPA, application support, fraud
systems, and core banking — Kansas City-area fintech professional with deep
domain knowledge in Reg E, Reg CC, BSA/AML compliance, and commercial loan
servicing. Currently building the technical skills to pair that domain
depth with hands-on AI engineering.

## Featured Projects

### [Reg Compliance Assistant](https://github.com/seifertlogan/Reg-Compliance-Assistant)
A RAG chatbot that answers Reg E and Reg CC questions using retrieved
regulation text with section-level citations — not a model's general
knowledge. Runs free and local by default (Ollama), with a one-line swap
to the Claude API for production-quality answers.

**Demonstrates:** retrieval-augmented generation, vector search, section-
aware chunking, grounded/cited generation, pluggable LLM backends.

### [Fraud Alert Extraction](https://github.com/seifertlogan/fraud-alert-extraction)
Extracts structured JSON (transaction type, amount, fraud indicators, SAR
recommendation) from unstructured fraud narratives. Originally built on
OpenAI fine-tuning; rebuilt on Claude few-shot prompting after OpenAI
discontinued self-serve fine-tuning mid-project — a real platform
deprecation, diagnosed and solved, not a hypothetical.

**Demonstrates:** structured extraction, schema design, adapting to a
vendor platform change, real fraud-typology domain knowledge.

### [Loan Servicing Note Classifier](https://github.com/seifertlogan/loan-servicing-note-classifier)
Classifies commercial loan servicing notes into 8 operational categories
(covenant breach, payment dispute, escrow inquiry, etc.) using few-shot
prompting. **100% accuracy on held-out test cases** covering all 8
categories.

**Demonstrates:** multi-class classification, few-shot prompting, balanced
evaluation design, commercial loan servicing domain knowledge.

## What connects these projects

Every project here started from an actual operational pain point I've seen
in banking, not a tutorial. Each README leads with the business problem
before the tech. Each one documents what it would actually take to run
this in production — monitoring, drift detection, audit trails, human
review — because that's the difference between a demo and something a
bank could actually deploy.

## Currently

Actively looking for AI Engineer / AI-adjacent roles in fintech where deep
banking domain knowledge is a differentiator, not a gap to work around.
