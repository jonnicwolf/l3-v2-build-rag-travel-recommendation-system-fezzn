# Travel Recommender - RAG-based Travel Recommendation Engine

<img src="./assets/travel.webp" alt="Travel Recommender" width="500">

## Context
This project demonstrates the implementation of a RAG (Retrieval Augmented Generation) system - a powerful AI architecture that combines the precision of information retrieval with the flexibility of AI generation. Unlike traditional AI that relies purely on trained knowledge, RAG first retrieves relevant information from a database and then uses that specific information to generate responses.

In this project, you'll learn how to build this system step by step with the guidance of Claude, Anthropic's AI assistant.

## Real World Application
This project tackles a common challenge in the travel and recommendation industry: how to provide personalized suggestions that are both accurate and context-aware. The techniques you'll learn are similar to those used by:

* Travel Companies:
  - Airbnb's matching of travelers with ideal accommodations
  - Booking.com's personalized destination recommendations
  - Expedia's travel package suggestions

* E-commerce & Entertainment:
  - Netflix's content recommendations
  - Spotify's playlist suggestions
  - Amazon's product recommendations

* Enterprise Applications:
  - Customer support systems finding relevant documentation
  - Content management systems with semantic search
  - Knowledge base systems with context-aware retrieval

The RAG system you'll build demonstrates how modern companies:
- Move beyond simple keyword matching
- Use real user behavior patterns
- Combine AI with actual data for better recommendations
- Scale recommendations for large user bases

These skills are increasingly valuable as companies seek to provide more personalized, context-aware experiences to their users.

## Learning Approach
This project is designed as a learning journey where you'll work with generative AI e.g. Claude to understand and implement each component. Rather than providing exact implementations, you'll be guided through the process of building the application while understanding and learning the core concepts.

## Project Overview
Create a web-based travel recommendation system that:
- Takes user travel preferences
- Matches them with similar profiles using vector similarity
- Generates personalized recommendations


👉 **Start with [SESSIONS](./sessions.md) for your step-by-step guide to building this project with Claude.**


## Technical Stack
* Frontend: ReactJS
* Backend: ExpressJS
* Database: PostgreSQL with pgvector
* AI Integration: OpenAI API for embeddings

## Dataset
This project uses the [Mountains vs Beaches Preference Dataset](https://www.kaggle.com/datasets/jahnavipaliwal/mountains-vs-beaches-preference) from Kaggle, containing over 52,000 travel preference profiles.

## Initial Setup Requirements

1. Tools/Accounts Needed:
- Node.js and npm
- PostgreSQL
- OpenAI API key
- Code editor
- Git

2. Download Required Dataset:
- Mountains vs Beaches dataset from Kaggle
- CSV to SQL converter access

3. Recommended Knowledge:
- Basic React
- Basic Express
- Basic PostgreSQL
- REST APIs

## Tiers

This project is designed to be built in 3 tiers. Tier 1 is the true goal of this project. Each tier builds on the previous one, adding more features and complexity. But remember, the goal is to understand and learn RAG systems by building one, not just to copy a solution. Total completion is not the goal, understanding is. The tier explanation is in [tier.md](./tier.md)

## Don't Panic!
This looks like a lot! Don't worry, let's break it down into manageable chunks. Take a look at the [Session Breakdown](sessions.md) file for a breakdown of the project and how you could potentially plan to use your time to complete the project. Also take a look at [Using Generative AI to Learn Concepts](learning-journey.md) as well as [Prompts](prompts.md) to understand how to use prompts to help you learn concepts and implement your project.
## Getting Started

1. Clone this repository
2. Review [Sessions](./sessions.md)
3. Start your journey with Claude
4. Follow the development phases outlined in the seaddions

Remember: The goal is to understand and learn RAG systems by building one, not just to copy a solution. Work through each step with Claude to get the most out of this learning experience.