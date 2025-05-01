# MatchMate: AI-Powered Agency Matching Assistant

This project is a **working prototype** developed as part of a job application assessment for the AI Developer position at DesignRush. It demonstrates the concept and flow of an AI-powered assistant designed to help businesses find best-fit agencies through a conversational interface.

## Overview
MatchMate simulates a smart virtual assistant that:
- Collects essential input from users (industry, budget, services, location)
- Matches user preferences with agency data
- Provides a curated list of agencies based on context and preferences

The prototype mimics the user experience of interacting with an intelligent assistant through a chat interface. It is visually polished, responsive, and designed to communicate both concept and execution clearly.

## Features
- Conversational UI with simulated interaction
- Step-by-step data collection
- Matching logic with sample agency data
- Placeholder for API-backed recommendations
- Branded UI with soft animations

## Tech Stack
-	HTML/CSS/JavaScript
-	Simulated embedding scoring logic (to reflect AI matching)
-	Semantic matching simulation using keyword-based scoring
-	Modular state orchestration (inspired by LangChain flow)


## API Integration (Demo Purposes Only)
The code includes a `POST` request to a mock API endpoint (`https://api.designrush.com/matchmate`). This is a placeholder to simulate how real-time data retrieval would be implemented in a production scenario.

The structure of `userInputs` includes:
```json
{
  "industry": "eCommerce",
  "budget": "$10k–$25k",
  "services": "SEO, web design",
  "location": "Europe"
}
```

Expected response format:
```json
{
  "matches": [
    { "name": "CreativeHaus", "specialty": "Branding", "price_range": "$10k–$25k" },
    { "name": "RankBoosters", "specialty": "SEO", "price_range": "$5k–$15k" }
  ]
}
```

## Limitations
- The backend API is not functional — it’s a placeholder.
- Matching results are hardcoded to simulate response behavior.
- No actual database or ML model is connected in this version.

## How to Use
1. Open the `index.html` file in a modern browser.
2. Enter inputs as prompted in the chat interface.
3. View simulated agency matches based on your answers.

## Credits
Developed by **Kerem Caliskan** as a task submission for the DesignRush recruitment process.

---
For any questions or walkthrough requests, feel free to reach out!
