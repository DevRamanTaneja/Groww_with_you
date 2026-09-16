# Groww for Gen Z
## Product README

---

# 1. Project Overview

### Problem Statement

Design a version of Groww that better serves Gen Z investors in India, particularly users between roughly 18 and 26 who may be:

- investing for the first time,
- earning their first salary,
- studying,
- freelancing,
- working part-time,
- starting with small amounts,
- or still learning how financial markets work.

The goal is **not** to redesign Groww simply to make it look younger.

The product should make investing:

- easier to understand,
- easier to try,
- more transparent,
- less intimidating,
- safer to learn,
- and increasingly powerful as the user becomes more experienced.

---

# 2. Core Product Thesis

## **Gen Z does not need a different investing app.**

## **They need an investing app that grows with them.**

A first-time investor putting ₹500 into the market should not experience Groww in the same way as someone actively trading derivatives.

The central product idea is:

> **Complexity should appear progressively as the user becomes more confident and experienced.**

The user journey should evolve through:

> **Confusion → Learning → Practice → First Action → Confidence → Independence**

rather than:

> **More products → More notifications → More transactions**

---

# 3. Product Positioning

# **Groww with you**

### **Simple when you're starting. Powerful when you're ready.**

Groww should gradually evolve with the user's financial experience.

At the beginning:

- reduce complexity,
- explain terminology,
- allow safe experimentation,
- make money movement transparent.

As the user becomes more experienced:

- expose deeper analytics,
- research tools,
- advanced investment products,
- and trading functionality.

Groww should never force advanced complexity onto users before they need it.

---

# 4. Research Insight

The product is based on several core insights.

### Insight 1 — Gen Z should not automatically be treated as risk-loving traders

The underlying research suggests many younger investors remain cautious and face barriers such as fear of losses, complexity and trust. Therefore, simply adding more gamification would address the wrong problem.

---

### Insight 2 — Groww's problem is not primarily visual design

Groww already receives positive feedback for being relatively simple and unintimidating.

The growing challenge is that more products and trader-focused functionality increase cognitive load, especially for beginners.

---

### Insight 3 — Beginners need answers, not a catalogue

Their important questions are usually:

> Where do I start?

> What does this term mean?

> What will this actually cost me?

> Where is my money?

> Am I understanding this correctly?

The product should answer these questions before exposing more complexity.

---

### Insight 4 — Learning should happen while doing

Users should not have to complete a long investment course before they can understand the app.

Education should appear at the exact moment when a user encounters something unfamiliar.

---

### Insight 5 — Transparency creates trust

Users become anxious when they do not understand:

- charges,
- P&L,
- settlement,
- redemption timelines,
- failed transactions,
- or support status.

Making these processes visible can improve trust more than simply improving visual design.

---

### Insight 6 — Young investors learn outside Groww

Financial ideas often reach users through:

- Instagram,
- YouTube,
- Reddit,
- WhatsApp,
- Telegram,
- X,
- creators and finfluencers.

Groww should help users critically evaluate what they encounter rather than pretending those external influences do not exist.

---

# 5. Target Users

## Primary Persona — The New Investor

Age: 18–24

Characteristics:

- student / intern / first job,
- ₹500–₹5,000 available to invest,
- financially curious,
- low-to-medium confidence,
- learns through social media,
- afraid of making an irreversible mistake.

Primary questions:

> What should I do first?

> Can I try this before risking money?

> What happens after I press Buy?

> What are these charges?

---

## Secondary Persona — The Growing Investor

Age: 21–26

Characteristics:

- already has SIPs/stocks,
- understands basics,
- wants better insights,
- wants more control,
- may be exploring ETFs, IPOs and other instruments.

Primary questions:

> How is my portfolio actually doing?

> Why did this number change?

> Am I unnecessarily duplicating investments?

> What features should I explore next?

---

## Tertiary Persona — The Young Trader

Characteristics:

- interested in intraday/F&O/advanced products,
- higher activity,
- requires stronger risk education,
- may benefit from simulation before real-money activation.

