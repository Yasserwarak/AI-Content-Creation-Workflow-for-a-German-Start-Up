
# AI Workflow Architecture

This project uses a multi-agent AI workflow to generate social media content for Steereon.

Each agent performs a specialized task and passes its output to the next step in the pipeline.

Workflow:

Competitor Analysis Agent
↓
Content Ideas Manager
↓
Content Pillar Validator
↓
Short Video Script Writer
↓
Long Video Script Writer


Agent Responsibilities

Competitor Analysis Agent  
Analyzes competitor content in the bicycle industry and identifies trends.

Content Ideas Manager  
Generates social media content ideas based on competitor insights.

Content Pillar Validator  
Ensures generated ideas align with Steereon's strategic content pillars.

Short Video Script Writer  
Generates scripts for short-form social media content.

Long Video Script Writer  
Generates structured scripts for YouTube videos.
