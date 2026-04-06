# Gemma Instant Pot Agent: "The One-Pot Pro"

An optimized system prompt for Gemma (or other LLMs) designed to act as a high-efficiency culinary assistant for experienced electric pressure cooker users.

## 📌 Project Overview
This agent is tailored for the **Instant Pot (Electric Pressure Cooker)**. It skips basic safety tutorials and focuses on technical precision, one-pot workflows, and ingredient-led recipe generation.

### Key Features:
* **The "Flavor Base" Logic:** Automatically incorporates a base of onions, celery, garlic, and olive oil into every recipe without being prompted.
* **Concise Output:** Delivers technical data (Time, Pressure, Release) in a "cheat sheet" format.
* **Interactive Workflow:** The agent is programmed to wait for your ingredient input before generating instructions, ensuring you only get recipes for what you actually have on hand.

---

## 🚀 Setup Instructions

1.  **Open your Gemma Interface:** Navigate to your LLM provider (e.g., Google AI Studio, Vertex AI, or a local instance).
2.  **Access System Instructions:** Locate the "System Instructions" or "Custom Instructions" field.
3.  **Paste the Logic:** Copy and paste the contents of `gemma_ip_agent.md` into that field.
4.  **Save:** Update or Save the model settings.

---

## 🛠 How to Use

### Step 1: The Initialization
When you start a new chat, the agent will acknowledge your "Flavor Base" (Onion, Celery, Garlic, Oil) and ask:
> *"What proteins, starches, or additional vegetables are we working with today?"*

### Step 2: Provide Your Ingredients
Simply list what you want to cook. 
* **Example:** *"I have 2lbs pork shoulder and some frozen peas."*

### Step 3: Execute the Technical Recipe
The agent will output a structured response including:
* **Technical Specs:** Pressure Level, Cook Time, and Release Method (QR/NPR).
* **Ingredient Table:** Measured amounts including the assumed base ingredients.
* **The One-Pot Flow:** Step-by-step instructions from Sauté to Pressure.

---

## 📋 Design Constraints
To maintain the efficiency of this agent, the following rules are hard-coded into the instructions:
* **No Fluff:** No conversational filler or introductory text.
* **One-Pot Only:** No instructions requiring external pots or pans.
* **Burn Protection:** Mandatory "Deglaze" steps for every recipe.
* **Experienced Mode:** Assumes the user knows how to seal the lid and operate the steam valve.

---

## 📝 Example Interaction
**User:** "Beef chuck and pearl barley."

**Agent:**
### Beef & Barley Pot
**Technical Settings:**
* **Mode:** Pressure Cook
* **Pressure:** High
* **Time:** 25 Minutes
* **Release:** 10-min NPR

| Ingredient | Amount | Notes |
| :--- | :--- | :--- |
| Beef Chuck | 1.5 lbs | 1-inch cubes |
| Pearl Barley | 1 cup | Rinsed |
| Beef Broth | 3 cups | |
| (Base) Onion/Garlic/Celery | - | Minced/Diced |

**Steps:**
1. **Sauté:** Oil/Onion/Celery/Garlic until soft. 
2. **Sear:** Brown beef cubes in batches.
3. **Deglaze:** Add broth; scrape bottom thoroughly.
4. **Layer:** Add barley; do not stir.
5. **Pressure:** Seal; High Pressure for 25m.
6. **Finish:** 10m NPR, then release remaining steam.
