# 🚴 AI Multi-Agent Content Generation Workflow for Steereon

## Overview

This repository contains a multi-agent AI workflow designed to generate social media content for **Steereon**, a German bicycle manufacturer that designs and produces bikes in Germany.

The workflow analyzes competitor activity in the bicycle and e-mobility market, generates content ideas, validates them against predefined content pillars, and produces scripts for both short-form and long-form videos.

This project was built as a hands-on learning project while preparing for the following Microsoft Azure certifications:

- **AI-900 – Microsoft Azure AI Fundamentals**
- **AZ-104 – Microsoft Azure Administrator**

---

## Project Goals

The main goals of this project are:

- practice designing AI workflows
- understand generative AI use cases
- explore AI agent orchestration
- apply concepts related to AI-900 and AZ-104
- document a practical Azure-focused AI learning project on GitHub

Instead of only studying theory, this repository shows how AI systems can automate a realistic content creation pipeline.

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
