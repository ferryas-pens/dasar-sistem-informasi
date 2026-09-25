*PART II INFORMATION AS SOMETHING OF VALUE*

*Chapter 5*

*Information Value and Decision Making*

*Chapter Map*

*Sub-CPMK (Course Learning Outcome):* Able to explain the dimensions of quality and value of information and their relationship to decision-making at each management level.

This chapter covers the second part of the Sub-CPMK: information value, decision models, and decision-making across management levels. The first part (information quality) was covered in Chapter 4.

After reading this chapter, you will be able to:
1. Explain how information creates economic value through uncertainty reduction;
2. Calculate expected value under uncertainty using decision tree logic;
3. Differentiate decision types across strategic, tactical, and operational management levels;
4. Explain cognitive limitations in human decision-making and how information systems mitigate them;
5. Determine appropriate information characteristics for each management level.

*Prerequisites:* Chapter 1 for the definition of information, Chapter 4 for information quality dimensions.

*Keywords:* Information value, uncertainty reduction, decision tree, expected value, management levels, structured/unstructured decisions, bounded rationality, cognitive bias.

*Deliverable:* A quantitative evaluation of information value in a simplified business scenario, accompanied by a profile of information needs across management levels.

---

*The Price of a Weather Forecast*

A Logistics Manager at an inter-island shipping firm faces a daily decision: whether to send a cargo vessel through a strait known for bad weather or divert to a longer route around it.

Taking the direct route saves $5,000 in fuel. However, if severe weather strikes midway, the ship must slow down, risking cargo damage and delay penalties totaling $50,000. Taking the safer, longer route adds $3,000 in fuel costs regardless of weather conditions.

Historical weather data indicates a 20% probability of severe storms in the strait on any given day.

Without a weather forecast, the manager must choose based purely on probabilities. With a specialized maritime weather subscription costing $500 per month, the firm receives highly accurate daily predictions.

Is the $500 monthly subscription worth paying? How exactly does the forecast create value if it cannot change the actual weather?

This scenario illustrates the core principle of this chapter: **information derives its value not from its existence, but from its ability to improve decisions made under uncertainty.**

---

### 5.1 How Information Creates Value

In economics, tangible goods have intrinsic utility—a truck carries cargo, and a server processes data. Information, however, has no physical utility on its own. A report or dataset stored on a drive generates zero value until someone reads it and alters an action based on its contents.

> **The value of information is the difference between the expected payoff of a decision made with that information and the expected payoff of the decision made without it, minus the cost of obtaining the information.**

$$\text{Value of Information} = E(\text{Payoff with Information}) - E(\text{Payoff without Information}) - \text{Cost of Information}$$

Information creates economic value through three primary mechanisms:

1. **Uncertainty Reduction:** Decreasing the variance of potential outcomes so decision-makers can select actions with higher probability of success.
2. **Error Avoidance:** Preventing costly mistakes (such as overproducing inventory or entering a failing market).
3. **Opportunity Capture:** Enabling early action on emerging market trends before competitors react.

---

### 5.2 Quantifying Information Value: Expected Value Logic

To determine whether acquiring information is financially justified, organizations use **Expected Value (EV)** logic, often represented via decision trees.

***Figure 5.1 Decision Tree Structure for Information Evaluation***

#### Step 1: Decision Without Information
Without additional data, the decision-maker calculates the expected value of each alternative action using base-rate probabilities ($P$):

* **Action A (Direct Route):**
  $$EV(\text{Direct}) = (P(\text{Storm}) \times \text{Cost}_{\text{Storm}}) + (P(\text{Clear}) \times \text{Cost}_{\text{Clear}})$$
  $$EV(\text{Direct}) = (0.20 \times -50,000) + (0.80 \times 0) = -\$10,000$$
  *(Note: Net fuel savings of $5,000 baseline; penalty cost is -$50,000).*

* **Action B (Longer Route):**
  $$EV(\text{Longer}) = -\$3,000 \text{ (guaranteed fuel cost)}$$

Comparing the two expected payoffs/costs, a rational decision-maker without additional information would choose the longer route to limit the expected loss ($-\$3,000$ vs $-\$10,000$).

#### Step 2: Decision With Perfect Information
If a hypothetical perfect forecast exists (100% accuracy):
* When it predicts a storm (20% of days): Choose the longer route (Cost: $-\$3,000$).
* When it predicts clear weather (80% of days): Choose the direct route (Cost: $\$0$).

$$\text{Expected Cost with Perfect Information} = (0.20 \times -\$3,000) + (0.80 \times \$0) = -\$600$$

