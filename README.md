---
NOTE : THE PPT (PDF) WHICH IS UPLOADED IN THE GOOGLE FORMS IS MY OLD ONE THE PPT WHICH I ULOADED HERE IS UPDATED ONE AND THIS THE FINAL PROJECT. KINDLY GO THROUGH THIS PDF ATTACHED IN THE REPO 
---
# 🧠 Agentic Career Counsellor

An intelligent AI-powered agent that helps students make informed, personalized, and future-ready career decisions by analyzing their interests, academic background, and real-time labor market trends. Built using IBM Watsonx.ai, this project fulfills the challenge outlined in Problem Statement No. 15 – Agentic Career Counseling Companion under the IBM Internship Program.

---

## 📌 Problem Statement

Students often face challenges in choosing the right career path due to fragmented access to guidance, lack of self-awareness about academic strengths, and rapidly evolving industry demands.

Traditional counseling methods:
- Lack personalization  
- Are not scalable  
- Miss dynamic labor trends  

> Goal: Build an autonomous, intelligent agent that provides tailored career pathway suggestions with minimal manual intervention.

---

## 🚀 Solution Overview

The **Agentic Career Counsellor** is an AI agent developed using **IBM Watsonx.ai**'s Prompt Lab. It is grounded on expert-provided knowledge and fine-tuned prompts to assess students' interests and academic strengths to recommend relevant, future-proof career paths.

**Key Features:**
- Conversational and interactive AI assistant
- Grounded with domain knowledge using vector index documents
- Uses IBM Foundation Models (Granite / LLaMA)
- Trained to ask context-aware questions
- Returns career suggestions based on responses and document grounding

---

## 🧰 Technologies Used

| Technology           | Purpose                                  |
|----------------------|------------------------------------------|
| IBM Watsonx.ai       | Foundation model inferencing and agent lab |
| Prompt Lab           | Prompt engineering & testing             |
| IBM Granite / LLaMA  | Language model for intelligent response  |
| Vector Store         | Grounding with `Career_Guidance_Professional.txt` |
| GitHub               | Version control & deployment             |


---
API KEY FOR THE PROJECT - CehB0B-WNRO9rpulDPYJ2wE5rjNI6bydmNLj51Aopx8I
---
## 🧠 How It Works

1. **User Input Collection:** The AI prompts the student with 4 structured questions:
   - What subjects do you enjoy the most?
   - Do you prefer working with people, data, machines, or ideas?
   - What is your academic background?
   - Are there any industries you're curious about?

2. **Knowledge Grounding:** The agent refers to the uploaded `.txt` document (Career_Guidance_Professional.txt) that contains expert career guidance data.

3. **Model Inference:** Based on responses, the model suggests 3 best-fit careers, explains why, and gives next actionable steps.


---

## ✨ Unique Features

- Semantic understanding of user responses
- Domain-grounded via vector-indexed career document
- Scalable and adaptable to multiple users
- Personalized and context-sensitive guidance
- Optional integration with external APIs and custom tools
- Recommends learning paths and next steps

---

## 👨‍🎓 Target Users

- High school students exploring career options
- Undergraduate or postgraduate students planning specializations
- Academic counselors and coaching institutions
- Career mentoring platforms

---

## ✅ How to Run Locally (Notebook)

> Ensure you have access to Watsonx.ai and the correct project environment setup.

1. Open the IBM Watsonx project
2. Go to the notebook interface
4. Upload the document `Career_Guidance_Professional.txt`
5. Run the notebook 
6. api key - CehB0B-WNRO9rpulDPYJ2wE5rjNI6bydmNLj51Aopx8I
---

## 🧩 Future Scope

- Expand to multilingual support using IBM Language Translator
- Connect with real-time labor market APIs
- Add student performance tracking & dashboards
- Enable voice-based interaction

---

## 📄 License

This project is licensed under the [IBM ILAN License](https://www.ibm.com/legal/licenses).

---

## Acknowledgments

- IBM Watsonx.ai team
- IBM Internship Challenge 2025 – Problem Statement No. 15
- Mentors and evaluators who guided the project
- OpenAI for prompt guidance and knowledge base support
