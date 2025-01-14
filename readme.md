# Travel Recommender - RAG-based Travel Recommendation Engine

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
This project is designed as a learning journey where you'll work with Claude to understand and implement each component. Rather than providing exact implementations, you'll be guided through the process of building the application while understanding the core concepts.

👉 **Start with [LEARNING_JOURNEY.md](./learning-journey.md) for your step-by-step guide to building this project with Claude.**

## Project Overview
Create a web-based travel recommendation system that:
- Takes user travel preferences
- Matches them with similar profiles using vector similarity
- Generates personalized recommendations

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

## Development Tiers

### Tier 1: Basic Recommendation Engine
- Database setup with pgvector
- Basic similarity search
- Simple frontend form

### Tier 2: Enhanced Features
- Weighted recommendations
- Rate limiting
- Creative AI descriptions

### Tier 3: Advanced Features
- Vector caching
- Budget filtering
- Detailed explanations
- More advanced CSS and Animation

## Getting Started

1. Clone this repository
2. Review [LEARNING_JOURNEY.md](./learning-journey.md)
3. Start your journey with Claude
4. Follow the development phases outlined in the learning journey

## Support
- Refer to [LEARNING_JOURNEY.md](./learning-journey.md) for guided development
- Use Claude for implementation guidance


Remember: The goal is to understand and learn RAG systems by building one, not just to copy a solution. Work through each step with Claude to get the most out of this learning experience.