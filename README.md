# CV-to-Email-Job-Application-Workflow
<img width="1372" height="445" alt="image" src="https://github.com/user-attachments/assets/23e180b9-4d84-4e2a-916e-06be5237916f" />
An automated, AI-native workflow built entirely in n8n that dynamically analyzes job postings, scores candidate alignment, logs tracking data into a Google Sheets CRM, and crafts deeply personalized, human-centric application emails.

⚡ Key Features & Architecture
Intelligent Web Scraping (Jina AI): Dynamically extracts raw text and markdown directly from any live target job posting URL submitted via an n8n form.

Structured Parsing (Gemini 1.5 Flash): Analyzes the scraped job description alongside an uploaded CV, generating a clean structured JSON schema that extracts the company name, role title, top 3 matched skills, an overall alignment score, and a tailored "core alignment edge."

Automated Application CRM (Google Sheets): Automatically updates a live spreadsheet tracking system with submission dates, job details, match scores, and specific value propositions for seamless pipeline management.

Context-Aware AI Agent: Utilizes an advanced prompt architecture to draft custom, compelling, and fluid English cover letters. It naturally weaves candidate experience into the team's core pain points while strictly avoiding robotic AI boilerplate or awkward clichés.

HTML Rendering & Multi-Input Merging (Gmail & JavaScript): Uses a native JavaScript node to structure the email layout, leverages a Merge node to safely recombine the generated HTML text stream with the original binary PDF file, and automatically dispatches the application via Gmail.
