Webhook Trigger

Receives queries from students (via form, website, or chatbot).

AI Agent

Introduces itself as “Hello, I am the AI Admission Assistant of Shambhunath Institute of Engineering and Technology, Prayagraj.”

Uses a LangChain-powered agent connected to OpenRouter LLM.

Answers only from data stored in the Google Sheet.

If the requested information isn’t available, politely redirects to the admission team.

Data Source (Google Sheets Integration)

Reads course details, fee structure, eligibility, scholarships, facilities, placements, deadlines, and contact details.

Ensures responses are always accurate and up to date.

Calendar Integration

Can create and manage events (e.g., admission counseling sessions, deadlines) in Google Calendar.

Memory System

Remembers conversation context during interaction, allowing follow-up questions.

Response Handling

Sends back a clear and student-friendly reply through the webhook.

🔹 Guidelines Built Into the Agent:

Always polite, professional, and easy to understand.

Gives step-by-step answers for clarity.

Encourages students to ask more questions.

Never makes up details beyond what’s in the sheet
