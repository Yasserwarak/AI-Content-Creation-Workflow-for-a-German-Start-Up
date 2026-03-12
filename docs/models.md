

This project uses different AI models depending on the type of task performed by each agent.

The goal is to match the **complexity of the task** with the **appropriate model capability**.

## Model Architecture

Competitor Analysis Agent → gpt-5.4-pro  
Content Ideas Manager → gpt-5.3-chat  
Content Pillar Validator → gpt-5.2  
Short Video Script Writer → gpt-5.3-chat  
Long Video Script Writer → gpt-5.4-pro  


## Reasoning Behind Model Selection

### gpt-5.4-pro
Used for tasks requiring deeper reasoning and structured thinking.

Examples:
- competitor analysis
- long-form script generation

These tasks require the model to analyze patterns, summarize insights, and structure longer content.

---

### gpt-5.3-chat
Used for creative content generation.

Examples:
- content ideas
- short-form video scripts

This model performs well for conversational and creative text generation tasks.

---

### gpt-5.2
Used for validation and classification tasks.

Example:
- verifying whether generated ideas align with predefined content pillars

This task does not require advanced creative generation, making a lighter model sufficient.

---

## Model Availability Constraints

Some models initially considered for this project were **not used due to deployment limitations in Azure regions located in Germany**.

Since this project was developed using Azure AI resources configured for **German data center regions**, certain models could not be deployed in the environment.

Examples of models that were considered but not used include:

- claude-opus models
- claude-sonnet models
- other partner models not available in the selected region

Because of these restrictions, the workflow was implemented using **models that are deployable in the configured Azure environment**.

---

## Learning Context

This model selection process reflects real-world constraints that engineers face when deploying AI systems in cloud environments.

It also supports the learning objectives of:

- **AI-900 – Microsoft Azure AI Fundamentals**
- **AZ-104 – Microsoft Azure Administrator**

Topics explored through this project include:

- model capability evaluation
- model deployment constraints
- Azure region availability
- practical AI architecture design
