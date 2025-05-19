# Jake’s guide to how to make money selling AI/ML

# Introduction
## Who am I?
- Decade-long client-facing DS+MLOps lead consultant:
    - 33% selling projects to ensure realistic (and fun) projects for my team
    - 33% leading model development to ensure accuracy
    - 33% leading MLE development to ensure models end up in production
- Switched to technical sales focused on AI.

## Why am I putting this together?
- Because I have a horrible memory so I need notes to remind myself of what I've learned.
- Because I have learned some things the hard way which some DS might find helpful.

## Highlights
- The most important question a Data Scientist should ask is **so what**... you have a good model, so what?
    - Problems before solutions
- Cloud revenue comes from data, not from AI/ML infra
    - Dangle latest AI to open the door, but pivot to underlying data
- AI requires domain expertise and industrial language
    - Must use customer’s language
- Get upstream of sales pipeline


# First principles
## AI
- Our team’s goal is entire platform spend, not just AI.
- AI is not money maker, DM is money maker. This is because “Data has gravity”.
- Thus makes the most sense to dangle latest AI to drive data gravity
    - How to ensure both short and long-term commitment?
- AI is a long-term play.
    - ROI-generating AI requires end user buy-in (UAT), data at scale (multiple teams, multiple warehouses), in production (DevOps, security)

## Sales
- Our team’s goal is platform spend (obviously).
- Friends buy from friends, and friends help each other succeed.
    - While we may not be able to help the stakeholder personally (yet), we may be able to help their careers. In general this means helping the stakeholder help their customers, both internal and external.
    - Thus helping our stakeholder help their customers (help their customers) = they get paid = we get paid
        - How does our stakeholder get paid?
- If our stakeholder gets paid more than they me us i.e. positive ROI, then paying us is an obvious choice.
    - How do we determine how much they’ll get paid i.e. the return?
    - How do we determine how much they’ll pay us i.e. the investment?
 
## Mistakes made, lessons learned
- Trying to sell solutions while not addressing business goals
    - Lesson: sell problems, not solutions; hide any technical discussion until calls 2 or 3
- Not being able to articulate how my models would impact their bottom line
    - Lesson: Not having enough domain expertise
    - Lesson: AI is not sold to IT, it’s sold to business
    - Action: Industry-specific language is key


# Part 1: Building a pipeline
First, we establish what the potential returns on a project will be. Returns on investment can be divided into two buckets: increasing profits or decreasing losses aka as generating revenue vs reducing cost.

## Identifying a use case base on efficiency gained or cost reduced.
- Easy: what are processes that a human can do within 3 seconds?
    - These are boring, tedious, prone to error, and ripe for automation.
- Medium: ask the above but for the customer’s customer.
- Hard: where is the industry going? Requires domain expertise
    - IoT 4, sustainability, efficiency

## Value chain-based discovery
- Organization/company:
    - What is their business model? Do they sell products, services, subscriptions, something else?
        - If B2C: Who is the end customer?
        - If B2B: Who is their end customer?
    - Domain expertise is key
- Team/unit/department: connect the dots
    - What is their "business model"?
- Personal: metrics
    - Step into their shoes
    - Validate pain points
    - Confirm prescriptions
- Bonus: personal aspirations
- Beware some DS can be defensive. Stress that you’re not here for their job and are only here to empower them
    - “1) you know more about your data than I do and 2) I’m very happy here at Google. I’m simply here to see if GCP can help you do your job easier.”
- Past use cases
- DS metrics → industry-specific metric
    - Precision and recall in industry terms
- Parallel long-term short-term path


# Part 2: Prioritizing pipeline based on ROI

## Calculating returns (Why)

### Calculating potential cost reduction
- Start with cost reduction as it's often the easier one to determine since AI/ML is about automation.
- Cost reduced = time reduced per person * people enabled.

### Calculating potential revenue gained
- What is customer willing to pay?
- What is baseline value customer is gaining from your AI product/service?

## Calculating investment
### Operating Expenditure
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

### Capital Expenditure
Implementation
- Internal: training, opportunity cost, new hires
- Partner inc. GCC: high bill rate, PM overhead

### Total expenditures
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
