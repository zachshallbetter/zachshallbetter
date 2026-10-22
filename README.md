# Zach Shallbetter

**I build the systems that make ambitious ideas work in the real world.**

[Website](https://zachshallbetter.com) · [Selected work](https://zachshallbetter.com/work) · [Systems & principles](https://zachshallbetter.com/systems)

I re-enter problems until they hold.

My work moves between foundational questions and practical implementation: understanding what a system actually needs to do, developing a model that can express it, building the machinery, and testing the model against what happens in practice. I've done this across software, interaction design, creative tooling, AI, physical products, and manufacturing for more than twenty years.

The current thread is how to make increasingly capable software systems useful and dependable. That means exploring new models of interaction, giving agents meaningful ways to operate existing tools, and building the contracts, context, and verification that help the results hold up.

## The work

### Rethinking interaction

- **[Fundamental Engine](https://github.com/zachshallbetter/fundamental-engine)** — A renderer-agnostic runtime for relationship-driven interaction. Instead of treating an interface as a fixed arrangement of components, it models elements as participants in a shared field whose relationships shape behavior. The engine also powers parts of my [website](https://zachshallbetter.com).
- **[Foundations of Computational Interaction](https://github.com/zachshallbetter/foundations-of-computational-interaction)** — Foundational work on what interaction is, how it can be represented, and which assumptions current systems inherit.
- **[Polymorphic Decision Protocol](https://github.com/zachshallbetter/polymorphic-decision-protocol)** — Protocol-level exploration of how computational systems can represent and work with decisions.

### Giving agents real tools

- **[Adobe MCP](https://github.com/zachshallbetter/adobe-mcp)** — MCP tooling for working with Adobe applications and real creative-document workflows, including an integration with [Artcraft](https://github.com/ArtCraftAI), an open-source project I contribute to.
- **[Blender MCP in Rust](https://github.com/zachshallbetter/blender-mcp-rs)** — A Rust implementation of Blender MCP with semantic tooling, exploring how an agent can work with the meaning and structure of a complex 3D scene rather than relying only on low-level actions.
- **[MCP-Tools](https://github.com/zachshallbetter/MCP-Tools)** — Browser automation and inspection that goes beyond clicks: WebDriver BiDi, network interception, console and request monitoring, screenshots, accessibility and performance analysis.
- **[Reflect](https://github.com/zachshallbetter/reflect)** — Rust work on reflection and making program structure available for inspection and use.

### Making the development loop trustworthy

- **[Formal Project Bootstrap — agent skills](https://github.com/zachshallbetter/formal-project-bootstrap/tree/main/.agents)** — Purpose-built agent skills and workflows for implementation, auditing, review, and failure detection.
- **[PYDocs](https://github.com/zachshallbetter/pydocs)** — A deterministic documentation-extraction contract that normalizes Python-authored associations into a shared structure usable across language-aware tooling.
- **[Text Diff Tool](https://github.com/zachshallbetter/text-diff-tool)** — Text comparison that looks beyond character changes toward semantic differences, explanations, and agent-friendly analysis.

I think about reliability at both ends of generative work. On the input side, systems need current, structured context; on the output side, they need explicit contracts and verification. Better generation helps, but it doesn't replace the work of defining what counts as correct and gathering evidence that the result meets it. I write about this in [Living Documentation](https://zachshallbetter.com/writing/living-documentation) and [Distance from Gray](https://zachshallbetter.com/writing/distance-from-gray).

## The throughline predates AI agents

Some of my older public projects make the same pattern visible in different domains:

- **[Image Inspector](https://github.com/zachshallbetter/Image-Inspector)** — Preflight analysis for print-and-cut workflows, extracting things like layers, spot colors, fonts, dimensions, and other production-relevant details from design files.
- **[Forma](https://github.com/zachshallbetter/forma)** — A photogrammetry pipeline for reconstructing 3D anatomy from images for medical analysis and custom prosthetic or orthotic workflows.
- **[Stateful Elements](https://github.com/zachshallbetter/Stateful-Elements)** — An earlier exploration of putting state closer to the DOM elements whose behavior it governs.

These aren't all versions of the same technology. They're examples of the same instinct: make hidden structure legible, give it a useful representation, and build a system that can act on it.

## How I work

Research and implementation are a feedback loop, not separate phases. A conceptual model should lead to something testable; implementation should expose where the model is weak. I build the protocol, write the code, examine the failures, and iterate.

I apply that discipline to agent-assisted development too. I create skills for the actual work, define constraints and sources of truth, audit the process, and verify results instead of treating plausible output as proof of completion.

My background also includes product and design leadership, teaching, entrepreneurship, and physical production. I took a hardware company from a Kickstarter campaign to a roughly $500K seed round and an end-to-end just-in-time manufacturing operation. That experience shaped how I approach software: prototypes are useful, but the real test is whether the system can operate under real constraints.

## Explore

- **[Portfolio & selected work](https://zachshallbetter.com/work)** — Products, systems, and experiments.
- **[Systems & principles](https://zachshallbetter.com/systems)** — The models behind the work, including assumptions and limits.
- **[Writing](https://zachshallbetter.com/writing)** — Research and essays on interaction, AI systems, product engineering, and reliability.