---

# 6. Product Principles

Every feature should satisfy these principles.

## 1. Simplify before adding

Do not solve complexity with additional complexity.

---

## 2. Explain before recommending

Groww should help users understand their choices rather than telling them what investment decision to make.

---

## 3. Practice before risking

Users should be able to experiment safely before committing real money.

---

## 4. Show where money goes

Costs and transaction states should always be visible.

---

## 5. Progressive complexity

Advanced functionality should be available, but not necessarily immediately prominent.

---

## 6. Financial progress ≠ transaction frequency

The app should not reward users simply for trading more.

---

## 7. Trust over engagement

A feature that increases session time but reduces financial confidence is not necessarily successful.

---

# 7. Core Product Architecture

The experience revolves around five major pillars:

# 1. My Groww

Personalised interface based on financial experience.

# 2. Practice Mode

Dummy money for learning investing and trading without financial risk.

# 3. Money Lens

Contextual explanations and transparent cost breakdowns.

# 4. Money Tracker

Real-time visibility into money movement and transaction status.

# 5. Claim Check

Help users investigate financial claims encountered online.

A supporting sixth layer is:

# 6. Risk Check

Friction and education before high-risk products.

---

# 8. Feature 1 — My Groww

## User Problem

Groww offers many products, but displaying everything equally creates unnecessary cognitive load for new investors.

## Solution

During onboarding, Groww asks:

### What brings you to Groww?

🌱 I'm completely new

💰 I want to start investing

📈 I already invest

⚡ I actively trade

This determines the initial interface.

The user can change it later.

Nothing is permanently locked.

---

# Beginner Home

The beginner experience prioritises:

### Your Money

Current investments and available balance.

### Practice Mode

Learn without real money.

### Goals

What are you investing toward?

### Start Investing

Simple investment discovery.

### Learn

Contextual guidance based on current actions.

---

## Beginner Home should de-emphasise

- F&O,
- commodities,
- MTF,
- aggressive top-mover feeds,
- constant ticker movement,
- trading-focused promotions.

These remain accessible when intentionally searched for.

---

# Intermediate Home

Can surface:

- stock investing,
- ETFs,
- mutual funds,
- IPOs,
- watchlists,
- portfolio analytics,
- research.

---

# Trader Home

Can surface:

- F&O,
- intraday,
- advanced charts,
- MTF,
- derivatives,
- advanced order types.

---

# Key Principle

> Do not remove functionality.

> Change what appears first.

---

# 9. Feature 2 — Groww Practice Mode

## User Problem

Reading about investing does not fully prepare someone for actually placing an order.

New investors may hesitate because they do not understand what will happen after pressing Buy.

Existing investors may also want to experiment with unfamiliar products.

---

# Solution

Every Groww user receives a separate virtual portfolio.

Example:

> **Practice Balance: ₹1,00,000**

A clear selector distinguishes:

### REAL MONEY

and

### PRACTICE MONEY

Practice transactions never affect real money.

---

# What users can practise

Users can simulate:

- buying stocks,
- selling stocks,
- ETFs,
- creating a portfolio,
- mock SIPs,
- market orders,
- limit orders,
- order execution,
- portfolio movement,
- profit/loss,
- diversification,
- transaction costs.

Advanced users may also practise higher-risk products in simulation before activating them with real funds.

---

# Example Flow

User selects:

> Practice Mode

Balance:

> ₹1,00,000 virtual money

User buys:

> 5 shares × ₹950

Portfolio now shows:

Investment:

> ₹4,750

Current Value:

> ₹4,620

P&L:

> −₹130

User taps:

### Why am I down ₹130?

Money Lens explains the price movement and P&L calculation.

---

# Simulated Charges

Practice Mode should replicate the economics of real transactions where possible.

Example:

Gross simulated profit:

> ₹350

Estimated charges:

> ₹42

Approximate simulated net:

> ₹308

Explanation:

> If this had been a real transaction, your approximate post-charge return would have been ₹308.

