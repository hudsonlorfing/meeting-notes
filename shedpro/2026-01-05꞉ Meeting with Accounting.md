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
  - "[[👤Hudson]]"
workspace: shedpro
analysis_apps: [sprint-retro, team-sync, one-on-one]
model: gemini-2.0-flash
processed_by: hudson
one-liner: 
---

# 2026-01-05꞉ Meeting with Accounting
*Meeting on 2026-01-05*

## Participants
- "[[👤Hudson]]"

# Meeting Analysis: Accounting Review

## 1. Current State of Accounting

*   **Description:** The current accounting system tracks setup, recurring subscriptions, and custom 3D models. The financials are not broken down by product, making it difficult to measure the profitability of each product or service. Time tracking is manual.
    *   *Evidence:* "But currently for accounting we just track setup, recursive, subscription and custom for 3D models."
    *   *Evidence:* "So it's manual and they just sign the... measure the time they spent on one project."
*   **Software/Tools:** Xero, Stripe, Team Metric, Fathom
    *   *Evidence:* "I think it's a zero software calls it category."
    *   *Evidence:* "So on the revenue side it would be figuring out how to code that stripe so that it comes in like..."
    *   *Evidence:* "Yeah team metric and it might be you have the amount for the month with payroll and you just do a journal entry and say 20% of the cost was ad sales, and 60% of the cost of, like, hours was the model configurator."
    *   *Evidence:* "Actually, I'm going to use Fathom because I have a consolidation."
*   **Metrics/KPIs:** Retention rate (currently flagged as inaccurate), production performance rate, and various others being tracked by the new team.
    *   *Evidence:* "The other I know I saw in 90 that you flagged the retention rate of the 94% is really like 88%."
    *   *Evidence:* "So because before we set that metric to measure the production performance, we follow the course and that course the theory is exactly."
    *   *Evidence:* "You mean for now the KVIS is so a lot of KVIs for the new team."

## 2. Identified Issues/Challenges

*   **Issue 1: Inaccurate Data/Metrics**
    *   **Description:** Some of the current metrics, such as the retention rate, are inaccurate and cannot be relied upon.
    *   **Accountant's Concern:** No specific concern voiced by the accountant in relation to this issue.
    *   **Nick Balsamo's Concern:** The current reported retention rate of 94% is actually closer to 88%, indicating unreliable data.
        *   *Evidence:* "The other I know I saw in 90 that you flagged the retention rate of the 94% is really like 88%."
        *   *Evidence:* "Those are like, like, in other words, you can't rely on the data."
*   **Issue 2: Lack of Granularity in Financial Reporting**
    *   **Description:** The current accounting system does not provide a breakdown of financials by product, making it difficult to assess the profitability of individual products/services.
    *   **Accountant's Concern:** Expresses the feeling that the accounting data doesn't provide enough information on the profitability of different areas, particularly custom 3D models.
        *   *Evidence:* "And we maybe we also realize that the accounting data now is haven't tell us enough information about how this area can make profit or not."
        *   *Evidence:* "Especially we have the same feeling... I have this at least have sent to me in 3D models because I see that we make a lot of time and effort on that and that's what we make problem."
    *   **Nick Balsamo's Concern:** The lack of detailed financial reporting hinders informed decision-making, especially in areas like pricing and resource allocation.
        *   *Evidence:* "But if the financials tell a clear story they can make an easier, faster, more accurate decision."
        *   *Evidence:* "Like basically we want to be able to build out the accounting to be able to provide insights to him so that he has better decision making tools."
*   **Issue 3: Difficulty in Allocating Costs Across Multiple Services**
    *   **Description:** General costs are not easily allocated to specific products/services, making it challenging to determine the true cost of each offering.
    *   **Accountant's Concern:**  Questions how to allocate general costs that serve multiple products and how to amortize costs for multiple services.
        *   *Evidence:* "But we have the general cost structure for multiple products. How... How do we do that?"
        *   *Evidence:* "So how is that or how do the amortization... You mean that way we need to do amortize amortization for all of the costs that is arise that arises."
    *   **Nick Balsamo's Concern:**  Highlights the need to find a method for allocating costs, suggesting the use of team metric hours and journal entries to split costs across categories.
        *   *Evidence:* "And then on the cost side I think that that's actually weird enough to lean into the like the hours the tracking with... Yeah team metric and it might be you have the amount for the month with payroll and you just do a journal entry and say 20% of the cost was ad sales, and 60% of the cost of, like, hours was the model configurator."
*   **Issue 4: Manual Time Tracking**
    *   **Description:** Time tracking is currently a manual process, potentially leading to inaccuracies and inefficiencies in cost allocation.
    *   **Accountant's Concern:** Acknowledges the challenge in accurately tracking time spent on different projects and services due to the manual nature of the current system.
        *   *Evidence:* "This is really challenging order because it's to do it that way. We need to initially we need to talk with the production team if they can track it that way."
    *   **Nick Balsamo's Concern:**  Identifies the need to determine how the current system monitors time spent on different clients and services.
        *   *Evidence:* "Do you know how the system monitors what they're doing? Like, are they putting it in to say I spent this much time on this client."
