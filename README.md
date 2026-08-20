# Skillbook

Skillbook is a public map of the Codex skills and plugins I use. It answers "what should I reach for?" without copying upstream instructions or turning installation into another system to maintain.

Each skill lives in its source repository. The groups below describe its job, useful pairings, and the shortest route into the right instructions. Router skills live in [sago-cream/skills](https://github.com/sago-cream/skills) with the other skills I maintain.

## Design and interfaces

- [$design](https://github.com/sago-cream/skills): Routes interface and product design work to the smallest useful set of installed design skills.
- [$animation-vocabulary](https://github.com/emilkowalski/skills/tree/main/skills/animation-vocabulary): Finds the precise name for a motion effect described in everyday language.
- [$emil-design-eng](https://github.com/emilkowalski/skills/tree/main/skills/emil-design-eng): Guides UI motion, component behavior, and interaction polish using Emil Kowalski's design-engineering principles.
- [$font-cut](https://github.com/sago-cream/skills/tree/main/font-cut): Audits typography variants and proposes a smaller type system without flattening meaningful hierarchy.
- [$make-interfaces-feel-better](https://github.com/jakubkrehel/make-interfaces-feel-better/tree/main/skills/make-interfaces-feel-better): Covers typography, surfaces, alignment, hit areas, and common interface-polish details.
- [$review-animations](https://github.com/emilkowalski/skills/tree/main/skills/review-animations): Reviews animation and motion code against a strict craft and performance bar.
- [$unslop-css](https://github.com/sago-cream/skills): Keeps styling changes on project tokens and a 4px grid, then checks the cascade for unintended overrides.

Use `$design` when you do not want to choose. It may pair `$emil-design-eng` with `$make-interfaces-feel-better` for motion plus static polish, add `$font-cut` for a typography-system audit, or add `$unslop-css` when styling code changes. Product research, audits, exploration, cloning, and validation route to the Product Design plugin.

## Codebase design

- [$codebase-design](https://github.com/mattpocock/skills/tree/main/skills/engineering/codebase-design): Provides a shared vocabulary for designing deep modules, narrow interfaces, and useful seams.
- [$domain-modeling](https://github.com/mattpocock/skills/tree/main/skills/engineering/domain-modeling): Sharpens project terminology and records it in context documents or ADRs.
- [$improve-codebase-architecture](https://github.com/mattpocock/skills/tree/main/skills/engineering/improve-codebase-architecture): Finds module-deepening opportunities, presents them visually, and grills the selected change.

These three pair naturally. Domain modeling establishes the words, codebase design establishes the module vocabulary, and architecture improvement applies both to a real repository.

## Planning and decisions

- [$grilling](https://github.com/mattpocock/skills/tree/main/skills/productivity/grilling): Stress-tests a plan as a decision tree before any implementation begins.
- [$grill-with-docs](https://github.com/mattpocock/skills/tree/main/skills/engineering/grill-with-docs): Runs the same decision interview while maintaining ADRs and a glossary.
- [$wizard](https://github.com/mattpocock/skills/tree/main/skills/engineering/wizard): Generates an interactive Bash guide for setup steps that only a person can perform.

Use `$grilling` for conversation-only decisions and `$grill-with-docs` when the outcome should live with the project.

## Writing and communication

- [$bro](https://github.com/dmmulroy/skills/tree/main/skills/bro): Restates the previous message in plain language without jargon.
- [$unslop](https://github.com/MohamedAbdallah-14/unslop/tree/main/skills/unslop): Removes common AI writing patterns and restores a more natural voice.

## Web, browser, and artifacts

- [$html-drop](https://github.com/sago-cream/skills/tree/main/html-drop): Creates a self-contained HTML artifact and manages its local preview workflow.
- [$forward-port](https://github.com/sago-cream/skills/tree/main/forward-port): Exposes an existing local HTTP port through a Cloudflare Quick Tunnel.
- [$pdf](https://github.com/openai/skills/tree/main/skills/.curated/pdf): Reads, creates, renders, and verifies PDFs when layout matters.
- [$playwright](https://github.com/openai/skills/tree/main/skills/.curated/playwright): Automates a real browser for navigation, screenshots, extraction, and UI-flow testing.

Pair `$html-drop` with `$forward-port` for a shareable live preview. Use `$playwright` when the work needs repeatable browser interaction rather than a simple preview.

## Git and GitHub

- [$pr](https://github.com/sago-cream/human-out-of-loop/tree/main/skills/pr): Reviews committed changes and publishes a maintainer-ready draft pull request.
- [$resolving-merge-conflicts](https://github.com/mattpocock/skills/tree/main/skills/engineering/resolving-merge-conflicts): Resolves an in-progress merge or rebase conflict while preserving intent from both sides.
- [$solve-issue](https://github.com/sago-cream/human-out-of-loop/tree/main/skills/solve-issue): Implements a GitHub issue and carries it through the `$pr` publication workflow.

`$solve-issue` composes `$pr`. Invoke `$pr` directly when the implementation is already committed.

## Specialized creation

- [$godot-master](https://github.com/thedivergentai/GD-Agentic-Skills/tree/main/skills/godot-master): Routes professional Godot 4 architecture, gameplay, performance, platform, and multiplayer work through a large reference library.
- [$hatch-pet](https://github.com/openai/skills/tree/main/skills/.curated/hatch-pet): Generates and validates Codex-compatible animated pet spritesheets and packages them with `pet.json`.

## Plugins

Plugins are listed as capabilities, not expanded into every skill they bundle.

- [Browser](https://learn.chatgpt.com/docs/plugins): Controls Codex's in-app browser for local navigation, interaction, screenshots, and testing.
- [Chrome](https://learn.chatgpt.com/docs/plugins): Controls existing Chrome tabs and signed-in browser state when that context matters.
- [Computer Use](https://learn.chatgpt.com/docs/plugins): Controls local macOS applications when no narrower tool fits.
- [Sites](https://learn.chatgpt.com/docs/plugins): Builds and publishes websites through Codex Sites.
- [Visualize](https://learn.chatgpt.com/docs/plugins): Creates interactive charts, diagrams, simulations, maps, and UI previews in conversation.
- [Cloudflare](https://github.com/openai/plugins): Adds Cloudflare Workers, Wrangler, Agents SDK, documentation, and API access.
- [Plugin Management](https://learn.chatgpt.com/docs/plugins): Finds plugins and manages their connections, permissions, and dependencies.
- [Product Design](https://learn.chatgpt.com/docs/plugins): Handles product exploration, UX audits, URL and screenshot implementation, and prototype validation.
- [Documents](https://learn.chatgpt.com/docs/plugins): Creates and edits Word and Google Docs-targeted documents with rendered verification.
- [PDF](https://learn.chatgpt.com/docs/plugins): Reads, creates, renders, and verifies PDF documents.
- [Presentations](https://learn.chatgpt.com/docs/plugins): Creates, edits, renders, and exports PowerPoint and Google Slides-ready decks.
- [Spreadsheets](https://learn.chatgpt.com/docs/plugins): Creates, analyzes, renders, and exports Excel and Google Sheets-ready workbooks.
- [Template Creator](https://learn.chatgpt.com/docs/plugins): Turns existing files, links, messages, and generated artifacts into reusable personal templates.
- [Ponytail](https://github.com/DietrichGebert/ponytail): Pushes coding work toward the smallest solution that meets the request.

## Maintenance

When a skill or plugin is installed, removed, renamed, or replaced:

1. Update its entry and source link here.
2. Revisit its group pairings.
3. Keep upstream instructions upstream.

## License

[MIT](LICENSE)
