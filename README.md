# Skillbook

A map to record the source, usage and useful pairings of the Codex skills I use.

## Agent Instructions

- [AGENTS.md repository](https://github.com/sago-cream/agents.md) · [AGENTS.md](https://github.com/sago-cream/agents.md/blob/main/AGENTS.md): So 5.6 Sol behaves.

## skills

### Easier Communication with Agents

- [$chill](https://github.com/sago-cream/skills/tree/main/chill): Stops agents from documenting problems that never reached upstream.
- [$bro](https://github.com/cursor/plugins/tree/main/pstack/skills/bro): Let agent restate the last message concisely and clearly.
- [$html-drop](https://github.com/sago-cream/skills/tree/main/html-drop): Creates a HTML artifact for complicated concepts, pair with `$forward-port` to view on mobile easily.
- [$forward-port](https://github.com/sago-cream/skills/tree/main/forward-port): Forward port through a Cloudflare Quick Tunnel, so we can work on frontend stuff when pooping.

### Sharing Prototypes

- [$sago-share](https://github.com/sago-cream/skills/tree/main/sago-share): Publishes a local HTML file or static prototype to `share.hsichen.dev`.

### Better Planning

- [$grill-with-docs](https://github.com/mattpocock/skills/tree/main/skills/engineering/grill-with-docs): Help you decide all the details before implementing while maintaining ADRs and glossary.
- [$grilling](https://github.com/mattpocock/skills/tree/main/skills/productivity/grilling): Called by `$grill-with-docs`.

### Better Design

- [$design](https://github.com/sago-cream/skills/tree/main/design): Decide which skill(s) below do we need and call them, no mental load at all, yay.
- [$emil-design-eng](https://github.com/emilkowalski/skills/tree/main/skills/emil-design-eng): Guides UI motion, component behavior, and interaction polish using Emil Kowalski's design-engineering principles.
- [$animation-vocabulary](https://github.com/emilkowalski/skills/tree/main/skills/animation-vocabulary): Finds the precise name for a motion effect described in everyday language.
- [$review-animations](https://github.com/emilkowalski/skills/tree/main/skills/review-animations): Reviews animation and motion code against a strict craft and performance bar.
- [$make-interfaces-feel-better](https://github.com/jakubkrehel/make-interfaces-feel-better/tree/main/skills/make-interfaces-feel-better): Covers typography, surfaces, alignment, hit areas, and common interface-polish details.
- [$unslop-css](https://github.com/sago-cream/skills/tree/main/unslop-css): Keeps styling changes on project tokens and a 4px grid, then checks the cascade for unintended overrides.
- [$font-cut](https://github.com/sago-cream/skills/tree/main/font-cut): Proposes a cleaner type system so Sol doesn't add 20 variants to your product :)

### Better Codebase Architecture

- [$codebase-design](https://github.com/mattpocock/skills/tree/main/skills/engineering/codebase-design): Provides a shared vocabulary for designing deep modules, narrow interfaces, and useful seams.
- [$domain-modeling](https://github.com/mattpocock/skills/tree/main/skills/engineering/domain-modeling): Sharpens project terminology and records it in context documents or ADRs.
- [$improve-codebase-architecture](https://github.com/mattpocock/skills/tree/main/skills/engineering/improve-codebase-architecture): Finds module-deepening opportunities, presents them visually, and grills the selected change.
- [$improve-codebase-layout](https://github.com/sago-cream/skills/tree/main/improve-codebase-layout): Rearranges files and folders for newcomer navigation without redesigning modules.

### Easier Credential Setup
- [$wizard](https://github.com/mattpocock/skills/tree/main/skills/engineering/wizard): Generates an interactive Bash guide for setup steps that only a person can perform.

## Quicker Git Workflow

- [$pr](https://github.com/sago-cream/human-out-of-loop/tree/main/skills/pr): Reviews committed changes and publishes a maintainer-ready draft pull request.
- [$solve-issue](https://github.com/sago-cream/human-out-of-loop/tree/main/skills/solve-issue): Implements a GitHub issue and carries it through the `$pr` publication workflow.
- [$resolving-merge-conflicts](https://github.com/mattpocock/skills/tree/main/skills/engineering/resolving-merge-conflicts): Resolves an in-progress merge or rebase conflict while preserving intent from both sides.
