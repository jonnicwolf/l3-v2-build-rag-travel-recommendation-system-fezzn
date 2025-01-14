# Travel Recommender - RAG-based Travel Recommendation Engine

## Project Overview
Create a web-based application that provides travel recommendations based on user preferences using ReactJS, ExpressJS, PostgreSQL with pgvector, and OpenAI's embedding API. This project showcases how to build a modern recommendation system using vector databases, embeddings, and similarity matching in a practical application.


## Context

This project demonstrates the implementation of a RAG (Retrieval Augmented Generation) system - a powerful AI architecture that combines the precision of information retrieval with the flexibility of AI generation. Unlike traditional AI that relies purely on trained knowledge, RAG first retrieves relevant information from a database and then uses that specific information to generate responses. Think of it like an AI having access to a specialized knowledge base that it can reference before making recommendations.

In our travel recommender, when a user inputs their preferences (like "winter skiing trip with $2000 budget"), the system:
1. Converts these preferences into a numerical vector (embedding)
2. Searches a database of real travel profiles for similar preference patterns
3. Uses the most similar matches to generate personalized recommendations

This approach, similar to how companies like Airbnb match travelers with destinations, ensures recommendations are grounded in real travel patterns while leveraging AI for personalization.


## Project Scope
This is a production-ready development project aimed at understanding RAG systems and vector databases used in real-world applications. It is broken into 3 tiers of complexity outlined below.

## Technical Learning Takeaways
* Vector Databases
  - Understanding pgvector for similarity search
  - Vector embeddings and how they represent meaning
  - Cosine similarity for finding similar preferences
  - Vector indexing and optimization

* RAG Implementation
  - Retrieval techniques using vector similarity
  - Converting user inputs to embeddings
  - Weighted matching strategies
  - Combining retrieved data with AI generation

* Data Processing
  - Working with embeddings API
  - Managing vector dimensions
  - Data quality and validation
  - Error handling for embedding generation

* Advanced Concepts
  - Similarity weights and scoring
  - Vector caching strategies
  - Rate limiting for API protection
  - Creative text generation with AI

## Core Features Required
* User preference input (season, budget, activities)
* Vector database storage with pgvector
* Embedding generation using OpenAI API
* Weighted similarity search
* Rate-limited API endpoints
* Real-time recommendation matching

## Technical Stack
* Frontend: ReactJS
* Backend: ExpressJS
* Database: PostgreSQL with pgvector
* AI Integration: OpenAI API for embeddings
* Additional: Express Rate Limiter, pg-promise

## Tiers of Development

### Tier 1: Basic Recommendation Engine
* Set up PostgreSQL with pgvector extension
* Create basic database schema for travel profiles
* Implement basic similarity search
* Frontend UI Components:
  - User input form with dropdowns
  - Basic styling and layout
  - Simple results display
  - Loading states
* Display basic recommendations

### Tier 2: Enhanced Features
* Add weighted similarity search
* Implement rate limiting
* Add input validation
* Create helper endpoints
* Enhance UI with better user feedback
* Add error handling
* Creative Enhancement:
  - Additional OpenAI call to generate personalized travel descriptions
  - Transform raw recommendations into engaging travel suggestions
  - Add context-aware travel tips based on selected preferences

### Tier 3: Advanced Features
* Vector Caching Implementation:
  - Cache frequently requested embedding vectors
  - Store similar preference patterns
  - Implement cache invalidation strategy
  - Optimize vector retrieval performance
* Add budget range filtering
* Implement recommendation confidence scores
* Enhanced activity matching
* Add detailed explanation for recommendations

## Technical Requirements

### Frontend (React)
* Single Page Application using React
* Form handling for user preferences
* Dynamic activity options based on season
* Loading states
* Error handling
* Results display component

### Backend (Express)
* Vector similarity search endpoints
* Rate limiting middleware
* Helper endpoints for form options
* OpenAI API integration
* PostgreSQL with pgvector queries

### Database
* pgvector extension setup
* Embeddings storage
* Profile data management
* Efficient similarity queries

## Setup and Installation

### Database Setup
1. Install PostgreSQL
2. Install pgvector extension
3. Create database schema
4. Import sample data

### Backend Setup
1. Install dependencies
2. Configure environment variables
3. Set up OpenAI API key
4. Initialize Express server

### Frontend Setup
1. Create React app
2. Install dependencies
3. Set up components
4. Configure API endpoints

## Getting Started
1. Review the technical requirements
2. Set up your development environment
3. Install required dependencies
4. Configure your database
5. Test your endpoints
6. Build the frontend interface

## Documentation
* Technical Documentation - Details on RAG implementation and vector similarity
* API Documentation - Available endpoints and usage
* Database Schema - Table structures and relationships