# 🏋️ Fitness Buddy — AI Fitness Coach

## Project Details
- **Internship:** Edunet Foundation IBM 4-Week Internship
- **Technology:** LangFlow + IBM watsonx.ai + Meta Llama on IBM Cloud

##Problem Statement
- Fitness Buddy 
The challenge - In today’s fast-paced world, many individuals struggle to maintain a healthy lifestyle due 
to lack of personalized guidance, time constraints, and inconsistent motivation. Traditional fitness 
solutions often require expensive subscriptions, in-person consultations, or rigid schedules that don't 
adapt to personal preferences or daily routines. 
There is a growing need for an accessible, friendly, and intelligent virtual assistant that can provide on
demand fitness advice, healthy lifestyle suggestions, and basic nutrition guidance—all tailored to 
individual needs and available at any time. 
Fitness Buddy aims to solve this problem by offering a conversational, AI-powered health and fitness 
coach that can: 
Recommend home workouts and routines based on user input. 
• Provide motivational tips and daily fitness inspiration. 
• Suggest simple, nutritious meal ideas. 
• Encourage habit-building and consistency.

## Features
- 💪 Personalized home workout routines
- 🥗 Healthy meal and nutrition suggestions
- 🔥 Daily motivation and fitness inspiration
- 📅 Habit building and consistency tips

##

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
