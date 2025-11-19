Rapid-Mind AI — Transaction Reversal Chatbot

An intelligent AI-powered chatbot designed to help fintech users retrieve and resolve unsuccessful or failed transactions. Built with Rasa NLU, this project demonstrates applied Natural Language Understanding, retrieval systems, and conversational AI pipeline design for real-world financial operations.
🚀 Project Overview

Rapid-Mind AI is an NLP-driven assistant that automates customer support tasks in fintech applications.
It identifies user intents, extracts key transaction details, checks transaction status, and provides step-by-step guidance for reversal or retry.

.This project showcases:

NLU modeling

Intent/entity design

Retrieval-augmented responses

Rasa pipeline configuration

Fintech problem-solving with AI

🧠 Key Features

Intent Classification: Detects user queries related to failed/unsuccessful transactions.

Entity Extraction: Identifies transaction ID, date, amount, platform, and failure type.

RAG Workflow: Fetches transaction information using retrieval-based methods.

Automated Troubleshooting: Guides users through resolution or escalation steps.

Fallback & Error Handling: Handles unclear queries and re-prompts cleanly.

API Integration (Optional): Connects to backend endpoints to validate transaction status in real time.

Continuous Improvement: Supports training updates using user logs and conversation history.

🏗️ Tech Stack

Rasa NLU

Python

YAML (for training data)

REST APIs

Vector retrieval tools (optional extension)
RapidMind-AI/
│
├── data/

│   ├── nlu.yml           # Training data (intents, entities, examples)

│   ├── stories.yml       # Dialogue stories

│   └── rules.yml         # Rules and fallback logic

│

├── domain.yml            # Intents, entities, slots, responses

├── config.yml            # NLU pipeline + policies

├── actions/              

│   └── actions.py        # Custom API calls + business logic

│

├── tests/

│   └── test_stories.yml  # Test conversations

│
└── README.md             # Project documentation




Here’s a ** step-by-step list** of how to run the Rapid-Mind AI project:

1. Clone the repository
2. Create a virtual environment
3. Activate the virtual environment
4. Install dependencies
5. Train the NLU and core models
6. Run the chatbot (Rasa shell)
7. Run the action server (if using custom actions)
8. Test the stories / conversations
9. Run the bot with API enabled (optional)


