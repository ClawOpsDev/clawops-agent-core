# clawops-agent-core
Multi-modal AI agent for autonomous E2E browser testing.



# ClawOps Agent Core 🦀

> **Status:** MVP Development Phase (Internal Build)
> **Goal:** Autonomous E2E browser testing using Multi-modal LLMs.

## 🚀 Overview
ClawOps is an agentic framework designed to replace rigid Selenium/Playwright scripts with autonomous agents. By leveraging **Claude 4.6 (Anthropic)** and **Gemini 1.5 (Google)** via **Amazon Bedrock**, ClawOps can "see" a web UI, understand intent, and execute complex testing workflows without manual selectors.

## 🛠️ Tech Stack
- **Engine:** Playwright (Headless Node.js)
- **Intelligence:** Anthropic Claude 3.5/4.6, Google Gemini 1.5 Pro
- **Orchestration:** LangGraph / Custom Agentic Loops
- **Cloud:** AWS (Bedrock, Lambda, S3)

## 🎯 Current Objectives
- [ ] Implement multi-modal vision processing for UI element detection.
- [ ] Develop self-healing selector logic using LLM-based DOM analysis.
- [ ] Integrate with AWS Bedrock for scalable inference.

## 📦 Getting Started
*Note: This repository contains the core orchestration logic. Enterprise modules are private.*

```bash
# Clone the core
git clone [https://github.com/ClawOpsDev/clawops-agent-core.git](https://github.com/ClawOpsDev/clawops-agent-core.git)
cd clawops-agent-core

# Install dependencies
npm install
