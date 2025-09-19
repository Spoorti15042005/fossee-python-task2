# 🚀 FOSSEE Python Screening Task 2 – AI Debugging Assistant

This repository contains my submission for the **FOSSEE Semester Long Internship – Autumn 2025**, under the **Python Project**.  
The selected task is **Screening Task 2: Write a Prompt for an AI Debugging Assistant**.

---

## 🎯 Task Objective
The goal is to design a natural-language prompt for an AI assistant to:  
- 🔍 Analyze a student’s buggy Python code  
- 💡 Offer helpful suggestions or hints  
- ❌ Avoid giving the full solution  

The prompt must be **general enough for any Python problem**, yet **specific enough** to guide the student effectively.

---

## 📂 Repository Contents
- `Prompt.md` → AI debugging assistant prompt  
- `README.md` → Task reasoning, examples, and submission notes  

---

## 🧠 Reasoning Behind Prompt Design

### 1️⃣ Why the prompt was worded this way
- Clear, step-by-step instructions ensure predictable AI behavior  
- Encourages **learning and independent problem-solving**  
- Uses a **supportive and friendly tone**  

### 2️⃣ How it avoids giving the solution
- AI highlights errors and asks questions instead of providing corrected code  
- Focuses on **hinting and reasoning**, not direct fixes  

### 3️⃣ How it encourages helpful, student-friendly feedback
- Uses **simple and approachable language**  
- Provides **tips and conceptual guidance**  
- Builds confidence while debugging  

### 4️⃣ Adapting to different learner levels
- **Beginners:** Use simple language, step-by-step hints, and examples  
- **Advanced learners:** Use high-level reasoning, fewer hints, focus on strategies  

---

## 🧑‍🏫 Example Interactions

**Beginner Code:**
```python
def multiply(a, b):
print(a * b)

3️⃣ How it encourages helpful, student-friendly feedback
- Uses simple and approachable language
- Provides tips and conceptual guidance
- Builds confidence while debugging  

4️⃣ Adapting to different learner levels
- Beginners: Use simple language, step-by-step hints, and examples  
- Advanced learners: Use high-level reasoning, fewer hints, focus on strategies  

---

🧑‍🏫 Example Interactions

Beginner Code:
```python
def multiply(a, b):
print(a * b)
- Reinforces “teach, don’t tell.”

How it encourages helpful feedback
- Supportive, confidence-building tone.
- Beginner-friendly explanations.
- Encourages thinking instead of spoon-feeding.

---

Required Q&A

Q1. What tone and style should the AI use when responding? 
Supportive, patient, beginner-friendly, encouraging.  

Q2. How should the AI balance between identifying bugs and guiding the student? 
Point out likely error spots, explain the concept, and ask guiding questions instead of giving final code.  

Q3. How would you adapt this prompt for beginner vs. advanced learners?  
- Beginners → simple step-by-step hints, examples, plain language.  
- Advanced learners → technical explanations, fewer hints, more conceptual questions.  
