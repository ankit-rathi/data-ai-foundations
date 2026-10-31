# Context Handover — Data & AI Foundations

**Project:** From Data to Decisions  
**Flagship:** Data & AI Foundations  
**Last major editorial revision:** 31 October 2026

This document is the handover point for future writing, curriculum design, research and course development.

## 1. Current direction

The project is a connected, first-principles book and course about Data, AI and decision-making.

Its central promise is to help readers understand systems rather than memorise tools.

The work must serve three audiences:
- Data & AI enthusiasts.
- Experienced Data & AI practitioners.
- Data & AI leaders.

The audiences share one intellectual foundation and use different learning tracks. Do not split the work into three books.

## 2. Current central thesis

Data and AI extend our ability to represent the world, derive knowledge from evidence and influence outcomes. Understanding the principles connecting these capabilities helps us build better systems, evaluate new technologies and make more informed decisions.

Central framework:

**Reality → Representation → Data & Information → Evidence → Intelligence → Decision → Action → Outcome → Learning**

This is a feedback system, not a linear pipeline.

## 3. Canonical syllabus

The current syllabus has:
- Six parts.
- 39 chapters.
- One introduction.
- One conclusion.
- 41 course sessions in total.

The canonical chapter titles and sequence are in `TABLE_OF_CONTENTS.md`.

Do not change the sequence or add chapters casually. First determine whether a gap can be handled through:
- Better chapter scope.
- A subsection.
- A worked example.
- A technical sidebar.
- A practical exercise.
- An appendix or supplementary resource.

Only propose a new chapter if the existing structure cannot accommodate a genuinely distinct fundamental question.

## 4. What changed after the three-persona review

### Experienced professional

The book needs more than conceptual breadth. It must demonstrate technical depth through mechanisms, architecture, failure modes and production implications.

Priority areas:
- Data modelling and contracts.
- Data integration and schema evolution.
- Streaming and event semantics.
- Distributed reliability and delivery guarantees.
- Platform operations and observability.
- ML evaluation, deployment and monitoring.
- RAG retrieval and grounding evaluation.
- Agent state, planning, permissions and failure recovery.

### Data & AI leader

The book must connect technology to organisational choices and outcomes.

Priority areas:
- Business objectives and value measurement.
- Ownership and decision rights.
- Centralised versus federated operating models.
- Build versus buy.
- Total cost and opportunity cost.
- Risk, accountability and governance.
- Adoption, skills and change management.
- Human versus machine authority.

These subjects should be integrated into relevant chapters rather than turning the book into a general management textbook.

### Enthusiast

The book must remain approachable without becoming superficial.

Priority areas:
- Plain-language introductions.
- Everyday examples and visual explanations.
- Explicit prerequisite signposting.
- Small practical experiments.
- Clear learning milestones.
- Optional deeper technical sections.

## 5. Three-layer chapter model

Every chapter should support:

1. **Understand:** intuitive explanation and mental model.
2. **Explain:** technical mechanism and worked example.
3. **Evaluate:** assumptions, limitations, failure modes, trade-offs and consequences.

Do not force equal length across these layers.

## 6. Required chapter components

A normal chapter should include:

1. Fundamental question.
2. Concrete problem.
3. Intuitive explanation.
4. Mechanism.
5. Anchor example.
6. Failure or boundary example.
7. Assumptions and limitations.
8. Trade-offs and alternatives.
9. Connection to earlier and later concepts.
10. Practical or reflective challenge.
11. Takeaway.
12. Next question.

Add a technical failure scenario where relevant.

Include a recurring section or equivalent treatment of **Why This Matters Beyond Technology** when the chapter has organisational, financial, human or decision-making implications.

## 7. Technical coverage expectations

Use the coverage map as a control document. At minimum, ensure the syllabus and chapters collectively address:

### Data engineering
- Data modelling.
- Schemas and contracts.
- ETL/ELT, APIs and CDC.
- Master/reference data.
- Transactions and concurrency.
- Batch and streaming.
- Event time and processing time.
- Partitioning, replication and consistency.
- Idempotency and delivery semantics.
- Warehouses, lakes and lakehouses.
- Orchestration, observability, recovery and cost.
- Quality, lineage, metadata, governance and ownership.

### Machine learning
- Features and labels.
- Training, validation and test separation.
- Leakage and overfitting.
- Generalisation and calibration.
- Evaluation and thresholds.
- Serving and deployment.
- Monitoring, drift and retraining.

### Generative AI
- Tokens and context windows.
- Embeddings and retrieval.
- Vector search and RAG.
- Grounding and hallucinations.
- Fine-tuning and inference.
- Evaluation methods.
- Application integration.
- Latency, cost, privacy and security.

