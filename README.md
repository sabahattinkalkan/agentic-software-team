![License](https://img.shields.io/badge/license-AGPL--3.0-blue)
![AI](https://img.shields.io/badge/AI-Agentic-blueviolet)
![Status](https://img.shields.io/badge/status-V1%20Stable-green)

# Agentic Software Team

> An agent-based AI software team that works like a real software company.

---

## 🌍 What is this?

**Agentic Software Team** is a framework for building software products using
multiple specialized AI agents that collaborate like a real-world software team.

Instead of relying on a single AI prompt, this project defines **clear roles,
responsibilities, boundaries, and workflows** for each agent involved in:

- Product planning
- UX & UI design
- Backend & frontend development
- Quality assurance
- Marketing & growth
- Final review and audit

This repository provides the **organizational brain** of an AI-driven software company.

---

## 🎯 Why this exists

Most AI-based development fails because:

- Roles are unclear
- Scope grows uncontrollably
- Decisions contradict each other
- Quality and business goals are disconnected

This project solves that by:

- Separating concerns into explicit AI roles
- Enforcing responsibility boundaries
- Creating a predictable execution order
- Making outputs reviewable and auditable

---

## 👤 Who is this for?

- Solo developers building serious products with AI
- Technical founders validating SaaS ideas
- Teams experimenting with agent-based workflows
- Anyone tired of chaotic, prompt-only AI development

---

## 🧠 How it works (High Level)

1. A product idea is introduced
2. The **Team Lead Agent** breaks it down
3. The **CTO Agent** defines technical direction
4. **UX & UI Agents** shape the experience
5. **Backend & Frontend Agents** define implementation
6. **QA Agent** hunts for bugs and risks
7. **Marketing & Ads Agents** plan go-to-market
8. **Review & Audit Agent** validates readiness

Each agent has:

- A strict role definition
- Clear inputs and outputs
- Explicit “must not do” rules
- 
Idea
 ↓
Team Lead
 ↓
CTO
 ↓
UX → UI
 ↓
Backend → Frontend
 ↓
QA
 ↓
Marketing → Ads
 ↓
Review & Audit

---

## 👥 Agent Roles

| Area | Agents |
|----|----|
| Leadership | Team Lead, CTO |
| Product & Design | UX Designer, UI Designer |
| Engineering | Backend Developer, Frontend Developer |
| Quality | QA / Bug Hunter |
| Growth | Marketing Strategist, Ads & Growth |
| Control | Review & Audit |

All agent specifications are located in the `/agents` directory.

---

## 🧩 How to use this repository

You can use this framework with:

- ChatGPT
- Cursor
- Antigravity
- Any LLM that follows system instructions

### Basic usage flow

1. Read the agent role definitions
2. Start with **Team Lead Agent**
3. Follow the execution order
4. Pass outputs between agents
5. Finish with **Review & Audit Agent**

This repository does not lock you into a tool.
It defines **how thinking and execution should be structured**.

---

## 📂 Repository Structure

```text
agents/        # AI role definitions
rules/         # Global rules and governance (coming next)
workflows/     # Execution flows between agents (coming next)
prompts/       # Reusable prompt templates (coming next)
examples/      # Example projects and outputs
docs/          # Extended documentation
