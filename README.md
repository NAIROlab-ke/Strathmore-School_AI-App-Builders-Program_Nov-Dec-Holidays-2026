<div align="center">
<h1> Welcome to the "AI App Builders" Program!</h1>
	
<img width="794" height="1123" alt="Remix — A4 portrait@1x" src="https://github.com/user-attachments/assets/bab1ca71-d61c-4305-96bd-5920b459f8e1" />

<!-- <img width="1393" height="777" alt="NAIROlab co ke" src="https://github.com/user-attachments/assets/5f3004c9-a41f-4924-8a62-15e6bc06f1a2" /> -->

</div>

## About This Course

November/December 2026 Holiday Program for [Strathmore School](https://www.strathmore.ac.ke/) students. A course on building **self-hosted** and **edge** AI apps for typical AI paradigms (e.g. Multimodal, RAG, AI agents) using opensource AI components and stacks.

**This program subscribes to:**

- **Complete setups**
  
  Students get both the finished apps and the full Python code behind it. All the AI models/apps can be run inside a Google Colab session in the cloud.
  
- **Modern AI Paradigms**
  
  Our case studies are guided by practical AI paradigms such as _Retrieval Augmented-Generation (RAG)_, Multimodality, Tool use, Function calling, AI agents, _Model Context Protocol (MCP)_, and Text-to-SQL
  
- **Open-Source, Open-Weights, and DIY Setups**
  
  We emphasize AI components and stacks that are publicly available for download and self-hosting:
  
  - Data Privacy first
  - No API billing
  - No Credit cards
  - No Rate limits  

## Topics

AI App Builders is a hands-on program where students build real AI apps, and discover that what makes a modern AI app useful is usually an AI agent inside it. 

A language model on its own can only predict the next word, so it guesses, sometimes confidently and wrongly. An agent wraps the model in a simple loop: it decides what to do, acts by calling a tool (running Python code, searching documents, querying a database), observes the result, and repeats until it can give an answer it has checked. 

<img src="ai-agents.png">
 
Each app below is that same loop with a different tool: Code fixes date and letter-counting mistakes, document search grounds answers in a handbook, and SQL turns 92 years of World Cup data into charts. 

Students get both the working app and its full code: beginners start by experimenting with the app, while experienced coders extend it. The apps run on small, open models (Qwen3) inside Google Colab, with no paid AI service. That makes their mistakes easier to see, so students learn not just to build AI apps, but when to trust them and how to check their work.

### Reducing LLM hallucination with agentic AI

- Large language models (LLMs) sometimes give confident but wrong answers, especially when they answer straight from the prompt. Smaller, self-hosted models like the Qwen models we'll use do this more often.
- This video shows an AI agent checking its answer by running code instead of guessing.
- [![YouTube Video](https://img.shields.io/badge/YouTube-Watch%20Video-red?style=for-the-badge&logo=youtube)](https://youtu.be/XmSW0WxyhFw) 

  
### Working around a built-in LLM limitation with agentic AI

- LLMs read text as tokens (words or pieces of words), not individual letters.
- So simple tasks like counting the letters in a word can trip them up without some help, especially smaller models.
- This video shows an agent using a tool to get it right.
- [![YouTube Video](https://img.shields.io/badge/YouTube-Watch%20Video-red?style=for-the-badge&logo=youtube)](https://youtu.be/XNNcMLpdb3g)

### Answering questions from your own documents (RAG)

- An LLM only knows what it learned in training. RAG lets it search documents it has never seen, such as a school handbook, before answering.
- This video shows the agent finding the answer in a handbook and quoting its source.
- [![YouTube Video](https://img.shields.io/badge/YouTube-Watch%20Video-red?style=for-the-badge&logo=youtube)](https://youtu.be/sGuqe05esxo)

### Text-to-SQL: an AI data analyst

- An LLM can turn a plain-English question into a database query (SQL). An AI agent goes further: it reads the database's error messages, fixes its own queries, and the app turns the results into charts.
- It still makes mistakes, so the SQL is always shown. Students learn to check the AI's work, not just trust it.
- This video shows the agent analysing 92 years of men's World Cup data.
- [![YouTube Video](https://img.shields.io/badge/YouTube-Watch%20Video-red?style=for-the-badge&logo=youtube)](https://youtu.be/_kUbgBJPulk)


### Multimodality: Helping a vision model with image tools

- A small vision language model (VLM) can make mistakes about what's in an image. External tools, such as an object detector (e.g. YOLO!) and cropping, help it check its own work.
- [![YouTube Video](https://img.shields.io/badge/YouTube-Watch%20Video-red?style=for-the-badge&logo=youtube)](https://youtu.be/-8sPzFp-DHI)
  
<!--
### AI Application Foundations

- We setup and explore the following basic AI Application Workflow

  <img src="basic-ai-app-workflow.png">
  
- Activities

  * Chat
  * _Visual Question Answering (VQA)_
  * Model switching for performance comparison and multimodality
-->
<!--
### C) Classroom / Lab 

- [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/112DSm11HmI3j-Ousy5XHJ-vXQUvWiOah)
  
### D) Outcome

- _"I understand the essential components and structure of a DIY AI application."_
-->
<!--
## Building Custom AI App (Connecting AI to Software)

- We explore a few common use cases e.g.
	
  <img src="streamlit-text2sql.png">

- Activities
	
	* Text-to-SQL
	* Data analysis and Visualization of SQL query results (Charts, Graphs)
-->
<!--
### C) Classroom / Lab

- [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1282oV3I0y7MJoC5g0uhpVZuHcbFNeIbV)

### D) Outcome

- _"I can build a custom frontend to extend AI app usability"_
-->
<!--
## RAG Pipelines (Connecting AI to Knowledge)

- We explore and construct RAG pipelines for documents and images
	
	<img src="doc-img-rag.png">

- Activities
	- Summarize documents (PDFs, Markdown, etc) with an offline engine
	- Offline cross-modal semantic search on a private collection of images
-->  
<!--
### C) Classroom / Lab

- [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1lovtOi-YHYqpTAolaFedJIygIGlErUfa)
  
### D) Outcome
- _"I can build AI apps that can retrieve and analyze **privately** stored information."_
-->
<!--
## AI Agents (Connecting AI to Systems)

- We employ [Qwen-Agent](https://github.com/QwenLM/Qwen-Agent) for a fully edge AI solution capable of tool use, function calling, and MCP
  
  <img src="ai-agents.png">

- Activities
	- Connect/Implement tools e.g. Calculator tool, Weather tool, Web search tool, Home automation tool
<!--
### C) Classroom / Lab

- [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/112DSm11HmI3j-Ousy5XHJ-vXQUvWiOah)
  
  
### D) Outcome
- _"I can automate how AI takes actions and interacts with external systems."_
-->
<!--
Notice this is not yet CrewAI territory.

No need for:

```text
Planner Agent
Research Agent
Writer Agent
Critic Agent
```
-->

## Capstone Projects

<!--
### A) School Sports Activity Planner

- Given a list of sports activities (by a student), the AI agent should be able to recommend a schedule for the week/month based on time of day, weather forecast, facility maintanance schedules, School calender, National calender, etc
    
### B) Fully-Edge Photo Album Assistant

- A **privacy first** and **offline** AI assistant capable of indexing a user's private collection of photos and retrieving them according to cross-modal queries (i.e. text prompts or image semantic searches)


-->
