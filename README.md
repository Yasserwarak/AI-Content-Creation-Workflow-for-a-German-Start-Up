# 🚴 AI Multi-Agent Content Generation Workflow for Steereon

## Overview

This repository contains a multi-agent AI workflow designed to generate social media content for **Steereon**, a German bicycle manufacturer that designs and produces bikes in Germany.

The workflow analyzes competitor activity in the bicycle and e-mobility market, generates content ideas, validates them against predefined content pillars, and produces scripts for both short-form and long-form videos.

This project was built as a practical learning project while preparing for the following Microsoft Azure certifications:

- **AI-900 – Microsoft Azure AI Fundamentals**
- **AZ-104 – Microsoft Azure Administrator**

---

## Project Goal

The main goal of this project is to apply AI and Azure concepts in a practical scenario instead of only studying theory.

This workflow demonstrates how a multi-agent AI system can support a real content creation process by:

- analyzing competitors
- generating content ideas
- validating ideas against brand strategy
- creating video scripts for different social media formats

At the same time, the project helps strengthen my understanding of:

- generative AI workflows
- prompt engineering
- AI agent orchestration
- model selection
- Azure-related AI thinking and architecture design

---

## Project Scenario

**Steereon** is a German bicycle manufacturer focused on:

- urban mobility
- sustainable transportation
- innovative bike technology
- cycling lifestyle
- German engineering

The workflow is designed to support weekly content creation for platforms such as:

- YouTube
- TikTok
- Instagram Reels
- YouTube Shorts

---

## Workflow Architecture

The system uses a multi-agent architecture in which each agent performs a specialized task.

```text
Competitor Analysis Agent
        ↓
Content Ideas Manager
        ↓
Content Pillar Validator
        ↓
Short Video Script Writer
        ↓
Long Video Script Writer
