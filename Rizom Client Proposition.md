# Recall

## Executive Summary

Recall is a self-hosted AI knowledge layer on top of the tools your teams already use (Slack, Teams, Notion, GitHub, etc.). It continuously captures and structures institutional knowledge from everyday communication and documentation, and makes it instantly accessible through an internal chatbot, topic dictionary, and conversation summaries. 

Result: faster onboarding, faster decision-making, fewer bottlenecks around key people, and less time wasted searching for context.


## The Problem 

In every organization, critical knowledge lives in a few people and scattered tools:

- Teams depend on informal **catalysts** who know how things really work. 
- Context is buried in Slack threads, docs, and AI chats, not in one place. 
- New hires take months to ramp up. 
- When key people leave or are unavailable, projects slow down or stall.

As long as organizational intelligence lives mainly in individual heads and fragmented conversations, you get:

- Bottlenecks and decision delays 
- Limited scalability of teams and processes 
- Concentrated risk around a handful of individuals 


## The Solution 
Recall turns your existing communication and documentation into a shared, searchable knowledge base:

- **Automatic knowledge capture** from Slack/Teams, Notion, GitHub, and relevant external content 
- **Instant answers** via a domain-specific internal chatbot (“Knowledge Oracle”) 
- **Always-up-to-date topic dictionary** of concepts, decisions, and definitions 
- **Conversation summaries & timelines** that connect related discussions over time 
- **Optional team insights** on knowledge gaps and key-person dependencies 

Deployed as a **private, self-hosted server** (web, API, MCP) on your own infrastructure, Recall keeps you in full control of your data.


## How It Works (Product View)

1. **Integrations** 
   Connect Recall to selected channels and spaces in: 
   - Slack / Microsoft Teams / Matrix 
   - Notion / Obsidian / GitHub 
   - Existing AI conversations (e.g. ChatGPT/Claude) and key external content 

2. **Knowledge Processing** 
   Intelligent agents continuously: 
   - Monitor conversations and documents 
   - Detect topics, decisions, definitions, FAQs 
   - Transform raw content into structured, searchable knowledge objects 

3. **Core Modules** 
   - **Knowledge Oracle** – Ask questions in natural language from within Slack/Teams or web. 
   - **Topic Dictionary** – Internal “Wikipedia” of your business and systems, auto-maintained. 
   - **Conversation Summaries** – Threaded summaries and decision timelines across channels. 
   - **Content Generation** – Drafts for blogs, proposals, internal memos using your own knowledge base. 


## Why Now?

- Teams already use many tools but lack a unifying knowledge layer. 
- Modern AI is finally good enough to understand, summarize, and connect large volumes of internal content. 
- Vendor-specific AI (e.g. inside Microsoft or Slack) remains siloed; Recall is: 
  - **Cross-tool and neutral** 
  - **Self-hosted and privacy-first** 
  - Designed as **“last-mile knowledge infrastructure”** on top of any foundation models you choose.


## Business Model (High-Level)

- **Annual license** for the Recall platform, based on active users or team size. 
- **Implementation package** for a 60–90 day pilot in one business unit, including: 
  - Integration with 2–3 core tools
  - Configuration of one domain-specific Knowledge Oracle and Topic Dictionary
  - Definition and tracking of success metrics (e.g. onboarding speed, search time, reduced interrupts)
- **Land-and-expand**: extend to additional teams and add optional modules (e.g. advanced analytics, team insights).

## Go-To-Market Approach

### Phase 1 – Prove Value (Design Partners)

- Target small to mid-sized, knowledge-intensive teams (product/engineering, consulting, CS).
- Run tightly scoped pilots with clear KPIs, such as:
    - Time to find answers
    - Reduction in “ask X” messages
    - Onboarding time for new hires
- Use results to produce reference cases and ROI stories.

### Phase 2 – Land & Expand in Mid-Market and Enterprise

- Position Recall as:
    - An internal knowledge OS over the existing toolstack
    - A risk mitigation layer for key-person dependency and knowledge loss
    - A productivity multiplier for distributed and hybrid teams
- Start in one business unit, then expand horizontally based on demonstrated value.

## Key Risks & Mitigations (Summary)

- Perceived as too abstract
    - Mitigation: always sell around concrete use cases and measurable outcomes.
- Employee resistance / “surveillance” concerns
    - Mitigation: clear scope and privacy controls; opt-in channels; position as team assistant, not monitoring.
- Competition from large AI vendors
    - Mitigation: focus on cross-tool neutrality, self-hosted deployment, and deep integration with each client’s unique knowledge graph rather than being another siloed feature.