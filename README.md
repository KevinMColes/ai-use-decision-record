# AI Use Decision Record

**A leadership record of what your company has actually decided about AI.**

By Kevin M. Coles · Version 1.2 · October 2026 · Licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)

---

## Why this exists

Most companies respond to AI by writing a policy. A policy states what leadership expects. It does not record what leadership actually knew, approved, rejected, or agreed to revisit. When a client, regulator, insurer, acquirer, or board member asks how a particular AI tool came to be used on their data, "we adopted an AI policy" is not an answer.

Meanwhile, the work has already moved. In research the security vendor BlackFog published in January 2026, 49% of 2,000 workers at UK and US companies with more than 500 employees said they used AI tools at work that their employer had not sanctioned, and 58% of those relied on free versions. Among presidents and C level respondents, 69% said speed trumps privacy or security. The rules are not only being bypassed from below. The people who set them are often the first to trade them away.

Shadow AI is not evidence that employees do not understand the rules. Often it is evidence that the rules do not understand the work. This record is built to fix both problems: it gives leadership a dated, attributable record of every meaningful AI decision, and it makes the approved path fast enough that people stop going around it.

## The core idea: decide the use, not the tool

The same tool can be harmless in one use and dangerous in another. An AI assistant drafting marketing copy and the same assistant screening job applicants are not the same decision. They involve different data, different people affected, different laws, and different consequences when the output is wrong.

So this record is completed **once per use**, not once per tool. "Microsoft Copilot" is not a use. "Copilot summarizing internal project meetings" is a use. "Copilot drafting client deliverables from client financial data" is a different use, and it gets its own record.

## What this is, and what it is not

This is a **leadership** record. It is designed to be completed by the business owner of each use, with input from whoever manages the technology and, for higher tiers, legal counsel.

It is **not** an AI policy. You still need one. This record is how you show the policy is being applied.

It is **not** a technical model evaluation or security assessment. Those still matter for higher risk uses. This record sits above them and asks whether the business has made a conscious, accountable decision.

It is **not** legal advice. AI law is changing quickly and varies by jurisdiction. Where this record asks whether a law applies, have counsel answer.

---

## Part 1: Find what is actually in use

You cannot decide about uses you cannot see. Before completing any record, build an honest inventory. Expect it to be longer than leadership thinks.

Look in five places:

1. **Expense reports and corporate cards.** Individual subscriptions to AI tools are the most common form of shadow AI.
2. **Sign in and app connections.** Your identity platform will show third party apps employees have connected with their work accounts, including AI tools granted access to email, files, and calendars.
3. **Browser extensions.** AI writing, summarizing, and meeting extensions often read everything on the page.
4. **AI you did not buy.** Many tools you already pay for (office suites, CRM, help desk, HR, accounting, design tools) have added AI features, often switched on by default. These count. New AI features arrive in routine updates, so check admin settings after each major release, not once.
5. **Ask people directly, with amnesty.** A short survey that promises no penalty for past use will surface more than any technical scan. Make the amnesty real, or nobody will answer honestly next time.

For each use you find, record the tool, the purpose, who uses it, and what data it touches. That list becomes the agenda for Part 2.

---

## Part 2: Classify each use

Classify the **use**, not the tool. When a use meets more than one tier, the highest tier applies.

| Tier | The use... | Examples | Who can approve |
|---|---|---|---|
| **Tier 1: Assist** | Helps a person draft, summarize, research, or brainstorm. Uses no confidential, personal, or regulated data. A person reviews everything before it is used. | Drafting routine internal emails with no confidential content, summarizing public articles, brainstorming campaign ideas | Department head |
| **Tier 2: Sensitive data** | Processes customer, client, employee, financial, health, legal, or other confidential or regulated data. | Summarizing client calls, analyzing financial statements, drafting from contracts, coding against production data | Business owner, plus whoever owns security and privacy |
| **Tier 3: Consequential** | Influences decisions about people (hiring, firing, pay, performance, credit, pricing for an individual, insurance, housing, health care, education). **Or** takes actions on its own (sends, buys, changes, approves, or deletes). **Or** produces output that reaches customers or the public without human review. | Resume screening, automated customer replies, AI agents with system access, chatbots on your website | An executive, with counsel reviewing before approval |

