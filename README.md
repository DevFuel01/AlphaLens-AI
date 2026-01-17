# AlphaLens-AI
AI-powered trading agent for U.S. markets using Gemini AI and the C Field sandbox.

AlphaLens AI

AlphaLens AI is an AI-powered trading agent designed for the AI Trading Sandbox Challenge – U.S. Market.
It leverages Gemini AI for reasoning and factor discovery, combined with deterministic risk controls and execution logic inside a simulated real-market environment.

🚀 Challenge Track

Agent Track – The Arena for Prompt Engineers

🧠 Core Idea

Turn structured AI reasoning into a controlled, explainable trading agent — not a black-box system.

🏗️ System Architecture

Flow:

Market Data → Gemini AI (Reasoning) → Trade Thesis
→ Risk & Rules Engine → Alpaca Sandbox Execution


Gemini AI generates insights and trade rationale, while final execution is governed by strict system-level rules.

🔍 Trading Strategy Overview
Logical Framework

Analyze earnings releases, news and sentiment

Detect expectation gaps and potential mispricing

Generate structured trade thesis

Validate via risk and rule engine

Execute in semi-automated or automated mode

AI Application Method

Gemini AI used for:

Sentiment interpretation

Narrative-to-signal conversion

Trade confidence scoring

Structured prompting ensures:

Consistency

Explainability

Auditability

Risk Management

Volatility-adjusted position sizing

Maximum exposure limits

Drawdown and cooldown protection

Event-based trade filters

Trade veto logic

AI cannot bypass risk controls.

Research Basis

Historical earnings surprise behavior

Empirical sentiment-to-price reaction studies

Regime-aware market conditions

Explainable AI best practices

🛠️ Tech Stack

Frontend: HTML, CSS and JavaScript

Backend: PHP

Database: MySQL

AI Engine: Gemini API

Sandbox Execution: Alpaca

📁 Repository Contents

/prompts – Gemini agent prompts

/backend – Agent logic & risk engine

/frontend – UI for monitoring & control

/docs – Strategy slides & system diagrams

🏁 Status

Sandbox trading & agent tuning in progress.

📜 License

MIT License
