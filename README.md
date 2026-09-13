# Voiceflow Job Search & Resume Assistant

An AI-powered career assistant designed in Voiceflow to automate resume evaluation, ATS match scoring, and candidate-to-job alignment.

## Features
- **Global Agent Routing:** Automated intake pathing for resume parsing, ATS feedback, and targeted role suggestions.
- **ATS Scoring Engine:** Calculates compatibility metrics (0–100) based on target keywords, formatting density, and structure.
- **Role & Seniority Alignment:** Analyzes candidate experience against target job descriptions to identify skill gaps.
- **Multi-Model Fallbacks:** Integrated LLM pipeline with primary routing on Voiceflow Core and fallback support across Claude and Gemini endpoints.

## Project Structure
- `file.vf`: Voiceflow export file containing complete agent routing logic, prompts, and tool configurations.

## How to Import & Use
1. Log in to your [Voiceflow Workspace](https://creator.voiceflow.com).
2. Click **Import** in the project dashboard.
3. Select the `.vf` file from this repository to load the complete workflow and agent configurations.
