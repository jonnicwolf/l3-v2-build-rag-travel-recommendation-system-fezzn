# Building a RAG-based Travel Recommender: Learning Journey

## Session 1: Planning
Ask Claude:
- "Can you explain the overall RAG system architecture?"
- "What components will we need to build?"
- "How will data flow through our system?"
- "What development environment do we need?"
- "Which APIs and tools should we prepare?"
- "How should we structure our project?"
- "What order should we build components in?"
- "What are potential challenges we might face?"
- "How can we test each component?"

You should understand:
- ✓ The complete system architecture
- ✓ Each component's role
- ✓ How components interact

Checkpoint: Can you:
- ✓ List all required tools and APIs?
- ✓ Explain where each tool fits in?
- ✓ Draw a system diagram?
- ✓ Create a development timeline?
- ✓ Identify critical dependencies?
- ✓ Plan your testing approach?

## Session 2: Understanding Core Concepts

### 1. Understanding Vector Databases
Ask Claude:
- "What is a vector database in simple terms?"
- "How is it different from a regular database?"
- "Can you explain vector similarity with a real-world example?"

You should understand:
- ✓ Why regular databases can't find "similar" items easily
- ✓ Why we need vector databases for recommendations
- ✓ What makes items "similar" in a vector database

### 2. Understanding Embeddings
Ask Claude:
- "What are embeddings and why do we need them?"
- "How do embeddings capture meaning?"
- "Can you explain embeddings using a simple analogy?"

You should understand:
- ✓ How text gets converted to numbers
- ✓ Why similar meanings have similar numbers
- ✓ How embeddings help find similar items

### 3. Understanding Weights
Ask Claude:
- "Why do we need weights in our recommendations?"
- "How do weights make recommendations better?"
- "Can you give examples of good and bad recommendation matches?"

You should understand:
- ✓ Why some matches should count more than others
- ✓ How weights improve logical recommendations
- ✓ When to apply different weights

## Development Journey

### Session 3: Database Setup
First, ask Claude about setting up PostgreSQL. Claude can guide you through:
- Installing PostgreSQL
- Adding pgvector
- Testing the installation

Checkpoint: Can you:
- ✓ Connect to your database?
- ✓ Create a test table?
- ✓ Add the vector extension?

### Session 4: Understanding Your Data
Ask Claude about:
- Loading the Mountains vs Beaches dataset
- Which fields are important for recommendations
- How to structure your database tables

Checkpoint: Can you:
- ✓ Load the CSV data?
- ✓ Query the basic data?
- ✓ Understand the relationships between fields?

### Session 5: Creating Embeddings
Work with Claude to:
- Set up OpenAI API
- Create your first embedding
- Store embeddings in pgvector

Checkpoint: Can you:
- ✓ Generate an embedding from text?
- ✓ Store it in your database?
- ✓ Retrieve it correctly?

### Session 6: Building Basic Recommendations
Ask Claude about:
- Writing similarity queries
- Testing with sample inputs
- Improving match quality

Checkpoint: Can you:
- ✓ Find similar profiles?
- ✓ Get meaningful recommendations?
- ✓ Explain why matches are similar?

### Session 7: Frontend Development
Ask Claude about:
- Setting up the React form
- Handling API calls
- Displaying recommendations

Checkpoint: Can you:
- ✓ Get user input correctly?
- ✓ Show loading states?
- ✓ Display recommendations clearly?

## Key Learning Checkpoints

After each session, ask yourself:
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

## Session Time Management

Each session is 2 hours. Use this time to:
1. Review previous session's concepts (15 minutes)
2. Work through current session's material (80 minutes)
3. Test your understanding with checkpoints (15 minutes)
4. Prepare questions for next session (10 minutes)

If you finish early:
- Review checkpoints again
- Try explaining concepts to others
- Experiment with what you've learned
- Prepare questions for next session

If you need more time:
- Note where you got stuck
- Prepare specific questions for Claude
- Review related concepts
- Don't rush - understanding is key