# Wayfair AI Agent Engineering — n8n Automation Portfolio

**Top 10% Performer | Wayfair n8n AI Agent Engineering Externship (via Extern) | October 2026**

## Overview
Five n8n automation projects demonstrating how e-commerce teams can connect market research, competitive analysis, AI-assisted content strategy, dashboard reporting, and visual ideation.

This is an **educational externship portfolio**, not an official Wayfair production deployment.

## Workflows

| Project | What it does |
| --- | --- |
| P2: Market Trend Agent | Parses rug category inputs and uses program-provided product and trend APIs to support market research. |
| P3: Competitor Analysis Agent | Compares product data from Wayfair, IKEA, and Amazon and produces AI-assisted competitive analysis. |
| P4: Content Strategy Agent | Accepts P2 and P3 HTML research reports, campaign parameters, audiences, and KPIs; generates a structured strategy report. |
| P5: Dashboard Generator | Combines market trend and competitor reports into an integrated HTML dashboard. |
| Moodboard Agent | Uses Gemini for image prompt engineering and a Hugging Face endpoint for moodboard image generation. |

## Architecture

```text
Research input
  ├── P2: Market Trends ─────────┐
  └── P3: Competitor Analysis ──┬┴──> P4: Content Strategy
                               └────> P5: HTML Dashboard

Creative input ──> Gemini Prompt Agent ──> Hugging Face ──> Moodboard
```

## Technology
- **Automation:** n8n workflows, conditional logic, orchestration
- **AI:** LLM agents, Google Gemini, OpenRouter
- **Integrations:** HTTP requests and Hugging Face image generation
- **Transformations:** JavaScript, JSON parsing and validation
- **Outputs:** Competitive analysis, content strategy reports, HTML dashboards, moodboard images

## Recognition
**Top Performer — Top 10% of participants.** Awarded October 19, 2026 by Extern for exceptional effort, initiative, and presentation.

## Running the workflows
Import the JSON exports into n8n and configure your own credentials and authorized API endpoints. Research workflows depend on externship-provided APIs; they are not standalone production systems. Never commit live API tokens. See security guidance before publishing workflow exports.

## About
Created by [Muzammil Paracha](https://github.com/muzammil1145-png) as part of the Wayfair n8n AI Agent Engineering Externship via Extern.
