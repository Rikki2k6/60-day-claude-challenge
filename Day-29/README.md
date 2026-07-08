# Day 29 — Operation Lifeline: Supply Chain Crisis Lab

## Overview

For Day 29 of the **60 Days Claude Challenge**, I built **Operation Lifeline**, an interactive Supply Chain Crisis Simulator using Claude.

The application places the user in charge of a randomly generated company facing a major supply chain disruption.

Instead of simply reading about supply chain management, the simulator requires the user to make decisions across multiple stages:

- Understand the company and its operational vulnerabilities
- Analyze a supply chain crisis
- Select crisis response actions
- Negotiate with a supplier
- Make CEO-level leadership decisions
- Choose long-term AI investments
- Review the final business performance dashboard

Every decision affects different business metrics, making the simulation a practical exercise in understanding trade-offs.

---

## Final Application

### Company Profile

![Company Profile](Screenshot%20(257).png)

The simulation generated the following company:

**Company:** Anchor Systems  
**Industry:** Home Furniture  
**Annual Revenue:** $835M  
**Factories:** 9  
**Warehouses:** 4  
**Active Suppliers:** 53  
**Inventory on Hand:** 12 days  
**Average Supplier Lead Time:** 66 days  
**Sourcing Countries:** Turkey and Mexico

One of the first important insights was the relationship between inventory and lead time.

The company had only **12 days of inventory available**, while suppliers required an average of **66 days** to deliver new stock.

This meant that the company had very little protection against a major supply disruption.

---

## The Simulation Flow

The application follows a complete crisis-management journey:

1. Company Profile
2. Crisis Briefing
3. War Room
4. Supplier Negotiation
5. CEO Boardroom
6. AI Strategy
7. Final Dashboard

A progress indicator tracks the user's movement through the simulation.

The company profile and crisis are randomly generated, meaning the application can produce different scenarios when replayed.

---

## War Room Decisions

![War Room Decisions](Screenshot%20(258).png)

During the crisis response stage, I had to choose exactly **3 out of 6 possible actions**.

My selected actions were:

- Activate Backup Supplier
- Temporarily Cut Low-Priority SKUs
- Deploy Real-Time Tracking Dashboard

Each action involved a different trade-off between:

- Cost
- Inventory
- Profit
- Delivery speed
- Customer satisfaction

---

## Why I Chose These Actions

### Activate Backup Supplier

The goal was to reduce dependency on the primary supplier and create an alternative source of supply.

This improved resilience and inventory availability, although the alternative supplier could introduce differences in price, quality, and delivery performance.

### Temporarily Cut Low-Priority SKUs

This decision focused limited resources on high-priority and high-demand products.

Reducing slower-moving products helped protect core revenue but also reduced product variety.

### Deploy Real-Time Tracking Dashboard

This improved supply chain visibility and decision speed.

An important insight from the simulator was that visibility does not directly move delayed goods, but it helps teams detect problems earlier and make better decisions.

---

## Simulated Outcome

The selected crisis actions produced the following scores:

| Business Metric | Score |
|---|---:|
| Cost Control | 47 |
| Inventory Health | 76 |
| Profit | 53 |
| Delivery Speed | 67 |
| Customer Satisfaction | 54 |

The strongest result was:

### Inventory Health — 76

The weakest result was:

### Cost Control — 47

This showed the main trade-off in my crisis strategy.

I successfully protected inventory and improved operational resilience, but the response came at a financial cost.

---

## Supplier Negotiation

The next stage simulated multiple rounds of supplier negotiation.

Each decision affected:

- Supplier trust
- Pricing
- Lead time
- Final negotiation performance

This section demonstrated that negotiation is not simply about getting the lowest possible price.

Aggressive negotiation can reduce costs but damage trust, while accepting every supplier demand may preserve the relationship but create an expensive agreement.

The challenge was to find a balance between:

- Short-term business needs
- Supplier relationships
- Financial discipline
- Long-term operational stability

---

## CEO Boardroom

![CEO Boardroom](Screenshot%20(259).png)

The Boardroom stage tested leadership decisions during the crisis.

I answered five CEO-level questions covering:

- Systemic thinking
- Accountability
- Financial discipline
- Employee and stakeholder trust
- Long-term planning

My final result was:

# Leadership Score — 98/100

The feedback highlighted the following strengths:

### Q1 — Systemic Thinking

The decision addressed the root cause instead of only reacting to symptoms.

### Q2 — Accountability

Direct accountability helped build trust even when communicating difficult information.

### Q3 — Balanced Decision-Making

The decision balanced urgency with financial discipline.

### Q4 — Honest Leadership

Transparent communication helped protect morale and trust during uncertainty.

### Q5 — Forward-Looking Thinking

The final decision moved the company from reactive crisis management toward proactive risk management.

This was the strongest section of my simulation.

---

## AI Strategy

After managing the immediate crisis, the simulator shifted toward long-term resilience.

The task was to select two AI investments for the company's future supply chain strategy.

The available technologies focused on areas such as:

- Demand forecasting
- Inventory optimization
- Supplier risk monitoring
- Warehouse intelligence
- Procurement support

This stage introduced an important distinction:

> Crisis actions help a company survive the current disruption, while technology investments help prepare for the next one.

AI creates the most value when it improves visibility, forecasting, risk detection, and decision-making before a crisis becomes severe.

---

## Final Dashboard

![Final Dashboard](Screenshot%20(260).png)

My final result was:

# Overall Crisis Score — 73/100

### Final Rating: Strong Operator

