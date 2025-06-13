# DCIT-313-EXPERT-SYSTEM-PROJECT
Project Overview:

The aim of this project is to develop an expert system that assists users in determining potential health conditions based on their symptoms. The system will ask users a series of questions regarding their symptoms and medical history to suggest possible ailments and recommend whether to consult a healthcare professional.


This project will enable students to apply their knowledge of computing principles to build a practical solution that has real-world applications in healthcare. By developing the Health Symptom Checker, students will enhance their skills in programming, user-centered design, and system analysis, preparing them for future challenges in technology and healthcare.


Learning Outcomes:

Understand the fundamentals of expert systems and knowledge-based systems.
Learn to design and implement a rule-based inference engine.
Develop user interaction skills and a user-friendly interface.
Gain experience in data collection, analysis, and recommendation systems.


Project Components:


1. Requirement Analysis:


Identify the target users (general public, students).

Gather data on common health symptoms and medical conditions.

Define user requirements through surveys or interviews to understand what users expect from a symptom checker.

2. Knowledge Base Development:


Compile a database of common symptoms, associated medical conditions, and recommended actions.

Structure the knowledge base using rules. For example:

IF [symptom = "fever" AND duration = "more than 3 days"] THEN [advice = "Consult a doctor"]


IF [symptom = "cough" AND [symptom = "sore throat" OR symptom = "runny nose"]] THEN [condition = "Common Cold"]


3. User Interface Design:


Create a simple and intuitive user interface where users can:

Input their symptoms.

Answer follow-up questions (e.g., duration of symptoms, severity).

View possible conditions and recommended actions.

4. Inference Engine:


Implement an inference engine to evaluate user input against the rules in the knowledge base.

Choose a reasoning method (e.g., forward chaining) to generate conclusions based on user responses.

5. Symptom Analysis and Recommendations:


Based on the inferred conditions, provide a list of potential health issues with brief descriptions.

Include recommendations indicating when users should seek medical advice.

6. Testing and Validation:


Conduct tests with real-world data scenarios by inputting various symptoms.

Gather user feedback to refine question flow and result accuracy.

7. Documentation:


Prepare user manuals explaining how to use the system.

Document the system architecture, design decisions, and limitations.


Tools and Technologies:


Programming Language: Python (recommended for ease of use) or Java or any other.

Framework: Use a web framework like Flask (for Python) or a Java-based framework for web applications or any other.

Database: Use SQLite or JSON files or any other for storing the knowledge base.

Project Timeline: 4 weeks
