Interactive AI-Powered Resume
This project is a single-page, interactive resume designed to showcase professional experience in a more engaging and modern way than a traditional PDF. It was built to demonstrate not just a list of skills, but also an understanding of product design, user experience, and the practical application of modern AI tools.

✨ Key Features
AI-Enhanced Storytelling: The core feature is an AI chatbot, or "AI clone," trained on the user's professional background, projects, and experience. This allows recruiters and visitors to ask specific questions and get immediate, context-aware answers.

Multi-Format Delivery: Recognizing that people consume information differently, the resume is accessible in multiple formats:

Read: A clean, scannable web page.

Listen: An audio summary of the professional profile, generated on-the-fly using Text-to-Speech (TTS).

Download: A traditional PDF version for offline viewing or HR systems.

Vibe-Coded Proof of Work: The page itself acts as a portfolio piece. By building and deploying this interactive experience, it demonstrates an awareness of modern web technologies and AI APIs.

🛠️ How to Customize
This project is built with vanilla HTML, Tailwind CSS, and JavaScript, making it easy to modify.

1. Editing Page Content
All text content (name, job titles, experience, etc.) can be edited directly in the index.html file. The structure is semantic and clearly commented.

2. Updating the AI Chatbot's Knowledge
The "brain" of the AI chatbot is a systemPrompt variable within the <script> tag at the bottom of the index.html file. To customize the chatbot's knowledge:

Navigate to the <script> section.

Find the systemPrompt constant.

Inside the backticks (``), you'll find a section marked --- START OF KNOWLEDGE BASE ---.

You can add any text you want the AI to know, such as detailed project descriptions, your product philosophy, answers to common interview questions, etc. This is a simple and secure alternative to a database or live file integration.

3. Changing the Audio Voice
The "Listen to my CV" feature uses the Gemini API for Text-to-Speech. You can change the voice by modifying the prebuiltVoiceConfig in the generateAndPlayAudio function. A list of available voices can be found in the API documentation.

🚀 Technologies Used
Frontend: HTML, Tailwind CSS

JavaScript: Vanilla JS for interactivity and API calls.

AI & APIs:

Google Gemini API (Generative AI): Powers the conversational chatbot.

Google Gemini API (TTS): Powers the text-to-speech audio resume.