Four notes on tiers:

- **Tier 3 is where the law is moving fastest.** Several jurisdictions now regulate automated decisions about people, especially in employment. As examples only: Illinois amended its Human Rights Act, effective January 1, 2026, to address AI in employment decisions. New York City requires an independent bias audit, a published summary, and candidate notice before automated tools are used in hiring or promotion. Colorado repealed and replaced its original AI Act in May 2026 with a narrower automated decision law effective January 1, 2027. Under the EU AI Act, as amended in 2026, obligations for high risk uses such as employment apply from December 2, 2027, while its transparency rules, including that people be told when they are interacting with an AI system, have applied since August 2, 2026. None of this is a complete list, and dates continue to shift. Counsel should confirm what applies to you.
- **"Takes actions on its own" includes AI agents.** An agent that can send email, move money, change records, or approve requests is closer to a new employee with system access than to a software feature. Treat its approval accordingly.
- **An action counts as "on its own" unless a named person approves that specific action before it happens.** Approving a batch once a day, or a rule written months ago, does not count.
- **The owner does not set the tier alone.** Someone other than the use owner confirms it. Anyone at the approval level or above can suspend a use immediately. Only the listed authority can approve one.

---

## Part 3: The record

Complete one record per Tier 2 or Tier 3 use. Tier 1 uses can share a single short record per department, as long as they genuinely meet every Tier 1 condition.

Three rules:

1. **Write a name, not a department,** wherever the record asks who.
2. **"We don't know" is a valid answer.** It is also a finding.
3. **Every record ends in a decision** (Part 5).

Questions marked **RF** are red flag questions. Part 4 explains what the answers mean.

### Section A: The use

| Question | Answer |
|---|---|
| What exactly is the use? (One sentence: what the AI does, for what purpose.) | |
| Tier (Part 2), and why | |
| **RF** Who owns this use, by name? | |
| Who uses it, and roughly how many people? | |
| Which tool, which vendor, and which plan? | |
| **RF** Is anyone using a free or personal account for this work instead of a company account? | |
| What problem was this solving? What did people do before? | |
| What result would justify keeping this use (time saved, cost avoided, quality, revenue), how will we measure it, and what does it cost per year, including licenses and review time? | |

### Section B: Data

| Question | Answer |
|---|---|
| What data goes in? Be specific. | |
| What data must **never** go in? Is that written down where users will see it? | |
| **RF** Does the vendor use our inputs or outputs to train or improve its models? | |
| **RF** If we have opted out, is that commitment in the contract, or only in a setting the vendor can change? | |
| How long does the vendor keep prompts, files, and outputs, where, and can we delete them? | |
| Does the tool connect to other systems (email, files, CRM)? What can it read there? | |
| Could outputs reproduce someone else's copyrighted or confidential material? Who checks? | |
| **RF** Do client contracts, NDAs, engagement letters, or professional duties limit putting this data into a third party AI service, require client consent, or require us to disclose AI use? Could it capture privileged communications, such as a note taker on a call with counsel? | |
| **RF** How will we learn if the vendor changes the model, changes these terms, switches on new AI features, or adds a model provider to its subprocessor list? Who watches, and does the contract require notice? | |
| Does the vendor indemnify us against third party IP claims over outputs on this plan, and on what conditions? Will we need to own or assign rights in the output, and has counsel considered how much is protectable? | |
| If personal data goes in, do our privacy notices cover this use, is there a data processing agreement, and can we find, export, or delete a person's data held by the vendor if asked? | |
| Are prompts, outputs, transcripts, and agent logs business records we must keep, or could be asked to produce in a dispute? Can they be placed on legal hold? | |

> **Why this matters.** Consumer and personal plans from major AI providers often carry different data terms than business and enterprise plans, including whether conversations can be used for training. The same product name can mean very different data handling depending on how the account was set up.

### Section C: The human role

"Human in the loop" means nothing until you name the human, what they check, and their authority to say no. A reviewer who approves two hundred outputs a day is not reviewing. They are signing.