This prevents users from learning unrealistic behaviour.

---

# Scenario Mode

Users should not have to wait months to experience different situations.

Practice Mode can include guided simulations such as:

### Market drops 10%

How does your portfolio react?

### One stock crashes 30%

What happens to a concentrated portfolio?

### SIP during volatility

How does regular investing change average purchase price?

### Limit order vs market order

What changes?

### Diversified vs concentrated investing

How does risk differ?

---

# Learning Missions

Practice Mode can provide tasks such as:

> Make your first practice investment.

> Create a portfolio with three different assets.

> Try a limit order.

> Find the estimated charges before buying.

> Create a simulated SIP.

The reward should be knowledge, not points.

No leaderboards.

No return competitions.

No transaction streaks.

---

# Moving to Real Money

After practising:

> Ready to explore real investing?

Options:

### Keep practising

### Explore real investing

Practice positions should never automatically convert to real trades.

The user must intentionally create a new real-money order.

---

# Why this feature matters

Practice Mode changes financial education from:

> Read → Memorise → Risk real money

to:

> Learn → Try → Observe → Understand → Decide

---

# 10. Feature 3 — Money Lens

## User Problem

Financial apps contain many numbers users can see but do not fully understand.

Examples:

- XIRR,
- NAV,
- absolute return,
- realised return,
- expense ratio,
- brokerage,
- DP charges,
- average price,
- P/E,
- settlement.

---

# Solution

Important financial numbers become interactive.

Example:

> XIRR: 11.4% [?]

Tap.

### What is this?

Your investments have effectively grown approximately 11.4% annually after accounting for when money was invested.

### Why is mine 11.4%?

Most of your investment occurred recently, so your annualised return differs from your total return.

### Show an example

A simple numerical explanation appears.

---

# Explanation Depth

Users choose:

### Explain in 10 seconds

### Show me an example

### Learn more

This prevents beginner explanations from frustrating advanced users.

---

# True Cost Preview

Before confirmation, Groww should show estimated transaction economics.

Example:

Investment:

> ₹500

Estimated applicable charges:

> ₹X

Approximate amount invested:

> ₹Y

Potential selling-side charges:

> ₹Z

---

# Explain Charges

Tap:

> Why am I paying this?

Breakdown:

- brokerage,
- GST,
- exchange charges,
- statutory charges,
- DP charges.

The guiding principle is:

# **No surprise money.**

---

# 11. Feature 4 — Money Tracker

## User Problem

"Processing" gives too little information when real money is involved.

Users want to know:

> What has happened?

> What is still pending?

> When will I get my money?

---

# Solution

Every money movement becomes trackable.

Example:

# Mutual Fund Redemption — ₹8,000

✅ Redemption requested

✅ Units submitted

✅ Redemption processed

⏳ Bank transfer initiated

○ Expected by 18 September

---

# Supported Transactions

Eventually:

- withdrawals,
- mutual-fund redemptions,
- SIP payments,
- switch transactions,
- refunds,
- settlement,
- KYC verification,
- account-related processes.

---

# Problem Detection

If expected time is exceeded:

> This transaction is taking longer than expected.

Actions:

### Understand why

### Get help

---

# Support Tracking

Instead of forcing users through repeated conversations:

> Case #23842

Issue:

> Redemption delayed

Status:

> Assigned

Last update:

> 2:14 PM

Expected response:

> Within X hours

Where appropriate, users should see whether a human agent is handling the issue.

---

# Trust Center

Money Tracker integrates with system transparency.

Example:

# Groww Status

Stocks — Operational

Mutual Funds — Operational

Payments — Operational

Withdrawals — Operational

If an incident occurs:

> Some users are experiencing delayed portfolio updates.

> Your underlying holdings remain unaffected.

> Last updated: 11:42 AM

---

# 12. Feature 5 — Claim Check

## User Problem

Many younger investors discover financial information before opening Groww.

Example:

> "XYZ stock is going to 5X."

