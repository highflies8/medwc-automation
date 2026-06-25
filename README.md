# medwc-automation

# MedWC Automation

> **7 days for a warranty decision isn't service. It's liability.**

MedWC Automation is an AI-powered Warranty & Claims Automation solution built on ServiceNow to accelerate warranty investigations and assist support teams with faster, explainable warranty decisions.

---

# Overview

Medical device manufacturers process thousands of warranty claims every year. Investigating each claim typically involves manually gathering customer information, locating the registered device, verifying warranty entitlement, reviewing coverage policies, and determining the appropriate resolution.

MedWC Automation demonstrates how ServiceNow AI Agents can automate these repetitive activities while keeping humans in control of the final decision.

---

# Business Problem

Traditional warranty processing is slow because it depends on multiple manual handoffs.

A support engineer typically needs to:

- Understand the customer issue
- Identify the customer
- Locate the registered device
- Verify warranty entitlement
- Review warranty coverage
- Recommend an action

This results in:

- Long turnaround times
- High operational costs
- Inconsistent decisions
- Poor customer experience

---

# Solution

MedWC Automation combines ServiceNow AI Agents, Build Agent and Integration Hub to automate warranty investigation.

The AI Agent:

- Reads the warranty claim
- Extracts product and serial information
- Retrieves warranty entitlement
- Evaluates coverage
- Generates an explainable recommendation
- Writes the recommendation back to the claim

A human reviewer remains responsible for the final approval.

---

# Architecture

```
Customer Claim
        │
        ▼
Warranty Claim
        │
        ▼
AI Agent
        │
        ├── Extract Claim Information
        ├── Retrieve Warranty Details
        ├── Evaluate Coverage
        ├── Generate Recommendation
        │
        ▼
Integration Hub
        │
        ▼
Warranty API
        │
        ▼
Recommendation
        │
        ▼
Human Review & Approval
```

---

# Features

- AI-assisted warranty investigation
- Automated entitlement verification
- Explainable warranty recommendations
- Human-in-the-loop approval
- Workflow automation using Flow Designer
- Executive visibility through dashboards
- Complete audit trail

---

# Technologies

- ServiceNow
- ServiceNow Build Agent
- AI Agents
- Flow Designer
- Integration Hub
- REST APIs
- Workspace Experience
- JavaScript

---

# Business Value

MedWC Automation helps organizations:

- Reduce warranty processing time
- Improve decision consistency
- Reduce manual effort
- Increase operational efficiency
- Deliver faster customer service
- Scale warranty operations without proportional staffing increases

---

# Screenshots

## AI Agent

<img width="1728" height="929" alt="image" src="https://github.com/user-attachments/assets/dcda1ed3-f946-42c1-9f02-fb5d38c8f188" />



## Dashboard

<img width="1706" height="646" alt="image" src="https://github.com/user-attachments/assets/99c13a95-aada-4c61-9102-3ab5fed97a89" />


## Flow Action

<img width="1444" height="857" alt="image" src="https://github.com/user-attachments/assets/8508a84b-dcd0-485c-80d5-6eb5c09b0319" />


# Demo



---

# Future Enhancements

- Warranty fraud detection
- Predictive warranty risk scoring
- Spare parts recommendations
- Automated technician dispatch
- Customer self-service AI assistant

---

# Author

**Sonam Tiwari**

Software Engineer | ServiceNow

AI-powered enterprise workflow automation using ServiceNow AI Agents and Build Agent.
