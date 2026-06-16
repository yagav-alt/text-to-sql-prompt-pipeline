   Text-to-SQL Prompt Engineering Pipeline

 An automated pipeline using Python and the Google GenAI SDK to convert natural language into production-ready SQL.
 This project demonstrates how to control Large Language Model (LLM) behavior, eliminate hallucinations, and enforce strict enterprise coding standards through engineered system instructions.

   Tech Stack
 AI & LLMs: Google GenAI SDK, Gemini 2.5 Flash
Prompting Techniques: Zero-shot prompting, few-shot prompting, system instructions
Languages: Python, SQL
  
   Core Features
 Strict Syntax Enforcement: Overrides default LLM behavior to enforce specific coding constraints (e.g., mandating the != operator and strictly forbidding the BETWEEN operator).
 Schema Mapping: Injects structured enterprise database schemas directly into system prompts to ensure 100% table and column accuracy.
 Automated Evaluation: Utilizes a Python-based batch testing loop to continuously validate model outputs for structural consistency and constraint adherence.

   About
 Developed by a 3rd-year Artificial Intelligence and Data Science BTech student to demonstrate practical prompt engineering for data management and enterprise systems.
 This version is sharp, technical, and takes exactly 15 seconds to read. Paste this into your repository, update your resume with the bullet points and the GitHub link, and you are ready to confidently submit your application to Zenotalent.# text-to-sql-prompt-pipeline
An automated prompt engineering pipeline using Python and Gemini API to convert natural language into strictly formatted SQL. Designed to enforce syntax constraints and eliminate LLM hallucinations.
