# Feature status — Events, venues & cultural institutions

| Capability | Status |
| --- | --- |
| Native sidebar and canonical feature registry | Built; 186 pages |
| Shared records, validation, relationships, persistence | Implemented in shared runtime |
| Clickable table rows with centered details popup | Implemented; Edit, Delete, Cancel, keyboard access and mobile layout |
| Domain field forms and source traceability | Imported from static source definitions; historical routes are labeled in mapping |
| CSV exports, attachments, audit and report totals | Implemented |
| At least 15 fictional rows per editable feature | Seeded by startup; measured in reports/seed-verification.json |
| AI question-and-answer workspace | Replaces AI feature tables; questions, context fields, formatted answers, follow-ups and saved history; live provider configuration required |
| Source calculation adapters | Available for explicitly registered calculation variants only |
| Source business-rule and state-machine parity | Incomplete beyond registered adapters and native records; verify each source journey |
| Original account/business data migration | Not performed; source data preserved |
| Provider integrations and external delivery | Not connected; request preparation only |
| Hosted authentication, independent-review roles and tenant isolation | Not migrated; local single-user boundary |

A successful build or populated table is not evidence of full source workflow parity. The source-to-feature map records every extracted definition and route, with explicit exclusions and migration warnings. Test/build reports distinguish checked behavior from remaining work.

