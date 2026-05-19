# SaaS Analytics Dashboard

Power BI project built using a synthetic SaaS dataset with multiple related tables.  
The dashboard focuses on subscription analytics, churn analysis, customer behavior, support operations, and product usage.

---

# Project Overview

This project simulates analytics commonly used in SaaS companies.

Main areas covered:
- MRR and ARR analysis
- Subscription growth
- Customer churn
- Product usage
- Support performance
- Customer retention

---

# Data Model

Tables used in the project:
- `accounts`
- `subscriptions`
- `feature_usage`
- `support_tickets`
- `churn_events`
- `calendar`

---

# Dashboard Pages

## Overview

General business performance dashboard.

Includes:
- MRR / ARR
- Active Accounts
- Expansion MRR
- Churn Rate
- Revenue Funnel

Key findings:
- Revenue growth is mainly driven by expansion MRR
- Churn remains relatively high
- Trial-to-paid conversion is strong

---

## Churn Analysis

Analysis of customer and revenue churn.

Includes:
- Logo Churn Rate
- Revenue Churn Rate
- Churned MRR
- Churn by plan, industry, and country
- Refund analysis
- Upgrade vs downgrade behavior

Key findings:
- Basic plan customers have the highest churn
- Pricing and feature limitations are major churn reasons
- Downgraded customers churn more frequently

---

## Product Usage

Product engagement and feature adoption analysis.

Includes:
- Feature usage trends
- Most used features
- Feature adoption
- Usage by plan
- Error rate analysis

Key findings:
- Core features show stable engagement
- Some highly used features also have higher error rates
- Enterprise and Pro users are more engaged

---

## Support

Support operations and customer satisfaction analysis.

Includes:
- Ticket volume trends
- Resolution time analysis
- Satisfaction scores
- Escalation rate
- Tickets by priority

Key findings:
- High-priority tickets take longer to resolve
- Faster response times are linked to higher satisfaction
- Escalated tickets have lower satisfaction scores

---

## Subscription Analytics

Subscription and recurring revenue analysis.

Includes:
- Active subscriptions
- Auto-renew analysis
- Expansion vs contraction MRR
- Billing frequency distribution
- Net revenue change

Key findings:
- Expansion MRR is higher than contraction MRR
- Most subscriptions use monthly billing
- Auto-renew subscriptions generate most recurring revenue

---

## Customer Analytics

Customer segmentation and acquisition analysis.

Includes:
- Trial conversion rate
- ARPA
- Seats per account
- Country distribution
- Referral source analysis
- Industry segmentation

Key findings:
- Organic channels bring the most active customers
- US customers represent the largest segment
- DevTools and FinTech industries dominate the customer base

---

# Tools & Technologies

- Power BI
- DAX
- Power Query
- Data Modeling
- Data Visualization

---

# Main Metrics

- MRR / ARR
- Expansion MRR
- Contraction MRR
- Churned MRR
- Logo Churn Rate
- Revenue Churn Rate
- Trial Conversion Rate
- ARPA
- Auto Renew Rate
- Escalation Rate

---

# Project Goal

The goal of this project was to build a realistic SaaS analytics dashboard and practice working with business KPIs, DAX calculations, and multi-table data models in Power BI.
