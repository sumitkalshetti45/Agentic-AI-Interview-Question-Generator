# Agentic-AI-Interview-Question-Generator
An **Agentic AI-powered interview preparation system** that generates **role-specific interview questions and answers** for **Data Science, Data Analyst, and related roles**, with interactive follow-up options such as difficulty selection and topic-wise question generation.

This project demonstrates **multi-agent collaboration using LangGraph** and **LLM-driven intelligence** to build an adaptive interview assistant.

---

## 🚀 Features

- Multi-agent workflow using **LangGraph (StateGraph)**
- LLM-powered interview **Question & Answer generation**
- Supports **Data Science / Data Analyst / GenAI** roles
- Interactive follow-up options:
  - More questions
  - Topic-wise questions
  - Harder (advanced) questions
- Beginner-friendly and interview-focused responses
- Runs smoothly in **Google Colab**

---

## 🏗️ System Architecture

The system is built using a **state-based agent architecture**:

1. **Manager Agent**
   - Understands the user goal and defines the interview task

2. **Research Agent**
   - Identifies relevant interview topics using tools

3. **Content Agent**
   - Uses an LLM to generate structured interview Q&A

4. **Reviewer Agent**
   - Reviews content and prompts the user with follow-up choices

5. **User Interaction Loop**
   - Dynamically adapts output based on user selection

---

## 🧠 Tech Stack

- Python
- LangGraph
- LangChain
- OpenAI (ChatOpenAI)
- Google Colab

---

## ▶️ How It Works

1. User enters an interview goal
2. Agents collaborate to generate interview questions
3. User selects a follow-up option
4. System generates refined questions based on selection

---

## 📥 Input

text
Enter your goal: give interview question on data science
Enter your choice (1 = More, 2 = Topic-wise, 3 = Harder): 3

1. What is Data Science?
Answer: Data Science is the process of extracting meaningful insights from structured and unstructured data.

2. What is the difference between supervised and unsupervised learning?
Answer: Supervised learning uses labeled data, while unsupervised learning works with unlabeled data.

3. What is overfitting?
Answer: Overfitting occurs when a model performs well on training data but poorly on unseen data.

...

Harder Interview Questions Generated:
- Explain the bias-variance tradeoff.
- How does regularization prevent overfitting?
- What are the assumptions of linear regression?

Would you like:
1) More questions
2) Topic-wise questions (Python / SQL / ML)
3) Harder questions


##🌟 Project Highlights

- Implements a multi-agent GenAI workflow using LangGraph
- Demonstrates agent coordination and state-based execution
- Uses tool calling for dynamic topic research
- Generates reviewed interview questions automatically
- Designed for fresher-level interview preparation
