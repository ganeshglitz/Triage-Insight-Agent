# Triage-Insight-Agent
Triage Insight Agent

The Problem

Every organization receives dozens of technology requests monthly. Evaluating each one — comparing options, checking standards, estimating costs, and producing a stakeholder recommendation — takes 3 to 6 weeks of manual effort involving multiple teams. Decisions are delayed, inconsistently documented, rarely grounded in organizational knowledge, and no one can answer "what if our requirements change?" — costing enterprises millions in delayed projects and suboptimal technology investments.

The Solution

Triage Insight Agent is a Microsoft 365 Copilot enterprise agent that transforms technology requests into structured, insight-backed decision packages in minutes — not weeks.
A user describes a business need in plain language through Microsoft Teams. The agent triages the request, asks targeted clarifying questions, and autonomously searches organizational knowledge using Foundry IQ — retrieving cited evidence from technology standards, reference architectures, past project outcomes, and rate cards stored in SharePoint Online.
From this grounded knowledge, the agent generates three competing solution options — each with architecture components, bill of materials, cost estimates, and risk assessments — scored with a confidence percentage backed by cited evidence. The recommended option and full decision package are delivered as a stakeholder-ready PowerPoint deck via Microsoft Graph API, saved to SharePoint, and surfaced through a Teams Adaptive Card with approval action buttons.
When constraints change, users ask "What if?" — and the agent dynamically re-evaluates all options, shifting the recommendation if warranted, and regenerates the decision package instantly.

Impact: 

Technology triage decisions in 3 minutes. Evidence-backed. Confidence-scored. Boardroom-ready.

Technologies Used
 
Technology	Role
Microsoft Copilot Studio	Agent orchestration & conversation design
Foundry IQ	Grounded knowledge retrieval with citations
SharePoint Online	Knowledge base storage (RAG source)
Azure AI Search	Vector + keyword retrieval
GPT-4 (Azure OpenAI)	Reasoning & option generation
Power Automate	Workflow orchestration & delivery
Microsoft Graph API	PowerPoint creation & file management
Teams Adaptive Cards	Decision package delivery & actions
Microsoft Entra ID	Authentication & permission enforcement

Microsoft IQ Layer
Foundry IQ (Primary)
- Agentic knowledge retrieval for AI agents
- Connects enterprise sources (SharePoint, Azure AI Search)
- Enforces permissions via Microsoft Entra ID
- Delivers cited, grounded answers to reduce hallucination
- Powers confidence scoring with evidence citations
 
