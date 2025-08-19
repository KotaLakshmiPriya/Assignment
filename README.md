# AI-Powered Role-Based Assessment & Evaluation System

## 📌 Overview
This project is a **mini AI-powered technical assessment system** that dynamically generates customized tests for different job roles.  
The system adapts based on the **role, tech stack, candidate experience, and custom natural language inputs**.  
It also evaluates answers using AI and provides a **detailed performance report**.

---

## 🚀 Features
### Phase 1 - Role & Requirements Gathering
- Collects structured inputs (role, skills, experience, duration, question types).
- Accepts natural language inputs to refine test (e.g., *"focus more on problem-solving"*).
- Parses and combines structured + natural language inputs into a **test blueprint**.

### Phase 2 - Dynamic Test Generation
- AI generates difficulty-adjusted questions:
  - **MCQs**
  - **Coding challenges**
  - **Scenario-based questions**
- Each question has **metadata**: skill tag, difficulty level, estimated time.
- Test is stored in the database and displayed via a clean frontend.

### Phase 3 - Test Taking & AI Evaluation
- Candidates take the test online.
- **Coding questions**: checked for correctness.
- **Open-ended answers**: evaluated by AI against expected answers.
- Generates a comprehensive **AI-powered report**:
  - Overall score
  - Per-skill breakdown
  - Strengths & weaknesses
  - Improvement recommendations
  - Suggested learning resources

---

## ⚡ Bonus Features (Optional)
- **Proctoring**: Timer & tab-switch detection
- **Multi-role Support**: Save & reuse role templates

---

## 🛠️ Tech Stack
- **Frontend**: React + TailwindCSS (or Material UI)
- **Backend**: Node.js + Express
- **Database**: MongoDB / PostgreSQL
- **AI/LLM**: OpenAI / Local LLM for:
  - Question generation
  - NLP parsing of natural language inputs
  - Answer evaluation

---


