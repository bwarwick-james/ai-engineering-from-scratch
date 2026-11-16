# My AI Engineering Path
<!-- Managed by the ai-engineering-from-scratch learning skills.
     Repo: https://github.com/rohitg00/ai-engineering-from-scratch -->

## Mission
"Ship an AI product" and "career change," as an AI Product Manager. Build goal: not sure yet, to be decided along the way.

The aim is AI product literacy, not model building: understand how AI features work, fail, cost money, and get measured, and apply product judgment to them.

## Placement
- Date: 2026-11-14
- Score: 4/10 (Math & Statistics 0/2, Classical ML 1/2, Deep Learning 1/2, NLP & Transformers 0/2, Applied AI 2/2)
- Entry point: Phase 11: LLM Engineering (PM route, chosen by the learner over the quiz's Phase 3 entry point)
- Pace: ~2 h/week (~15 weeks for the route)

## Route (tutor: follow this)
This is a curated PM route. In each `Do` phase, teach **only** the lessons listed below, in this order. Lessons not listed are out of scope unless the learner asks for one by name. If a lesson assumes math the learner hasn't seen, explain only that concept inline rather than detouring to Phase 1.

**Phase 11: LLM Engineering — how AI features work (~11 h)**
1. phases/11-llm-engineering/01-prompt-engineering
2. phases/11-llm-engineering/03-structured-outputs
3. phases/11-llm-engineering/04-embeddings
4. phases/11-llm-engineering/05-context-engineering
5. phases/11-llm-engineering/06-rag
6. phases/11-llm-engineering/10-evaluation
7. phases/11-llm-engineering/11-caching-cost
8. phases/11-llm-engineering/12-guardrails
9. phases/11-llm-engineering/13-production-app
10. phases/11-llm-engineering/14-model-context-protocol

**Phase 14: Agent Engineering — agents and product judgment (~14 h)**
11. phases/14-agent-engineering/01-the-agent-loop
12. phases/14-agent-engineering/12-anthropic-workflow-patterns
13. phases/14-agent-engineering/26-failure-modes-agentic
14. phases/14-agent-engineering/27-prompt-injection-defense
15. phases/14-agent-engineering/30-eval-driven-agent-development
16. phases/14-agent-engineering/47-outcomes-before-output
17. phases/14-agent-engineering/48-discover-the-real-workflow
18. phases/14-agent-engineering/49-map-assumptions-and-risk
19. phases/14-agent-engineering/50-choose-the-smallest-testable-slice
20. phases/14-agent-engineering/51-write-specifications-that-preserve-judgment
21. phases/14-agent-engineering/52-design-success-metrics
22. phases/14-agent-engineering/53-prototype-pilot-or-production
23. phases/14-agent-engineering/54-build-the-feedback-ratchet

**Phase 17: Infrastructure & Production — shipping and measuring (~4 h)**
24. phases/17-infrastructure-and-production/13-llm-observability
25. phases/17-infrastructure-and-production/20-shadow-canary-progressive
26. phases/17-infrastructure-and-production/21-ab-testing-llm-features
27. phases/17-infrastructure-and-production/23-sre-for-ai

## Path
| Phase | Name | Status | Est. hours |
|-------|------|--------|------------|
| 0 | Setup & Tooling | Skip | -- |
| 1 | Math Foundations | Skip | -- |
| 2 | ML Fundamentals | Skip | -- |
| 3 | Deep Learning Core | Skip | -- |
| 4 | Computer Vision | Skip | -- |
| 5 | NLP — Foundations to Advanced | Skip | -- |
| 6 | Speech & Audio | Skip | -- |
| 7 | Transformers Deep Dive | Skip | -- |
| 8 | Generative AI | Skip | -- |
| 9 | Reinforcement Learning | Skip | -- |
| 10 | LLMs from Scratch | Skip | -- |
| 11 | LLM Engineering | Do (route lessons only) | 11 |
| 12 | Multimodal AI | Skip | -- |
| 13 | Tools & Protocols | Skip | -- |
| 14 | Agent Engineering | Do (route lessons only) | 14 |
| 15 | Autonomous Systems | Skip | -- |
| 16 | Multi-Agent & Swarms | Skip | -- |
| 17 | Infrastructure & Production | Do (route lessons only) | 4 |
| 18 | Ethics, Safety & Alignment | Skip | -- |
| 19 | Capstone Projects | Skip | -- |

Total: ~30 hours across 27 lessons. Skipped phases can be added later by re-running `start-learning`.

## Progress log
| Date | Lesson | Quiz | Note |
|------|--------|------|------|
| 2026-11-16 | 11/01-prompt-engineering | 3/3 | Strong instincts. Initially used vague adjectives ("precise, concise") instead of testable rules and left input/example unlabeled; picked up delimiters, temp 0 for reproducibility, prefill. Asked why latency matters. Spotted eval-slide tie-breaking issue once explained. |
| 2026-11-16 | 11/03-structured-outputs | 3/3 | Warm-up 2/2. Nailed "schema checks shape, not truth" and spotted the fake "Unknown/$0" row. Needed nudge that range limits (min/max) aren't always enforced by providers and business-sense checks still belong in the app. |
| 2026-11-16 | 11/04-embeddings | 3/3 | Warm-up 2/2. Ranked semantic vs keyword results correctly; explained word-count embedder failure as "doesn't consider synonyms"; knew docs embed ahead of time, queries at search time, edits need re-embedding. Introduced: model switch = full re-embed. |

## Review queue