| Question | Answer |
|---|---|
| **RF** Who reviews the output before it is used, sent, or relied on? | |
| What exactly are they checking for (accuracy, tone, confidentiality, bias, legal exposure)? | |
| **RF** Do they have the time, expertise, and authority to reject the output, or is the review a formality? | |
| If volume makes reviewing every output unrealistic, what is reviewed (a sample, every item above a threshold), and who checks that the sampling actually happens? | |
| What have the people using it been shown about its limits, typical errors, and the never input list, and when? | |
| **RF** Does any output reach customers, clients, or the public without a person reviewing it first? | |
| Who is accountable when an AI generated error causes harm? | |

### Section D: Decisions about people (Tier 3 only)

| Question | Answer |
|---|---|
| Which decisions about people does this use influence? | |
| **RF** Has counsel reviewed which laws apply to this use, in every jurisdiction where the affected people are? | |
| Are affected people told that AI is involved? When and how? | |
| Can an affected person ask for human review or appeal a decision? | |
| What evidence does the vendor provide about accuracy and bias testing? Have we tested it on our own population? | |
| Who monitors outcomes over time for unfair patterns? | |

### Section E: Agents and autonomy (any use that takes actions)

| Question | Answer |
|---|---|
| What actions can it take on its own? List them. | |
| **RF** What untrusted content does it read and act on (inbound email, web pages, shared files, tickets, other agents)? | |
| Can it be connected to new tools or data sources without a fresh decision? | |
| What systems, data, and accounts can it reach? | |
| **RF** Does it act under its own identity with limited permissions, or under a person's credentials? | |
| **RF** Which actions require a person's approval before they happen (sending externally, spending money, deleting, approving, changing permissions)? | |
| Are there hard limits (dollar amounts, recipients, volume per day)? | |
| Is every action logged in a way someone actually reviews? | |
| **RF** Who can switch it off, how fast, and has that been tested? | |

> **Why this matters.** An AI agent with access to email, files, and business systems has the reach of a privileged employee and none of the judgment. It can also be manipulated by content it reads, such as instructions hidden in an email or document. Governing it like a software feature instead of like a privileged account is how a small error becomes a large one.

### Section F: When it fails

| Question | Answer |
|---|---|
| What happens if the output is confidently wrong? Who would notice, and how fast? | |
| What happens to the work if the tool is unavailable for a day? | |
| Is there a fallback process, and does anyone still know how to do the work without the tool? | |
| **RF** Has our broker reviewed our general liability, professional liability, cyber, and D&O policies for AI exclusions, and told us in writing how this use is likely to be treated? | |

> **Why this matters.** In January 2026, Verisk made optional ISO endorsements (CG 40 47, CG 40 48, and CG 35 08) available that let insurers exclude generative AI exposures from commercial general liability policies. The carrier, not the policyholder, decides whether to attach them, often at renewal. Professional liability, cyber, and other specialty policies carry their own AI exclusions, some broader. Exclusions written as "arising out of" generative AI can reach further than a business expects. Find out what your policies exclude before you need them.

---

## Part 4: Reading the answers

