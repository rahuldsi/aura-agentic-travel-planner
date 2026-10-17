# aura-agentic-travel-planner
Vibe based travel assistant
Aura - Agentic Travel Planner
`aura-agentic-travel-planner` is an AI-powered travel planning platform designed to solve planning fatigue and budget anxiety for Gen-Z travelers, digital nomads, and busy professionals. Unlike traditional search-driven OTAs, Aura uses multi-agent orchestration to balance aesthetic preferences (the "vibe") with hard financial constraints (the "wallet").
---
✨ Core Features
Vibe-Based Discovery: Search using moods, aesthetics, and identity-driven preferences instead of rigid keyword filters.
Wallet-First Budget Agent: Enforces a hard spending limit and automatically balances trip components (e.g., trading transport luxury for a better stay).
Smart Itinerary Builder: Generates structured, day-by-day itineraries complete with local activities, food, and total cost estimations.
Total Cost Transparency: Accounts for hidden expenses like local transport and authentic meals in the initial quote.
Itinerary Export & Sharing: Export generated plans into mobile-friendly formats, calendar files, or downloadable PDFs.
---
🛠️ Technology Stack
AI Layer
Orchestration Frameworks: LangChain, LangGraph
LLM Providers: OpenAI GPT-4o, Google Gemini
Vector Database: Pinecone, Qdrant
Backend Layer
Core Services: Golang (Gin & Fiber frameworks)
Communication & Caching: gRPC, Redis
External Integrations
Travel Data: Amadeus, Skyscanner
Environment & Maps: OpenWeatherMap, Google Maps API
---
🚀 Getting Started
Prerequisites
Python 3.13+
Go (latest stable version)
Redis
Installation & Setup
Clone the repository:
```bash
   git clone https://github.com/your-username/aura-agentic-travel-planner.git
   cd aura-agentic-travel-planner
   ```
Configure environment variables:
Set up your API keys for OpenAI/Gemini, Pinecone, and travel data providers in your environment or a `.env` file.
Run backend microservices:
```bash
   go run main.go
   ```
---
📈 Architecture Overview
The platform relies on an Agentic Orchestration Layer where specialized agents negotiate backend trade-offs:
Persona Agent (The Curator): Maps user identity, aesthetic tastes, and destination vibes.
Budget Agent (The Protector): Manages financial constraints and optimizes cost trade-offs.
Live Concierge (The Companion - Future Release): Provides real-time event monitoring and adaptive re-routing.
---
📄 License
This project is developed as part of a capstone project submission.
