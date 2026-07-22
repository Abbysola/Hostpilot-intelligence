# Product Requirements Document

## Product Name

HostPilot Intelligence

## Document Purpose

This document defines the initial product requirements for HostPilot Intelligence, an AI-powered Product Intelligence Platform for a fictional domain registration and web hosting company.

The platform is designed to help product managers, executives, customer success teams, and data professionals understand customer behaviour, monitor product performance, identify risks and opportunities, and make data-informed decisions.

---

## 1. Product Overview

HostPilot Intelligence combines product analytics, customer analytics, machine learning, forecasting, and AI-generated insights in one platform.

The platform will use synthetic data representing realistic customer, product, subscription, usage, and revenue activity within a domain registration and web hosting company.

The first version will focus on answering practical product and business questions rather than attempting to reproduce every feature of a large commercial analytics platform.

---

## 2. Problem Statement

Domain registration and web hosting companies generate data across multiple products and customer touchpoints, including:

- Domain registrations and renewals
- Hosting subscriptions
- Customer account activity
- Product usage
- Support interactions
- Payments and revenue
- Upgrades, cancellations, and churn

This information may exist across separate systems, making it difficult for product teams to obtain a complete view of customer behaviour and product performance.

As a result, teams may struggle to answer questions such as:

- Why are customers cancelling?
- Which customers are likely to churn?
- Which product features encourage retention?
- Which customers are likely to upgrade?
- How are registrations, renewals, and revenue changing?
- Which product areas require attention?
- What actions should the product team prioritise?

HostPilot Intelligence will bring these signals together and convert them into useful analytics, predictions, forecasts, and recommendations.

---

## 3. Product Vision

To help product teams in the domain and hosting industry make faster and better decisions using analytics, machine learning, forecasting, and AI.

---

## 4. Product Goals

The platform should:

1. Provide a unified view of customers and their products.
2. Track important product and business metrics.
3. Help teams understand customer engagement and product adoption.
4. Identify customers at risk of churn or non-renewal.
5. Identify customers with a high likelihood of upgrading.
6. Forecast important business metrics.
7. Generate clear AI-powered summaries and recommendations.
8. Demonstrate an end-to-end Product Data Science workflow.
9. Be reproducible and deployable using modern engineering tools.

---

## 5. Non-Goals

The first version will not:

- Process real Hostlooni customer data.
- Reproduce Hostlooni's internal systems.
- Operate as a real domain registrar.
- Process real payments.
- Provision real hosting infrastructure.
- Replace a production customer relationship management system.
- Replace an enterprise product analytics platform.
- Make fully automated business decisions without human review.

All data used in the project will be synthetic.

---

## 6. Target Users

### 6.1 Product Manager

The Product Manager needs to:

- Monitor product performance.
- Understand customer journeys.
- Measure feature adoption.
- Identify friction points.
- Evaluate retention and conversion.
- Decide which product improvements to prioritise.

### 6.2 Executive or Business Leader

The executive needs to:

- Monitor revenue and customer growth.
- Review important business trends.
- Understand major risks and opportunities.
- Receive concise weekly or monthly summaries.
- Make strategic decisions using reliable metrics.

### 6.3 Customer Success Manager

The Customer Success Manager needs to:

- Identify customers at risk of cancelling.
- Understand the factors behind customer risk.
- Prioritise customers who may need support.
- Recognise opportunities for upgrades or cross-selling.

### 6.4 Product Data Scientist or Analyst

The Product Data Scientist needs to:

- Explore customer and product data.
- Define and calculate KPIs.
- Build customer segments.
- Develop and evaluate predictive models.
- Analyse experiments.
- communicate insights to stakeholders.

### 6.5 Marketing or Growth Team

The Marketing or Growth Team needs to:

- Understand acquisition and conversion.
- Identify valuable customer segments.
- Measure campaign and funnel performance.
- Find upgrade and cross-selling opportunities.

---

## 7. Core Product Areas

The platform will be organised into six main product areas:

1. Executive Overview
2. Customer Intelligence
3. Product Analytics
4. Predictive Intelligence
5. Forecasting
6. AI Product Copilot

---

# 8. Functional Requirements

## 8.1 Executive Overview

The Executive Overview should provide a concise summary of company and product performance.

### Required Metrics

- Total customers
- Active customers
- New customers
- Monthly recurring revenue
- Total revenue
- Active subscriptions
- Domain registrations
- Domain renewals
- Hosting subscriptions
- Customer churn rate
- Domain renewal rate
- Average revenue per customer
- Upgrade rate

### Required Features

- Display current KPI values.
- Compare KPIs with the previous period.
- Show trends over time.
- Highlight unusually strong or weak performance.
- Allow users to filter by date range.
- Allow users to filter by product type or customer segment.

### User Story

As an executive, I want to see the most important company and product metrics in one place so that I can quickly understand business performance.

