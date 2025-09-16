This project fulfills the Groq AI/ML Developer Internship assignment by implementing two core tasks using the Groq API with OpenAI-compatible SDK:

Task 1: Managing Conversation History with Summarization
Implements a system to maintain and manage a running history of user-assistant conversations. The conversation history is dynamically summarized to ensure conciseness through truncation by number of turns or character/word length. Periodic summarization is performed after every k-th conversation run, replacing the existing history with a condensed summary. The functionality is demonstrated with multiple sample conversations, showing the effects of different truncation settings and k-th run summarization.

Task 2: JSON Schema Classification & Information Extraction
Defines and utilizes a JSON schema to extract structured information including name, email, phone, location, and age from user chats. The extraction leverages Groq API’s OpenAI-compatible function calling feature to produce validated and cleaned JSON outputs. Multiple sample chats are parsed and normalized to ensure consistency and accuracy of the extracted data.

Together, these tasks showcase the ability to effectively handle conversational data, perform summarization, and extract structured information without using external frameworks—fully meeting the assignment requirements.