#### Step 3: Calculating Expected Value of Perfect Information (EVPI)
$$\text{EVPI} = \text{Expected Cost without Information} - \text{Expected Cost with Perfect Information}$$
$$\text{EVPI} = \vert{}-\$3,000 - (-\$600)\vert{} = \$2,400 \text{ per day}$$

The theoretical upper limit of what the company should pay for weather information is **$2,400 per day**. Any subscription costing less than this limit (such as $500/month) yields a net positive return on investment.

---

### 5.3 Decision Types and Management Levels

Information requirements vary dramatically across an organization. A top executive and a frontline supervisor require entirely different types of information to make their respective decisions.

***Figure 5.2 Anthony's Triangle: Management Levels and Decision Types***

#### 1. Operational Level (Operational Control)
* **Users:** Frontline supervisors, operators, clerks.
* **Focus:** Performing specific daily tasks efficiently.
* **Decision Characteristics:** Highly **structured** (routine, repetitive, follow predefined rules and standard operating procedures).
* **Information Needs:** Real-time, detailed, internal, historical, and highly accurate transactional data.
* **Example:** Approving a routine credit purchase based on pre-set credit limits.

#### 2. Tactical Level (Management Control)
* **Users:** Department managers, unit heads, regional directors.
* **Focus:** Allocating resources and monitoring performance to achieve unit goals.
* **Decision Characteristics:** **Semi-structured** (combine standard procedures with managerial judgment).
* **Information Needs:** Aggregated summaries, comparative reports, trend analysis, internal combined with selective external data.
* **Example:** Adjusting monthly regional sales quotas based on quarterly performance trends.

#### 3. Strategic Level (Strategic Planning)
* **Users:** Executive board, CEO, Vice Presidents.
* **Focus:** Defining long-term organizational goals, strategy, and policy.
* **Decision Characteristics:** **Unstructured** (novel, non-routine, no fixed algorithms, high uncertainty).
* **Information Needs:** High-level summaries, projections, external competitive and economic indicators, broad and flexible formats.
* **Example:** Deciding whether to enter an emerging international market or acquire a competitor.

---

### 5.4 Information Characteristics Across Levels

| Information Attribute | Operational Level | Tactical Level | Strategic Level |
| --- | --- | --- | --- |
| **Scope** | Narrow, specific task | Departmental / Functional | Organization-wide, Industry |
| **Aggregation Level** | Detailed (Itemized) | Summarized / Grouped | Highly Aggregated |
| **Time Horizon** | Historical / Real-time | Short-to-medium term | Long-term future projections |
| **Source** | Primarily Internal | Internal & External | Heavily External |
| **Currency** | Highly current / Live | Periodic (Daily/Weekly) | Periodic / Ad-hoc |
| **Structure** | Standardized / Rigid | Semi-formatted | Unstructured / Customized |

---

### 5.5 Human Cognitive Limitations and Biases

Even when high-quality information is available, human decision-makers rarely act like ideal rational machines. **Bounded Rationality** (Herbert Simon) recognizes that human cognitive capacity, time, and memory are limited.

To cope with complex decisions, humans rely on mental shortcuts (heuristics), which often introduce systematic cognitive biases:

* **Confirmation Bias:** Seeking out or prioritizing information that confirms pre-existing beliefs while ignoring contradicting evidence.
* **Availability Bias:** Overestimating the likelihood of events that are easily recalled from memory (e.g., recent crises or vivid incidents).
* **Anchoring Bias:** Over-relying on the first piece of information received when making subsequent judgments.
* **Overconfidence Effect:** Overestimating the accuracy of one's own estimates or forecasts.

> **Role of Information Systems:** Information systems are designed not just to transmit data, but to act as cognitive prosthetics—counteracting human bias through standardized algorithms, objective data visualization, structured workflows, and automated decision rules.

---

> **Behind the Scenes: Why Dashboards Often Fail Executives**
> 
> Many business intelligence software vendors sell executive dashboards filled with dense, real-time operational metrics (e.g., server load, minute-by-minute transaction counts).
> 
> When CEOs use these dashboards, they often experience information overload. Executive decisions (strategic) require broad environmental context, market trends, and long-term forecasts—not raw operational transaction streams.
> 
> Effective executive information systems (ESS/EIS) filter out daily operational noise and focus on strategic KPIs, external benchmark comparisons, and scenario modeling ("What-If" analysis).

---

> **Common Misconceptions**
> 
> * **"More information always leads to better decisions."** Excessive information causes information overload, increasing decision latency and reducing overall decision quality.
> * **"Information has inherent value."** Unused information has zero economic value regardless of how expensive or accurate it was to collect.
> * **"Strategic decisions can be fully automated."** Unstructured decisions involve qualitative factors, strategic intuition, and ethical judgments that algorithms cannot fully address.

