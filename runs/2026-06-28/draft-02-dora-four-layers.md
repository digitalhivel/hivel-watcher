# CONTENT BRIEF + DRAFT
# Signal ID: S002
# Format: blog_post
# Theme: Engineering analytics
# Priority: standard | Turnaround: 72 hours
# Angle: thought_leadership
# Status: in_review
# Assigned to: Simran
# Signal source: https://oobeya.io/blog/dora-metrics-not-enough-2026
# Run date: 2026-06-28

---

## BRIEF

**Primary keyword:** engineering analytics AI era

**Title options:**
1. Elite Engineering Teams Track Four Layers. DORA Is One of Them.
2. DORA Metrics Are Not Enough in 2026: What You Are Missing
3. Four Things DORA Cannot Tell You About Your Engineering Team
4. Why "Good DORA Scores" Are No Longer Good Enough
5. The Three Engineering Analytics Blind Spots That Cost You Board Credibility

**Full TOC:**
- H2: What DORA does well and what it cannot do
  - H3: The outcomes DORA reliably measures
  - H3: The causation DORA cannot provide
- H2: The three blind spots that matter most in 2026
  - H3: No causation, just correlation
  - H3: Human experience is invisible
  - H3: AI attribution is missing
- H2: The four measurement layers that elite teams combine
  - H3: Layer 1: DORA baseline
  - H3: Layer 2: Developer experience signals
  - H3: Layer 3: AI attribution
  - H3: Layer 4: Business alignment
- H2: Making the case to leadership
- FAQ (5 questions)

**Integration plan:**
- Sudheer POV: #3 "DORA metrics are incomplete — elite DORA scores do not mean business impact" and #2 "Most analytics tools are a waste of money — they measure activity not outcomes"
- Customer proof points: AvidXChange (PR cycle time down 56%), Klenty (49% more features, cycle time down 25%, review down 22%), MoveInSync (dev cycle down 60%, review down 37%)
- CTA: "See how Hivel measures this" (informational)
- Market language to use: "AI attribution gap", "DORA blind spots", "engineering measurement framework", "AI ROI accountability"

---

## DRAFT

**Elite Engineering Teams Track Four Layers. DORA Is One of Them.**

Your deployment frequency is up 40%. Lead time for changes is down 35%. Change failure rate is stable. By every DORA standard, your engineering organization is performing well.

So why cannot you explain to your board why the $1.8 million AI tooling investment is working?

DORA metrics are the right foundation. They are not the complete answer. In 2026, with AI-assisted code making up 26 to 41% of what engineering teams are producing, the gap between what DORA measures and what leadership needs to know has become a real business problem.

## What DORA does well and what it cannot do

The DORA framework measures delivery performance: how often you deploy, how long it takes to go from commit to production, how quickly you recover from failure, and how often failures happen. These are the right outcomes to track. The organizations that built DORA got this right.

The framework has two hard limits.

First, it measures what happened, not why it happened. A rising change failure rate shows a problem exists. It does not tell you whether the problem is review quality, AI-generated code quality, deployment pipeline stability, or engineer overload. You have a signal. You do not have a root cause.

Second, it was designed before AI assistance was a significant factor in software delivery. DORA cannot tell you whether your deployment frequency increase came from better engineering or from developers accepting more AI suggestions that then create a downstream quality problem two sprints later.

### The outcomes DORA reliably measures

Deployment frequency captures how often working software reaches production. Lead time for changes measures cycle time from commit to deploy. Change failure rate tracks how often deployments cause incidents. Mean time to recover measures how quickly you resolve those incidents.

These four metrics, with the 2025 addition of rework rate, give you a solid picture of delivery health. Teams that track them consistently outperform teams that do not.

The issue is not that DORA is wrong. The issue is that DORA answers "what is the outcome?" while leadership is asking "why is the outcome happening and is our AI investment the cause?"

### The causation DORA cannot provide

DORA shows you the trend. It cannot explain it.

If your change failure rate went up 12% after a quarter of heavy AI adoption, DORA records the fact. It cannot tell you whether AI-generated code is causing it, whether a specific team is the source, whether your review process loosened, or whether you happened to deploy into a more complex part of the product during that period.

You have a data point. You do not have a diagnosis. And without a diagnosis, the board conversation stalls.

## The three blind spots that matter most in 2026

### No causation, just correlation

Root cause analysis in an AI-assisted workflow requires knowing the origin of code that caused failures. Was it AI-assisted or not? What was the suggestion acceptance rate in PRs that triggered incidents? Which teams contributed the failing code?

Without causal attribution layered on top of DORA, every trend is a mystery to be debated in sprint retrospectives rather than a signal to be acted on. Teams argue about whether AI is helping or hurting. Nobody can prove it either way. The conversation ends without a decision.

### Human experience is invisible

DORA tells you that review cycle time is 48 hours. It does not tell you that three of your senior engineers are approaching burnout reviewing AI-generated code because it arrives at 3x the volume but requires the same level of scrutiny as human code.

Developer experience signals, collected through regular team pulse surveys and workflow analysis, capture what DORA cannot: trust in AI suggestions, perceived cognitive load, collaboration quality, and the quiet friction that predicts retention risk before it becomes an attrition event.

