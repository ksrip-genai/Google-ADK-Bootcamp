# Google-ADK-Bootcamp - Kiran Sripathi
# AI Agent Development Skills Validation Workshop

This repository contains the completed challenge labs from an AI Agent Development 
skills validation workshop using Google ADK and Vertex AI Agent Engine.

Each notebook represents a hands-on challenge lab that builds progressively on 
the previous, culminating in a fully deployed, production-ready AI agent system.

---

## Labs

### Challenge Lab 1: Real-Time Weather Alerts Agent
Build a foundational agent that retrieves live weather data and active emergency 
alerts using the National Weather Service API and Google Maps Geocoding.

### Challenge Lab 2: Using Callbacks
Extend the agent with `before_model` and `after_model` callback functions to log 
all user-agent interactions and validate inputs using Google Cloud Model Armor.

### Challenge Lab 3: Creating a Multi-Agent System
Design and wire together a multi-agent system with specialized sub-agents for 
weather analysis, news search.

### Challenge Lab 4: Creating an Agent Workflow
Implement a sequential agent workflow pipeline that coordinates all sub-agents 
in order, passing outputs between agents via session state.

### Challenge Lab 5: Deploying an Agent to Agent Engine
Package and deploy the completed agent system to Vertex AI Agent Engine, 
and test it via the Agent Engine Playground and remote API calls.

### Challenge Lab 6: Final Case Study
Build and deploy the Federal Emergency Management Assistant (FEMA-AI) — 
a production-ready multi-agent system combining all skills from previous labs 
into a complete emergency response tool with real-time weather alerts, 
disaster news, evacuation routing, input validation, and full interaction logging.

---

## Technologies Used

- **Google ADK** — Agent Development Kit for building multi-agent systems
- **Vertex AI Agent Engine** — Managed deployment and hosting for AI agents
- **Gemini 2.0 Flash** — Underlying LLM powering all agents
- **Google Cloud Model Armor** — Input safety validation and content filtering
- **National Weather Service API** — Real-time weather forecasts and alerts
- **Google Maps API** — Geocoding and evacuation route planning
- **Google Search (ADK built-in)** — Live disaster and emergency news retrieval