The problem is not necessarily exposure to the claim.

The problem is knowing:

> What part is fact?

> What part is prediction?

---

# Solution

Users can share a financial claim into Groww.

Example input:

> "ABC stock will double before December."

Groww produces:

# Claim

ABC stock will double before December.

# Type

Prediction

# What can be verified

- recent revenue,
- profit,
- stock movement,
- valuation,
- company announcements,
- volatility.

# Source Context

Where possible:

- registered adviser status,
- official filing,
- public statement,
- opinion,
- unverified claim.

---

# Important Rule

Groww should not say:

> This creator is wrong.

Instead:

> This is a prediction and cannot currently be verified as fact.

The feature should improve critical thinking rather than become a financial truth-ranking system.

---

# Share Sheet Integration

Future experience:

Instagram / YouTube / Reddit / X

↓

Share

↓

Groww

↓

### Check this claim

↓

Claim Check report

---

# 13. Feature 6 — Risk Check

## User Problem

Opening a mutual-fund SIP and trading leveraged derivatives do not carry the same risk.

Yet risk disclosures are often reduced to banners users quickly dismiss.

---

# Solution

Before activating selected high-risk products:

### Step 1 — Plain-language explanation

Example:

> Options can lose most or all of their value quickly.

---

### Step 2 — Simulation

Example:

Initial simulated position:

> ₹5,000

Scenario:

> −40%

Remaining:

> ₹3,000

---

### Step 3 — Understanding Check

Three quick questions.

Not designed as an exam.

Designed to verify basic comprehension.

---

### Step 4 — Practice First

Option:

> Try this with Practice Money before activation.

---

### Step 5 — Protection Controls

User may set:

> Maximum daily loss I'm comfortable with

Example:

₹500

---

# Goal

Create:

> respectful friction before risk

rather than:

> restrictions after damage.

---

# 14. Contextual Learning

Groww should not become a financial textbook.

Education should be embedded directly into actions.

Example:

User sees:

> Expense Ratio: 0.22%

Tap:

> A fund charging 0.22% would charge approximately ₹22 annually for every ₹10,000 invested, though the actual amount changes with portfolio value.

Then:

### Show example

or

### Learn more

---

# Core Learning Loop

> See something unfamiliar

↓

> Tap it

↓

> Understand it

↓

> Try it in Practice Mode

↓

> Observe outcome

↓

> Make your own decision

This learning loop connects the entire product.

---

# 15. Notification Experience

## Problem

Financial notifications range from critical to completely optional.

Treating them equally causes overload.

---

# Solution

Notifications are organised by urgency.

## Essential

Only:

- failed SIP,
- payment issue,
- withdrawal issue,
- KYC action,
- security alert,
- order problem.

---

## Balanced

Essential +

- portfolio updates,
- SIP updates,
- important investment events.

---

## Active

Balanced +

- market updates,
- price alerts,
- investment news.

---

# Digest

Non-critical notifications can be bundled into a digest rather than delivered individually.

Example:

> Your weekly Groww update

---

# 16. What We Deliberately Do Not Build

## No public P&L leaderboard

Financial returns should not become social status.

---

## No trade streaks

Trading more frequently is not inherently better behaviour.

---

## No confetti for executing trades

Transaction completion is not financial success.

---

## No copy-trading social feed

This could encourage herd behaviour.

---

## No "hot stock" feed as a beginner default

Beginner discovery should not be built around FOMO.

---

## No AI telling users exactly what to buy

AI may explain:

- concepts,
- costs,
- transaction states,
- user-owned financial information.

It should not pretend certainty about financial outcomes.

---

# 17. Optional Future Features

## Portfolio X-Ray

Show:

- duplicated fund exposure,
- sector concentration,
- stock concentration,
- portfolio overlap.

Example:

> 63% of the underlying holdings of Fund A and Fund B overlap.

---

## Flexible Investing

For irregular-income users.

Example:

> Got paid?

Allocate:

₹500 → Goal A

₹500 → Investment

