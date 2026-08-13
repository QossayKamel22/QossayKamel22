<div align="center">

# Hi, I'm Qossay Kamel 👋

### Software Engineer building modern mobile, web, and AI-powered applications

**Mobile → Web → Backend → AI Agents**

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=QossayKamel22&label=Profile%20Views&color=B22222&style=flat-square)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Qossay%20Kamel-0D1117?style=flat-square&logo=linkedin&logoColor=D4AF37&labelColor=0D1117)](https://www.linkedin.com/in/qossay-kamel-6944a0283)
[![Email](https://img.shields.io/badge/Email-kamelqossay%40gmail.com-0D1117?style=flat-square&logo=gmail&logoColor=B22222&labelColor=0D1117)](mailto:kamelqossay@gmail.com)

</div>

<br/>

## About Me

I'm a Software Engineer focused on building real-world software across mobile, web, and backend — and, increasingly, on the systems that sit on top of them. My core work is in Flutter and React, backed by Python and JVM/Node services, with a growing specialization in AI agents and automation.

I'm actively developing skills in Python and [LangGraph](https://www.langchain.com/langgraph) to build AI agent systems and intelligent, multi-step workflows — not as a side interest, but as the direction the rest of my stack is built to support. I'm not an AI researcher; I'm an engineer applying agentic systems to practical, business-facing problems.

<br/>

## Tech Stack

**Mobile**

![Flutter](https://img.shields.io/badge/Flutter-0D1117?style=for-the-badge&logo=flutter&logoColor=D4AF37&labelColor=0D1117)
![Dart](https://img.shields.io/badge/Dart-0D1117?style=for-the-badge&logo=dart&logoColor=D4AF37&labelColor=0D1117)
![Firebase](https://img.shields.io/badge/Firebase-0D1117?style=for-the-badge&logo=firebase&logoColor=D4AF37&labelColor=0D1117)

**Frontend**

![React](https://img.shields.io/badge/React-0D1117?style=for-the-badge&logo=react&logoColor=FFFFFF&labelColor=0D1117)
![JavaScript](https://img.shields.io/badge/JavaScript-0D1117?style=for-the-badge&logo=javascript&logoColor=FFFFFF&labelColor=0D1117)
![HTML5](https://img.shields.io/badge/HTML5-0D1117?style=for-the-badge&logo=html5&logoColor=FFFFFF&labelColor=0D1117)
![CSS3](https://img.shields.io/badge/CSS3-0D1117?style=for-the-badge&logo=css3&logoColor=FFFFFF&labelColor=0D1117)

**Backend**

![Python](https://img.shields.io/badge/Python-0D1117?style=for-the-badge&logo=python&logoColor=B22222&labelColor=0D1117)
![FastAPI](https://img.shields.io/badge/FastAPI-0D1117?style=for-the-badge&logo=fastapi&logoColor=B22222&labelColor=0D1117)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-0D1117?style=for-the-badge&logo=springboot&logoColor=B22222&labelColor=0D1117)
![Express.js](https://img.shields.io/badge/Express.js-0D1117?style=for-the-badge&logo=express&logoColor=B22222&labelColor=0D1117)
![Java](https://img.shields.io/badge/Java-0D1117?style=for-the-badge&logo=openjdk&logoColor=B22222&labelColor=0D1117)

**AI & Agent Development**

![Python](https://img.shields.io/badge/Python-0D1117?style=for-the-badge&logo=python&logoColor=D4AF37&labelColor=0D1117)
![LangGraph](https://img.shields.io/badge/LangGraph-0D1117?style=for-the-badge&logo=langchain&logoColor=D4AF37&labelColor=0D1117)
![LangChain](https://img.shields.io/badge/LangChain-0D1117?style=for-the-badge&logo=langchain&logoColor=D4AF37&labelColor=0D1117)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-0D1117?style=for-the-badge&logo=postgresql&logoColor=D4AF37&labelColor=0D1117)

**Tools & Platforms**

![Git](https://img.shields.io/badge/Git-0D1117?style=for-the-badge&logo=git&logoColor=FFFFFF&labelColor=0D1117)
![GitHub](https://img.shields.io/badge/GitHub-0D1117?style=for-the-badge&logo=github&logoColor=FFFFFF&labelColor=0D1117)
![Figma](https://img.shields.io/badge/Figma-0D1117?style=for-the-badge&logo=figma&logoColor=FFFFFF&labelColor=0D1117)
![VS Code](https://img.shields.io/badge/VS%20Code-0D1117?style=for-the-badge&logo=visualstudiocode&logoColor=FFFFFF&labelColor=0D1117)

<br/>

## AI & Agent Development

This is the direction the rest of my stack is converging on: Flutter and React give me the product surface, Python and backend engineering give me the systems layer, and LangGraph is where I'm building the reasoning layer on top of both.

Concretely, I'm exploring and building with:

- AI agents and multi-step, tool-calling workflows
- LangGraph for stateful, graph-based agent orchestration
- LLM-based application logic and structured decision-making
- Memory and context handling across agent steps
- Automation of real, operational business processes

The clearest evidence of this is **POS Agent** (below) — a real-time monitoring system where an agent-based detection layer, built on LangGraph and a Python/FastAPI backend, is the core of the product rather than an add-on.

<br/>

## Featured Projects

### 🤖 POS Agent — Restaurant Live Monitoring Layer
An operational monitoring system for restaurants: it reads a branch's live POS data, detects deviations from that branch's own baseline using a statistical (not ML) detection layer, and routes alerts to the responsible manager through a LangGraph-based alert lifecycle — while there is still time to act. Backed by 90+ architecture decisions and a full requirements/spec trail; backend, detection engine, and Flutter client are in active development.

**Tech:** Python · FastAPI · LangGraph · PostgreSQL · SQLAlchemy · Alembic · Flutter (client) · Docker
**Repository:** [`QossayKamel22/POS_Agent`](https://github.com/QossayKamel22/POS_Agent) *(private — available on request)*

---

### 🧩 Draggable Widget Dashboard
A client-only React SPA that composes a dashboard from reorderable Clock and Note widgets, with layout and content persisted across refreshes. The project's defining engineering constraint is render isolation — a Clock's per-second tick re-renders only that Clock, never a sibling — solved through deliberate state ownership rather than blanket memoization, documented in a full architecture write-up with ADRs.

**Tech:** React · TypeScript (strict) · Vite · @dnd-kit/sortable
**Repository:** [`QossayKamel22/Task`](https://github.com/QossayKamel22/Task)

---

### 📱 QossayApp — E-Commerce Mobile App
A Flutter-based e-commerce mobile application.

**Tech:** Flutter · Dart
**Repository:** [`QossayKamel22/QossayApp`](https://github.com/QossayKamel22/QossayApp)

<br/>

## Currently Building

Right now I'm splitting my time between an AI agent system built on Python and LangGraph, Flutter mobile applications, and full-stack web products — with a growing focus on automation and AI-powered business tools. The common thread is scalable architecture: systems designed to hold up as the logic and the traffic both grow, not just to work in a demo.

<br/>

## Engineering Interests

`Mobile Development` `Full-Stack Development` `Backend Engineering` `Artificial Intelligence` `AI Agents` `Agentic Workflows` `Automation` `Software Architecture` `Product Development`

<br/>

## GitHub Stats

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=QossayKamel22&show_icons=true&hide_border=true&bg_color=0D1117&title_color=D4AF37&icon_color=B22222&text_color=FFFFFF&ring_color=B22222" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=QossayKamel22&layout=compact&hide_border=true&bg_color=0D1117&title_color=D4AF37&text_color=FFFFFF" />

</div>

<br/>

## Connect With Me

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0D1117?style=for-the-badge&logo=linkedin&logoColor=D4AF37&labelColor=0D1117)](https://www.linkedin.com/in/qossay-kamel-6944a0283)
[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-0D1117?style=for-the-badge&logo=todoist&logoColor=B22222&labelColor=0D1117)](YOUR_PORTFOLIO_URL)
[![Email](https://img.shields.io/badge/Email-Contact-0D1117?style=for-the-badge&logo=gmail&logoColor=D4AF37&labelColor=0D1117)](mailto:kamelqossay@gmail.com)

</div>

