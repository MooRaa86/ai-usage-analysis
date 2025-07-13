# 📊 AI Assistant Usage Analysis by Students

## 🗂️ Dataset Overview  
I analyzed a dataset containing **10,000+ sessions** of students using an AI assistant for academic purposes. Each row in the dataset represents one session, capturing how students interacted with the AI tool across different tasks and disciplines.

---

## 📋 Data Columns  
Key columns included in the dataset:

- `StudentLevel`: Whether the student is undergraduate or graduate  
- `Discipline`: The academic field (e.g., Computer Science, Psychology, etc.)  
- `TaskType`: Type of academic task (e.g., writing, coding, brainstorming)  
- `SessionLengthMin`: Duration of the session in minutes  
- `TotalPrompts`: Number of prompts exchanged with the AI  
- `AI_AssistanceLevel`: How helpful the AI was rated (1–5)  
- `FinalOutcome`: What was achieved during the session (e.g., idea drafted, assignment completed)  
- `SatisfactionRating`: User satisfaction with the session (1–5)  
- `UsedAgain`: Whether the student returned to use the tool again

---

## 🧠 SQL Techniques Used  
To explore the data and extract meaningful insights, I used a variety of SQL techniques:

- `SELECT`, `WHERE`, and `DISTINCT` to explore and filter records  
- `GROUP BY` with `COUNT` and `AVG` to summarize data  
- `ORDER BY` to rank sessions based on satisfaction and usage  
- `BETWEEN`, `TOP`, and logical conditions to focus on specific data ranges  
- `Subqueries` to calculate overall percentages (e.g., assignment completion rate)

---

## 📈 Insights We Gained from the Analysis  

The SQL analysis helped uncover several key findings:

- **Writing and brainstorming** were the most common task types where students used the AI.
- **Graduate students in Computer Science** showed high engagement and satisfaction levels.
- **Longer sessions (over 30 minutes)** indicated deeper academic tasks and focused usage.
- **Psychology and Business students** reported the highest average AI assistance levels.
- A significant percentage of sessions ended with **“assignment completed”**, proving the AI’s usefulness.
- Students who were **dissatisfied (low rating)** and **didn’t reuse** the tool revealed areas for improvement.
- A high count of students who **used the AI again** reflects a strong satisfaction and trust in the tool.
- By analyzing **average session duration** and **prompt counts**, we gained insight into typical engagement behavior.
- Sorting sessions by satisfaction helped us highlight **top-performing use cases**.
- Sessions grouped by discipline revealed which academic fields are **early adopters of AI tools**.

---

## ✅ What I Gained from This Project  

- Strengthened my **SQL skills** through real data exploration and problem-solving  
- Learned how to apply data analysis to **understand user behavior and product performance**  
- Practiced converting raw usage data into **clear, actionable insights**  
- Developed the ability to communicate findings in a way that supports **product improvement and decision-making**
