# no-cope

A Claude skill that gives you honest feedback instead of validation.

Install it and Claude stops softening the truth. Ask for feedback on anything — your copy, your fitness plan, your resume, your dating profile, your pitch deck — and you get a real answer.

---

## Install

```bash
npx skills add Jakerc992/no-cope
```

That's it. Works with Claude Code, Cursor, Codex, Gemini CLI, and most other coding agents.

For **claude.ai** (web/mobile): download the `.skill` file from [Releases](../../releases) and install it under Settings → Skills.

---

## What it does

Activates automatically whenever you ask for feedback, a review, or an opinion. No special trigger word needed.

Covers: copywriting, resumes, dating profiles, fitness plans, business plans, pitch decks, financial plans, design, social media content, hiring decisions, product ideas, and more.

**What you get:**
- A verdict up front, not buried at the end
- The 2–3 highest-impact problems, named specifically
- Honest assessment of what's working (only if something actually is)
- Concrete direction on what to fix
- The thing most people skip saying

**What you don't get:**
- "Great question!"
- Compliments used as cushioning
- Hedging language
- A morale boost that contradicts the critique

---

## Example

**You:** here's my landing page headline: "The Future of Productivity is Here"

**Claude (no-cope):** The headline says nothing. "Future of productivity" is a phrase every SaaS company has used since 2015 — it gives the reader zero reason to keep reading. It's not a promise, it's a category label.

The core problem is it's positioning-first instead of outcome-first. Your reader doesn't care about the category. They care about what changes for them.

What to do: lead with the specific result your product delivers. If someone uses this and their Tuesday looks different, describe that Tuesday.

The hard truth: a generic headline signals a generic product. Even if yours isn't, that's the first impression you're making.

---

## Manual install (without npx)

```
~/.claude/skills/
└── no-cope/
    └── SKILL.md
```

Clone or copy the `no-cope/` folder into your agent's skills directory.

---

## License

MIT
