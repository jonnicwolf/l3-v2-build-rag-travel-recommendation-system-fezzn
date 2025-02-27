# Building a RAG-based Travel Recommender: Learning Journey

## Before You Start Coding

### 1. Understanding Vector Databases (Day 1 Morning)
Ask Claude:
- "What is a vector database in simple terms?"
- "How is it different from a regular database?"
- "Can you explain vector similarity with a real-world example?"

You should understand:
- ✓ Why regular databases can't find "similar" items easily
- ✓ Why we need vector databases for recommendations
- ✓ What makes items "similar" in a vector database

### 2. Understanding Embeddings (Day 1 Afternoon)
Ask Claude:
- "What are embeddings and why do we need them?"
- "How do embeddings capture meaning?"
- "Can you explain embeddings using a simple analogy?"

You should understand:
- ✓ How text gets converted to numbers
- ✓ Why similar meanings have similar numbers
- ✓ How embeddings help find similar items

### 3. Understanding Weights (Day 1 Evening)
Ask Claude:
- "Why do we need weights in our recommendations?"
- "How do weights make recommendations better?"
- "Can you give examples of good and bad recommendation matches?"

You should understand:
- ✓ Why some matches should count more than others
- ✓ How weights improve logical recommendations
- ✓ When to apply different weights

## Development Journey

### Phase 1: Database Setup (Day 2)
First, ask Claude about setting up PostgreSQL. Claude can guide you through:
- Installing PostgreSQL
- Adding pgvector
- Testing the installation

Checkpoint: Can you:
- ✓ Connect to your database?
- ✓ Create a test table?
- ✓ Add the vector extension?

### Phase 2: Understanding Your Data (Day 2-3)
Ask Claude about:
- Loading the Mountains vs Beaches dataset
- Which fields are important for recommendations
- How to structure your database tables

Checkpoint: Can you:
- ✓ Load the CSV data?
- ✓ Query the basic data?
- ✓ Understand the relationships between fields?

### Phase 3: Creating Embeddings (Day 3-4)
Work with Claude to:
- Set up OpenAI API
- Create your first embedding
- Store embeddings in pgvector

Checkpoint: Can you:
- ✓ Generate an embedding from text?
- ✓ Store it in your database?
- ✓ Retrieve it correctly?

### Phase 4: Building Basic Recommendations (Day 4-5)
Ask Claude about:
- Writing similarity queries
- Testing with sample inputs
- Improving match quality

Checkpoint: Can you:
- ✓ Find similar profiles?
- ✓ Get meaningful recommendations?
- ✓ Explain why matches are similar?

### Phase 5: Adding Weights (Day 5-6)
Work with Claude on:
- Identifying logical combinations
- Implementing weight calculations
- Testing weighted results

Checkpoint: Can you:
- ✓ Explain your weighting strategy?
- ✓ See improvement in recommendations?
- ✓ Handle edge cases?

### Phase 6: Frontend Development (Day 6-7)
Ask Claude about:
- Setting up the React form
- Handling API calls
- Displaying recommendations

Checkpoint: Can you:
- ✓ Get user input correctly?
- ✓ Show loading states?
- ✓ Display recommendations clearly?

## Key Learning Checkpoints

After each phase, ask yourself:
1. Could I explain this concept to someone else?
2. Do I understand why we're doing this step?
3. Can I predict what should happen next?

If "no" to any of these, ask Claude for clarification before moving on.

## Working with Claude Effectively

1. Start Simple:
- Ask for basic explanations first
- Request real-world analogies
- Build up to technical details

2. Show Your Understanding:
- Explain concepts back to Claude
- Ask if your understanding is correct
- Request challenges to test your knowledge

3. When Stuck:
- Explain what you're trying to do
- Share what you've tried
- Ask for step-by-step guidance

4. For Technical Issues:
- Share error messages
- Explain your setup
- Ask for debugging strategies

Remember: The goal is understanding, not just copying code. Take time to grasp each concept fully before moving forward.