# 🏋️ Fitness Buddy — AI Fitness Coach

## Project Details
- **Internship:** Edunet Foundation IBM 4-Week Internship
- **Problem Statement:** #13 - Fitness Buddy
- **Technology:** LangFlow + IBM watsonx.ai + Meta Llama on IBM Cloud

## Features
- 💪 Personalized home workout routines
- 🥗 Healthy meal and nutrition suggestions
- 🔥 Daily motivation and fitness inspiration
- 📅 Habit building and consistency tips

## How to Run
1. Import `Fitness_Buddy.json` into LangFlow
2. Add your IBM watsonx API key
3. Add your IBM watsonx Project ID
4. Set endpoint to your region
5. Run in LangFlow Playground

## Flow Architecture
Chat Input → Prompt Template → IBM watsonx.ai → Chat Output
                    ↑
            Message History (Memory)