---

## 8.2 Customer Intelligence

The Customer Intelligence section should provide a complete view of customer behaviour and value.

### Required Features

- Search for individual customers.
- View customer profile information.
- View active and previous products.
- View subscription history.
- View domain registration and renewal history.
- View customer activity over time.
- View payment and revenue history.
- View support interaction history.
- Display customer segment.
- Display customer health score.
- Display churn risk.
- Display upgrade probability.
- Display estimated customer lifetime value.

### Customer Profile Fields

- Customer ID
- Registration date
- Country or region
- Customer type
- Acquisition channel
- Active products
- Subscription status
- Account age
- Total revenue
- Last activity date
- Number of support interactions
- Customer segment
- Health score
- Churn probability
- Upgrade probability

### User Story

As a Customer Success Manager, I want to understand a customer's history, product usage, and risk level so that I can decide whether the customer needs support or presents an upgrade opportunity.

---

## 8.3 Product Analytics

The Product Analytics section should help users understand how customers interact with the company's products and features.

### Required Analyses

- Product adoption
- Feature adoption
- Active users
- Customer engagement
- User journeys
- Funnel analysis
- Cohort retention
- Product conversion
- Upgrade behaviour
- Cancellation behaviour
- Cross-product adoption

### Example Products

- Domain registration
- Shared hosting
- Managed WordPress hosting
- Virtual private server hosting
- Business email
- SSL certificates
- Website builder

### Example Product Events

- Account created
- Domain searched
- Domain registered
- Hosting plan purchased
- Website created
- SSL activated
- Email account created
- Control panel accessed
- Website published
- Hosting plan upgraded
- Subscription renewed
- Subscription cancelled
- Support ticket submitted

### Required Features

- Compare adoption across products.
- Compare adoption across customer segments.
- Measure the percentage of customers using each feature.
- Track product usage over time.
- Analyse common customer journeys.
- Identify drop-off points in conversion funnels.
- Compare retention across acquisition cohorts.
- Compare customers who remain active with those who churn.

### User Story

As a Product Manager, I want to understand which features customers adopt and where they abandon important journeys so that I can improve the product experience.

---

## 8.4 Funnel Analysis

The platform should support analysis of important customer funnels.

### Domain Registration Funnel

1. Domain search
2. Domain selected
3. Checkout started
4. Payment completed
5. Domain registered

### Hosting Activation Funnel

1. Hosting plan viewed
2. Plan selected
3. Payment completed
4. Control panel accessed
5. Website created
6. Website published

### Upgrade Funnel

1. Upgrade offer viewed
2. Upgrade page opened
3. Plan compared
4. Checkout started
5. Upgrade completed

### Required Outputs

- Number of customers at each stage
- Conversion rate between stages
- Overall conversion rate
- Drop-off rate
- Funnel comparison by segment, acquisition channel, product, and time period

### User Story

As a Product Manager, I want to identify where customers leave important product journeys so that I can prioritise improvements.

---

## 8.5 Cohort and Retention Analysis

The platform should group customers into cohorts and track their behaviour over time.

### Possible Cohorts

- Registration month
- First purchase month
- Acquisition channel
- First product purchased
- Country or region
- Customer segment

### Required Outputs

- Monthly retention
- Product retention
- Revenue retention
- Renewal retention
- Cohort comparison
- Retention heatmap

### User Story

As a Product Data Scientist, I want to compare retention across customer cohorts so that I can identify which groups remain active and valuable over time.

---

## 8.6 Predictive Intelligence

The platform should provide machine learning predictions that support product and customer decisions.

### 8.6.1 Churn Prediction

The model should estimate the probability that an active customer will cancel or become inactive within a defined future period.

#### Possible Input Features

- Account age
- Product usage frequency
- Time since last activity
- Number of active products
- Payment failures
- Support interactions
- Recent changes in activity
- Subscription type
- Renewal history
- Customer revenue
- Feature adoption

#### Required Outputs

- Churn probability
- Risk category
- Main contributing factors
- Model performance metrics

#### User Story

As a Customer Success Manager, I want to identify customers with a high risk of churn so that I can prioritise retention actions.

---

### 8.6.2 Domain Renewal Prediction

The model should estimate the probability that a customer will renew an expiring domain.

#### Possible Input Features

- Domain age
- Time until expiration
- Previous renewal history
- Hosting connection
- Website activity
- Customer account age
- Number of domains owned
- Customer engagement
- Payment history

#### Required Outputs

- Renewal probability
- Renewal risk category
- Important prediction factors

#### User Story

As a Product Manager, I want to identify domains at risk of non-renewal so that the company can improve renewal communication and customer support.

---

### 8.6.3 Upgrade Prediction

The model should estimate the probability that a customer will upgrade to a higher-value product or plan.