| Canonical feature | Native mode | Source entries | Calculators | Status |
| --- | --- | ---: | ---: | --- |
| Clients & customers | records | 0 | 0 | Native records/view |
| Work items & projects | records | 0 | 0 | Native records/view |
| Contacts & parties | records | 0 | 0 | Native records/view |
| Tasks | records | 1 | 0 | Native records/view |
| Calendar | records | 5 | 0 | Native records/view |
| Deadlines & reminders | records | 0 | 0 | Native records/view |
| Notes | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Documents | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Templates | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Invoices & billing | records | 0 | 0 | Native records/view |
| Time tracking | records | 0 | 0 | Native records/view |
| Messages & communications | records | 0 | 0 | Native records/view |
| Reports & analytics | report | 1 | 0 | Native records/view |
| Activity & audit trail | audit | 1 | 0 | Native records/view |
| Provider connections | integration | 0 | 0 | Provider request records only |
| Ticketing agreement library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Event seat inventory | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Primary sale ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Resale transaction ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Face value reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Service fee calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Resale participation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Refund cancellation control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Chargeback allocation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Tax settlement | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Venue promoter split | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Ticketing statement audit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Dispute workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Cash reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Event channel analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Venues | records | 4 | 0 | Native records/view |
| Guest Lists | records | 2 | 0 | Native records/view |
| Catering Menus | records | 1 | 0 | Native records/view |
| Vendors | records | 1 | 0 | Native records/view |
| Budget Tracking | records | 2 | 0 | Native records/view |
| Invitations | records | 2 | 0 | Native records/view |
| Seating Plans | records | 2 | 0 | Native records/view |
| Entertainment | records | 1 | 0 | Native records/view |
| AI Event Suggestions | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Menu Generator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Budget Optimizer | records | 3 | 0 | AI question-and-answer workspace; records available as context |
| AI Schedule Optimizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Vendor Matcher | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Collections | records | 1 | 0 | Native records/view |
| Object Records | records | 1 | 0 | Native records/view |
| Loan Management | records | 1 | 0 | Native records/view |
| Exhibitions | records | 1 | 0 | Native records/view |
| Galleries | records | 1 | 0 | Native records/view |
| Conservation | records | 1 | 0 | Native records/view |
| Environmental Monitoring | records | 1 | 0 | Native records/view |
| Storage Locations | records | 1 | 0 | Native records/view |
| Insurance & Valuation | records | 1 | 0 | Native records/view |
| Ticketing & Admissions | records | 1 | 0 | Native records/view |
| Memberships | records | 1 | 0 | Native records/view |
| Donors | records | 1 | 0 | Native records/view |
| Gift Shop | records | 1 | 0 | Native records/view |
| Education Programs | records | 1 | 0 | Native records/view |
| Volunteers | records | 1 | 0 | Native records/view |
| Tours | records | 1 | 0 | Native records/view |
| Visitor Analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Security Rounds | records | 1 | 0 | Native records/view |
| Maintenance | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Environment monitor | records | 1 | 0 | Native records/view |
| Donor insights | records | 1 | 0 | Native records/view |
| Advisor | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Loan condition risk | records | 1 | 0 | Native records/view |
| Box office | records | 1 | 0 | Native records/view |
| Donor stewardship | records | 1 | 0 | Native records/view |
| Script analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Ticket pricing | records | 3 | 0 | Native records/view |
| season planning optimizer recommending show mix | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| performance outcome prediction for ticket sales and review | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| fundraising campaign planning with donor segment targeting | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| script recommendation engine based on available cast and | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| community partnership matcher identifying sponsors by affinity | records | 1 | 0 | Native records/view |
| volunteer management module with shift scheduling | records | 1 | 0 | Native records/view |
| ai driven season planning | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| performance outcome prediction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| conversational marketing copilot | records | 1 | 0 | Native records/view |
| integration with ticketing platforms eventbrite brown paper | integration | 1 | 0 | Provider request records only |
| email marketing automation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| grant database matching | records | 1 | 0 | Native records/view |
| volunteer management | records | 1 | 0 | Native records/view |
| patron subscriber self service portal | records | 1 | 0 | Native records/view |
| webhooks or notifications | integration | 1 | 0 | Provider request records only |
| payment processor integration | integration | 1 | 0 | Provider request records only |
| crm style segmentation beyond donor records | records | 1 | 0 | Native records/view |
| AI ROI Predictor | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| AI Lead Scorer | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| AI Competitor Intelligence | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| AI Follow-up Email Writer | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| AI Event Recommender | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| AI Booth Design Advisor | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| AI Marketing Copy Generator | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| AI Staff Optimizer | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| AI Performance Reporter | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| AI Sponsorship Advisor | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| AI Networking Strategy | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| AI Post-Event Survey Automation | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Lead capture | records | 1 | 0 | Native records/view |
| Crm sync | records | 1 | 0 | Native records/view |
| Cadences | records | 1 | 0 | Native records/view |
| Heatmap | records | 1 | 0 | Native records/view |
| Briefing | records | 1 | 0 | Native records/view |
| Booths | records | 1 | 0 | Native records/view |
| Leads | records | 1 | 0 | Native records/view |
| Expenses | records | 1 | 0 | Native records/view |
| Staff | records | 1 | 0 | Native records/view |
| Sponsors | records | 1 | 0 | Native records/view |
| Materials | records | 1 | 0 | Native records/view |
| Competitors | records | 1 | 0 | Native records/view |
| Followups | records | 1 | 0 | Native records/view |
| Post event sentiment | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Abm targeting | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Competitor winloss | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Portfolio optimizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| attendee sentiment tracking via post event surveys to predict | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| account based marketing targeting personalizing outreach to high value attendees | records | 1 | 0 | Native records/view |
| real time booth traffic heatmapping for on the spot optimization | records | 1 | 0 | Native records/view |
| competitor win loss analysis tied to shared events | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| multi event portfolio optimization across calendar year | records | 1 | 0 | Native records/view |
| badge scan integration for live lead ingestion | integration | 1 | 0 | Provider request records only |
| ai post event sentiment analysis of attendees | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| ai lead quality clustering | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| ai booth traffic anomaly detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| limited crm integration single integration module not salesforce | integration | 1 | 0 | Provider request records only |
| email campaign platform integration | integration | 1 | 0 | Provider request records only |
| attendee badge integration for real time tracking | integration | 1 | 0 | Provider request records only |
| webhooks | integration | 2 | 0 | Provider request records only |
| notifications subsystem | records | 2 | 0 | Native records/view |
| Performers | records | 2 | 0 | Native records/view |
| Bookings | records | 2 | 0 | Native records/view |
| Seat Assignments | records | 2 | 0 | Native records/view |
| Seat Recommend | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Tech Riders | records | 2 | 0 | Native records/view |
| Settlements | records | 2 | 0 | Native records/view |
| Dynamic Pricing | records | 1 | 0 | Native records/view |
| Revenue Forecast | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Artist Match | records | 1 | 0 | Native records/view |
| Marketing Campaign | records | 1 | 0 | Native records/view |
| Scheduling | records | 1 | 0 | Native records/view |
| Eventbrite Sync | integration | 1 | 0 | Provider request records only |
| Stripe Payment | integration | 1 | 0 | Provider request records only |
| dynamic pricing optimizer adjusting by demand time to event comparables | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| artist audience matcher recommending artists by target audience | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| revenue prediction forecasting event profitability | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| scheduling optimizer minimizing cannibalization across events | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| marketing campaign recommender suggesting channels budgets | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| patron crm with loyalty season ticket subscription support | records | 1 | 0 | Native records/view |
| ai dynamic pricing based on demand | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| ai artist audience matching | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| ai demand forecasting | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| integrations with ticketing platforms eventbrite ticketmaster | integration | 1 | 0 | Provider request records only |
| payment processing integration | integration | 1 | 0 | Provider request records only |
| marketing automation | records | 1 | 0 | Native records/view |
| customer self service portal | records | 1 | 0 | Native records/view |
| multi venue franchise chain management | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Vendor Matching | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Budget Optimizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Timeline Planner | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Seating Planner | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Menu Designer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Invitation Writer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Floral Designer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Music Curator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| General Advice | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Budget Risk | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Vendor Performance | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Budget Manager | records | 1 | 0 | Native records/view |
| Timeline & Checklist | records | 1 | 0 | Native records/view |
| Menu Planning | records | 1 | 0 | Native records/view |
| Wedding Registry | records | 1 | 0 | Native records/view |
| Photography | records | 1 | 0 | Native records/view |
| Music & Entertainment | records | 1 | 0 | Native records/view |
| Floral Arrangements | records | 1 | 0 | Native records/view |
| Transportation | records | 1 | 0 | Native records/view |
| Accommodation | records | 1 | 0 | Native records/view |
| Guest preferences | records | 1 | 0 | Native records/view |
| Budget overrun | records | 1 | 0 | Native records/view |
| Seating optimize | records | 1 | 0 | Native records/view |
| Destination itinerary | records | 1 | 0 | Native records/view |
| Event day coordination | records | 1 | 0 | Native records/view |
| Thank you cards | records | 1 | 0 | Native records/view |
| Counseling referrals | records | 1 | 0 | Native records/view |
| Assistant | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Budget summary | records | 1 | 0 | Native records/view |