The final business scores were:

| Category | Score |
|---|---:|
| Leadership | 98 |
| Negotiation | 71 |
| Resilience | 72 |
| Cost Control | 47 |
| Risk Management | 72 |
| Customer Satisfaction | 65 |

---

## Performance Analysis

### Strongest Area — Leadership

With a score of **98**, leadership was my strongest area.

The simulator recognized decisions based on:

- Root-cause thinking
- Transparency
- Accountability
- Long-term planning

### Weakest Area — Cost Control

My lowest score was **47 in Cost Control**.

The crisis response improved resilience and inventory health, but some decisions were expensive.

This demonstrated one of the central lessons of supply chain management:

> The fastest or safest response is not always the cheapest response.

---

## Biggest Mistake

The final dashboard identified my biggest mistake as:

### Activating the Backup Supplier

The simulator concluded that this decision came at a real cost to profit or customer satisfaction and may not have been the most efficient use of resources.

This was interesting because the action initially appeared to be a strong resilience decision.

It showed that a decision can be strategically reasonable but still perform poorly depending on:

- The specific crisis
- Other actions selected
- Existing inventory
- Financial impact
- Available alternatives

---

## Best Decision

My strongest decision was:

### Proposing a Formal Supply Chain Risk Audit Across All Regions

The simulator identified this as a strong example of systemic thinking.

Instead of only solving the immediate crisis, the decision focused on finding structural weaknesses across the entire supply chain.

This could help the company identify:

- Supplier concentration risks
- Regional dependencies
- Long lead times
- Weak inventory buffers
- Future points of failure

The key lesson was:

> Strong crisis management should not only restore operations. It should reduce the probability and impact of the next crisis.

---

## Expert Recommendation

The final recommendation was to continue investing in:

- Supply chain visibility
- Operational flexibility
- Faster decision-making

These capabilities helped the company respond during the current crisis and could become even more valuable across future disruptions.

---

## What I Learned

### 1. Supply chain resilience depends on preparation

A company with only 12 days of inventory and a 66-day supplier lead time is extremely vulnerable to disruption.

The crisis begins long before the actual event if the company has not built enough flexibility.

### 2. Every crisis response has a trade-off

There was no action that improved every metric.

Improving delivery speed could increase costs.

Protecting inventory could reduce profit.

Improving visibility could help decisions without directly solving the physical disruption.

### 3. The best-looking decision is not always the best-performing one

Activating a backup supplier appeared to be a logical response, but the final analysis identified it as my biggest mistake.

This showed why decisions should be evaluated in the context of the entire system.

### 4. Leadership decisions matter as much as operational decisions

My leadership score of 98 was much higher than my cost control score of 47.

A company can make strong strategic and leadership decisions while still facing operational and financial weaknesses.

### 5. Transparency is a powerful crisis-management tool

The simulation repeatedly rewarded honest communication with:

- Customers
- Investors
- Employees
- Suppliers

Good communication does not remove the crisis, but it protects trust while the crisis is being solved.

### 6. AI should support decisions, not replace them

The AI strategy stage focused on using technology to improve:

- Forecasting
- Visibility
- Risk monitoring
- Inventory decisions
- Procurement

The value of AI comes from helping teams detect risks earlier and make better decisions.

---

## Technical Concepts Explored

Through this task, I explored:

- React-based interactive applications
- Random scenario generation
- Multi-stage simulation design
- State management
- Conditional rendering
- Dynamic scoring systems
- Decision-based outcomes
- Metric calculations
- Interactive negotiation logic
- Progress tracking
- Replay functionality
- Responsive dashboard design

---

## Observation

One of the most interesting parts of the application was how multiple independent decisions were combined into a final score.

The result was not based on a single correct answer.

Instead, the application evaluated performance across:

- Leadership
- Negotiation
- Resilience
- Cost control
- Risk management
- Customer satisfaction

This made the simulation feel more realistic than a simple quiz.

---

## Limitation

The simulation uses predefined decision effects and scoring rules.

Although scenarios are randomly generated, the application does not use a live AI model to dynamically evaluate every decision.

The outcomes are calculated using logic written inside the application.

A more advanced version could use an AI model to:

- Analyze free-text crisis strategies
- Generate dynamic supplier responses
- Create new crisis scenarios
- Evaluate reasoning instead of only selected options
- Provide more personalized executive feedback

---

## Key Takeaway

The most important insight from Day 29 was:

> **Crisis management is not about finding a perfect decision. It is about managing trade-offs better than the crisis manages you.**

A strong operator must balance:

- Speed
- Cost
- Profit
- Inventory
- Customer trust
- Supplier relationships
- Long-term resilience

The simulation showed that strong leadership alone is not enough.

The best response combines good judgment with operational preparation and financial discipline.

---

## Conclusion

Day 29 was one of the most detailed simulations in the challenge so far.

Unlike a static dashboard or simple educational application, **Operation Lifeline** created a complete decision-making journey.

I had to:

- Understand the company
- Analyze its vulnerabilities
- Respond to a crisis
- Make operational trade-offs
- Negotiate with suppliers
- Answer leadership questions
- Select AI investments
- Analyze the final results

My final score of **73/100 — Strong Operator** reflected both strengths and weaknesses.

The strongest part of my performance was leadership, while cost control remained the biggest area for improvement.

This task helped me understand how interactive simulations can turn complex business concepts into practical decision-making experiences.

---

## Challenge

**60 Days Claude Challenge — Day 29**

Built with Claude and explored through interactive supply chain crisis simulation.