#### Possible Input Features

- Current hosting plan
- Storage or bandwidth usage
- Number of websites
- Account age
- Product activity
- Support interactions
- Previous upgrades
- Revenue
- Number of active services

#### Required Outputs

- Upgrade probability
- Recommended upgrade category
- Important prediction factors

#### User Story

As a Growth Manager, I want to identify customers who may benefit from an upgrade so that relevant offers can be presented to them.

---

### 8.6.4 Customer Segmentation

The platform should group customers based on behaviour, value, engagement, and product usage.

### Example Segments

- New customers
- Highly engaged customers
- High-value customers
- Low-engagement customers
- At-risk customers
- Growth-potential customers
- Multi-product customers
- Domain-only customers

### User Story

As a Product Manager, I want meaningful customer segments so that product and communication strategies can be tailored to different customer needs.

---

## 8.7 Customer Health Score

The platform should calculate a customer health score summarising customer engagement, value, and risk.

### Possible Components

- Product activity
- Feature adoption
- Payment behaviour
- Renewal history
- Support activity
- Account age
- Revenue contribution
- Churn probability

### Required Outputs

- Health score from 0 to 100
- Health category
- Explanation of score
- Change from previous period

### Example Categories

- Healthy
- Stable
- Needs attention
- High risk

### User Story

As a Customer Success Manager, I want a simple health score so that I can quickly identify which customers require attention.

---

## 8.8 Forecasting

The forecasting section should estimate future product and business performance.

### Required Forecasts

- Monthly revenue
- New customer registrations
- Domain registrations
- Domain renewals
- Active customers
- Hosting subscriptions
- Customer churn
- Support ticket volume

### Required Features

- Display historical values.
- Display future forecasts.
- Display uncertainty intervals.
- Compare forecasted and actual values when available.
- Support multiple forecast horizons.
- Explain major trends where possible.

### User Story

As an executive, I want forecasts of important business metrics so that I can plan resources and make informed strategic decisions.

---

## 8.9 AI Product Copilot

The AI Product Copilot should help users understand platform data through natural-language summaries and questions.

### Initial Features

- Generate weekly product summaries.
- Generate executive performance summaries.
- Explain major KPI changes.
- Summarise churn risks.
- Summarise customer segments.
- Highlight product adoption changes.
- Suggest questions for further analysis.
- Generate recommended product actions.
- Answer approved natural-language questions about available metrics.

### Example Questions

- Why did churn increase this month?
- Which customer segment has the highest renewal rate?
- Which features are associated with better retention?
- Which products experienced the strongest growth?
- What are the main risks this week?
- Which customers should the Customer Success team prioritise?

### Requirements

- AI-generated claims should be based on available data.
- The platform should distinguish observations from recommendations.
- Recommendations should be reviewable by a human.
- Generated summaries should include the reporting period.
- The system should avoid exposing confidential or personally identifiable information.
- The interface should clearly state that AI outputs may require verification.

### User Story

As a Product Manager, I want to ask questions about product performance in natural language so that I can obtain understandable insights without manually reviewing every dashboard.

---

## 8.10 Experiment Analysis

The platform should support the analysis of product experiments.

### Required Features

- Define control and treatment groups.
- Track experiment exposure.
- Select a primary success metric.
- Compare group performance.
- Calculate absolute and relative differences.
- Estimate statistical uncertainty.
- Record experiment conclusions.

### Example Experiments

- Renewal reminder design
- Hosting onboarding flow
- Upgrade recommendation placement
- Website builder activation prompt
- Domain checkout simplification

### User Story

As a Product Manager, I want to evaluate product experiments so that decisions are based on measured outcomes rather than assumptions.

---

## 8.11 Reporting

The platform should support regular reporting for stakeholders.

### Required Reports

- Weekly product performance report
- Monthly executive report
- Customer risk report
- Product adoption report
- Revenue and forecasting report
- Experiment report

### Output Formats

The first version may provide reports through:

- Interactive dashboards
- Downloadable CSV files
- Generated text summaries
- PDF export as a later enhancement

---

# 9. Dashboard Requirements

The dashboard should contain the following pages:

1. Executive Overview
2. Customer Intelligence
3. Product Analytics
4. Funnel Analysis
5. Cohort Retention
6. Predictive Intelligence
7. Forecasting
8. AI Product Copilot
9. Experiment Analysis

### General Dashboard Requirements

- Clear navigation
- Consistent metric definitions
- Date filtering
- Product filtering
- Customer segment filtering
- Responsive charts
- Clear titles and labels
- Explanations for complex metrics
- Loading and error states
- No exposure of sensitive information

---

# 10. Data Requirements

The synthetic dataset should contain realistic relationships between customers, products, subscriptions, usage, payments, support interactions, and outcomes.

## Core Data Entities