Row popup verification passed: dashboard and feature rows, keyboard/focus, editing and persistence, delete confirmation/cancellation, centered mobile layout and full-record navigation. See `reports/row-popup-verification.json`.

## Verified local build

Build, API, browser and actual `start.sh` checks passed. All 186 feature pages were visited in the browser; 184 editable tables contain at least 15 fictional rows each. CRUD persistence and mobile layout were checked. Evidence is in `reports/verification.json`, `reports/browser-verification.json` and `reports/startup-verification.json`.

These checks cover the native local workspace. Full source-specific business rules, authentication and live provider operations remain incomplete as described above. Test servers were stopped after verification.

## AI workspace verification

All 78 AI feature routes were checked in the browser and show questions and formatted answers instead of the original record table. Existing records are retained as optional context. Questions, follow-ups, saved history across restart, Markdown tables, safe rendering, downloads, provider-failure recovery and mobile layout passed with a mocked provider. See `reports/ai-workspace-verification.json`.

Live answers require `OPENROUTER_API_KEY` and `OPENROUTER_MODEL` in this app's `.env` and an app restart. No live provider call was made during verification. Conversational answers do not execute unmigrated specialist engines, read record attachments automatically or perform external actions.


## AI word limits

Questions support up to 5,000 words with a live counter and server validation. AI responses and record drafts have a 16,000-token output budget and a default 180-second timeout to support answers up to 5,000 words; actual length depends on the request and model. Answers show their word count, and long questions can be expanded. Browser checks passed for 5,000-word questions and answers, saved history, full downloads, mobile layout and rejection of 5,001-word questions. See `reports/word-limit-verification.json` (mock-provider boundary checks).

## Merged AI assistants

78 original AI entries are now grouped into **8 assistants** in the sidebar. Choose up to 8 related capabilities and add up to 10 questions for one provider request and one saved response. Shared context is sent once; repeated questions are removed after trimming and whitespace/case normalization. The total question limit is 5,000 words and the combined answer target is up to 5,000 words.

Original feature URLs still open the appropriate assistant with that capability selected. Existing records and answers stay in place; the assistant history includes answers saved under its member features. Non-AI record tables retain their popup actions. This merges the assistant workflow and navigation; it does not implement previously missing external integrations or specialist engines. See `reports/assistant-merge-map.json` and `reports/assistant-merge-verification.json`.

## Floating Ask AI assistant

Implemented across this workspace. The bottom-right **Ask AI** button opens a persistent chat panel on every page. Use **Ask AI about item** in a row popup or record view, or **Use current item** inside the panel, to supply the selected record.

- Questions about the page, any explicitly chosen app record, and general topics.
- Formatted answers, comparison tables, follow-ups, copy and Markdown download.
- Conversation and question drafts stay intact during in-app navigation. Saved answers persist in SQLite; the last conversation restores in the same browser tab after reload. The latest 50 saved answers are listed; restoring one displays up to 20 turns. Up to four preceding turns are sent as AI context.
- Up to 5,000 input words and a response budget of up to 5,000 words. Output length remains dependent on the provider and the question.
- Page title and description are supplied automatically; record fields and notes are sent only for a selected item. Attachments and unselected records are not included. **New chat** starts without earlier conversation context.
- Existing AI provider configuration, timeout, rate limit and safe response renderer are reused. The assistant answers and drafts; it does not execute record changes or external actions.

Validation: shared backend tests, all 64 app builds/API checks, and all 64 browser checks passed with an injected test provider. Browser checks cover item context, navigation, saved history/reload, follow-ups, new-chat isolation, error recovery, word limits, keyboard controls, mobile bounds, safe Markdown rendering and attachment refresh. See [verification](reports/floating-ai-verification.json).
