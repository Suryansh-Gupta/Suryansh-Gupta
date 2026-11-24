# Competitive Landscape: AI Autopilot Accounting / Bookkeeping / Controller Products (as of Nov 2026)

Research date: 2026-11-24. Method: 15 web searches/fetches. Many figures come from secondary aggregators and vendor-comparison blogs; these are flagged. Items in the "Gaps" sections marked "prior knowledge, unverified" are from the researcher's background knowledge (pre-mid-2026) and were NOT re-verified with a source this session. The report writer should treat them as leads, not facts.

Classification key used below:
- **Autopilot** = agent performs the work end-to-end, human reviews exceptions only
- **Copilot** = assists a human accountant who still owns the work
- **Tech-enabled service (TES)** = software + human bookkeepers/CPAs deliver the outcome
- **Firm-tool** = sold to accounting/CPA firms rather than to the operating company

---

## 1. Incumbents: what AI/agentic features have Intuit, Xero, Sage, NetSuite, Dynamics, BILL, Ramp, Brex launched in 2025-2026, and how close are they to autopilot?

### Takeaway
Incumbents have all shipped named "agents" in 2025-2026, and Intuit has the largest deployed base (3M+ customers using agents by Q2 FY26). But every incumbent's agents are scoped to sub-tasks (categorization, reconciliation, invoice coding, expense review) with human approval gates. None sells "the accounting manager function" as an outcome. They are copilots with growing autonomous sub-routines. Their moat is distribution and data, not end-to-end ownership.

### Cited Findings

