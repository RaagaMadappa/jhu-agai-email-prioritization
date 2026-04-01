# Automating Email Prioritization \& Responses with LLMs

**JHU Applied Generative AI | Week 9 Mid-Term Project**



## Overview

This project tackles a real-world enterprise challenge: the cognitive overload of managing a high-volume inbox. Using large language models (LLMs) and structured prompt engineering, the notebook builds an end-to-end pipeline that automatically triages, summarizes, and drafts responses for incoming emails, mimicking the decision-making of a skilled executive assistant.



## Problem Statement

Professionals in fast-paced roles receive hundreds of emails daily. Manually sorting urgent from non-urgent, identifying deadlines, and drafting replies is both time-consuming and error-prone. This project explores how generative AI can automate this workflow reliably and evaluably.



## What's Inside

|Task|Description|
|-|-|
|**Task 1A**|Executive Dashboard — high-level summary of the previous day's inbox|
|**Task 1B**|Urgent Email Detection — surfaces must-act-first emails with reasoning|
|**Task 1C**|Deadline-Driven Email Extraction — flags time-sensitive items needing same-day attention|
|**Task 2**|AI-Generated Draft Replies — auto-composes first-response drafts for critical emails|
|**Task 3**|LLM-as-a-Judge Evaluation — uses a second LLM call to score output quality against defined criteria|
|**Task 4**|Summary \& Recommendations — synthesizes findings and proposes production deployment considerations|



## Key Concepts Demonstrated

* **Prompt Engineering** — zero-shot, few-shot, and structured output prompting
* **LLM Chaining** — multi-step pipelines where one LLM output feeds the next
* **LLM-as-a-Judge** — automated evaluation of generative outputs using evaluation rubrics
* **Email Triage Logic** — urgency vs. priority classification with reasoning traces
* **Applied NLP** — text understanding, summarization, and generation in a business context



## Tech Stack

* Python 3
* OpenAI / LLM API (via course-provided setup)
* Jupyter Notebook (exported as HTML for easy viewing)



## How to View

The notebook is published as a rendered HTML file for easy viewing without any setup:

👉 [**View the Notebook**](https://raagamadappa.github.io/jhu-agai-email-prioritization/JHU_AGAI_W9_Mid_Term_Project_Learners_Notebook.html)

> To view it rendered, clone this repo and open the HTML file in a browser.



## Running the Notebook Locally

If you want to re-run the `.ipynb` version:

```bash
git clone https://github.com/YOUR\_USERNAME/YOUR\_REPO\_NAME.git
cd YOUR\_REPO\_NAME
pip install -r requirements.txt   # if provided
jupyter notebook
```

> You will need to supply your own LLM API key in the LLM Setup section and provide your own data file which would be a csv file with emails.



## Course Context

This project was completed as part of the **Applied Generative AI** program, a collaboration between **Johns Hopkins University (JHU)** and **Great Learning**. The course covers the practical application of LLMs, prompt engineering, RAG, agents, and evaluation frameworks.



## Data

The email dataset used in this project was provided as part of the JHU Applied Generative AI course curriculum and is not redistributed here. To run the notebook, substitute your own email dataset in the same format, or contact Great Learning for course access.



## Disclaimer

This notebook was completed as part of a structured course assignment. Course materials, dataset scaffolding, and the assignment brief are the intellectual property of JHU / Great Learning. The prompt solutions, code implementations, and analysis presented here are my own original work submitted in fulfillment of the course requirements.



## Author

**Raaga** Madappa | AI/ML Professional | [LinkedIn](https://www.linkedin.com/in/raaga-madappa/)

