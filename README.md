# Fitness Buddy

An AI-powered fitness and wellness coaching agent, built for the AICTE-IBM SkillsBuild 2026 University Engagement Program.

## About the Project
This project addresses **Problem Statement No. 13**, which calls for an accessible AI assistant to help users stay consistent with fitness through personalized workout suggestions, nutrition guidance, and motivation — without requiring a gym membership or personal trainer.

I built Fitness Buddy using **IBM watsonx Orchestrate**, focusing specifically on users who don't have access to a gym or budget for equipment. Rather than assuming a premium fitness lifestyle, the agent recommends workouts using everyday household items and suggests affordable, regionally relevant meal ideas.

## Features
- Personalized home workout suggestions based on the user's goal (weight loss, toning, general fitness, or a busy schedule)
- No-equipment workout adaptations using household items (water bottles, chairs, stairs)
- Simple, budget-friendly meal ideas
- Motivational support to help build consistent habits
- Built-in safety guardrails — the agent avoids medical diagnoses, unsafe/extreme advice, and stays on-topic

## How It Works
1. The user asks a fitness, nutrition, or motivation-related question
2. The agent checks the request against its safety guidelines
3. Relevant information is retrieved from a custom knowledge base (RAG)
4. The agent responds in a structured format: Suggestion Type, Details, and a motivational Tip

## Tech Stack
- **IBM watsonx Orchestrate** — used to build, configure, and deploy the agent
- **GPT-OSS 120B** — the foundation model powering the agent
- **RAG-based Knowledge Base** (PDF) — grounds responses in curated, accurate content
- **Custom Guidelines** — condition-action rules enforcing safe, on-topic behavior

## Repository Contents
- `Fitness_Buddy_Knowledge_Base.pdf` — the knowledge base document used for retrieval
- `Problem_Statement_13_Fitness_Buddy.pdf` — the official problem statement
- `Fitness_Buddy_AICTE_Submission.pptx` — the full project submission deck
- Screenshots — agent configuration, guidelines, deployment status, and sample chat interactions

## What Makes This Different
Most fitness apps assume users already have gym access or can afford equipment and subscriptions. Fitness Buddy is designed around the opposite assumption — that many users, particularly students and those in tier-2/3 cities, need guidance that works with what they already have at home. Safety and consistency are treated as core design priorities, not afterthoughts.

## Future Scope
- Calendar/reminder integration for automated workout notifications
- Progress tracking (streaks, logged workouts)
- Voice-based and multilingual interaction
- Integration with wearable fitness devices

## Submission Details
Submitted by: **Sejal Yadav**

AICTE-IBM SkillsBuild 2026 — University Engagement Program