₹1,000 → Savings

Start manually before introducing automatic bank/account detection.

---

## Financial Progress Recap

Monthly or quarterly summary:

> You invested ₹4,000.

> Your SIP continued successfully.

> You paid ₹X in charges.

> Your portfolio moved by Y%.

> You learned about XIRR.

The focus is understanding progress rather than celebrating returns.

---

# 18. Full New-User Journey

User downloads Groww.

↓

## My Groww

Question:

> What brings you here?

User selects:

> I'm completely new.

↓

Beginner Home appears.

↓

Primary CTA:

# Try investing with ₹1,00,000 Practice Money

↓

User enters Practice Mode.

↓

Buys a stock with dummy money.

↓

Sees:

> Unrealised P&L

Doesn't understand it.

↓

Taps Money Lens.

↓

Understands P&L.

↓

Tries another investment.

↓

Uses True Cost Preview.

↓

Understands charges.

↓

Eventually chooses:

> Explore real investing

↓

Places first real investment.

↓

Later redeems.

↓

Money Tracker shows progress.

↓

User sees an investing claim online.

↓

Shares it into Claim Check.

↓

Groww separates facts from prediction.

↓

Over time, the user becomes more comfortable.

↓

They enable additional Groww tools.

Groww has progressively grown with them.

---

# 19. MVP

The prototype should not attempt to reproduce all of Groww.

It should demonstrate the product thesis through a small number of high-quality flows.

## MVP Feature 1

# My Groww

Build:

- onboarding,
- experience selection,
- beginner home.

---

## MVP Feature 2

# Practice Mode

Build:

- virtual balance,
- asset selection,
- practice order,
- practice portfolio,
- dummy P&L,
- simulated charges.

---

## MVP Feature 3

# Money Lens

Build:

- tap-to-explain metrics,
- charge explanation,
- True Cost Preview.

---

## MVP Feature 4

# Money Tracker

Build:

- withdrawal/redemption tracker,
- delay state,
- support state.

---

## MVP Feature 5

# Claim Check

Build:

- example social-media claim,
- claim classification,
- facts vs prediction,
- source-context card.

---

# 20. Prototype Screens

A strong clickable prototype could contain approximately:

### Onboarding

1. Welcome
2. Experience selection
3. Beginner home

### Practice Mode

4. Practice dashboard
5. Asset page
6. Practice buy order
7. Practice portfolio
8. Practice P&L explanation

### Money Lens

9. Explain metric
10. True Cost Preview
11. Charge breakdown

### Money Tracker

12. Transaction tracker
13. Delayed state
14. Support status

### Claim Check

15. Claim input/share
16. Claim analysis
17. Evidence/context screen

### Risk Check

18. Risk introduction
19. Simulated loss
20. Understanding check

A 15–20 screen prototype should be enough to communicate the product without recreating the entire Groww application.

---

# 21. Success Metrics

The project should not optimise primarily for transaction volume.

## Activation

Percentage of new users reaching their first meaningful investment action.

---

## Practice Adoption

Percentage of new users who use Practice Mode.

---

## Practice → Understanding

Percentage of Practice Mode users who successfully understand the concept demonstrated.

---

## Beginner Confidence

Self-reported confidence before vs after using Practice Mode.

---

## First Real Investment

Percentage of Practice Mode users who voluntarily move to real investing.

This should be monitored, not aggressively optimised.

---

## Cost Transparency

Reduction in:

- charge-related searches,
- brokerage confusion,
- support tickets related to unexplained deductions.

---

## Money Tracking

Reduction in:

> Where is my withdrawal?

> Why is my redemption pending?

support cases.

---

## Learning Engagement

Percentage of users using Money Lens when encountering unfamiliar concepts.

---

## Claim Check

Measure:

- claims checked,
- percentage opening supporting facts,
- percentage distinguishing prediction from verifiable information.

---

## Long-Term Success

Better measures include:

- SIP continuation,
- retention,
- voluntary progression from beginner to advanced mode,
- lower support dependency,
- confidence improvements.