**Intuit QuickBooks / Intuit Enterprise Suite (IES)**
- Intuit has moved from "Intuit Assist" branding to named agents. The Accounting Agent handles categorization and works with the customer's accountant, and a Payroll Agent is rolling out through 2026 — [usecarly.com category map](https://www.usecarly.com/blog/ai-accounting-software/) (secondary)
- The best AI features (Finance AI, full Accounting AI) are gated to the QBO Plus/Advanced tiers. Some premium agent features were free in beta, with fees expected at GA around late spring 2026 — [bookkeepertools.uk](https://bookkeepertools.uk/best-ai-features-uk-accounting-software-2026/) (secondary)
- Agent adoption: 2.8M customers were "leveraging these agents to do the work for them" (Q1 FY26), and over 3M by Q2 FY26 — [Intuit Q1 FY26 remarks](https://investors.intuit.com/_assets/_25d0832d8f64a0e6da9a25f2f35656c4/intuit/db/946/10339/webcast_transcript/Q1FY26+Earnings+Script+v1.pdf); [Intuit Q2 FY26 remarks](https://investors.intuit.com/_assets/_7139a1ed54d6cf58906c72317fb24153/intuit/db/946/10358/webcast_transcript/Q2FY26+Earnings+Script+02.26.2026.pdf)
- "Over 75% of Intuit Enterprise Suite customers use our AI agents every month to keep their books current, automate transaction work, and close faster" (Q4 FY26 call, third-party transcript) — [Motley Fool Q4 FY2026 transcript](https://www.fool.com/earnings/call-transcripts/2026/09/01/intuit-intu-q4-2026-earnings-call-transcript/)
- In Q4 FY26, QBO accounting revenue grew 20%, and 23% for the full year. Online Paying Customers were 8.9M at FY end, growing 3% YoY (down from 5%). FY27 revenue guidance is $23.279B–$23.512B (+9–10%) — [Motley Fool Q4 FY2026 transcript](https://www.fool.com/earnings/call-transcripts/2026/09/01/intuit-intu-q4-2026-earnings-call-transcript/)
- In Q3 FY26, Online Ecosystem revenue for QBO Advanced + IES grew about 38% — [Intuit Q3 FY26 remarks](https://investors.intuit.com/_assets/_b47bef62c2922576cfc0ce6fc96bb015/intuit/db/946/10372/webcast_transcript/Q3FY26+Earnings+Script+(1).pdf)
- FY2026 10-K describes "agents that not only surface insights, but also take action across the business" — [Intuit 10-K FY2026](https://www.sec.gov/Archives/edgar/data/0000896878/000089687826000037/intu-20260731.htm)
- Intuit Ventures participated in Collective's $40M Series B (Oct 2026), a bookkeeping/tax/payroll service for solo businesses. This signals Intuit hedging via service-layer investments — [newmarketpitch funding table](https://newmarketpitch.com/blogs/news/ai-accounting-top-startups-fundraising)

**Xero (JAX, "Just Ask Xero")**
- JAX is described as agentic and real-time, and is included across all plans at no extra charge — [bookkeepertools.uk](https://bookkeepertools.uk/best-ai-features-uk-accounting-software-2026/) (secondary, single-source view)
- It auto-reconciles over 80% of bank lines in real time — [rework.com](https://resources.rework.com/tools/ai-agents/best-ai-agents-for-accounting-2026) (secondary)
- JAX shows its reasoning and asks for approval before acting, and every action is logged. This is explicitly a human-in-the-loop design — [curatesuite.com](https://curatesuite.com/accounting/articles/sage-copilot-vs-intuit-assist)
- Xero co-founder Craig Walker joined Digits (Mar 2025), a talent signal toward AI-native GLs — [GlobeNewswire, Digits AGL launch](https://www.globenewswire.com/news-release/2025/03/10/3039814/0/en/AI-Startup-Digits-Takes-on-QuickBooks-with-the-World-s-First-Autonomous-General-Ledger-for-Accounting-Xero-Co-founder-Craig-Walker-Joins-Digits.html)

**Sage (Sage Copilot / Intacct)**
- Sources disagree on packaging: one says Copilot is embedded in all Sage Accounting plans at no charge, another calls it an optional generative-AI add-on — [usecarly.com](https://www.usecarly.com/blog/ai-accounting-software/); [bookkeepertools.uk](https://bookkeepertools.uk/best-ai-features-uk-accounting-software-2026/)
- Sage Intacct's Copilot is aimed at orchestrating month-end close for a client with a finance team — [curatesuite.com](https://curatesuite.com/accounting/articles/sage-copilot-vs-intuit-assist)
- A Sage "Finance Intelligence Agent" is in phased rollout, with GA scheduled later in 2026 — [allainews.net](https://allainews.net/ai-agents-for-accounting/) (secondary)
- Consensus across comparison sources: QuickBooks has the widest agent suite, Xero leads on default reconciliation and transparency, and Sage is strongest in Intacct for mid-market close — [curatesuite.com](https://curatesuite.com/accounting/articles/sage-copilot-vs-intuit-assist)

**Ramp**
- Agents include a Policy Agent, an AP Agent, and an Accounting Agent. The Accounting Agent auto-codes transactions to GL, department, class, and location at posting. "Ramp Stack," an AI operating system for accounting firms, launched June 2026 — [rework.com finance agents](https://resources.rework.com/tools/ai-agents/best-ai-agents-for-finance-2026) (secondary)
- Vendor claims: the Policy Agent catches 7x more out-of-policy spend at 99% accuracy. The AP Agent has 85% first-attempt GL coding accuracy and processes invoices 2.4x faster — [rework.com](https://resources.rework.com/tools/ai-agents/best-ai-agents-for-finance-2026)
- Ramp's AP module includes invoice OCR at no charge but lacks some BILL approval features — [eightx.co](https://eightx.co/blog/ramp-vs-bill-com-ap-automation)

**Brex**
- Agents: Brex Assistant, Audit Agent, and Review Agent. The Review Agent auto-approves low-risk expenses and requests and escalates exceptions. Its AP is described as weaker than the AP specialists' — [rework.com](https://resources.rework.com/tools/ai-agents/best-ai-agents-for-finance-2026); [ustechautomations](https://ustechautomations.com/resources/blog/billcom-vs-ramp-vs-brex-for-ap-automation-2026) (secondary)

**BILL (Bill.com)**
- AI branding is "BILL AI," with Touchless AP and Vendor Tax Forms. No launch date was found — [ustechautomations](https://ustechautomations.com/resources/blog/bill-com-vs-ramp-brex-for-ap-automation-2026)
- Accounting firms tend to favor BILL for its multi-client console, growth companies favor Ramp, and startups favor Brex — [rework.com Ramp vs BILL](https://resources.rework.com/tools/spend-expense/ramp-vs-bill-com)

**Oracle NetSuite / Microsoft Dynamics**
- Rillet claims customers are replacing Oracle Fusion, SAP, Workday, Microsoft Great Plains, and NetSuite. A counter-view: installing Maxio on top of NetSuite lets a company defer a full ERP migration — [Sacra / Rillet coverage](https://sacra.com/c/rillet/); [Business Wire, Rillet Series C](https://secure.businesswire.com/news/home/20260819978953/en/Rillet-Raises-$100M-Series-C-at-$1B-Valuation-to-Build-Accounting-Superintelligence)

### Inferences
- Intuit's "3M customers using agents" is a breadth metric (any agent use, e.g., auto-categorization), not evidence of books closed without a human. Intuit's own framing still routes work to "your accountant."
- QBO's net customer growth is slowing to 3% while revenue grows 20%+ via price and mix. That is an opening for a cheaper, outcome-priced autopilot at the bottom of the market, but also means Intuit will fight hard on retention by bundling agents.
- Spend platforms (Ramp, Brex, BILL) are eating the "transaction coding + AP + expense" slice of the accounting manager role from the cash-movement side. A startup that does not own payments must integrate with them, not compete.
- No incumbent has a credible "autonomous month-end close + financial statements + controller sign-off" product for SMBs. That is the gap a full-autopilot startup would target.

### Gaps
- No primary-source documentation was retrieved on NetSuite's 2025-26 AI agents (e.g., NetSuite "Next"/SuiteAgents) or Microsoft Dynamics 365 Copilot finance agents. Prior knowledge, unverified: Oracle announced AI agents in Fusion/NetSuite (SuiteWorld 2025), and Microsoft shipped Copilot for Finance and Dynamics 365 agents (Account Reconciliation, Financial Reconciliation) in 2024-25.
- Prior knowledge, unverified: Intuit launched its agent suite (Accounting, Finance, Payments, Customer, Project Management agents) in July 2025, and Xero launched JAX in 2025 at Xerocon/Xero's AI event.
- BILL agent launch dates and pricing, and Brex agent dates, were not found in primary sources.
- Accuracy and autonomy rates (percent of transactions or close tasks with zero human touch) for incumbents are not disclosed except Xero's ">80% bank lines" (secondary).

---

## 2. AI-native startups: funding, pricing, segment, scope, autopilot vs copilot vs service

### Takeaway
2025-2026 capital has flowed into three clusters. (a) AI-native ERP/GL for venture-backed mid-market: Rillet $1B, Campfire ~$375M (offers at $1B), DualEntry. (b) Agents sold to accounting firms: Basis $1.15B, Accrual $75M. (c) Close/reconciliation agents for mid-market finance teams: Numeric, Hyphenate (ex-Maximor), Stacks. The SMB "do my books for me" segment is crowded with tech-enabled services (Pilot, Zeni, Bench, finally, Collective) and a new wave of seed-stage autopilots (Synthetic, Sumary, Safebooks, Agent F). No player has yet proven a pure-software, no-human autopilot at scale.

### Cited Findings

**Valuation leaders (2026)**
- **Basis** (NYC, agents for accounting firms; Firm-tool, Autopilot-on-tasks): $100M Series B, announced Feb 24, 2026, at a $1.15B valuation, led by Accel with GV participating (one source names a16z as lead, which conflicts). Its agents run autonomously on complex tasks over many hours, and it reported an automated completion of a 1065 tax return. Total raised about $138M — [Yahoo Finance](https://finance.yahoo.com/news/ai-accounting-startup-basis-raises-184711527.html); [PYMNTS](https://www.pymnts.com/news/investment-tracker/2026/basis-raises-100-million-to-build-up-ai-in-accounting/); [newmarketpitch](https://newmarketpitch.com/blogs/news/ai-accounting-top-startups-fundraising)
- **Rillet** (AI-native ERP/GL for mid-market and venture-backed companies; Autopilot ambitions, "accounting superintelligence"):
  - $100M Series C, Aug 17–19, 2026, at a $1B post-money valuation, led by ICONIQ. It was the third raise in about a year.
  - Earlier rounds: a $25M Series A (Sequoia, May 28, 2025) and a $70M Series B (a16z + ICONIQ, Aug 6, 2025). Total about $208M.
  - Over 600 customers, and new ARR doubled in the prior three months. Absolute ARR is not disclosed.
  - Customer Mercor's 3-person finance team scaled past $2B ARR on Rillet.
  - Investors also include Scale VP.
  - Sources: [Business Wire](https://secure.businesswire.com/news/home/20260819978953/en/Rillet-Raises-$100M-Series-C-at-$1B-Valuation-to-Build-Accounting-Superintelligence); [Fortune](https://fortune.com/2026/08/18/rillet-unicorn-1-billion-valuation-series-c-nicolas-kopp-accounting-ai/); [ICONIQ](https://www.iconiq.com/growth/insights/iconiq-leading-rillets-100m-series-c); [Sacra](https://sacra.com/c/rillet/); [Scale VP](https://www.scalevp.com/blog/announcing-our-investment-in-rillet)
- **Campfire** (AI-native ERP; Copilot/ERP): $65M Series B (Oct 2025), co-led by Accel and Ribbit. Its last confirmed valuation was $375M (Oct 2025), and it has reportedly received offers at $1B but had not taken the round as of Aug 2026. Total about $104–108M — [vff.ai summary of The Information](https://vff.ai/article/2026/08/19/quickbooks-challengers-are-fetching-1-billion-valuations); [Silicon Bay Partners](https://ourblog.siliconbaypartners.com/ai-accounting-startups-are-fetching-1-billion-valuations/)
- **DualEntry** (AI-native ERP): $90M Series A (Oct 2025), $98M total — [newmarketpitch](https://newmarketpitch.com/blogs/news/ai-accounting-top-startups-fundraising)
- **Pennylane** (France; accounting platform for SMBs plus accountants): $205M Series E (Jan 2026), led by TCV, $408M total. It is the EU leader — [newmarketpitch](https://newmarketpitch.com/blogs/news/ai-accounting-top-startups-fundraising)

**Close / reconciliation / controller agents (mid-market finance teams)**
- **Numeric** (close management and reconciliation; Copilot to autopilot): $51M Series B (Nov 2025), led by IVP, $89M total. No valuation disclosed — [Silicon Bay Partners](https://ourblog.siliconbaypartners.com/ai-accounting-startups-are-fetching-1-billion-valuations/); [newmarketpitch](https://newmarketpitch.com/blogs/news/ai-accounting-top-startups-fundraising)
- **Hyphenate (formerly Maximor)** (finance and accounting agents for companies with ≥$50M revenue; Autopilot-on-tasks):
  - Founded by ex-Microsoft executives (launched Sept 2025 with a $9M seed; Perplexity CEO Aravind Srinivas invested).
  - $45M Series A led by Nexus Venture Partners with B Capital, about $54M total.
  - 25+ customers. Integrates with NetSuite, Intacct, QuickBooks, and Zoho.
  - Pricing is per work that "goes live," not per seat.
  - Customer Rently cut close from 8 to 4 days. Revenue up 35x in 9 months (company claim).
  - Sources: [FinTech Futures](https://www.fintechfutures.com/venture-capital-funding/newly-rebranded-hyphenate-lands-45m-series-a); [TechCrunch 2025](https://techcrunch.com/2025/09/29/former-microsoft-executives-launch-ai-agents-to-end-excel-driven-finance-for-mid-market-enterprise-businesses); [CFO Dive](https://www.cfodive.com/news/startup-raises-9m-rescue-finance-teams-buried-reconciliations-agentic-ai/761444/); [HackerNoon](https://hackernoon.com/maximor-scales-revenue-35x-in-just-9-months-as-cfos-run-out-of-accountants)
- **Stacks AI** (agentic close automation, Netherlands origin): $23M Series A (Feb 2026), $38M total — [newmarketpitch](https://newmarketpitch.com/blogs/news/ai-accounting-top-startups-fundraising)
- **Maxima** (enterprise accounting agents): $33M Series A (Nov 2025) — same source
- **Light** (AI-native accounting platform, Denmark/EU): $30M Series A (Sep 2025), $43M total — same source
- **Truewind** (accounting agents): $13M Series A (Dec 2024, older), $18M total — same source
- **Nominal** (accounting/ERP automation): $20M Series A (Jul 2025) — same source
- **Double** (month-end close): $6.6M; **Eagl** (month-end agents): $975K; **Emblematic** (mid-market agents): $2M — same source
- **FloQast** (incumbent close software): $100M Series E (Apr 2024, older), about $1.6B valuation, $283M total — same source

**SMB bookkeeping: software autopilots**
- **Digits** (AI GL for startups and SMBs; Autopilot positioning):
  - Launched its "Autonomous General Ledger" in Mar 2025, claimed as the world's first. Then launched agents on the AGL.
  - Funding: $98M total, last round a $65M Series C (Mar 2022, older).
  - Outcome-based pricing for accounting firms (Apr 2026): firms pay only for clients with ≥95% zero-touch transactions.
  - Direct pricing was cited at "from $100/mo" at the 2025 launch and "from $65/mo" in an Aug 2026 listing. Each entity needs its own subscription.
  - Sources: [CPA Practice Advisor 2025](https://www.cpapracticeadvisor.com/2025/03/11/digits-autonomous-general-ledger-will-take-on-quickbooks-company-says/157183/); [CPA Practice Advisor Apr 2026](https://www.cpapracticeadvisor.com/2026/04/07/digits-announces-outcome-based-pricing-for-accounting-firms/181110/); [Digits agents blog](https://digits.com/blog/introducing-digits-accounting-agents/); [newmarketpitch](https://newmarketpitch.com/blogs/news/ai-accounting-top-startups-fundraising)
- **Puzzle** (AI-native GL for startups; software plus optional accountants):
  - Funding: $30M Series B (Nov 2023, older), $45M total.
  - 2026 tiers: Starter $25/mo, Core $60/mo, Complete $120/mo, Scale $360/mo. Other listings show a $50 start, so sources conflict.
  - Pricing page offers "50% faster month-end close — or your money back."
  - It separates software-only from services delivered by Puzzle accountants or partner firms.
  - Sources: [PricingSaaS](https://pricingsaas.com/companies/puzzle); [Puzzle pricing](https://puzzle.io/pricing); [newmarketpitch](https://newmarketpitch.com/blogs/news/ai-accounting-top-startups-fundraising)
- **Synthetic** (autonomous bookkeeping for startups; Autopilot): $10M seed (May 2026), led by Khosla. It connects to bank, payroll, billing, and email inboxes to produce accrual-basis financial statements, and is positioned as "replacing human accountants" — [Axios Pro](https://www.axios.com/pro/fintech-deals/2026/05/14/synthetic-10m-ai-bookkeeping-seed); [ai-market-watch](https://www.ai-market-watch.com/news/synthetic-raises-10m-seed-funding-for-ai-bookkeeping-platform-7q86hm)
- Other 2025-2026 seed-stage autopilot entrants (funding per aggregator):
  - Sumary, bookkeeping automation: $25M seed, Nov 2026
  - Safebooks, AI bookkeeping: $15M seed, Dec 2025
  - Cleavr: $8.8M seed, Oct 2026
  - SimpleAI: $5M, Jul 2026
  - Byron, bookkeeping assistant: $6.5M, May 2026
  - Neno, SMB bookkeeping: $7.7M, Aug 2026
  - Agent F, bookkeeping and controls agents with approval: $4M, Nov 2026
  - Open Ledger: $3M, Jan 2025
  - BOB, AI finance agent bundled with banking: $5.5M, Oct 2026
  - Source: [newmarketpitch](https://newmarketpitch.com/blogs/news/ai-accounting-top-startups-fundraising)
- **Kick** (SMB bookkeeping, self-driving positioning): undisclosed additional financing (Nov 2025), $9M total — same source
- **Docyt** (bookkeeping automation; SMB, hospitality, franchise): $12M pre-Series B (Aug 2025), $24M total — same source
- **Vic.ai** (autonomous AP invoice processing): $52M Series C (Dec 2022, older), $115M total — same source

**SMB bookkeeping: tech-enabled services (humans + AI)**
- **Pilot** (startups and SMBs; TES):
  - Total raised is reported as $155M+, $222M (Tracxn), or $325M (PitchBook). The last priced round was the 2021 Series C, which is old.
  - Launched an "AI Accountant" (Feb 2026), a $99/mo AI-only "Essentials" tier, and "Meridian," a month-end close platform (headline June 2026).
  - Also launched a $250K Small Business Growth Fund (Feb 2026).
  - Sources: [Tracxn](https://tracxn.com/d/companies/pilot/__Th2X3okFvgCFodN8q7oEdzficf8tGJCqG5wAA9tJhq4); [PitchBook](https://pitchbook.com/profiles/company/226728-64); [Yahoo Finance, growth fund](https://finance.yahoo.com/news/pilot-launches-250-000-growth-172000492.html); [tooldirectory.ai](https://tooldirectory.ai/tools/pilot-com) (secondary for the product claims)
- **Zeni** (startups; TES, "AI accountant" plus human team): $34M Series B (Aug 2021, older), $48M total. AI Bookkeeping Starter is from $494/mo billed annually ($549 month-to-month). CFO tiers carry $2K–$6K setup fees, and payroll is a $199/mo add-on. Distributed via JPMorgan and SVB startup offer portals — [Toolradar Nov 2026](https://toolradar.com/tools/zeni/pricing); [JPMorgan startup offers](https://startupoffers.jpmorgan.com/vendor/ai-powered-accounting-by-zeni); [SVB offers](https://offers.svb.com/vendor/accounting-finance/zeni-ai-powered-accounting)
- **finally** (Miami, SMB; TES plus software): $50M Series B plus a $150M credit line ($200M debt + equity; Sep 2024, older) — [TechCrunch](https://techcrunch.com/?p=2850315); [newmarketpitch](https://newmarketpitch.com/blogs/news/ai-accounting-top-startups-fundraising)
- **Collective** (solo businesses; bookkeeping, tax, payroll; TES): $40M Series B (Oct 2026) with Intuit Ventures, $110M total — [newmarketpitch](https://newmarketpitch.com/blogs/news/ai-accounting-top-startups-fundraising)
- **Gradient** (AI bookkeeping and close with CPA review): $4M seed, Oct 2026. **Noewe Accounting** (AI-native bookkeeping with human oversight): $550K — same source
- Vertical TES and software: Finaloop (ecommerce, $35M Series A Jun 2024), Ambrook (agriculture, $30M Series B Aug 2026), Fondo (startup bookkeeping and tax, $4.6M seed) — same source

**Adjacent: tax, audit, AR/AP agents**
- **Fieldguide** (audit and advisory platform for firms): $75M Series C (Feb 2026), led by Goldman Sachs Alternatives, $122M+ total — [newmarketpitch](https://newmarketpitch.com/blogs/news/ai-accounting-top-startups-fundraising)
- **Blue J** (tax research and agents): $80M (Nov 2026), $202M+ total
- **Numeral** (sales tax filing): $100M Series C (Sep 2026)
- **Black Ore** (autonomous tax prep for firms): $60M
- **Stuut** (autonomous AR): $52M Series B (Oct 2026)
- **Xelix** (AP and audit): $160M Series B (Jul 2025)
- **AppZen** (finance automation): $180M growth round (Sep 2025), led by Riverwood
- Source for Blue J through AppZen: same source

**Keeper / Booke.ai / Finta / Kick**
- No 2025-2026 funding or pricing data was retrieved for Keeper (tax and bookkeeping for 1099 workers), Booke.ai, or Finta. Kick is listed at $9M total — [newmarketpitch](https://newmarketpitch.com/blogs/news/ai-accounting-top-startups-fundraising)

### Inferences
- Valuation premium is going to companies that **own the system of record** (Rillet, Campfire, DualEntry as ERPs) or **sell to firms with high-value workflows** (Basis, Accrual, Black Ore). SMB "do my books" plays (Pilot, Zeni, Digits, Puzzle) have not raised priced rounds at rising valuations since 2021-2023. This suggests investors see weaker economics there.
- Pricing is converging on **outcome- or work-based models**: Digits charges only for ≥95% zero-touch clients, Hyphenate charges per work that goes live, and Puzzle offers a money-back close guarantee. This is the pricing model a full-autopilot startup would use.
- Pilot's $99 AI-only tier signals TES players compressing price to defend against autopilots, which pressures the SMB price floor (roughly $25–$100/mo for software and $500+/mo for human-backed service).
- Rillet's Mercor example (a 3-person finance team at $2B ARR) is the strongest public proof point that agents replace headcount in the accounting function. It is still a team of 3 humans, though, not zero.
- The "fully replace the accounting manager inside a company" positioning sits between ERP-native (Rillet) and close agents (Numeric, Hyphenate). A company-facing (not firm-facing), outcome-priced controller agent for $5M–$100M revenue companies sitting on QBO/Xero/NetSuite is contested by Hyphenate (≥$50M revenue), Numeric, Stacks, and Digits/Puzzle at the low end, but no one dominates it.

### Gaps
- Revenue/ARR is undisclosed for almost all startups (Rillet gives growth rate only). Customer counts are known only for Rillet (600+), Hyphenate (25+), and Bench (~12K at shutdown).
- Founding years were not systematically retrieved. Prior knowledge, unverified: Pilot 2017, Bench 2012, Digits 2018, Puzzle 2019, Zeni 2019, Rillet 2021, Campfire 2023, Numeric 2022, Basis 2023, Truewind 2022, Docyt 2016, Vic.ai 2016, Fieldguide 2020, Keeper 2019, Kick ~2021.
- Prior knowledge, unverified: Pilot raised at about a $1.2B valuation in 2021 (Series C, $100M, Whale Rock). Basis raised a $34M Series A (Khosla) in 2025. Campfire raised a $35M Series A (Accel) in 2025. Numeric raised a $28M Series A (Menlo) in 2025. Light raised a $30M Series A led by Balderton (Sept 2025).
- The aggregator (newmarketpitch) dates and round labels have some inconsistencies (e.g., Pilot's "latest round" label). Verify before citing precise round names.
- India: no India-specific data retrieved. Prior knowledge, unverified: Zoho Books (with Zia AI), and India-based offshore bookkeeping/BPO firms serving US CPAs are a major substitute.
- UK/EU: Pennylane (FR), Light (DK), Dougs (FR, $55M growth Oct 2026), Stacks (NL), and Xero/Sage UK dominance were noted. No deeper UK data was retrieved.

---

## 3. AI-native accounting firm roll-ups / PE roll-ups of CPA firms

### Takeaway
The biggest-dollar competition to a pure software autopilot is now capital-heavy "buy the CPA firm and rewire it with AI" plays. Thrive Holdings' Current (ex-Crete) is the largest: ~$1B committed, ~50 firms, OpenAI partnership. General Catalyst does this via its $1.5B Creation fund (Accrual, Long Lake-style). Multiplier and Modus are smaller. These own the client relationship and trust (the CPA signature), which is the hardest asset for software startups to acquire.

### Cited Findings
- **Thrive Holdings / Current (formerly Crete Professionals Alliance):**
  - Thrive Holdings is committing about $1B to buying local accounting practices and rewiring them with AI. It runs them through operating company Current, which had pulled together close to 50 practices as of June 2026.
  - It was reportedly in talks to raise about $2B from investors including SoftBank, Altimeter, and D1. One unconfirmed source reports $2B raised at a $12B valuation.
  - Sources: [Forbes, June 2 2026](https://www.forbes.com/sites/annatong/2026/06/02/thrive-holdings-to-bet-1-billion-on-ai-powered-accounting-roll-up/) (paywalled; details via search summary); [agentclawhq, unconfirmed](https://www.agentclawhq.com/blog/openai-thrive-accounting-rollup)
- Crete earlier announced a $500M, two-year acquisition budget using OpenAI tools (June 2025). Selling partners keep a minority equity stake in the local business, unlike classic PE — [Tech Startups](https://techstartups.com/2025/06/04/thrive-backed-crete-to-acquire-accounting-firms-with-500m-boost-growth-using-openai-tools/); [Yahoo Finance](https://finance.yahoo.com/news/thrive-backed-accounting-firm-crete-130200467.html)
- **General Catalyst / Accrual:**
  - Launched Feb 5, 2026, with $75M (described as two rounds) led by General Catalyst, with Go Global Ventures, Pruven Capital, and Edward Jones Ventures. Accounting Today says $65M came from GC.
  - Product: AI tax prep and review for firms, starting with individual returns.
  - Design partners include H&R Block, Armanino, Creative Planning, and other Top 100 firms.
  - Founders are ex-Brex/Stripe leaders. It is part of GC's $1.5B Creation fund. A $300M valuation appears on Dealroom only (unconfirmed).
  - Sources: [Business Wire](https://www.businesswire.com/news/home/20260205968515/en/Accrual-Launches-with-$75-Million-to-Bring-AI-Native-Automation-to-Accounting); [Bloomberg](https://www.bloomberg.com/news/articles/2026-02-05/general-catalyst-backed-startup-raises-75-million-to-bring-ai-to-accounting); [Accounting Today](https://www.accountingtoday.com/articles/general-catalyst-backed-startup-raises-75m-to-bring-ai-to-accounting); [General Catalyst](https://www.generalcatalyst.com/stories/our-investment-in-accrual)
- GC's Marc Bhargava frames the goal as enabling firms to take on 2–3x more clients with AI, not cutting staff — [Jupid blog](https://jupid.com/blog/who-is-buying-accounting-firms-2026) (secondary)
- **Other roll-ups:** Multiplier has raised $62.5M and bought 8 firms. Modus raised $85M for audit-first deals and is an AI-native audit firm (Series A, Apr 2026) — [Jupid](https://jupid.com/blog/who-is-buying-accounting-firms-2026); [newmarketpitch](https://newmarketpitch.com/blogs/news/ai-accounting-top-startups-fundraising)
- **Software for firms competes in parallel:**
  - Basis ($1.15B) and Ramp Stack (June 2026)
  - Clark: $11M seed, Nov 2026
  - Ravical: $17M seed, Oct 2026
  - Repodo: $9M pre-seed, Aug 2026
  - Kabilio: ~$12M, Nov 2026
  - Accordance: $10M seed
  - Sources: [newmarketpitch](https://newmarketpitch.com/blogs/news/ai-accounting-top-startups-fundraising); [rework.com](https://resources.rework.com/tools/ai-agents/best-ai-agents-for-finance-2026)
- VC framing of accounting firms as "ripe for AI-led rollups" — [The Finance Story](https://thefinancestory.com/vc-backing-ai-led-accounting-firm-rollups); [footnote.news](https://footnote.news/p/private-equity-bet-accounting-was-a-fortress-ai-is-lowering-the-walls)

### Inferences
- Roll-ups compete with a company-facing autopilot by offering the same outcome (books, close, tax) with a licensed CPA's signature and an existing relationship. They are effectively AI-augmented TES at scale with better gross margins over time.
- They also become **channel partners or acquirers**: a roll-up with ~50 firms and thousands of SMB clients needs an autopilot engine. Selling the engine to roll-ups (as Basis does) may be easier than displacing them.
- Roll-ups are focused on tax and audit (high-fee, regulated) more than monthly bookkeeping. Monthly controller work for mid-sized private companies is less directly targeted.

### Gaps
- No revenue or margin data for Current/Crete, Multiplier, or Modus was retrieved. The Forbes article was paywalled (403).
- Other PE platforms (e.g., Citrin Cooperman, Baker Tilly, Grant Thornton PE deals) were not researched this session. Prior knowledge, unverified: over 25 of the top-100 US CPA firms had taken PE money by 2025.

---

## 4. Where is the market saturated vs underserved? What moats exist?

### Takeaway
**Saturated:** SMB transaction categorization and bank reconciliation (every incumbent plus 20+ startups), AP invoice capture and coding (BILL, Ramp, Brex, Vic.ai, Stampli, Ottimate), and venture-funded AI-native ERPs for startups (Rillet, Campfire, DualEntry, Light). **Underserved:** true end-to-end ownership of the close and controller sign-off for $5M–$100M revenue private companies on legacy QBO/Xero/NetSuite stacks, with outcome pricing and minimal human contact. Hyphenate, Numeric, and Stacks are moving here but are early (Hyphenate has 25+ customers). Moats are distribution (bank and ERP channels), system-of-record ownership, accuracy proof, and trust (CPA signature, audit trail).

### Cited Findings
- **Crowding:** an aggregator tracks 185 funded AI accounting startups and another tracks 53 AI-native accounting and finance-ops companies — [newmarketpitch](https://newmarketpitch.com/blogs/news/ai-accounting-top-startups-fundraising); [teahose](https://www.teahose.com/themes/ai-native-accounting-finance-ops)
- **Distribution via banks:** Zeni is distributed through JPMorgan and SVB startup offer portals. BOB bundles an AI finance agent with banking — [JPMorgan offers](https://startupoffers.jpmorgan.com/vendor/ai-powered-accounting-by-zeni); [SVB offers](https://offers.svb.com/vendor/accounting-finance/zeni-ai-powered-accounting); [newmarketpitch](https://newmarketpitch.com/blogs/news/ai-accounting-top-startups-fundraising)
- **Distribution via accounting firms:**
  - Digits' outcome pricing for firms requires ≥95% zero-touch transactions.
  - BILL is favored by firms for its multi-client console.
  - Ramp Stack targets firms.
  - Sources: [CPA Practice Advisor](https://www.cpapracticeadvisor.com/2026/04/07/digits-announces-outcome-based-pricing-for-accounting-firms/181110/); [rework.com](https://resources.rework.com/tools/spend-expense/ramp-vs-bill-com)
- **System of record moat:**
  - Rillet replaces NetSuite, SAP, Workday, and others.
  - A counter-strategy is bolting billing or rev-rec tools onto NetSuite to avoid migration. This is the "integrate, don't replace" path an autopilot agent would use.
  - Sources: [Business Wire](https://secure.businesswire.com/news/home/20260819978953/en/Rillet-Raises-$100M-Series-C-at-$1B-Valuation-to-Build-Accounting-Superintelligence); [Sacra](https://sacra.com/c/rillet/)
- **Trust and approval design:**
  - Xero JAX asks for approval and logs every action.
  - Brex's Review Agent auto-approves low-risk items and escalates the rest.
  - Agent F markets "agents with approval."
  - Gradient and Noewe market CPA review or human oversight.
  - Sources: [curatesuite](https://curatesuite.com/accounting/articles/sage-copilot-vs-intuit-assist); [rework.com](https://resources.rework.com/tools/ai-agents/best-ai-agents-for-finance-2026); [newmarketpitch](https://newmarketpitch.com/blogs/news/ai-accounting-top-startups-fundraising)
- **Accuracy benchmarks published:**
  - Ramp AP Agent: 85% first-attempt GL coding.
  - Xero: >80% of bank lines auto-reconciled.
  - Hyphenate: ~90% reduction in repetitive work and ~75% fewer audit exceptions.
  - All are vendor claims.
  - Sources: [rework.com](https://resources.rework.com/tools/ai-agents/best-ai-agents-for-finance-2026); [FinTech Futures](https://www.fintechfutures.com/venture-capital-funding/newly-rebranded-hyphenate-lands-45m-series-a)

### Inferences
- An 85% first-pass accuracy on GL coding (Ramp) means about 15% of items still need human touch, which is far from "minimal human contact." Closing that last 5–15% (judgment items such as accruals, revenue recognition, and unusual transactions) is the actual technical moat and the claim a new entrant must prove.
- Underserved segments:
  1. Lower mid-market ($5M–$50M revenue) companies that are too complex for QBO auto-categorization but cannot afford a controller ($150K+). Hyphenate starts at $50M+, and Rillet requires an ERP migration.
  2. Multi-entity/franchise and vertical businesses (Docyt is in hospitality/franchise).
  3. Non-venture-backed "main street" businesses that are underserved by Silicon Valley-focused players (Pilot, Zeni, Digits, Puzzle, Synthetic all target startups).
- Likely durable moats for an autopilot: (a) a proprietary labeled-correction dataset across many ledgers, (b) deep write-access integrations into QBO, Xero, and NetSuite plus banks and payroll, (c) distribution through banks, PEOs, payroll providers, or CPA roll-ups, and (d) assurance artifacts (audit trail, SOC 1/2, CPA sign-off partner, or an accuracy guarantee like Puzzle's money-back offer).
- Incumbent dependency risk: Intuit and Xero control API access to the ledgers that most SMB autopilots sit on top of.

### Gaps
- No independent (non-vendor) benchmark of autopilot accuracy or zero-touch rates was found.
- No market-sizing data (TAM for outsourced bookkeeping or controller services) was retrieved this session.
- No data on API access restrictions or pricing changes by Intuit or Xero toward third-party AI apps in 2025-26.

---

## 5. Notable failures and why (Bench, others)

### Takeaway
Bench, the largest VC-backed US bookkeeping TES (~12K customers, 600+ staff), abruptly shut down on Dec 27, 2024. It locked customers out at year-end and was bought days later by Employer.com, a buyer with no accounting background. The root cause was not officially disclosed. The lesson usually drawn is that human-heavy bookkeeping at low SMB price points has poor unit economics, and that customer trust and data portability are existential in this category.

### Cited Findings
- Bench shut down on Dec 27, 2024. On Dec 30 it said it was being acquired by Employer.com. Bench had about 12,000 customers — [TechCrunch](https://techcrunch.com/2024/12/30/bench-to-be-acquired-after-abruptly-shutting-down); [CPA Practice Advisor](https://www.cpapracticeadvisor.com/2024/12/30/employer-com-set-to-acquire-bench-accounting/153755/)
- It abruptly locked customers out of their accounts just before year-end and tax season, which caused backlash — [PYMNTS](https://pymnts.com/smbs/2024/online-bookkeeping-platform-bench-accounting-announces-abrupt-shutdown); [GeekWire](https://www.geekwire.com/2024/bench-accounting-to-be-acquired-by-employer-com-following-abrupt-shutdown/)
- Bench had over 600 employees before the shutdown, and only some were invited back — [TechCrunch, inside the fall](https://techcrunch.com/2025/01/03/inside-the-wild-fall-and-last-minute-revival-of-bench-the-vc-backed-accounting-startup-that-imploded-over-the-holidays)
- Employer.com had no accounting experience. Its CEO saw the news while on vacation, and the deal was struck in about 36 hours. BetaKit reported that an M&A process had started earlier in 2024, which conflicts with the fast-deal story — [American Banker](https://www.americanbanker.com/news/why-employer-com-bought-fintech-bench-days-after-it-shut-down); [BetaKit](https://betakit.com/?p=381640)
- Customers could port their data or stay. Bench resumed operations in Jan 2025 as an Employer.com subsidiary — [Accounting Today](https://accountingtoday.com/news/bench-acquired-by-employer-com-after-sudden-shutdown); [Wikipedia](https://en.wikipedia.org/wiki/Bench_Accounting)
- Competitors still market directly against Bench and Pilot displacement, e.g., Puzzle's "Pilot alternatives" page and Pilot's "Puzzle alternatives" page — [Puzzle](https://puzzle.io/pilot-alternative); [Pilot](https://pilot.com/blog/puzzle-alternatives)

### Inferences
- Bench's lessons for an autopilot founder:
  1. A proprietary ledger with no easy export creates catastrophic trust risk. Build on, or export cleanly to, a standard GL (QBO/Xero) or offer guaranteed data portability.
  2. Labor-heavy service at about $300–$500/mo does not scale profitably. Autopilot gross margins must actually reach software levels, not "AI-washed" TES.
  3. SMB churn and price sensitivity are high, and tax-season timing creates concentrated operational risk.
- Pilot's 2026 pivot to a $99 AI-only tier and an "AI Accountant" suggests TES survivors are trying to convert into software margins, validating Bench's lesson.
- Many 2021-era AI bookkeeping players (Zeni, Digits, Puzzle, Pilot, Vic.ai) have not announced priced equity rounds since 2021–2023, which may indicate down-round or flat-round risk. This is unconfirmed.

### Gaps
- Bench's total funding and debt details were not retrieved this session. Prior knowledge, unverified: about $113M raised (Shopify, iNovia, Bain Capital Ventures) and a ~2024 venture debt burden.
- No other confirmed 2025-2026 shutdowns of AI accounting startups were found. Acquisitions noted in the aggregator: Fifteenth, Finmatics, Materia (acquired by Thomson Reuters, prior knowledge, unverified), and Midship — [newmarketpitch](https://newmarketpitch.com/blogs/news/ai-accounting-top-startups-fundraising)
- Prior knowledge, unverified: Botkeeper (AI bookkeeping for firms, ~$90M raised) had layoffs and struggles. ScaleFactor (AI bookkeeping, $100M raised) shut down in 2020 after it was revealed to rely heavily on human bookkeepers behind "AI." This is a classic cautionary tale for autopilot claims. Verify before citing.
