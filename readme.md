# 🍽️ Smart Foodie Tour Planner using Julep

## Project Idea

This Julep workflow takes a list of cities and creates a one-day foodie tour for each, based on today's weather. It recommends indoor or outdoor dining, picks 3 iconic local dishes, and finds the best-rated restaurants for breakfast, lunch, and dinner.

---

## Workflow Steps

1. Input: List of cities (e.g., Mumbai, Tokyo, Paris)
2. Fetch current weather for each city
3. Decide on indoor or outdoor dining based on weather
4. Get 3 iconic local dishes (using Julep Prompt Node)
5. Search for restaurants serving those dishes
6. Generate breakfast, lunch, and dinner itinerary
7. Output as a structured Markdown summary

---

## Tech Used

- [Julep](https://dashboard.julep.ai/home/)
- Weather API (built-in node)
- OpenAI prompt nodes (no API key required)
- Markdown for output formatting

---

## Example Output (for Paris)

**Weather:** 🌧️ Rainy → Indoor dining suggested

**Dishes:** Croissant, Coq au Vin, Crème Brûlée

- **Breakfast:** Croissant @ Angelina Paris (Cozy atmosphere, warm coffee)
- **Lunch:** Coq au Vin @ Bistrot Paul Bert (Elegant indoor dining)
- **Dinner:** Crème Brûlée @ Le Cinq (Luxury indoor ambiance)

---

## 🧠 Workflow Architecture
Here's a high-level flowchart of how the foodie tour planner works:

![flowchart](flowchart.drawio.png)

---

## 👩‍💻 Created by

**Mauli Patel** | [GitHub](https://github.com/itsmemauliii)