- Customers
- Products
- Plans
- Domains
- Subscriptions
- Product events
- Payments
- Support tickets
- Marketing campaigns
- Experiments
- Prediction outputs
- Forecast outputs

## Data Characteristics

The generated data should include:

- Different customer segments
- Different acquisition channels
- Seasonal trends
- Product usage differences
- Renewals and cancellations
- Successful and failed payments
- Customer upgrades
- Churn behaviour
- Missing values where realistic
- Outliers where realistic
- Relationships that can be learned by machine learning models

---

# 11. Non-Functional Requirements

## 11.1 Reproducibility

- The project should be runnable using documented setup instructions.
- Data generation should use a fixed random seed where appropriate.
- Model training steps should be reproducible.
- Dependencies should be recorded.

## 11.2 Maintainability

- Code should be organised into reusable modules.
- Functions should have clear names and documentation.
- Configuration values should not be unnecessarily hard-coded.
- Tests should cover important functions.

## 11.3 Explainability

- Important metrics should have documented definitions.
- Machine learning predictions should include understandable explanations.
- AI summaries should be traceable to platform data.

## 11.4 Privacy

- Only synthetic data will be used.
- No real customer information will be included.
- Generated data should not imitate identifiable individuals.

## 11.5 Deployment

The platform should eventually support:

- Local execution
- Docker-based execution
- Database integration
- Cloud deployment
- Environment-based configuration

## 11.6 Performance

The initial version should:

- Load dashboard pages within a reasonable time.
- Avoid retraining models during every user interaction.
- Store reusable model outputs.
- Handle the expected synthetic dataset without major delays.

---

# 12. Minimum Viable Product

The Minimum Viable Product will include:

- Synthetic customer and product data
- PostgreSQL database
- Data ingestion and transformation pipeline
- Executive KPI dashboard
- Product adoption analysis
- Customer segmentation
- Churn prediction model
- Revenue forecast
- Basic AI-generated product summary
- Docker-based local deployment
- Project documentation

The MVP will prioritise a complete, working workflow over a large number of partially implemented features.

---

# 13. Later Enhancements

Possible later additions include:

- Domain renewal prediction
- Upgrade prediction
- Customer lifetime value prediction
- Real-time event processing
- More advanced experiment analysis
- Recommendation systems
- Role-based access control
- Automated scheduled reports
- Notification system
- Advanced natural-language data querying
- Model monitoring
- Data quality monitoring
- AWS deployment
- Continuous integration and deployment

---

# 14. Success Metrics

The product will be considered successful when:

- Users can view core business and product KPIs.
- Users can analyse product adoption and customer behaviour.
- The churn model produces documented and meaningful evaluation results.
- Forecasts can be generated and evaluated.
- The AI Copilot generates summaries grounded in platform metrics.
- The full project can be run using documented instructions.
- The distinction between synthetic data and real company data is clear.
- The project demonstrates product thinking, analytics, machine learning, and engineering skills.

---

# 15. Risks and Limitations

## Synthetic Data Risk

Synthetic data may not capture all complexities of real customer behaviour.

### Mitigation

The generation process will include realistic business rules, correlations, seasonality, missingness, and noise.

## Project Scope Risk

The project contains many possible features and may become too large.

### Mitigation

Development will focus first on the MVP. Additional features will only be added after the core workflow is complete.

## AI Reliability Risk

AI-generated summaries may contain unsupported interpretations.

### Mitigation

Summaries will be grounded in calculated metrics, clearly labelled, and designed for human review.

## Model Performance Risk

Prediction models may appear unrealistically strong if synthetic outcomes are generated too directly from model features.

### Mitigation

The data-generation process will include randomness, overlapping customer behaviour, and realistic uncertainty.

---

# 16. Development Priorities

## Priority 1: Foundation

- Define data entities.
- Design the database.
- Generate synthetic data.
- Build the ingestion pipeline.
- Calculate core KPIs.

## Priority 2: Product Analytics

- Build executive dashboard.
- Analyse feature adoption.
- Implement funnel analysis.
- Implement cohort retention.

## Priority 3: Machine Learning

- Build customer segmentation.
- Build churn prediction.
- Add prediction explanations.

## Priority 4: Forecasting

- Forecast revenue and customer activity.
- Evaluate forecast performance.
- Display forecasts in the dashboard.

## Priority 5: AI and Deployment

- Build AI-generated summaries.
- Add the AI Product Copilot.
- Containerise the application.
- Deploy the platform to the cloud.

---

# 17. Open Questions

The following decisions will be refined during development:

- What period should define customer churn?
- What event should define an active customer?
- Which customer actions should contribute to the health score?
- Which product features should be represented in the synthetic data?
- Which forecasting horizon is most useful?
- Which metrics should appear on the main executive dashboard?
- Which questions should the first version of the AI Copilot support?
- Which cloud services should be used for deployment?