---

# 22. Risks

## Risk 1 — Practice Mode becomes a game

Mitigation:

- no leaderboard,
- no transaction streak,
- no social P&L,
- no prize for maximum returns.

---

## Risk 2 — Users confuse practice and real money

Mitigation:

Use highly distinct UI states.

Every practice screen must clearly display:

> PRACTICE MONEY

Never allow one-tap conversion of a practice order into a real order.

---

## Risk 3 — Money Lens gives incorrect financial explanations

Mitigation:

Calculations should be deterministic.

AI may explain calculated values but should not generate financial numbers independently.

---

## Risk 4 — Claim Check becomes perceived financial advice

Mitigation:

Separate:

> verifiable fact

from

> interpretation

from

> prediction.

Never automatically recommend buying or selling.

---

## Risk 5 — Progressive UI hides useful features

Mitigation:

Features remain searchable and discoverable.

Personalisation changes priority, not access.

---

## Risk 6 — Too much beginner protection feels patronising

Mitigation:

Let the user change experience level at any time.

The app adapts rather than permanently labels the person.

---

# 23. Assumptions

This product currently assumes:

1. A meaningful portion of Gen-Z Groww users are still early in their financial journey.

2. Information overload is more damaging to new users than lack of product availability.

3. Users are more likely to understand investing through interaction than through standalone courses.

4. Virtual practice can reduce anxiety before real-money investing.

5. Young users value knowing exactly what is happening to their money.

6. Contextual education can reduce dependence on external searches.

7. Financial claims from creators and social media meaningfully influence some investing decisions.

8. Advanced functionality should remain available but does not need equal prominence for every user.

These assumptions should eventually be tested through interviews, usability studies and product analytics.

---

# 24. Product Differentiation

Many investing products compete on:

- lower fees,
- more charts,
- faster trading,
- more instruments.

This concept competes on something different:

# **Financial confidence.**

Groww becomes the platform where someone can:

> learn,

> practise,

> understand,

> invest,

> track,

> verify,

and gradually become independent.

---

# 25. Product North Star

The ideal outcome is not:

> "The user spends more time on Groww."

It is:

> **"The user understands their financial actions better because they used Groww."**

The product succeeds when users require less hand-holding over time.

---

# 26. Final Product Story

A Gen-Z user should be able to say:

> I didn't understand investing when I joined.

> Groww simplified what I saw.

> It let me practise before using my own money.

> When I didn't understand something, I could tap it.

> Before investing, I knew what it would cost.

> When my money moved, I could track it.

> When I saw financial claims online, I could investigate them.

> As I learned more, Groww gave me more powerful tools.

That is the experience this product is designed to create.

---

# **Groww with you**

## **Simple when you're starting. Powerful when you're ready.**

---

# 27. Next Project Artifacts

Once the product direction is finalised, two additional submission artifacts should be created.

## Artifact 2 — Prompts Used to Create the Tool

This should document the important prompts used while:

- researching the problem,
- identifying user pain points,
- generating product hypotheses,
- challenging assumptions,
- designing UX flows,
- generating the prototype,
- refining UI,
- and debugging the final product.

The prompts should demonstrate deliberate iteration rather than one giant "build this app" request.

---

## Artifact 3 — Evals Used to Test the Solution

The product should be evaluated through scenarios such as:

### Beginner comprehension

Can a first-time user understand what to do?

### Practice Mode safety

Can users clearly distinguish dummy money from real money?

### Cost transparency

Can users identify the complete estimated cost before investing?

### Money tracking

Can users tell exactly where their money is?

### Claim Check neutrality

Does the tool distinguish facts from predictions without turning into investment advice?

### Progressive complexity

Does Beginner Mode reduce clutter without making advanced features inaccessible?

### Risk understanding

Do users understand what can happen before entering high-risk products?

### UX consistency

Can users complete all important tasks without unnecessary steps?

These should later be converted into explicit test cases with expected outcomes and pass/fail criteria.