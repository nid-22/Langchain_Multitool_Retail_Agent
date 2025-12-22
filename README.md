# Agentic Product Intelligence System for Clothing Catalogs

## Overview
This project demonstrates how to build a multi-tool, agent-driven application using LangChain’s latest Agent API. The system processes a clothing product catalog stored in CSV format and enables intelligent querying through natural language.

The agent dynamically decides which tools to invoke based on user intent and composes final responses using retrieved data, structured analysis, and reasoning provided by an LLM.

---

## Capabilities
- Semantic product recommendations using vector search
- Product comparison with tabular output
- Gender-aware outfit generation (topwear, bottomwear, shoes)
- Natural-language filtering using pandas
- Robust error handling via agent middleware
- Full traceability of tool calls and agent decisions

---

## Architecture
User Query
↓
LangChain Agent (Tool-Calling LLM)
↓
Tool Selection
↓
Vector Search / Pandas Filtering / Comparison Logic
↓
Final User-Facing Response