*   **Issue 5: Lack of Clarity on Profitability of Custom 3D Models**
    *   **Description:** There's a lack of data to determine if custom 3D models are profitable.
    *   **Accountant's Concern:** Expresses concern that a lot of time and effort is spent on custom 3D models without knowing if they are profitable.
        *   *Evidence:* "Especially we have the same feeling. I have this at least have sent to me in 3D models because I see that we make a lot of time and effort on that and that's what we make problem."
    *   **Nick Balsamo's Concern:** Underscores the need to determine if custom models are profitable.
        *   *Evidence:* "Like custom models, like I don't have space for pricing, you know."

## 3. Proposed Changes/Improvements

*   **Change 1: Implement Tracking Categories in Xero**
    *   **Proposed By:** Nick Balsamo
    *   **Rationale:** To break down financials by product and service type (setup, ongoing, custom) for better profitability analysis.
    *   *Evidence:* "So Xero has the same capability and they're called tracking categories. So this is a smaller company. So tracking categories, you can create a category of anything. So yeah, you could do by product."
*   **Change 2: Allocate Costs Using Team Metric Hours and Journal Entries**
    *   **Proposed By:** Nick Balsamo
    *   **Rationale:** To allocate costs to different product/service categories based on time spent.
    *   *Evidence:* "Yeah team metric and it might be you have the amount for the month with payroll and you just do a journal entry and say 20% of the cost was ad sales, and 60% of the cost of, like, hours was the model configurator."
*   **Change 3: Move Payment Processing Fees to Cost of Goods Sold**
    *   **Proposed By:** Nick Balsamo
    *   **Rationale:** To accurately reflect the cost of acquiring revenue by including payment processing fees as part of the cost of goods sold.
    *   *Evidence:* "The other thing I specifically think would make sense to move into cost of goods sold is the bank fees like the processing fees."
*   **Change 4: Improve Time Tracking to Differentiate Between Setup, Ongoing, and Custom Work**
    *   **Proposed By:** Nick Balsamo and Accountant (implied agreement)
    *   **Rationale:** To accurately allocate costs and understand the profitability of each service type.
    *   *Evidence:* "So to move towards measuring it financially and analytically and we could say like it's a good investment to do it or that's a distraction be able to get the financials the help tell the story to be the mutual tie breaking vote on certain things."
*   **Change 5: Analyze Pricing and Consider Price Increases**
    *   **Proposed By:** Nick Balsamo
    *   **Rationale:**  To increase revenue and improve the bottom line, especially for clients with outdated pricing.
    *   *Evidence:* "Is the pricing, because you have clients from forever ago that have never had a price increase. If you increase their rates, that's directly benefiting the bottom line."

## 4. Next Steps

*   **Action 1:** Discuss the proposed changes with the production team to determine the feasibility of tracking time by product and service type.
    *   **Responsible Party:** Accountant
    *   **Deadline:** Implied to be as soon as possible.
    *   *Evidence:* "We need to initially we need to talk with the production team if they can track it that way."
*   **Action 2:** Meet in person to discuss the most complicated changes.
    *   **Responsible Party:** Nick Balsamo and Accountant
    *   **Deadline:** Possibly the next day (tomorrow morning).
    *   *Evidence:* "Yeah, I would prefer to talk about it in person so I can get your real feedback and like you can challenge if you think something is not quite right or why it's very difficult... Maybe tomorrow in the morning."
*   **Action 3:** Hudson to put together a full analysis of price increases.
    *   **Responsible Party:** Hudson
    *   **Deadline:** Not explicitly stated, but implied to be within the next few months.
    *   *Evidence:* "Hudson's putting like a full analysis together on price increase."
*   **Action 4:** Accountant to check the data that Hudson pulls and make sure it is accurate.
    *   **Responsible Party:** Accountant
    *   **Deadline:** Before Hudson presents the data to leadership.
    *   *Evidence:* "And so before I, before I like present any of this, I'll get you to check it and make sure that like, you know, I pulled everything correctly and like I already know there's some errors."

## 5. Accountant's Overall Perspective

*   The accountant recognizes the need for more detailed financial reporting to better understand the profitability of different services, particularly custom 3D models. They are open to implementing changes and are willing to work with the production team to improve time tracking and cost allocation. They also express a need for guidance on US tax laws and financial strategies. The accountant is excited to set up the system in a better way.
    *   *Evidence:* "And we maybe we also realize that the accounting data now is haven't tell us enough information about how this area can make profit or not."
    *   *Evidence:* "Especially we have the same feeling. I have this at least have sent to me in 3D models because I see that we make a lot of time and effort on that and that's what we make problem."
    *   *Evidence:* "So we can set up the system this way."
    *   *Evidence:* "That is the one area that I'm lacking. The second one is that I'm not sure about the... the law in the US So I can give Jim a good advice for that."

## 6. Nick Balsamo's Overall Perspective

*   Nick Balsamo believes that the current accounting system needs significant improvements to provide better insights for decision-making. They propose several changes to improve financial reporting, cost allocation, and pricing strategies. They believe that by implementing these changes, the company can gain a clearer understanding of its profitability and make more informed decisions about resource allocation and sales strategies. Nick Balsamo also sees their role as a financial storyteller, helping the company understand its financial data and make strategic decisions.
    *   *Evidence:* "But if the financials tell a clear story they can make an easier, faster, more accurate decision."
    *   *Evidence:* "Like basically we want to be able to build out the accounting to be able to provide insights to him so that he has better decision making tools."
    *   *Evidence:* "So that's my job as a financial stone storyteller."