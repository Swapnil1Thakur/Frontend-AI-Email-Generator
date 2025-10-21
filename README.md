
# Email Writer Assistant  
A Generative AI-powered email automation tool built using Spring Boot and a Chrome Extension, demonstrating practical application of LLMs in everyday workflows.

# Overview
This project showcases my ability to blend software engineering and AI integration, where a browser extension connects to a backend powered by Google Gemini (LLM) to generate intelligent, context-aware Gmail replies in real time.


# Features
1. One-click AI reply in Gmail
2. Integrated with Google Gemini API
3. Spring Boot backend for AI requests
4. Custom tone (professional, friendly, etc.)
5. Real-time email content parsing  

# Tech Stack
**Frontend:** JavaScript, HTML, CSS (Chrome Extension)  
**Backend:** Spring Boot, WebClient (Reactive)  
**AI:** Gemini API  
**Tools:** Maven, GitHub  

# API Example
**POST** `/api/email/generate`
JSON:
{
  "emailContent": "Hi, can you share the report update?",
  "tone": "professional"
}

**Response:** "Sure! Here's a quick update on the report progress..."

## Project Structure

Email-Writer-Assistant/
├── backend/
│   ├── EmailGeneratorController.java
│   ├── EmailGeneratorService.java
│   └── EmailRequest.java
└── extension/
    ├── content.js
    ├── manifest.json
    └── content.css

A simple yet powerful full-stack AI integration — built with Java, Spring Boot & Chrome Extension magic.

# My Learnings: 
1. Gained practical experience integrating LLMs (Gemini API) into real-world applications.
2. Built a full-stack AI product combining frontend (Chrome Extension) and backend (Spring Boot).
3. Learned to design prompt-based workflows for generating dynamic, context-aware responses.
4. Understood API integration, request–response optimization, and data parsing for AI systems.
5. Strengthened skills in modular software design, debugging, and rapid prototyping in ambiguous problem spaces.
6. Explored the fundamentals of agent-style architecture and LLM orchestration concepts (similar to LangChain workflows).

