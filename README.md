# Parmarbrook Strategy System

A strategic analysis toolkit built for [Parmarbrook Limited](https://parmarbrook.co.uk) — designed to evaluate markets, sectors, projects, and business decisions using a structured AI skill pipeline.

## What It Does

Runs a multi-stage analysis pipeline that takes a business opportunity from raw context through to a final strategic recommendation:

1. **Context Primer** — Captures company context, constraints, and objectives
2. **Market Analysis** — Evaluates industry structure, trends, and growth drivers
3. **Competitive Analysis** — Maps competitors and competitive positioning
4. **Project Opportunity Evaluator** — Scores the opportunity against key criteria
5. **Strategy Operating System** — Synthesises all outputs into a final recommendation with next steps

Additional skills:
- **Decision Framework** — Structured decision-making support
- **Founder Strategy Advisor** — Strategic guidance tailored for founder-led businesses
- **Opportunity Scoring** — Quantitative opportunity assessment

## How It Works

Each skill in the pipeline runs sequentially and feeds into the next. Every skill finishes with:
- **Recommendation** — Clear strategic direction
- **Next Step** — Actionable follow-up

Built to run with [Claude Code](https://docs.anthropic.com/en/docs/claude-code) using the `.claude/skills/` directory structure.

## Project Structure

```
.claude/
  skills/
    context-primer/
    market-analysis/
    competitive-analysis/
    project-opportunity-evaluator/
    strategy-operating-system/
    decision-framework/
    founder-strategy-advisor/
    opportunity-scoring/
CLAUDE.md          # Pipeline configuration
README.md          # This file
```

## Usage

Open this repo in Claude Code. The skills are automatically available. Start with the **Context Primer** and work through the pipeline, or run individual skills as needed.

## License

Private — Parmarbrook Limited.
