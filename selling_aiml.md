# Jake’s guide to how to make money selling Cloud-native AI/ML

# Introduction
## Who am I?
- Decade-long client-facing DS+MLOps lead consultant:
    - 33% selling projects to ensure realistic (and fun) projects for my team
    - 33% leading model development to ensure accuracy
    - 33% leading MLE development to ensure models end up in production
- Switched to technical sales focused on AI.
- 7 years AWS then 1+ GCP.

## Who is this for?
This is for anyone who is selling AI/ML products and services at GCP or other Cloud providers.


# Part 0: First principles
## AI/ML
- AI is not money maker, data is money maker: “data has gravity”.
- Thus makes the most sense to dangle latest AI to drive data gravity
- AI is a long-term play: ROI-generating AI requires end user buy-in (UAT), data at scale (multiple teams, multiple warehouses), in production (DevOps, security)
    - *Is this still the case w/ LLMs?*

## Sales
- Friends buy from friends, and friends have each other's best interests at heart.
- While we may not be able to help the stakeholder personally (yet), we may be able to help them get promoted.
- Helping the stakeholder get promoted usually means helping their customers, both internal and external.
- Thus helping our stakeholder help their customers (help their customers) = they get paid = we get paid
- If our stakeholder gets paid more than they pay us i.e. **positive ROI**, then buying from us is an obvious choice.
 
## Mistakes made, lessons learned
- Trying to sell solutions while not addressing business goals
    - Lesson: Sell problems being solving; do not sell products and solutions
    - Action: Hide any technical discussion until calls 2 or 3
- Not being able to articulate how my models would impact their bottom line
    - Lesson: Not having enough domain expertise
    - Lesson: AI is not sold to IT, it’s sold to business
    - Action: Industry-specific language is key


# Part 1: Building a pipeline
Let's expand on the first principle that a positive ROI makes a buying from us an obvious choice, starting with breaking down identifying and calculating returns. Returns can be divided into two buckets based on P&L: generating revenue vs reducing cost.

## Opportunities for cost reduction
- AI/ML = automation = cost reduction and efficiency improvement

### Identification
What are processes that are boring, tedious, and thus prone to error?
    - What tasks would humans not mind giving up once trust is established?
    - For classic ML, consider 3 second rule: what are processes that a human can do within 3 seconds?
    - For GenAI, most are comfortable now with summarization across multi-modal inputs. Repetitive text-based tasks can also be considered as boredom sets in and by then dataset will exist for evaluation. Other use cases may be considered based on trust and risk of potential harm.

Important: be sure to establish that increased performance should be baselined against existing processes e.g. humans, and not a hypothetical perfect future. Do not let perfect be the enemy of progress.

### Calculating potential cost reduction
- Start with cost reduction as it's often the easier one to determine since AI/ML is about automation.
- Cost reduced = time reduced per person * people enabled.

## Opportunities for revenue generation using value chain
- Logical to use value chain to extend cost reduction to customers's customers.
- See Gemini and LLMs: $20/mo subscription 

### Identification
- Organization/company
    - What is their business model? Do they sell products, services, subscriptions, something else?
        - If B2C: Who is the end customer?
        - If B2B: Who is their end customer?
    - Domain expertise is key
- Team/unit/department
    - What is their "business model"?
    - What teams are their "end customers"?
- Personal
    - What are their metrics?
    - How would they get promoted?
    - Beware some DS can be defensive. Stress that you’re not here for their job and are only here to empower them
        - “1) you know more about your data than I do and 2) I’m very happy here at Google. I’m simply here to see if GCP can help you do your job easier.”

### Calculating potential revenue gained
- What is customer willing to pay?
- What is baseline value customer is gaining from your AI product/service?


# Part 2: Prioritizing pipeline based on ROI
Next, we establish what the potential investment 

## Operating Expenditure
Cloud consumption for custom AI/ML
- Compute: data engineering
- Compute: model training and inference
    - Vertex train
    - Vertex deploy
    - Cloud Run
    - GKE
- Compute: end-user UI / API
    - Dashboard
    - Pipeline to 
- Storage:
    - Structured data in BQ, etc
    - Unstructured data in GCS

Cloud consumption for GenAI
- LLM API
    - Managed
        - Gemini 2.5
        - Gemini 2.0
    - Custom model training and inference
        - See above for AI/ML
- Compute: end-user UI / API
    - Agent Engine
    - Cloud Run
    - GKE
- Storage
    - Embedding index
    - Context cache

## Capital Expenditure
Implementation
- Internal: training, opportunity cost, new hires
- Partner inc. GCC: high bill rate, PM overhead

## Total expenditures
- What is breakeven? What are assumptions to / probablity of breakeven?

## Realizing ROI
### Path to production

### Stakeholders

### Politics
If the above calculations result in a positive ROI and you are still facing objections, then there may be political forces at play.

## Examples
### Example 1: GCP AI CE
Metrics

### Example 2: Plant manager, TSMC
Metrics

### Example 3: VP of Digital Transformation, TSMC
Metrics


# Part 3: Ensuring success of a DS project
TBD


# 2 path for stickiness
- Short-term AI POC, target long-term digital transformation
    - Depends on data migration for full scalability
- Short-term DA, target long-term data migration
    - This is money maker for GCP


# Templates
## Discovery questions
1. Business: WHY should this project be done? Who is buying? What is current end-user day-in-the-life/UX? Why will the end-user buy (with money or with time) this?
2. Technical: WHAT is being built to generate value? What data is needed? What model is used? What agents are being deployed? What is the UI/UX the end user will use? What is the orchestration and pipelining?
3. Operational: WHO will own and maintain the code? How will value be realized?

## Discovery workshop agenda
Purpose: Working backwards from business outcomes, arrive at informtion to derive 1+ projects/SOWs.
Agenda: 
- Hour 1: Voice of customer
- Hour 2: Business process understanding (we'll listen in for use cases here)
- Hour 3: Use case deep dive, ROI justification, prioritization/triage
- Hour 4: Technical deep dive, next steps


# Feedback
- Working backwards from personas to products
- Specific examples
- Working with account managers as specialists e.g. AI/ML strategy, stakeholders, etc


# Unused
## Highlights
- The most important question an AI/ML project should ask is **so what**... you have a good model, so what?
    - Projects must solve a business problem
    - Communicate in domain language e.g. in manufacturing recall is defects caught and precision is good products scrapped
- Cloud revenue comes from data, not from AI/ML infra
    - Dangle latest AI to open the door, but LLMs don't make money
    - pivot to underlying data
- AI requires domain expertise and industrial language
    - Must use customer’s language
- Get upstream of sales pipeline
