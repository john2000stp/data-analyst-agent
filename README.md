# data-analyst-agent

AI agent that analyzes datasets, generates insights, creates visualizations, and answers data questions using Python and SQL.

## Run

```bash
npx @open-gitagent/gitagent run -r https://github.com/john2000stp/data-analyst-agent
```

## What It Can Do

- **Data Analysis** — load, clean, explore, and summarize any dataset
- **SQL Queries** — write and run queries with aggregations, joins, window functions, and CTEs
- **Visualization** — create publication-ready charts (bar, line, scatter, heatmap, histogram)
- **Statistical Analysis** — distributions, correlations, hypothesis testing, trend detection

## Structure

```
data-analyst-agent/
├── agent.yaml
├── SOUL.md
├── RULES.md
├── skills/
│   ├── data-analysis/
│   │   └── SKILL.md
│   ├── sql-query/
│   │   └── SKILL.md
│   └── visualization/
│       └── SKILL.md
├── tools/
│   ├── python-exec.yaml
│   └── csv-reader.yaml
└── knowledge/
```

## Built with

[gitagent](https://github.com/open-gitagent/gitagent) — a git-native, framework-agnostic open standard for AI agents.
