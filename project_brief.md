# My agent: Smart Travel Concierge

One-liner: A conversational travel agent that helps users plan personalized vacations with a catalog of destinations, activities, and real-time weather/flight lookups.

Tool coverage:
- Memory: Remembers user travel preferences, budget constraints, dietary restrictions, and past booked trips across sessions.
- Tools: Looks up weather forecasts, flight options, and venue recommendations via function tools.
- Catalog/UI: Destination & itinerary recommendations rendered as interactive A2UI cards.
- Image gen: Generates visual postcard previews for suggested destinations.
- Sandbox: Calculates trip budget breakdowns and currency conversions.

Core rails (everyone): memory, tools, eval, deploy, frontend
My stretch menu (pick later): A2UI cards, image generation, code sandbox
First eval question: "Recommend a 3-day weekend trip to a sunny destination under $1,000 for someone who loves seafood."
