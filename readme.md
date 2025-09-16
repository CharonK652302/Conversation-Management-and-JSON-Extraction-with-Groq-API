# Groq AI/ML Developer Internship Assignment — Conversation Management & Structured Chat Classification

This repository contains the Google Colab notebook for the Groq AI/ML Developer internship assignment.

## Overview

This project implements two core tasks using Groq APIs with OpenAI SDK compatibility:

- **Task 1:** Managing conversation history with summarization and truncation by number of turns and character/word length; periodic summarization after every k-th run.
- **Task 2:** JSON schema classification and information extraction from user chat data (name, email, phone, location, age).

## How to Run

1. Clone the repository or open the notebook directly in Google Colab.
2. Set your Groq API and OpenAI API keys as environment variables in Colab for secure usage:
3. Run each cell sequentially.
4. Observe conversation history management, summarization results, and JSON extraction outputs.

## Dependencies

- Python 3.x
- `openai` (Groq API compatible OpenAI client)
- Standard Python libraries: `re`, `json`

## Repository Contents

- `assignment_notebook.ipynb` — The full Google Colab notebook with Task 1 and Task 2 solutions.
- `README.md` — Project overview and instructions.

## Notes

- The code avoids external frameworks, using only standard Python and Groq API calls.
- API keys are not hardcoded; user must set them in environment variables.
- Outputs demonstrate proper conversation truncation, periodic summarization, and accurate JSON extraction with cleaning and validation.

---

Thank you for reviewing my assignment. I look forward to the opportunity to contribute as an intern at Groq!
