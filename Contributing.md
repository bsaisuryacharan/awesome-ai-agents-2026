# Contributing to Awesome AI Agents 2026

First off, thank you. This list only stays useful because people like you take the time to keep it accurate and current.

There are four ways to contribute:

- **Add a new tool** - something missing that belongs here
- **Update an existing entry** - description is wrong or links are broken
- **Remove a dead project** - unmaintained repos that no longer belong
- **Improve the structure** - better categories, clearer descriptions, fixed typos

All contributions go through a pull request. It takes about 5 minutes.

---

## Entry Format

Every entry follows this exact format:

```markdown
- [Tool Name](https://github.com/org/repo) - One sentence describing what the tool does and what makes it distinct.
```

**Rules:**

- Entry starts with `- ` (a markdown list item)
- Tool name is a link in square brackets: `[Tool Name](url)`
- Description follows ` - ` (space, hyphen, space) after the closing parenthesis
- Description is exactly **one sentence**, ending with a period
- No promotional language ("the best", "revolutionary", "game-changing")
- No trailing metadata (stars, language tags) - the maintainers add those during review
- Entries within each category are sorted **alphabetically** by tool name

**Good example:**

```markdown
- [Mem0](https://github.com/mem0ai/mem0) - Memory layer for AI applications with long-term, short-term, and semantic memory extraction.
```

**Bad examples:**

```markdown
# Wrong: uses heading instead of list item
### Mem0
**[GitHub](https://github.com/mem0ai/mem0)** - Memory layer for AI

# Wrong: uses em-dash instead of hyphen
- [Mem0](https://github.com/mem0ai/mem0) — Memory layer for AI applications.

# Wrong: promotional language
- [Mem0](https://github.com/mem0ai/mem0) - The best and most revolutionary memory solution for AI.

# Wrong: multiple sentences
- [Mem0](https://github.com/mem0ai/mem0) - Memory layer for AI applications. It supports long-term memory extraction.
```

---

## Inclusion Criteria

Your tool should meet **all** of the following:

1. **Directly related to AI agents** - not a general LLM tool, not a prompt library, not a generic API wrapper
2. **Actively maintained** - last commit within the past 6 months
3. **Publicly available** - open-source with a GitHub/GitLab repo, or a live hosted product with a public URL
4. **Not a duplicate** - check the list first to make sure it is not already included
5. **Functional** - the tool must actually work, not just be a README with no code

Tools that are **experimental, early-stage, or have few stars** are welcome as long as they meet all five criteria above. We value breadth of coverage.

---

## Category Placement

Place your entry in the **most specific category** that fits. If it spans multiple categories, pick the primary one. The maintainers may move it during review.

Current categories:

- **Orchestration Frameworks** - core agent building frameworks
- **Coding Agents** - tools that write, edit, and debug code
- **Memory and Context** - persistent memory and knowledge graphs
- **Multi-Agent Systems** - multi-agent coordination frameworks
- **Agent Communication Protocols** - MCP, A2A, and tool protocol implementations
- **Browser and Computer Use Agents** - web navigation and UI automation
- **Agent Tooling and Infrastructure** - sandboxes, scrapers, and networking
- **Low and No-Code Builders** - visual and browser-based agent builders
- **Voice and Multimodal Agents** - audio, video, and cross-modal agents
- **Safety Guardrails and Observability** - monitoring, security, and governance
- **Agent Deployment and Hosting** - platforms for running agents in production
- **Agent Evaluation and Benchmarks** - benchmarks and evaluation frameworks
- **Learning Resources** - courses, papers, and guides

---

## Pull Request Process

1. **Fork** this repo
2. **Add** your entry in the correct category, in alphabetical order
3. **Verify** that your link works and your description follows the format above
4. **Submit** a pull request with a clear title like: `Add [Tool Name] to [Category]`

The maintainers will review your PR within a few days. We may suggest edits to the description or move the entry to a different category.

---

## Quality Standards

This list passes `awesome-lint` and automated link checking on every push. Your PR must:

- Pass the awesome-lint check (no em-dashes, no duplicate links, correct formatting)
- Have no broken links
- Follow alphabetical ordering within its category

---

## Code of Conduct

By contributing, you agree to abide by the [Code of Conduct](Code_of_conduct.md). Be respectful, constructive, and collaborative.

---

Thank you for helping make this the most useful AI agent resource on GitHub.
