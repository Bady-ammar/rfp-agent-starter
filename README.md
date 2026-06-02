# RFP Agent Starter

> **🤖 If you're an AI coding agent that just opened this repo:** read
> `CLAUDE.md` first — it's your job description. Then read the worked example
> in `rfps/2026-annual-conference-riyadh/` to see the shape of a finished
> RFP. There's no setup step; when the person names something to procure,
> interview them, research the specs, and draft their RFP in a new folder.

A small kit for writing **RFPs** (requests for proposals) with an AI agent.
You tell the agent what you need to buy or commission — a service, a product,
a project — and it interviews you for the details, researches the right
specifications and standards, challenges anything vague or unrealistic, and
writes a clear, complete RFP on a consistent template.

It ships as a **working example**: one full RFP for a company's annual
conference in Riyadh, with the supporting market research sitting right
beside it. Read it, then build your own the same way.

## What's inside

```
.
├── CLAUDE.md            ← the agent's job description + house rules
├── template/
│   ├── RFP-TEMPLATE.md  ← the RFP structure every RFP is built on
│   ├── STYLE.md         ← how RFP language must read
│   └── rfp-CLAUDE.md    ← per-RFP notes file, copied into each new RFP folder
└── rfps/
    └── 2026-annual-conference-riyadh/   ← the worked example
        ├── CLAUDE.md     ← decisions specific to that RFP
        ├── RFP.md        ← the finished RFP
        ├── intake.md     ← the interview it was built from
        ├── research/     ← market research with sources
        └── references/   ← supporting files for that RFP
```

**Each RFP lives in its own folder** under `rfps/`. Everything about it — the
document, the intake notes, every research report, every reference file —
stays inside that one folder, so it's easy to share, archive, or delete on
its own.

## How it works

1. **Tell the agent what you're procuring.** A sentence is enough to start.
2. **It interviews you.** Using sensible options to react to (not blank
   questions), it pins down scope, requirements, budget, timeline,
   evaluation criteria, and eligibility — and pushes back when something
   doesn't add up.
3. **It researches the specs.** It looks up the relevant standards and
   benchmarks for what you're buying and saves the evidence (with sources)
   in the RFP's `research/` folder.
4. **It drafts the RFP** on the shared template, in clear, measurable
   language, and refines it with you.

## What you need

- **An AI coding agent** (e.g. Claude Code) to do the work.
- *(Optional)* **Internet** — so the agent can research specs and standards.

That's it. The RFPs themselves are plain text documents you can open, edit,
and share anywhere.

## License

MIT — see `LICENSE`. Use it, fork it, adapt it for your organization.
