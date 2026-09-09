# Lecture 1 - Introduction to Agentic AI

## 1. Generative AI

Generative AI creates new content.

It can generate:
- Text
- Images
- Code
- Audio
- Video

Example:

Prompt → LLM → Generated response

---

## 2. Traditional AI vs Generative AI

Traditional AI:
Input → Prediction / Decision

Example:
Email → Spam / Not Spam

Generative AI:
Prompt → New Content

Example:
"Explain recursion" → Generated explanation

---

## 3. Applications of Generative AI

Generative AI can be used for:

- Chatbots
- Code generation
- Image generation
- Summarization
- Translation
- Content writing
- Question answering

---

# Evolution of Chatbots

## 4. Chatbot 1 - Basic LLM Chatbot

Flow:

User → LLM → Response

Example:

User:
"What is FastAPI?"

LLM:
Generates an answer.

### Problem

The LLM only knows what it learned during training.

It does not automatically know:
- Private company data
- Your documents
- Latest information
- External application data

---

## 5. Chatbot 2 - RAG Based Chatbot

RAG = Retrieval Augmented Generation.

Flow:

User Question
↓
Retrieve relevant documents
↓
Send documents + question to LLM
↓
Generate answer

Example:

User asks:
"What is the attendance policy?"

System searches college policy documents and gives the relevant content to the LLM.

### Why RAG?

It gives the LLM external knowledge.

### Problem

RAG mainly helps the LLM READ information.

It still cannot easily perform actions.

---

## 6. Chatbot 3 - Tool Augmented Chatbot

Now the LLM can use tools.

Examples of tools:

- Search API
- Calculator
- Database
- Email
- Calendar
- Weather API
- GitHub

Flow:

User
↓
LLM decides whether a tool is needed
↓
Tool is called
↓
Tool result goes back to LLM
↓
Final response

Example:

User:
"What meetings do I have tomorrow?"

LLM uses Calendar tool and answers.

### Important

The LLM itself does not know the answer.

It uses a tool to get the answer.

---

## 7. Chatbot 4 - Agentic AI

Agentic AI goes one step further.

Instead of only answering a question, the AI can:

- Decide what steps are needed
- Choose tools
- Perform multiple steps
- Check results
- Make another decision
- Repeat if needed
- Maintain state
- Work towards a goal

Example:

User:
"Find a good time for a meeting with Rahul and schedule it."

Agent can:

1. Check your calendar
2. Check Rahul's availability
3. Find common free time
4. Ask for approval if needed
5. Create the meeting

---

# Main Difference

Basic LLM:
Think → Answer

RAG:
Retrieve → Think → Answer

Tool-Augmented:
Think → Use Tool → Answer

Agentic AI:
Think → Decide → Use Tools → Observe → Decide Again → Act

---

# What is Agentic AI?

Agentic AI is an AI system that can make decisions and perform multiple actions to achieve a goal.

It can:

- Plan
- Use tools
- Maintain state
- Make decisions
- Repeat steps
- Take actions

---

# Key Idea

LLM = Brain

Tools = Hands

Memory = Past information

Agent = Brain + Tools + Memory + Decision making
