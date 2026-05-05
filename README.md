# Mind the Product — Agent Skills

Skills for product managers, distributed via the [Agent Skills](https://agentskills.io/) standard.

These are **reusable practices** from the Mind the Product community, packaged so you can drop them into any AI agent — Claude, Cursor, Codex, ChatGPT, Gemini, Cline, Windsurf, Roo, and others — and have a sharper thinking partner on tap.

[![skills.sh](https://skills.sh/b/mindtheproduct/skills)](https://skills.sh/mindtheproduct/skills)

## Install

Install all skills in this repo with one command:

```bash
npx skills add mindtheproduct/skills
```

Or install a single skill:

```bash
npx skills add mindtheproduct/skills/make-the-call
```

The `skills` CLI ([skills.sh](https://skills.sh/)) is open source and works with most major AI coding agents.

## Available skills

### [`make-the-call`](./make-the-call/)

A 3-stage practice for clarifying a hard product decision. Translate stakeholder asks into the actual problems underneath, stress-test those problems, then pick what matters. Ends with a structured snapshot.

**Use when:** you have a real product call to make and need a sharp thinking partner — not a search engine, not a summariser, not a cheerleader.

**Trigger phrases:** `/make-the-call`, "make the call", "I have a decision to make", "help me think through this decision".

[Original web tool →](https://www.mindtheproduct.com/make-the-call)

---

*More skills coming. We're working on practices for prioritisation, stakeholder management, OKR-setting, post-mortems, and more. [Suggest one.](https://github.com/mindtheproduct/skills/issues/new)*

## Why we made this

Product management is mostly judgement under ambiguity. The hard parts aren't framework recall — they're knowing which question to ask next, which lens to apply, when to push back on yourself. AI agents are surprisingly good at that *when* you give them the right structure. Skills are the structure.

We're packaging the practices that experienced product leaders use and making them install-anywhere. Free, open source, no signup, no lock-in.

## Contributing

We welcome PRs that add new skills or sharpen existing ones. A skill is just a folder with a `SKILL.md` and (optionally) a `references/` directory. See the [Agent Skills spec](https://agentskills.io/) and the [`make-the-call`](./make-the-call/) skill as a reference.

Quality bar:

- A single, well-defined practice — not a kitchen sink.
- A clear `when_to_use` so the agent invokes it at the right moment.
- Progressive disclosure: a short main `SKILL.md`, with detail loaded from `references/` only when needed.
- No filler. If the skill could be 200 lines instead of 800, make it 200.

## License

MIT. See [LICENSE](./LICENSE).

## About Mind the Product

[Mind the Product](https://www.mindtheproduct.com/) is the world's largest product management community — conferences, content, and a community of 500,000+ product people learning together.
