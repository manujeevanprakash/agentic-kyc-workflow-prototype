Agentic AI Workflow for High-Net-Worth KYC Onboarding
This is a prototype that shows how an agentic AI workflow can reduce high-net-worth client onboarding time.
Banks typically take 40+ days to onboard a high-net-worth client. The problem is not compliance. The problem is coordination. Cases bounce between teams. Documents go missing. Reviews get duplicated. Nobody knows what's already verified and what still needs attention.
This prototype demonstrates how an agentic workflow fixes the coordination problem.
What this prototype does
The prototype shows how a case moves through a KYC workflow:

A simple UI captures client information and creates a structured case package
The Workflow Controller coordinates the full process - it doesn't make decisions, it keeps things moving
The Orchestrator decides which agents to run based on what's in the case
Specialist agents run in parallel - identity verification, screening, wealth review, business structure review
The Signal Aggregator combines the findings into one unified view
The Risk Engine applies rules to assign risk tier and determine the review path
An AI agent converts the output into plain English so the compliance officer knows where to focus
The compliance officer makes the final decision
