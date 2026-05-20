# Agentic AI Workflow for High-Net-Worth KYC Onboarding

This is a prototype that shows how an agentic AI workflow can reduce high-net-worth client onboarding time.

Banks typically take 40+ days to onboard a high-net-worth client. The problem is not compliance. The problem is coordination. Cases bounce between teams. Documents go missing. Reviews get duplicated. Nobody knows what's already verified and what still needs attention.

This prototype demonstrates how an agentic workflow fixes the coordination problem.

## What this prototype does

The prototype shows how a case moves through a KYC workflow:

1. **A simple UI captures client information** and creates a structured case package
2. **The Workflow Controller coordinates the full process** - it doesn't make decisions, it keeps things moving
3. **The Orchestrator decides which agents to run** based on what's in the case
4. **Specialist agents run in parallel** - identity verification, screening, wealth review, business structure review
5. **The Signal Aggregator combines the findings** into one unified view
6. **The Risk Engine applies rules** to assign risk tier and determine the review path
7. **An AI agent converts the output into plain English** so the compliance officer knows where to focus
8. **The compliance officer makes the final decision**

The key design principle is simple:

**LLMs summarize. Rules decide. Humans review.**

## Read the companion blog post

For the full architecture walkthrough, read:

[How to Reduce High-Net-Worth Client Onboarding Time With an Agentic KYC Workflow](https://pmexaminer.com/reduce-high-net-worth-client-onboarding-time-with-an-agentic-kyc-workflow/)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/manujeevanprakash/agentic-kyc-workflow-prototype/blob/main/KYC_Agentic_AI_Workflow_Public.ipynb)
