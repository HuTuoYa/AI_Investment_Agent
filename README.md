# AI Investment Agent

AI Investment Agent is a lightweight research workspace for tracking AI-related investment signals. It is designed to collect monitoring prompts, watchlists, source lists, generated reports, and decision logs in one place so that AI infrastructure, model, semiconductor, cloud, and application-layer developments can be reviewed consistently over time.

## Project Purpose

This project helps investors and researchers:

- Monitor major AI industry events and their possible investment implications.
- Track core companies, ETFs, and A-share mappings related to the AI value chain.
- Follow AI capital expenditure, cloud demand, GPU supply, model progress, and commercialization signals.
- Produce daily alerts, weekly AI industry summaries, and event-driven investment notes.
- Keep a decision log for assumptions, follow-up actions, and changes in investment view.

The repository is meant to be used as a structured knowledge base and repeatable workflow for AI investment monitoring, not as automated financial advice.

## Repository Structure

- `prompts/` - Reusable prompts for daily monitoring, weekly reports, and major event alerts.
- `watchlist/` - Companies, ETFs, indicators, and market mappings to follow.
- `sources/` - Official and media source lists used for monitoring.
- `reports/` - Generated daily, weekly, and alert reports.
- `logs/` - Decision records, assumptions, and follow-up items.

## Typical Workflow

1. Update the watchlists and source lists when the AI investment universe changes.
2. Run the relevant prompt from `prompts/` for daily, weekly, or event-driven monitoring.
3. Save outputs into the matching folder under `reports/`.
4. Record important conclusions, open questions, and next actions in `logs/decision_log.md`.

## Disclaimer

This repository is for research and monitoring purposes only. Any investment decision should be based on independent judgment, additional due diligence, and personal risk tolerance.
