# AI-Powered Adaptive Learning Path Generator

## 📌 Overview
This project is an AI-driven adaptive learning system that personalizes educational content based on student performance. It analyzes assessment scores, identifies weak topics, recommends learning resources, and adjusts difficulty using automated workflows.

## 🚀 Features
- Personalized learning plans
- Weak topic detection
- Resource recommendation (videos, articles, quizzes)
- Weekly progress tracking
- Adaptive difficulty adjustment
- Automated email notifications

## 🛠️ Tech Stack
- n8n (workflow automation)
- Google Sheets (data storage)
- Gmail API (notifications)
- JavaScript (logic nodes)

## 📊 Workflow Architecture
1. Read student data
2. Analyze assessment results
3. Detect weak topics
4. Match learning resources
5. Send personalized emails
6. Track weekly progress
7. Adjust difficulty

## 📷 Screenshots
![Workflow]<img width="1600" height="589" alt="image" src="https://github.com/user-attachments/assets/3bde6dd8-4dfb-48ce-b452-11b3a4476e13" />
[AI-Powered Adaptive Learning Path Generator.pdf](https://github.com/user-attachments/files/25396167/AI-Powered.Adaptive.Learning.Path.Generator.pdf)


## ⚙️ Setup Instructions

### 1️⃣ Import Workflow
- Open n8n
- Click Import
- Upload `adaptive-learning-workflow.json`

### 2️⃣ Configure Google Sheets
Create sheets:
- STUDENTS TABLE
- ASSESSMENT RESULTS TABLE
- LEARNING RESOURCES TABLE
- WEEKLY PROGRESS TABLE

### 3️⃣ Connect Gmail
- Add Gmail credentials in n8n
- Allow email permissions

### 4️⃣ Run Workflow
- Trigger manually or schedule

## 🎯 Use Cases
- EdTech platforms
- Personalized tutoring systems
- Student performance monitoring
- Adaptive learning environments

## 📌 Future Enhancements
- AI-generated study plans
- Dashboard analytics
- Chatbot tutor integration
