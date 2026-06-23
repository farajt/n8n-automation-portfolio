# 🗞 Daily Tech News Digest Automation

## What it does
Fetches top English-language tech and AI headlines daily,
filters by relevance, and delivers a clean formatted digest
to email automatically — zero manual effort.

## Business value
- Saves 15–20 minutes of manual news checking daily
- Can be sold as a personalized news briefing service
- Adaptable to any industry (finance, health, crypto)

## Tech stack
- n8n (automation engine)
- NewsAPI (data source)
- Gmail (delivery)

## Workflow architecture
Schedule Trigger → NewsAPI (HTTP GET) → Code node (filter + format) → IF node → Gmail

## Nodes used
- HTTP Request (GET)
- Code node (JavaScript)
- IF node
- Gmail node
- Schedule Trigger

## Setup
1. Get free API key from newsapi.org
2. Connect Gmail credential in n8n
3. Import workflow.json
4. Update your email and API key in the nodes
5. Activate workflow

## Screenshots
Canvas and email output in /screenshots folder
