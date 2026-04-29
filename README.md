# Guest-post-link-building-curation
🚀 AI Guest Posting Prospect Workflow

An automated SEO prospecting and validation pipeline designed to streamline guest posting outreach using AI agents, data enrichment, and strict qualification logic.

This workflow eliminates manual effort in:

Duplicate checking across master sheets
Domain quality validation
SEO metric enrichment (via Semrush)
Prospect qualification for UK-based link building
🧠 Workflow Overview

This system processes submitted domains through a multi-stage AI pipeline:

User Input → Duplicate Detection → SEO Screening → Final Qualification
⚙️ Architecture
1. Prospect Submission (Human Input)
Accepts up to 100 domains/URLs
Automatically normalizes inputs

Example:

https://www.example.com/blog → example.com
2. Duplicate Checker (AI Agent)

Purpose: Prevent redundant outreach

Key Capabilities:
Aggressive domain normalization
Generates multiple search variations:
example.com
www.example.com
http/https variations
Subdomains
Partial matches
Data Sources:
LRG - Link Building Master Sheet
LRG Master Outreach Sheet
Starberry Link Building Sheet
Output:
✅ DUPLICATE → Pull full historical data
🆕 NEW → Send to SEO screening
3. SEO Prospect Screener (AI Agent)

Purpose: Validate domain quality using strict SEO filters

Data Enrichment:
Integrated with Semrush API
Pulls:
Authority Score (AS)
Traffic (Total + UK)
Organic trends
Traffic geography
Content freshness
Niche relevance
📊 Screening Logic
❌ Automatic Rejection Criteria
AS ≤ 20
Traffic < 1,000/month
Non-UK traffic dominance
Last post > 90 days
Irrelevant niche
Presence of spam/illegal content
Ad-heavy (AdSense banners)
✅ Acceptance Criteria
UK / London traffic (mandatory)
Relevant niche:
Real Estate
Home Improvement
Business
News
Healthy traffic & activity
🏷️ Scoring Model
Score	Niche Type
🟢 Good	Real Estate, Home, Property
🟡 Moderate	Lifestyle, Business, News
🔴 Bad	All others
📄 Output Format

Final output is a structured table:

Url	Domain	Brand	AS	Traffic	UK Traffic	Trend	Niche	Status
Duplicate domains → flagged + enriched
New domains → evaluated + accepted/rejected
🔄 Workflow Flow
[User Input]
     ↓
[Duplicate Checker]
     ↓
[SEO Screener]
     ↓
[Final Output Table]
🧩 Tech Stack
AI Agent Framework (MindPal / Custom Agent OS)
Semrush API (SEO metrics)
Excel Knowledge Bases (LRG Sheets)
Prompt Engineering (domain normalization + filtering logic)
🛡️ Guardrails
Enforces strict UK-only targeting
Prevents duplicate outreach
Blocks spam/low-quality domains
Ensures niche alignment
⏱️ Efficiency Gains
Task	Manual	Automated
Duplicate Check	5–10 min/domain	Instant
SEO Validation	10–15 min	<10 sec
Prospect Qualification	Manual judgment	Rule-based AI

👉 Estimated Time Saved: 80–90%

🎯 Use Case

Ideal for:

SEO agencies
Link building teams
Real estate marketing teams (UK-focused)
Programmatic outreach systems
🚧 Future Improvements
GPT-based content relevance scoring
Automated outreach email generation
CRM integration
Dashboard UI (CLI or Web-based)
📌 Summary

This workflow acts as a semi-autonomous SEO prospecting engine, combining:

AI reasoning
Structured datasets
Real-time SEO metrics

Result: Higher-quality backlinks, faster execution, zero duplication.