At the organizations we have analyzed, teams with the highest DORA scores sometimes have hidden developer experience problems that surface three to six months later as turnover. Engineers do not leave for money. They leave because you waste their time. Being asked to review 200 AI-generated PRs a week without visibility into which ones need real scrutiny is a very effective way to waste their time.

### AI attribution is missing

The most pressing blind spot in 2026 is that DORA has no concept of where code comes from. It cannot tell you how much of your throughput is AI-generated, whether AI-assisted code has different quality characteristics, or whether your improvements are sustainable.

Klenty tracked this directly. After implementing AI attribution alongside DORA measurement, they found 49% more features shipped, cycle time down 25%, and review time down 22%. The attribution layer showed which teams were getting sustainable efficiency gains and which were running up code churn that would cost them in future sprints.

Without attribution, you cannot replicate what is working. You cannot stop what is not.

## The four measurement layers that elite teams combine

### Layer 1: DORA baseline

Keep what works. Deployment frequency, lead time, change failure rate, mean time to recover, and rework rate. These are the foundation. The goal is not to replace them but to make them interpretable.

Track DORA trends consistently. Do not add layers as a substitute for delivery discipline. The four-layer model only has value if the DORA baseline is clean.

### Layer 2: Developer experience signals

Run regular team pulse surveys. Measure perceived productivity, tool trust, cognitive load, and review burden. Track retention risk signals alongside delivery performance. Teams that combine DORA with developer experience signals catch problems earlier and retain engineers longer.

MoveInSync tracked this layer explicitly. Dev cycle time went down 60%, review time down 37%. Both numbers came from understanding where friction was actually coming from, not just where the clock was running. Without the developer experience layer, those insights would not have been findable in the DORA data.

### Layer 3: AI attribution

Track the origin of code reaching production. Measure: AI-assisted code share of production-merged commits, code churn rate for AI-generated versus human-written code, cycle time for AI-assisted PRs, and review comment density on AI-generated code.

These signals tell you whether AI is creating sustainable efficiency or front-loading output at the cost of downstream quality.

A healthy AI attribution profile in 2026 looks like: 25 to 40% of production-merged commits are AI-assisted, AI code churn is within 1.5x of human code churn, and AI-assisted PR cycle times are equal to or shorter than non-AI cycle times. Any significant deviation from this profile is a signal to investigate.

### Layer 4: Business alignment

Connect delivery metrics to outcomes that leadership can act on. Time-to-market for specific feature categories. Incident cost and customer impact. R&D allocation: what percentage of engineering time is going to new value versus maintenance and rework?

This is the layer that makes engineering analytics valuable to a CEO or CFO, not just to an engineering manager. It is also the layer that most tools skip entirely.

Freshworks used this approach to demonstrate 16% more features shipped at stable reliability. AvidXChange showed PR cycle time down 56% within six months, with a clear attribution to specific workflow changes that leadership could understand and invest in further.

These conversations do not happen when you only show DORA bars. They happen when DORA connects upward to business outcomes and downward to causal attribution.

## Making the case to leadership

The standard DORA presentation to leadership shows four bars going in the right direction. Deployment frequency: up. Lead time: down. Change failure rate: stable. The conversation ends there.

The four-layer presentation is different. It shows delivery performance, explains causation, surfaces developer health, attributes AI impact, and connects everything to business outcomes. It answers the three questions leadership is actually asking: what is happening, why is it happening, and is our AI investment working?

One question to ask your team this week: of these four layers, how many are you currently measuring? If the answer is one, you have two conversations with your board that you cannot have: why your outcomes changed, and whether AI is the reason.

[See how Hivel measures this]

---

## FAQ

**Is DORA still worth tracking in 2026?**

Yes. DORA remains the clearest baseline for software delivery performance. The argument here is not to replace it but to add the three layers it cannot cover on its own: causation, developer experience, and AI attribution. Organizations that abandon DORA in favor of newer frameworks often lose the historical baseline they need to show trend improvement to leadership.

**How do we add AI attribution without significant engineering effort?**

AI attribution at its simplest requires connecting three data sources: AI tooling telemetry (which suggestions were accepted), your git history (which commits reached production), and your deployment pipeline. Platforms that already join Jira and Git data can surface the AI attribution signal with minimal additional integration. The key is not a new tool but a connection between existing data sources.

**What developer experience surveys should we run?**

The DX Core 4 survey and the SPACE framework both provide validated instruments for measuring developer experience alongside delivery metrics. The key signals to capture quarterly are perceived productivity, trust in AI suggestions, cognitive load, and review burden. Running these consistently and connecting them to DORA trends creates a combined picture that neither dataset provides on its own.

**We have good DORA scores but high engineer attrition. Why might this be?**

DORA measures delivery, not experience. Teams can maintain elite delivery performance while engineer satisfaction is declining, particularly when volume pressure from AI tools creates high review load on senior engineers without visibility into which reviews need the most attention. Developer experience signals should be measured separately from DORA and reviewed alongside it monthly.

**How often should we review all four layers together?**

Delivery performance (DORA) can be reviewed weekly. Developer experience signals should be reviewed monthly at minimum, with a structured quarterly review. AI attribution should be visible in real time and reviewed alongside every sprint retrospective. Business alignment is a quarterly conversation, connected to roadmap and budget reviews.