### Agentic AI
- Tool use and permissions.
- State and memory.
- Planning and execution.
- Human approval and autonomy.
- Failure recovery and observability.
- Prompt injection and unsafe tool execution.

### Organisational context
- Business value.
- Ownership and decision rights.
- Operating models.
- Build versus buy.
- Total cost of ownership.
- Adoption and change.
- Accountability and risk.

Do not turn this list into a checklist of terms to mention. Every item included in the main book must be explained at a useful level.

## 8. Examples and case continuity

Use a recurring banking payment journey for continuity.

Supplement it with:
- Retail and e-commerce.
- Healthcare and public services.
- Everyday digital products.
- Other physical or organisational systems when they reveal a principle.

For each chapter, select:
- One anchor example.
- One boundary or failure example.
- One transfer challenge.

Avoid making every chapter banking-specific.

## 9. Course architecture

The course contains 41 sessions.

Each session should normally include:
- Hook and fundamental question.
- Intuition and example.
- Mechanism and sketch.
- Failure and trade-offs.
- Practical challenge.
- Recap and next question.

Suggested learning tracks:

**Enthusiast**
- Explain a concept.
- Draw a model.
- Explore a small example.
- Connect it to another domain.

**Practitioner**
- Implement a mechanism.
- Test an assumption.
- Measure behaviour.
- Introduce a failure.
- Diagnose the result.

**Leader**
- Evaluate alternatives.
- Assess cost and risk.
- Identify decision rights.
- Define value and success measures.
- Consider organisational consequences.

The course must be more than narrated book chapters.

## 10. Practical learning environment

Prefer accessible tools:
- Google Colab.
- GitHub.
- SQLite or MySQL.
- DuckDB.
- Synthetic datasets.
- Open-source AI models such as Ollama where hardware permits.
- Simple diagrams and simulations.

A small dataset can evolve throughout the course:
1. Represent a real-world situation.
2. Store and query the data.
3. Validate quality.
4. Analyse patterns.
5. Build and evaluate a model.
6. Create a grounded AI application.
7. Evaluate an automated decision workflow.

The tools are replaceable. The learning objectives are not.

## 11. Pilot-first strategy

Before writing all chapters in full, pilot:

1. Session 0 — Introduction.
2. Chapter 2 — Representation.
3. Chapter 17 — Distributed reliability.
4. Chapter 29 — Grounding and evaluating AI outputs.
5. Chapter 34 — Trust, risk and accountability.

Chapter 34 is particularly useful for testing the leadership layer.

Each pilot must include:
- Complete chapter.
- Concept sketch.
- System or case sketch.
- Session transcript.
- Enthusiast activity.
- Practitioner activity.
- Leadership exercise.
- Assessment questions.
- Independent review.

Test with real readers from all three audiences where possible. Persona simulations are useful for critique but are not a substitute for learner feedback.

## 12. Validation questions

Ask pilot readers:

- What can you explain now that you could not explain before?
- Can you describe the mechanism without relying on the analogy?
- Can you identify a limitation or failure mode?
- Can you apply the principle to a different domain?
- Did the chapter change a technical or organisational decision you would make?
- Which sections were too basic, too difficult or unnecessary?
- Would you continue to the next chapter?
- Would you recommend the book or course to someone like you?

## 13. Editorial safeguards

Avoid:
- Expanding the syllabus to chase every new technology.
- Repeating definitions across chapters.
- Confusing breadth with depth.
- Using analogies in place of mechanisms.
- Treating model output as evidence.
- Treating prediction as a decision.
- Treating a successful prototype as a production system.
- Assuming feedback automatically improves a system.
- Adding generic leadership commentary without technical grounding.
- Requiring expensive tools for core learning.

## 14. Immediate next steps

1. Update the repository's foundational documents using this revision.
2. Update the chapter template to enforce the three learning layers and failure analysis.
3. Create a coverage map linking each required topic to a chapter and a depth expectation.
4. Create a concept-boundary register.
5. Create an example map showing anchor, boundary and transfer examples.
6. Update the session roadmap and learning assets.
7. Develop the five pilot sessions.
8. Gather independent feedback and revise before scaling production.

## 15. Final editorial test

The book should help a reader approach an unfamiliar Data or AI system and ask:

- What is the real-world problem?
- How is reality being represented?
- What assumptions are being made?
- How does the mechanism work?
- What evidence supports the result?
- What can fail?
- What decision does it enable?
- Who is accountable?
- What does it cost?
- How will we measure the outcome?
- What should we learn next?

The objective is to develop people who can reason about systems, not merely operate tools.