| Red flag answer | What it means | Pushes the decision toward |
|---|---|---|
| **No named owner** | Nobody is accountable for whether this use is still appropriate. | Assign an owner first. No other decision is valid until someone owns this one. |
| **Free or personal accounts used for company work** | Company data is flowing under terms the company never agreed to and cannot see. | Move the use to a company account with business terms, or prohibit it. This is usually the fastest risk reduction available. |
| **Vendor can train on our data, or the opt out is only a setting** | Confidential information may leave your control in ways you cannot reverse. | Restrict to non confidential data until the commitment is contractual, or prohibit for sensitive data. |
| **Client or professional confidentiality terms unchecked** | You may be breaking a promise to a client before the AI makes a single error. | Restrict to non client data until the owner, with counsel where needed, has checked the governing contracts and duties. |
| **No way to detect vendor changes** | The use you approved can become a different use without anyone deciding. | Approve with conditions: name who monitors vendor notices and release notes, and treat a material change as a review trigger. |
| **No defined reviewer, or review is a formality** | The "human in the loop" is decorative. Errors will pass straight through. | Approve with conditions: name the reviewer and what they check, or reduce the scope. |
| **Output reaches customers or the public unreviewed** | Your company is publishing statements it has not read. | Require review before release, or limit to low consequence content clearly labeled as AI generated, approved at Tier 3. |
| **Influences decisions about people without counsel review** | Legal exposure is unknown, and in some jurisdictions notice and audit duties may already apply. | Restrict to pilot or hold until counsel has reviewed. |
| **Agent acts under a person's credentials** | Its actions are indistinguishable from that person's, and its access is everything that person can reach. | Give it its own identity with only the permissions it needs before expanding use. |
| **Agent reads untrusted content and can act externally** | Anyone who can send it an email or a document can try to steer it. | Require a person's approval for any external action that follows untrusted input. |
| **Agent can send, spend, delete, or approve without human approval** | One manipulated or mistaken instruction becomes a real world action. | Require approval for those actions, or set hard limits. |
| **Nobody has tested the off switch** | In an incident, you will be learning how to stop it while it is still running. | Approve with conditions: test it within 30 days. |
| **Insurance position unconfirmed** | A loss from this use may fall entirely on the company. | Get the broker's written view before expanding the use. Expect an opinion, not a guarantee. Only the carrier decides a claim. |

When several red flags apply, the most restrictive direction governs.

**Two patterns deserve escalation to the CEO, and to the board's risk or audit committee where one exists, regardless of anything else:**

1. **Sensitive data plus no contractual protection.** A Tier 2 or Tier 3 use where the vendor can train on the data or the terms are unknown.
2. **Autonomy plus consequence.** An AI system that can take actions on its own *and* affects customers, money, or decisions about people.

**Rules apply to leadership first.** If executives are exempt in practice, the record is theater. Executive uses go through the same process, and they go first.

---

## Part 5: The decision

Choose one outcome and record it.

- [ ] **Approve.** The use is understood and appropriate, and any red flags are explicitly accepted by someone with authority for this tier.
- [ ] **Approve with conditions.** Allowed, with specific gaps closed by specific dates.
- [ ] **Restrict.** Allowed only as a pilot, with limited users, limited data, or limited actions, until conditions are met.
- [ ] **Prohibit.** Not allowed. Record what people should use instead, so the need does not go back underground.

A condition not closed by its date does not roll forward. The use is suspended, or cut back to its restricted scope, until the condition closes or the approver for that tier accepts the risk in writing.

| | |
|---|---|
| **Use** | |
| **Tier** | |
| **Red flags found** | |
| **Decision** | |
| **Rationale** | |
| **Conditions, with owners and dates** | |
| **Risks explicitly accepted, and by whom** | |
| **Approved by (name and role)** | |
| **Date** | |
| **Next review date** | |

Review early, without waiting for the date, if the vendor changes its terms or model, the use expands to new data or new people, the AI begins taking actions it did not take before, an incident occurs, or the law affecting the use changes.

At each scheduled review, compare the result against the value test in Section A. A use that is safe but not paying for itself is a candidate for retirement, not renewal.

Keep every record, and every superseded version, for as long as the use runs and for your normal retention period after it ends. The old versions are the evidence of what you knew and when.

---

## Part 6: The AI register

Roll every record into one page that leadership can read in five minutes.

| Use | Tier | Owner | Data involved | Decision | Open conditions | Next review |
|---|---|---|---|---|---|---|
| | | | | | | |
| | | | | | | |
| | | | | | | |

Below the table, add three lines:

1. **Highest exposure:** the one use that would hurt most if it went wrong.
2. **Escalations:** any use that triggered one of the two escalation patterns.
3. **Unmet demand:** the uses people asked for that have not yet been approved.

---

## Part 7: Make the approved path faster than the shadow path

Shadow AI is a signal of unmet demand. Blocking tools without offering an alternative only moves the use somewhere you cannot see it.