---

### Guided Case Study: Retail Inventory Replenishment

A retail chain with 50 branch stores currently relies on individual store managers to manually place weekly inventory reorders based on personal judgment.

#### Problem Analysis
* **Operational Level:** Store managers spend 6 hours per week manually counting stock and writing orders, resulting in inconsistent stockout rates across branches.
* **Tactical Level:** Regional managers lack real-time visibility into overall stock distribution, preventing inventory rebalancing between stores.
* **Strategic Level:** Executives cannot forecast supply chain costs accurately for the upcoming fiscal year.

#### Proposed Information System Solution
1. **Automate Operational Decisions:** Implement an automated Inventory Management System using a Reorder Point (ROP) algorithm to auto-generate replenishment orders when stock hits predefined thresholds.
2. **Support Tactical Decisions:** Build aggregated dashboard reports for regional managers showing inventory turnover rates and demand anomalies across branch clusters.
3. **Enable Strategic Planning:** Implement predictive analytics tools to model supplier lead times and raw material price fluctuations under different economic scenarios.

#### Impact Mapping

| Level | Decision Type | System Feature | Expected Outcome |
| --- | --- | --- | --- |
| **Operational** | Structured | Automated ROP Reordering | 80% reduction in stockouts; eliminates manual ordering effort. |
| **Tactical** | Semi-Structured | Regional Stock Analytics | 15% reduction in total holding costs via inter-store transfers. |
| **Strategic** | Unstructured | Predictive Supply Chain Modeling | Improved long-term vendor negotiations and risk management. |

---

### Summary

* Information derives economic value solely from its capacity to improve decisions made under uncertainty.
* The Expected Value of Information (EVPI) sets the theoretical maximum cost an organization should pay for additional data.
* Management decisions are categorized into operational (structured), tactical (semi-structured), and strategic (unstructured) levels.
* Information characteristics must match the management level: operational levels need granular real-time data, while strategic levels need aggregated, forward-looking external data.
* Information systems mitigate human cognitive biases and bounded rationality by structuring information and providing objective analytical tools.

---

### Exercises

#### Level A: Remembering
1. Define the economic value of information in your own words. `[Sub-CPMK-2]`
2. Explain the difference between structured, semi-structured, and unstructured decisions. `[Sub-CPMK-2]`
3. Identify the three levels of management in Anthony's Triangle and state the primary focus of each. `[Sub-CPMK-2]`
4. What is bounded rationality, and who introduced the concept? `[Sub-CPMK-2]`
5. List four common cognitive biases that affect managerial decision-making. `[Sub-CPMK-2]`

#### Level B: Applying
1. A factory manager must decide whether to perform preventive maintenance on a critical machine ($2,000 cost). If unmaintained, there is a 30% chance the machine breaks down, causing $10,000 in lost production. Calculate the expected value of both options and determine the optimal choice without additional diagnostic data. `[Sub-CPMK-2]`
2. Using the scenario in Question 1, calculate the Expected Value of Perfect Information (EVPI) for a diagnostic sensor system. `[Sub-CPMK-2]`
3. Map the information requirements for an e-commerce platform across the three management levels (Operational, Tactical, Strategic). Use a structured comparison table. `[Sub-CPMK-2]`

#### Level C: Analyzing & Evaluating
1. A company director demands that the IT department build a single dashboard showing every transaction in real-time for all executive board members. Critique this request based on the concepts of management levels, information overload, and information characteristics. `[Sub-CPMK-2]`
2. Analyze a situation in which an organization implemented a technically sound information system, but decision quality failed to improve due to human cognitive biases. Suggest system design improvements to address these human factors. `[Sub-CPMK-2]`

---

### References
1. Laudon, K. C., & Laudon, J. P. *Management Information Systems: Managing the Digital Firm*. Pearson (Latest Edition). Chapter on Enhancing Decision Making.
2. Simon, H. A. *The New Science of Management Decision*. Harper & Row. Concepts of Bounded Rationality and Decision Structures.
3. Anthony, R. N. *Planning and Control Systems: A Framework for Analysis*. Harvard Business School. Management Control Framework.

---

### Appendix: List of Figures
*This page is not printed in the book. Both vector figures are completed and ready.*

| No. | Title | Print Height | Status |
| --- | --- | --- | --- |
| 5.1 | Decision tree structure for information evaluation | 2.5 inches | Complete |
| 5.2 | Anthony's Triangle: Management levels and decision types | 2.8 inches | Complete |