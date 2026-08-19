# Austen Tucker

**Forward-deployed AI builder · Applied AI engineer · Agent systems**

I turn messy human workflows into working AI systems: map the job, build the product, evaluate the behavior, add durable state and approval boundaries, and ship an interface people can actually use.

My sweet spot is the territory between **product engineering and agent engineering**: tools, orchestration, evals, human review, accessibility, and the stubborn last 20% that turns a demo into something trustworthy.

## Flagship systems

### Conductor · private, available to demo
A local-first orchestration system for approval-gated agent work.

- Planner → worker → evaluator execution across Codex and Claude
- Immutable plan-hash approvals and action-scoped authorization
- Isolated workspaces, durable SQLite state, interruption recovery, and idempotent imports
- Human acceptance before work reaches Done
- E2E verification, token capture, keyboard coverage, and 200% zoom testing

### 🦊 [Furry Image Studio](https://github.com/Arcadesys/furry-image-studio)
Reusable multimodal tooling for character-preserving image transformation.

- Installable Codex plugin with reusable skills, character profiles, and style profiles
- Character identity kept separate from rendering style
- CI-validated packaging and release consistency checks
- Checksum-backed eval traces, human review, and an optional private MCP evaluation service

### 🧙 [Wizwor](https://github.com/Arcadesys/wizwor)
An agentic Nintendo recommendation experience built with Next.js, TypeScript, and the OpenAI Agents SDK.

- Agent-driven preference discovery backed by deterministic recommendation logic
- Evals for preference extraction, conversation policy, recommendation quality, and UX behavior
- Regression cases promoted from real failures
- Browser E2E coverage and deterministic catalog-generation pipelines

### ✍️ [NovelTools](https://github.com/Arcadesys/NovelTools)
A VS Code extension for long-form writing and publishing.

- Structured manuscript schemas and drag-and-drop editing
- AI context export for Cursor, Copilot, and other assistants
- Automated PDF, EPUB, Markdown, and TXT release builds
- A useful proof that I build software, not just LLM wrappers

### 📚 [Heinlein](https://github.com/Arcadesys/heinlein)
The production publishing system used by FREE PLAY Publishing.

- Markdown → branded PDF, EPUB, DOCX, HTML, and plain text
- Reusable Codex skill and project configuration
- Chapter navigation, live preview, archives, and tested builds

## How I build

- **Agents:** orchestration, tools, guardrails, planner/worker/evaluator patterns
- **Evals:** deterministic checks where possible, rubric judging where necessary, regressions always
- **Human control:** consequential actions get explicit approval boundaries and review
- **Durability:** persistent state, interruption recovery, reproducible artifacts, idempotent workflows
- **Accessibility:** keyboard, high zoom, low-vision, screen-reader, and cognitive accessibility are product requirements
- **Product judgment:** AI should improve the workflow, not merely decorate it

## The workshop

I also build accessibility tools, retro-computing toys, ComputerCraft systems, writing software, image pipelines, music experiments, and assorted strange little machines.

I build for blind and neurodivergent communities, write furry literary fiction, and like playful interfaces with serious engineering underneath them.

[Website](https://thearcades.me) · [LinkedIn](https://www.linkedin.com/in/austen-tucker-0968a914/)