- **Set a turnaround time and publish it.** A Tier 1 decision within five business days, Tier 2 within fifteen. Tier 3 takes as long as it takes, but the requester gets a date. If approval takes a quarter, people will not wait.
- **Provide a sanctioned default.** One approved, company account AI assistant with business data terms removes the most common reason people sign up for free tools.
- **Publish the register internally.** When people can see what is approved, they stop guessing.
- **Measure the shadow path.** Rerun the Part 1 inventory every quarter. If unsanctioned use is not falling, the approved path is still too slow or too weak, and that is a leadership problem, not a user problem.

---

## A worked example

*A fictional 90 person accounting and advisory firm reviews its use of an AI meeting assistant.*

| | |
|---|---|
| **Use** | An AI assistant joins client video calls, records them, transcribes them, and emails a summary with action items to everyone on the invite, including the client. |
| **Tier** | Tier 3. It processes client financial data (Tier 2), it sends email to clients on its own (Tier 3), and those summaries reach clients without human review (Tier 3). |
| **How it started** | Two partners signed up individually last year on personal plans. It spread to 30 staff through calendar invites. |
| **Owner** | None when the inventory found it; IT did not know it was in use. Before the decision, the managing partner named the director of operations as owner. |
| **Data** | Client financial details, tax positions, and occasionally client employee information. Personal plans; training terms unconfirmed, and personal plans often allow training unless each user opted out. Recordings retained indefinitely on the vendor's servers. Engagement letters have not been checked for limits on sharing client data with third party services, and some calls cover tax return information, which carries its own federal disclosure rules. |
| **Human role** | Nobody reviews summaries before they go to clients. One summary sent last month misstated a client's estimated tax payment. |
| **Consent** | No process for telling call participants they are being recorded. Clients are in several states, and recording consent rules vary by state. |
| **Insurance** | The firm's professional liability and cyber policies have not been reviewed for AI exclusions. |
| **Red flags** | No named owner. Personal accounts used for client work. Training terms unconfirmed. No defined reviewer. Output reaches clients unreviewed. Sends externally without approval. Client confidentiality terms unchecked. No way to detect vendor changes. Insurance position unconfirmed. **Escalation patterns 1 and 2:** sensitive data with no contractual protection, and a system that acts on its own toward clients. |
| **Decision** | **Restrict,** decided by the managing partner after a same day call with counsel. |
| **Conditions** | Use on personal accounts stops today, and the assistant stays off all calls until the firm account is live. Firm account on a business plan with contractual no training terms, automatic emails disabled at the account level, and the engagement lead reviews and sends every summary (14 days). Counsel confirms a recording notice process for all client states, and whether engagement letters or tax disclosure rules require client consent (30 days). Retention set to 90 days, and older recordings deleted except anything under legal hold or the firm's retention schedule (30 days). Broker reviews professional liability and cyber policies for AI exclusions and responds in writing (30 days). |
| **Risks explicitly accepted** | None. The tool is off all calls until the firm account is live. From then until the 30 day conditions close, it runs as a pilot on internal meetings only. |
| **Next review** | When conditions close, then every six months. |

Notice that the decision is not "ban the tool." Staff adopted it because it saves real time. The problem was that nobody had decided how it should be used.

---

## If you only have ten minutes

Answer these five questions for each AI use:

1. Who, by name, owns this use?
2. Is anyone doing this work on a free or personal account?
3. Can the vendor train on our data, and is our protection in the contract?
4. Does anything reach a customer, or affect a decision about a person, without a human reviewing it?
5. If it can take actions on its own, who can switch it off?

If any answer is "we don't know," that is where to start.

---

*Kevin M. Coles is the founder of [Coles Technical Group](https://colestechnicalgroup.com), a technology governance and fractional CIO/CTO consulting firm based in Phoenix, Arizona. He writes weekly at [substack.com/@kevinmcoles](https://substack.com/@kevinmcoles). Also see the [Vendor Dependency Review](https://github.com/KevinMColes/vendor-dependency-review).*

*You are free to share and adapt this record for any purpose, including commercial use, provided you give appropriate credit to Kevin M. Coles and link to the license. Suggested credit: "AI Use Decision Record by Kevin M. Coles, licensed under CC BY 4.0."*
