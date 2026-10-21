# Example: Software engineering + AI-assisted development

## Known design intent
The learner formerly studied software engineering and used Java, but has been away from technical work for roughly a decade. They want to **rebuild fundamentals** (programming, data structures, algorithms, engineering design), to create Web systems, apps, tools and services addressing discovered internet needs. AI/vibe coding is a powerful collaborator **after** enough fundamentals to evaluate architecture, trace code, discuss design and inspect errors; not a substitute for understanding.

## Proposed competency map and stages
1. **Recovery & diagnosis:** Java literacy, control flow, functions, object model, command line, Git, HTTP, SQL, and problem solving. Gate: independently explain/repair an unfamiliar program.
2. **Modern programming:** core language, types, modularity, debugging, tests, errors, collections; small utility. Gate: maintainable working CLI.
3. **CS foundations:** data structures, algorithmic complexity, recursion, common algorithms, databases, networking, operating-system concepts. Gate: explain trade-offs and implement unseen exercises.
4. **Web/backend/frontend:** HTTP, API contracts, authentication, persistence, JavaScript/TypeScript, security, browser UX, deployment. Gate: tested full-stack service.
5. **Software engineering:** architecture, requirements, domain modeling, version control, CI/CD, observability, reliability, documentation, reviews. Gate: inspect/refactor a nontrivial repository and justify architectural choices.
6. **AI agent collaboration:** prompt/spec/plan, code review, Codex-like agents, automated verification, tool orchestration, MCP/Skills where useful, guarding against hallucinated implementation. Gate: AI builds a feature; learner can explain, test, critique and repair it.
7. **Commercial capstone:** independently scoped real user problem, working product, tests, deployment, feedback and maintenance roadmap.

## Diagnose interactively
- Ask the learner to predict output/bugs of a short Java-like snippet.
- Compare a list and map for a real task, including complexity.
- Sketch API + DB schema for a tiny service.
- Let the learner diagnose a test failure before offering a solution.

## First lesson candidate
`S01-M01-L01` — trace state and control flow of a small program; prove current understanding with a novel debugging task. Adjust after diagnosis.

**Never** treat AI-produced code or the learner's old degree alone as a mastery certificate.
