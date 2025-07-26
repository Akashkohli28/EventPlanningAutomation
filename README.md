# 🎯 Event Planning Automation using CrewAI

This project automates the process of **event planning** using the [CrewAI](https://docs.crewai.com/) framework. It assigns intelligent agents to handle different aspects of planning — from venue booking to logistics and marketing — and executes tasks using external tools like web scraping and search.

---

## 📌 Features

- 🤖 Multi-agent coordination using CrewAI
- 🔍 Web search and scraping with `SerperDevTool` and `ScrapeWebsiteTool`
- 🏢 Automated venue discovery and booking
- 🍽️ Catering and logistics planning
- 📣 Event promotion and communications
- 📂 Outputs structured reports in JSON and Markdown

---

## 🛠️ Requirements

Install the necessary packages:

```bash
pip install crewai crewai[tools] openai pydantic
