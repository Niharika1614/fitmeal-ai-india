# 🇮🇳 FitMeal AI – Indian Edition 🍛  
AI-powered personalized Indian meal planner — built with **Lovable.dev + n8n.io + GPT AI**

---

## 🚀 Overview  
**FitMeal AI (Indian Edition)** generates a **30-day personalized Indian meal plan** based on user health and lifestyle inputs.

Most AI meal planners focus on Western diets — this project is designed **for Indian users**, including affordable ingredients, regional meals, and PCOS-friendly nutrition.

---

## 🎯 Features
- 🧠 AI-generated 30-day Indian meal plans  
- 🍛 Daily meals: breakfast, lunch, dinner, snacks  
- 🛒 Weekly grocery list  
- 💸 Budget-based customization  
- 👩‍⚕️ PCOS-friendly and hormone-balanced  
- 📱 Mobile-first Lovable landing page  
- 🔗 n8n webhook for AI meal plan generation  

---

## 🧩 Tech Stack
| Layer | Tool | Purpose |
|-------|------|----------|
| Frontend | [Lovable.dev](https://lovable.dev/) | Mobile-first landing page |
| Workflow | [n8n.io](https://n8n.io/) | Automation + webhook handler |
| AI | GPT model | Personalized Indian meal generation |
| UI | React + Tailwind | Clean, fast, responsive design |

---

## 🧾 Example Input
```json
{
  "weight": 68,
  "height": 162,
  "pcos_symptoms": ["irregular periods", "acne"],
  "menstrual_cycle": { "length_days": 31, "flow_intensity": "moderate" },
  "budget": 7000,
  "living_situation": "flat"
}
