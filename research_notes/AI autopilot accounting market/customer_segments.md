# Customer Segments and Buyer Demand for an "Autopilot" AI Accounting Manager (as of Nov 2026)

Scope: US first, with brief international notes. Most figures come from search-result summaries of the linked pages. Only the BLS page was fetched and checked directly; the SBA FAQ PDF returned HTTP 403. Vendor-sponsored surveys are flagged as such.

## Segments: who exists and how many (sizing)

### Takeaway
The US has about 36.2M small businesses. Most are nonemployers (about 30.4M); roughly 6.4M are employer firms. There are about 200k mid-market companies ($10M-$1B revenue). Software penetration is high: QuickBooks Online has 8.9M paying customers worldwide (mostly US) and Xero has about 4.9M subscribers globally, of which roughly 0.4M are in North America. For autopilot accounting, the strongest early-wedge candidates are the ~6.4M employer SMBs already on QBO/Xero who pay for bookkeeping, and the accounting firms that serve them.

### Cited Findings
- **Total small businesses:** about 36.2M US small businesses (firms with fewer than 500 employees), 99.9% of all US businesses. They employ 62.3M people, or 45.9% of private employees. Source: SBA Office of Advocacy 2025 national profile, released June 30, 2025. — [SBA Advocacy 2025 US Profile](https://advocacy.sba.gov/wp-content/uploads/2025/06/United_States_2025-State-Profile.pdf); [SBA press release (>36M)](https://advocacy.sba.gov/?p=30239)
- **Employer firms:** the SBA Advocacy 2026 FAQ (search snippet) gives 6,395,635 employer firms and 21,041 large businesses. The number of small employer firms has risen every year since 2011. The snippet did not make clear whether 6.4M counts only small employers or all employers. — [SBA Advocacy FAQ 2026](https://advocacy.sba.gov/wp-content/uploads/2026/02/FINAL_FAQsAboutSmallBusiness_2026_012826.pdf)
- **Nonemployers:** 30,427,808 nonemployer establishments in 2023 (up from 29.8M in 2022), with about $1.8T in receipts. Nonemployers grew about 2.7% a year from 2012 to 2023, faster than employer businesses in nearly every year. — [Census 2023 Nonemployer Statistics release](https://www.census.gov/newsroom/press-releases/2025/2023-nonemployer-statistics.html); [Census story](https://census.gov/library/stories/2025/07/nonemployer-business-growth.html)
- **Mid-market:** the National Center for the Middle Market defines the middle market as $10M-$1B in revenue and counts nearly 200,000 such US businesses. RSM uses a $30M-$10B band and counts about 125,000. — [ABF Journal on NCMM](https://www.abfjournal.com/the-200000-company-landscape-where-institutional-capital-still-falls-short-in-the-u-s-middle-market/); [RSM](https://rsmus.com/insights/economics/redefining-the-american-middle-market-for-the-modern-era.html)
- **QuickBooks Online base:** 8.9M total Online paying customers at the end of FY2026 (July 31, 2026), up 3% year over year. Growth slowed about 2 points from the prior year. Intuit says it will push harder to acquire customers new to the franchise in FY27. — [Intuit Q4 FY26 earnings script](https://investors.intuit.com/_assets/_64f3415e6601d7a94d9a083d8f6622dc/intuit/db/946/10378/webcast_transcript/Q4+FY26+Earnings+Script.pdf); [Trefis](https://www.trefis.com/articles/613541/intuits-real-problem-is-not-on-its-income-statement/2026-08-28)
- **Xero base and revenue:** FY26 (to March 31, 2026) revenue was about NZ$2.8B, up 31%, helped by the Melio (US payments) acquisition. Subscribers were about 4.92M (+11%). A stock-data page shows North America at about 419k subscribers (period unconfirmed). — [Rask Media](https://www.raskmedia.com.au/2026/05/14/xero-asxxro-share-price-on-watch-after-31-growth-in-fy26-result/); [Capital Brief](https://www.capitalbrief.com/briefing/xero-posts-31-jump-in-full-year-revenue-as-melio-growth-accelerates-88005c35-c976-4785-bad7-21212346943e/); [stockanalysis.com](https://stockanalysis.com/quote/fra/0XE/financials/metrics)
- **Accounting firms as buyers and acquirers:**
  - Accounting firm M&A set a record in 2025, with transaction volume up 26% (Capstone, via CPA Practice Advisor). — [CPA Practice Advisor](https://www.cpapracticeadvisor.com/2026/07/28/accounting-firm-ma-had-a-record-2025/187499/)
  - Nearly half of the top 30 US CPA firms had PE investment or an alternative practice structure by early 2026. — [CPA Practice Advisor](https://www.cpapracticeadvisor.com/2026/09/09/financial-engineer-or-operator-how-to-choose-the-right-buyer/189932/)
  - Numica, which describes itself as an "AI-first" acquirer of small US firms (billings as low as about $700k), raised about $21.5M in Nov 2026. — [CPA Practice Advisor](https://cpapracticeadvisor.com/2026/11/06/private-equity-group-raises-21-5m-to-acquire-small-accounting-firms/193246)
  - Grant Thornton agreed to buy CBIZ for about $5B, which coverage frames as a response to pressure from PE and AI in the mid-market. — [Bloomberg Tax](https://news.bgov.com/financial-accounting/grant-thornton-cbiz-merger-raises-bar-in-battle-over-mid-market)
  - A secondary LinkedIn source counts 62 accounting M&A deals in 2026 YTD (57 PE-backed, 15 "tech-first"). Treat this cautiously. — [LinkedIn post](https://hk.linkedin.com/in/stefanopassarello)
  - Bloomberg Tax describes PE's push into public accounting as reflecting a "tech shock." — [Bloomberg Tax](https://news.bloombergtax.com/daily-tax-report/private-equitys-public-accounting-push-reflects-a-tech-shock)

### Inferences
- **Practical serviceable market:** the 6.4M employer firms, not all 36M. Most of the 30M nonemployers are side businesses with low transaction volume and very low willingness to pay; they are a self-serve, sub-$50/mo market that QBO, Xero and banks already address.
- **QBO + Xero North America is about 9M ledgers already in the cloud.** That makes "integrates with minimal human contact" plausible through API connectors. It also means Intuit and Xero are the incumbents, building their own agents (Intuit's AI agents, Xero's JAX), and they control distribution.
- **Best wedge by economics:** employer SMBs with about $1M-$20M revenue that already pay $400-$2,500/mo for outsourced bookkeeping. They feel the cost directly, have messy multi-system data, and lack a controller. VC-backed startups are a well-known sub-segment: high willingness to pay, high software tolerance, and already served by Pilot, Puzzle and Digits.
- **Mid-market (~200k firms):** fewer accounts, but each would pay roughly controller-salary-equivalent value. They have a longer sales cycle, ERP complexity (NetSuite/Intacct), and need auditors to sign off.
- **CPA firms, especially PE-backed and AI-native rollups, are an emerging buyer.** Their thesis is to buy firms and strip labor cost with automation, so they are natural design partners and channel buyers for an autopilot engine.

### Gaps
- No verified 2025-2026 count of US VC-backed startups (Carta or PitchBook). Search did not return it.
- No reliable US counts of Amazon or Shopify sellers, or of restaurants, real-estate firms, healthcare practices or agencies with accounting spend.
- No authoritative total count of US CPA firms. AICPA and IRS data were not found in this pass.
- Could not confirm whether the SBA's 6.4M figure covers only small employers. The FAQ PDF returned 403.
- QBO's 8.9M is global "Online" paying customers, not US-only QBO accounting subscribers.

## Pain points: talent shortage, labor cost, close, compliance, outsourcing cost

### Takeaway
Demand for automation rests on two real forces.
- **A shrinking accounting talent pipeline.** Accounting graduates are at roughly 20-year lows, and the widely cited 300k+ departures are reported via WSJ/BLS.
- **Expensive human labor.** Bookkeeping clerks have a $50.7k median salary, staff accountants $74k and controllers $185k midpoint. Outsourced bookkeeping typically costs $300-$1,500+/mo. BLS itself projects bookkeeping-clerk jobs to fall because of software automation.

### Cited Findings
- **Graduates:** US accounting degree completions fell 6.6% to 55,152 in the 2023-24 academic year (AICPA 2025 Trends). The decline is slowing. — [Journal of Accountancy](https://www.journalofaccountancy.com/news/2025/oct/the-accounting-graduate-pipeline-where-do-things-stand/); [CFO Dive](https://www.cfodive.com/news/us-accounting-degree-graduates-drop-talent-shortage/803914/); [CPA Trendlines: 20-year low](https://cpatrendlines.com/?p=150829)
- **CPA exam candidates:** new candidates spiked to 42,626 in 2023, then fell about 34% in 2024. The swing came from the CPA Evolution exam changeover. 2025 showed a rebound, with 16,448 new candidates in the first half. — [Journal of Accountancy](https://www.journalofaccountancy.com/news/2025/oct/the-accounting-graduate-pipeline-where-do-things-stand/)
- **Firm hiring:** 75% of public accounting firms surveyed hired accounting graduates in 2024 and expected to maintain or increase hiring. Demand still exceeds supply. — [AICPA](https://www.aicpa-cima.com/news/article/accounting-firms-report-strong-hiring-outlook-aicpa-report-finds); [CFO Brew](https://www.cfobrew.com/stories/2025/10/28/demand-for-accounting-grads-still-outstrips-supply)
- **The 300k+ departures figure:** more than 300,000 US accountants and auditors left their jobs, a reported 17% decline. The figure comes from WSJ analysis of BLS data and covers roughly 2019-2021/22. Sources disagree on the exact window, and I could not retrieve the original WSJ article. Departures were concentrated among 25-34 and 45-54 year-olds. — [Fox Business (WSJ)](https://www.foxbusiness.com/economy/why-accountants-quitting); [McGraw Hill on WSJ](https://mheducation.com/highered/blog/2024/06/check-out-this-wall-street-journal-article-on-why-so-many-accountants-are-quitting); [Becker's](https://www.beckershospitalreview.com/finance/an-exodus-of-accountants/)
- **BLS bookkeeping, accounting and auditing clerks:**
  - Median pay was $50,670/yr ($24.36/hr) in May 2025, across 1,532,400 jobs in 2025.
  - BLS projects a 6% decline (-85,600 jobs) from 2025 to 2035 because "software innovations have automated many of the tasks."
  - Source: [BLS OOH](https://www.bls.gov/ooh/office-and-administrative-support/bookkeeping-accounting-and-auditing-clerks.htm)
- **Robert Half 2026 Salary Guide national midpoints:**
  - Corporate controller: $185,000 (range $152,000-$213,250)
  - Senior accountant: $94,750
  - Staff accountant: $73,750 ($61,000-$87,750)
  - Entry-level staff accountant: $62,000
  - The 2027 guide has since appeared; its senior accountant midpoint is $96,750.
  - Source: [Robert Half salary guide](https://www.roberthalf.com/us/en/insights/salary-guide/finance-and-accounting); [Robert Half senior accountant](https://www.roberthalf.com/us/en/insights/career-development/whats-the-typical-senior-accountant-salary); [Robert Half staff accountant](https://www.roberthalf.com/us/en/insights/career-development/building-your-careeer-as-a-staff-accountant-salary)
- **Outsourced bookkeeping prices (third-party roundups, 2026):**
  - Pilot: from $399/mo (monthly) or $599/mo (weekly). Core plan is priced by expense volume.
  - Bench: Grow from $199, Core from $399, Core + Tax from $599 per month. Pelcro lists Bench Bookkeeping + Tax at $649, so sources disagree.
  - Bookkeeper360: from about $400/mo, custom-quoted.
  - Typical SMB range is $300-$1,500/mo. Micro businesses under 100 transactions/mo pay about $300-$500; established SMBs with payroll and AP pay about $900-$1,500.
  - Sources: [Fit Small Business](https://fitsmallbusiness.com/best-online-bookkeeping-services/); [NerdWallet](https://www.nerdwallet.com/business/software/learn/bookkeeping-pricing); [Pelcro](https://www.get.pelcro.com/blog/best-online-bookkeeping-services); [TechRepublic](https://www.techrepublic.com/fr/article/best-online-bookkeeping-services/)

### Inferences
- **Cost to beat:** an SMB that hires in-house pays about $51k (clerk) to $74k (staff accountant) plus benefits. One that outsources pays about $4k-$18k a year. One that needs controller-level oversight pays $150k+ or a fractional CFO/controller. A credible autopilot product can price at about $200-$1,000/mo for SMBs and still be a fraction of human cost.
- **The talent shortage hits accounting firms hardest.** They lack staff to take on more clients, which makes "capacity" a strong value proposition for selling to firms.
- **BLS projecting job loss from automation is useful, neutral evidence** that the work is automatable. Expect incumbents (Intuit, Xero, Pilot, Bench) to compete on the same claim.

### Gaps
- No reliable 2025-2026 quantitative data on month-end close duration or SMB bookkeeping error rates. Benchmarks such as APQC or Ventana were not found in this pass.
- No survey quantifying SMB hours spent on bookkeeping or tax compliance (e.g., NFIB) was retrieved.
- The original WSJ article with the 300k figure was not retrieved.

## Willingness to pay and trust in AI acting autonomously

### Takeaway
SMBs widely say they "use AI," but paid adoption is low: Intuit's payment data puts it at about 12% of US SMBs over 2021-2025. Trust in AI acting without review is the binding constraint. About 67% of owners would not let an AI agent spend money without approving each transaction, and about 78% don't fully trust AI on low-level tasks without oversight. The product should be sold as "autopilot with approvals and guardrails," not full autonomy.

### Cited Findings
- **Intuit 2026 AI Impact Report:**
  - Paid AI adoption from 2021-2025 was 12% of US SMBs (Canada 11%, UK 7%), measured from anonymized payment records of 4.3M+ US businesses on the Intuit platform. Intuit calls paid use "still a minority behavior."
  - Self-reported regular AI use is about 77% in the US.
  - Source: [Intuit AI Impact Report](https://www.intuit.com/blog/global-stories/ai-impact-report/); [PDF](https://digitalasset.intuit.com/render/content/dam/intuit/sbseg/en_us/Blog/Downloadable-assset/2026-ai-impact-report.pdf); [Stacker: 77%](https://stacker.com/stories/small-business/77-small-businesses-now-use-ai-regularly-heres-where-theyre-starting)
- **Intuit Small Business Insights:** 71% of small businesses regularly used AI tools in July 2025, versus 39% a year earlier. The 2025 Small Business Index found 23% cite cost as the top barrier to adopting digital tools. Note that the CNBC piece reporting this is sponsored by Intuit. — [CNBC Select](https://www.cnbc.com/select/6-ways-ai-helps-business-owners-manage-their-finances/); [Bill.com blog](https://www.bill.com/blog/smbs-are-leveraging-ai)
- **AI in accounting specifically:** a Verizon survey found only 21% of SMBs use AI tools to manage accounting and financial operations. — [Bill.com blog citing Verizon](https://www.bill.com/blog/smbs-are-leveraging-ai)
- **Trust in AI for money tasks:**
  - Bill.com reports 90% of SMBs have high (40%) or moderate (50%) trust in AI for financial operations. This is vendor data and the survey is not specified. — [Bill.com](https://www.bill.com/blog/smbs-are-leveraging-ai)
  - In a survey cited by Relay, 64% would trust AI to manage cash flow, 48% would trust it to track income and expenses, and 14% don't trust it at all. — [Relay](https://relayfi.com/blog/small-business-ai-trends/)
- **Autonomy limits:**
  - Small Business Expo survey of 285 owners: 67.0% would not let an AI agent spend money without approving each transaction. 14.4% would allow it up to a preset limit, 8.1% without restriction, and 10.5% were unsure. Small sample. — [Small Business Expo](https://www.thesmallbusinessexpo.com/blog/ai-in-the-workplace/)
  - Bluevine-commissioned survey of 942 owners: 78% don't fully trust AI to handle low-level tasks without oversight. Stacker headline: "3/4 of small businesses don't trust AI for basic tasks." — [Bluevine 2026 report](https://www.bluevine.com/blog/small-business-ai-trends-report-2026); [Stacker](https://stacker.com/stories/small-business/34-small-businesses-dont-trust-ai-basic-tasks)
  - Simply Business survey of 1,047 US owners: owners keep "a human hand on the wheel" for finances, insurance and customer trust. — [Simply Business](https://www.simplybusiness.com/small-businesses-are-using-ai-but-theyre-not-letting-it-run-the-show-2026-outlook/)
  - PayPal (June 2025): "Small Businesses Ready for AI That Acts, Not Just Assists." This is a vendor survey; details were not retrieved. — [PayPal newsroom](https://newsroom.paypal-corp.com/2025-06-18-Small-Businesses-Ready-for-AI-That-Acts-Not-Just-Assists)
- **Clients of accounting firms** back AI use but demand transparency (Karbon, July 2026). — [IT Brief](https://itbrief.com.au/story/clients-back-ai-in-accounting-but-demand-transparency)

### Inferences
- **Willingness to pay is anchored on existing spend:** QBO or Xero subscriptions plus $300-$1,500/mo for outsourced bookkeeping (see the pain-points section). An autopilot product that replaces the bookkeeper captures that budget. One sold as add-on software competes with about 12% paid-AI adoption and cost sensitivity.
- **Trust gradient:**
  - Read-only and categorization tasks (reconciliation, categorization, reporting): high trust.
  - Cash flow guidance: moderate.
  - Moving money (bill pay, payroll): low. A minority, about 22%, would allow autonomous spending even with limits.
  - Implication: autonomous bookkeeping and close can lead; AP and payments should run behind approval thresholds.
- **Bundling human sign-off reduces trust friction.** A CPA reviews the output, or an accounting firm white-labels it. This is a likely reason hybrid "AI + human" models (Pilot, Bench successors, AI-native firms) dominate.

### Gaps
- No 2025-2026 Xero or Gusto survey on SMB willingness to let AI act without review was found.
- No direct price-sensitivity study (e.g., Van Westendorp) for AI bookkeeping was found.
- Survey wording differs across sources; the numbers are not directly comparable.

## Buyer personas, decision process and channels

### Takeaway
- **SMBs:** the founder/owner is the buyer and signs. Distribution flows through the accountant or bookkeeper (who chooses and influences the ledger software) and through platforms (QBO/Xero app stores, banks, payroll providers).
- **Mid-market:** the controller or CFO decides, with audit and governance concerns.
- **Accounting firms:** partners decide. Firms are near-universal AI users but lack governance, and PE-backed firms are now buying technology aggressively.

### Cited Findings
- **Accounting firm AI use (Karbon, State of AI in Accounting 2026; 593 respondents surveyed Oct 2025, mostly US; vendor report):**
  - 98% of firms use AI, mostly daily.
  - ChatGPT is used by 87%, Karbon AI by 61%, Microsoft Copilot by 53%.
  - 70% report efficiency gains.
  - Sources: [Karbon](https://karbonhq.com/resources/state-of-ai-accounting-2026/); [PDF](https://a.storyblok.com/f/321253/x/e2116b7c8a/the-state-of-ai-in-accounting-report-2026-by-karbon.pdf); [CFOtech](https://cfotech.asia/story/accountants-embrace-ai-tools-as-scepticism-increases)
- **Firm AI governance:** only 21% of firms have a documented AI policy covering client disclosure. — [IT Brief](https://itbrief.com.au/story/clients-back-ai-in-accounting-but-demand-transparency)
- **Tech-forward firms:** they generate 28% more revenue per employee than cautious adopters (Karbon, State of Technology in Accounting 2027, Oct 2026). — [Karbon](https://karbonhq.com/resources/accounting-technology-report-2027-karbon/)
- **AI is reshaping firm staffing structures.** — [Accounting Today](https://www.accountingtoday.com/news/ai-leading-to-shifts-in-firm-personnel-structures)
- **Intuit accountant survey (July 2025):** accountants are embracing AI and shifting toward strategic advisory, a channel signal. — [Intuit investor PDF](https://investors.intuit.com/_assets/_6a9ee074199c0a511699c988d19108db/intuit/news/2025-07-30_Accountants_Embrace_AI_and_Strategic_Advisory_1263.pdf)
- **PE-backed firm ownership:** PE-backed CPA platforms (nearly half of the top 30) and AI-first acquirers (Numica) are centralized technology buyers. AICPA rules require CPA firms to be majority-owned by licensed CPAs, which shapes how these structures work (alternative practice structures). — [CPA Practice Advisor](https://www.cpapracticeadvisor.com/2026/09/09/financial-engineer-or-operator-how-to-choose-the-right-buyer/189932/); [Thomson Reuters on PE](https://www.thomsonreuters.com/en-us/posts/tax-and-accounting/pe-enable-tech-growth)
- **Xero's US distribution** is increasingly payments-led through Melio. — [Motley Fool AU](https://www.fool.com.au/2026/02/03/xero-highlights-ai-progress-and-melio-momentum-in-us-market-update/)

### Inferences
- **Personas:**
  1. SMB owner/founder: economic buyer, values time and cost, low accounting literacy, wants "done for you."
  2. Fractional CFO or outsourced controller: an influencer who may resist the product or adopt it as leverage.
  3. Startup finance lead: fast self-serve evaluation, often tied to VC or bank (Brex/Mercury) ecosystems.
  4. Mid-market controller/CFO: needs audit trail, SOX-lite controls and ERP integration. Sales cycle is likely 3-9 months.
  5. CPA firm partner or PE platform COO: buys for capacity and margin across many clients. One deal can bring hundreds of client ledgers.
- **Channels by likely efficiency:**
  - Accountant/firm partnerships, since accountants influence most SMB software choices.
  - QBO/Xero app marketplaces, which are easy to reach but where the incumbent can compete.
  - Banks, neobanks and payroll providers (Gusto, ADP), for embedded distribution.
  - Direct self-serve, for startups and e-commerce sellers.
- **Sales cycle length** is not documented in the sources found. The figures above are reasoned estimates only.

### Gaps
- No sourced data on sales-cycle length, or on the share of SMBs whose accountant chose their ledger software.
- No sourced data on bank or payroll distribution partnerships for AI bookkeeping.
- No qualitative Reddit or forum sentiment was gathered in this pass, due to the tool-call budget.

## Adoption data: CFO and finance-team AI agent deployment

### Takeaway
Finance AI is widely used (about 59-63% of finance functions). Fully integrated agents remain rare (about 14%), and only about 21% of leaders see tangible value so far. Finance leaders are comfortable with agentic workflows but not with full autonomy on critical decisions; only 14% support that. Budgets are rising, and the fastest-payback use cases are AP/AR automation, data extraction and reporting.

### Cited Findings
- **Gartner adoption:** 59% of finance leaders reported AI use in their finance function in 2025 (survey of 183), and adoption growth had slowed. Another Gartner figure says only 4% have moved beyond pilots (undated page). — [Gartner Nov 2025](https://www.gartner.com/en/newsroom/press-releases/2025-11-18-gartner-survey-shows-finance-ai-adoption-remains-steady-in-2025)
- **Gartner value focus (March 2026 survey of 204):** 45% of CFOs say AI investment leans toward productivity, versus 20% toward decision quality. 63% said 2025 implementation was slower than expected. — [Gartner Jul 2026](https://www.gartner.com/en/newsroom/press-releases/2026-07-20-gartner-survey-shows-45-percent-of-cfos-say-their-ai-investments-lean-towwards-productivity-while-20-percent-say-these-investments-lean-towards-decision-quality); [Gartner May 2026](https://www.gartner.com/en/newsroom/press-releases/2026-05-28-gartner-says-cfos-must-stop-mistaking-finance-ai-deployment-for-value-creation)
- **Gartner payback (Sept 2026, 160 finance leaders):** data extraction, AP/AR automation and report creation generally return value within 9-10 months. — [Gartner Sep 2026](https://www.gartner.com/en/newsroom/press-releases/2026-09-24-gartner-says-cfos-must-take-a-more-disciplined-approach); [CPA Practice Advisor](https://cpapracticeadvisor.com/2026/09/24/cfos-must-be-more-disciplined-with-ai-expectations-according-to-gartner-research/190477)
- **Gartner budgets and priorities:** about three-quarters of CFOs are increasing technology budgets for 2026, and nearly half by 10% or more. AI agents show strong investment intent despite early adoption. — [Gartner 2026 Controller Agenda](https://www.gartner.com/en/finance/trends/the-2026-controller-agenda/unlocked); [CPA Practice Advisor](https://www.cpapracticeadvisor.com/2026/05/01/cfos-who-implement-strategic-ai-deployment-will-add-10-margin-points-of-growth/182355/)
- **Deloitte Finance Trends 2026 (1,326 global finance leaders; field timing unclear):** 63% have fully deployed AI solutions, 14% have fully integrated AI agents into finance, and 21% say AI has delivered tangible value. — [CFO Dive](https://www.cfodive.com/news/cfos-face-expanded-mandate-pressures-volatile-2026-deloitte-ai/816558/); [Deloitte](https://www.deloitte.com/global/en/insights/topics/leadership/finance-trends-leadership/2026.html)
- **Deloitte Finance Trends 2027:** 95% of finance leaders are comfortable with agentic workflows in at least some activities, but only 14% support full autonomy for critical decisions. — [Deloitte press](https://www.deloitte.com/us/en/about/press-room/deloitte-finance-trends-2027-finance-leaders-balance-ambition-with-accountability.html)
- **Deloitte CFO Signals Q2 2026:** 44% use AI for planning and budgeting; 41% use it to analyze financial data. — [Deloitte Q2 2026 CFO Signals](https://www.deloitte.com/us/en/about/press-room/deloitte-q2-2026-cfo-signals-survey.html)
- **Fortune (Jan 2026):** CFOs are moving finance AI from pilots to deployment in 2026. — [Fortune](https://fortune.com/2026/01/13/cfos-move-finance-ai-pilots-deployment-2026/)

### Inferences
- **Enterprise and mid-market are in a "pilots to production" phase** with value skepticism. That favors narrow, measurable autopilot modules with fast payback (AP, reconciliation, close tasks) over a broad "replace the finance team" pitch.
- **The 14% figure for full autonomy on critical decisions** (Deloitte), together with the SMB survey data (67% require per-transaction approval), shows a consistent ceiling. Autonomy should be marketed as configurable, with human checkpoints at material decisions.
- **International notes:**
  - UK paid AI adoption is lower (7%; Intuit), but Making Tax Digital mandates push SMBs toward digital bookkeeping.
  - Xero is strongest in the UK, Australia and NZ.
  - EU e-invoicing mandates and India's GST digitization were not researched in this pass.

### Gaps
- No McKinsey 2025-2026 CFO survey figure on agent deployment was retrieved.
- No Thomson Reuters 2026 Future of Professionals or State of Tax Firms data was retrieved.
- No AI adoption data split by company size for finance teams specifically, for SMB versus mid-market.
- International data (EU e-invoicing, India GST, UK MTD timelines) was not covered in depth.
