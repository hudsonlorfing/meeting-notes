---
up: 
in:
  - "[[Meetings]]"
related: 
created: 2026-01-05
tags:
  - meeting
  - shedpro
meeting_date: 2026-01-05
meeting_with: "[[👤Accounting]]"
participants:
  - "[[👤Nick Balsamo]]"
  - "[[👤Huong]]"
workspace: shedpro
analysis_apps: [sprint-retro, team-sync, one-on-one]
model: claude-sonnet-4
processed_by: hudson
one-liner: 
---

# 2026-01-05꞉ Meeting with Accounting
*Meeting on 2026-01-05*

## Participants
- "[[👤Nick Balsamo]]"
- "[[👤Huong]]"

> [!warning] ⚠️ GEMINI API KEY NEEDS ROTATION
> The Gemini API key appears to be invalid or expired. Please rotate the key.
> Fallback to Claude was used for this analysis.

# Meeting Analysis: Accounting Sessions Discussion

## Executive Summary
This meeting focused on implementing advanced financial categorization and tracking systems to provide better insights for strategic decision-making at CDAP. The core discussion centered around restructuring accounting processes to track profitability by product lines and service types, with particular emphasis on the challenges and opportunities in custom 3D model development.

## Current State: How Accounting Sessions Work

### Process Overview
- **Current Financial Reporting**: Basic P&L consolidation across two entities using Xero and Fathom
  - "So this is the two entities combined. So I didn't make any other changes except for the... I'm just showing November and October"
- **Time Tracking System**: Manual time entry by production teams
  - "So it's manual and they just sign the... And measure the... Measure the time they spent on one project"
- **Revenue Recognition**: Currently tracking setup, subscription, and custom 3D model revenue without detailed cost attribution
  - "But currently for accounting we just track setup, recursive, subscription and custom for 3D models"

### Operational Details
1. **Data Integration**: Stripe integration exists but doesn't provide detailed cost attribution
   - "The stripe integration with Sift will give you a Visa view without having to do anything on it"

2. **Current Reporting Limitations**: All financials "come together" without product-level breakdowns
   - "So right now you have like all of the financials kind of come together"

3. **KPI Tracking**: Multiple KPIs monitored but lacks focus on most critical metrics
   - "So among this KPI that we are tracking, we will pick some obviously important in this quarter"

## Issues and Challenges Identified

### Critical Issues
- **Issue**: Data reliability concerns affecting performance metrics
  - **Impact**: Management cannot rely on reported metrics for decision-making
  - **Quote**: "The other I know I saw in 90 that you flagged the retention rate of the 94% is really like 88%. Those are like, like, in other words, you can't rely on the data"
  - **Speaker**: Hudson Lorfing

- **Issue**: Inability to measure profitability of custom 3D models
  - **Impact**: Significant time and effort investment without profit visibility
  - **Quote**: "It take us a lot of time and then an effort to deliver one model, additional model and as convenience, no way for us to measure if it makes we make profits or not"
  - **Speaker**: Huong

### Process Inefficiencies
- **Issue**: Lack of product-level cost attribution
  - **Impact**: Cannot determine which services are profitable or loss-making
  - **Quote**: "But the problem that we had is for the cost we for now we can separate the cost for setup the cost for custom... because for example for delivery team then they serve for everything"
  - **Speaker**: Huong

- **Issue**: Outdated pricing for legacy clients
  - **Impact**: Significant revenue leakage from clients paying well below current rates
  - **Quote**: "Because there are some right now we expect the company to lose so much money in the budget together... there's like clients that have three products that are paying $225 a month"
  - **Speaker**: Hudson Lorfing

### System Problems
- **Issue**: Time tracking system doesn't differentiate between service types
  - **Impact**: Cannot allocate costs properly across setup, ongoing, and custom work
  - **Quote**: "But then do they know if it's set up ongoing. And so it's just... So it's all going to one project currently"
  - **Speaker**: Hudson Lorfing

## Questions and Uncertainties

### Resolved Questions
**Q**: "How we deal with the general cost that served in multiple services... We can measure the profit and loss for each product?"
**A**: Use journal entries to allocate costs based on time tracking percentages
**Quote**: "So if your team metric hours are tagged according to the product or according to as it's set up for ongoing or custom. Then you can just create a summary table of that at the end of the month"

### Unresolved Questions
**Q**: "We need to talk with the production team if they can track it that way"
**Status**: Requires operational team consultation to determine feasibility
**Quote**: "This is really challenging order because it's to do it that way. We need to initially we need to talk with the production team if they can track it that way"

**Q**: Whether payment processing fees should be classified as cost of sales vs. operating expenses
**Status**: Need to establish industry standard practice
**Quote**: "But is it different from cost of sales versus conception? In my perspective that is different concept is to be separate from cost of function"

## Key Insights and Patterns

- **Strategic Decision-Making Gap**: Management making pricing and resource decisions based on "instinct" rather than data
  - "So like, I think that in the past they're making those kinds of thoughts or decisions partially based on instinct... But as it gets bigger, as it gets more complex, as there's more customers, like their ability to do that gets less just naturally"

- **Product Development Investment Uncertainty**: Custom models improve overall product but profitability unclear
  - "And the custom 3D models, like every time you do it, you've made your own product better. So in some ways I feel like it's easy to justify. Like it's okay that we lose money and I'm doing this... But like if we run this and we basically say like we lose tons of money on this, then like the approach"

## Action Items and Next Steps

- [ ] **Implement product-level tracking categories in Xero** - Huong/Hudson - Within 2-3 months
  - **Source**: "Obviously we don't have to solve this today, but because that's the most complicated change that I'm suggesting"

- [ ] **Consult with production team on time tracking capabilities** - Huong - Immediate
  - **Source**: "So we should proceed us fast... we need to talk with the production team if they can track it that way"

- [ ] **Complete pricing analysis for legacy clients** - Hudson - Ongoing
  - **Source**: "Hudson's putting like a full analysis together on price increase"

- [ ] **Move payment processing fees to cost of goods sold** - Huong - Quick implementation
  - **Source**: "And this chain is easy for us because this chain, if we change it that way, then this chain is easy for us because we just use one platform"

- [ ] **Set up monthly journal entries for cost allocation** - Huong - After time tracking system confirmed
  - **Source**: "So in terms of going forward, it would just be one set of journal trees each, like each month"

## Supporting Evidence

### Key Quotes by Theme

**Data Quality Concerns**:
> "The real truth was it's 88%. And I think those are the perfect kind of insights for you to be able to bring. So because before we set that metric to measure the production performance, we follow the course and that course the theory is exactly. That we apply. But from the real practice, I realized that because we have the five pencil in the middle a lot. It's not a lot, but it's material. Material that maybe apply that metric is not a problem. By 6% feels material, you know." - Hudson Lorfing

**Strategic Financial Insights**:
> "So to move towards measuring it financially and analytically and we could say like it's a good investment to do it or that's a distraction be able to get the financials the help tell the story to be the mutual tie breaking vote on certain things. Ultimately it should still be a management making decision on strategic direction of the company. But if the financials tell a clear story they can make an easier, faster, more accurate decision." - Hudson Lorfing

**Implementation Feasibility**:
> "So from a Client perspective. I think that way that is feasible. But not... we need to talk with the production team if they can trust the system to monitor stuff to give me the enough results to... Do you know how the system monitors what they're doing?" - Huong

---
*Analysis Date: 2026-01-05*
*Transcript Source: Meeting with Accounting - Nick Balsamo, Huong, Hudson Lorfing*