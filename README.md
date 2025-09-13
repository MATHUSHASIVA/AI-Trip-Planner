# 🌍 AI Travel Planner Agent — Your Personal Trip Assistant

> **Plan trips anywhere in the world with real-time data — weather, attractions, costs, currency — all in one click.**

An intelligent, tool-using AI agent that plans detailed travel itineraries with cost breakdowns, weather forecasts, hotel/restaurant recommendations, and more — powered by LangGraph, Groq/OpenAI, and real-time APIs.

Perfect for travelers, travel agencies, or as a demo of advanced agentic AI systems.

---

## 🌟 Features

✅ **Real-Time Data Integration**
- Live weather forecasts (OpenWeatherMap)
- Attractions, restaurants, transport (Google Places + Tavily fallback)
- Currency conversion (ExchangeRate-API)
- Cost calculation (hotels, food, activities)

✅ **Two Itineraries in One**
- **Generic Tourist Plan** — popular spots
- **Offbeat Plan** — hidden gems

✅ **Comprehensive Output**
- Day-by-day itinerary
- Hotel & restaurant recommendations with prices
- Transportation options
- Total & daily budget breakdown
- Weather for each destination

✅ **Tech-Powered**
- Built with **LangGraph** for agentic workflows
- Uses **Groq** (Llama 70B)
- FastAPI backend + Streamlit frontend
- Modular, production-ready architecture


## 🚀 Tech Stack

| Category       | Technologies Used |
|----------------|-------------------|
| **AI/LLM**     | Groq (Llama 3 70B), OpenAI (GPT-4o-mini) |
| **Framework**  | LangChain, LangGraph, LangSmith (optional) |
| **Backend**    | FastAPI |
| **Frontend**   | Streamlit |
| **APIs**       | OpenWeatherMap, Google Places, Tavily, ExchangeRate-API |
| **Tools**      | Weather, Places, Calculator, Currency Converter |
| **Utils**      | Config Loader, Model Loader, Document Saver |
| **Deployment** | Local (Docker/CI-CD ready) |
