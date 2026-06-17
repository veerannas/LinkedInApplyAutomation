# LinkedIn Apply — AI Job Application Automation

LinkedIn Apply is a Python-based automation system that streamlines the job application process across multiple hiring platforms. It automatically discovers relevant job postings, tailors resumes to each position using offline LLMs (via Ollama), answers application-specific questions with AI, and submits applications at scale — all while keeping personal data local and private. The system supports LinkedIn Easy Apply, Greenhouse, Ashby, and custom application portals.

The tool operates as a full pipeline: it searches for jobs matching configurable criteria, evaluates fit against your profile, generates tailored responses for each application's unique questions, handles multi-page form filling through browser automation, and logs all activity for tracking. By using local LLMs, it ensures no sensitive career data leaves your machine.

## Features & Modules

| Module | Description |
|--------|-------------|
| **Job Discovery** | Automated search across LinkedIn, Greenhouse, Ashby |
| **AI Resume Tailoring** | Per-application resume customization via Ollama |
| **Question Answering** | LLM-powered responses to application-specific questions |
| **Form Automation** | Browser-driven multi-page form completion |
| **Multi-Platform Support** | LinkedIn Easy Apply, Greenhouse, Ashby, custom portals |
| **Fit Scoring** | AI-driven job relevance evaluation before applying |
| **Application Tracking** | Full audit log of submissions and outcomes |
| **Credential Management** | Encrypted local storage for platform credentials |
| **Rate Limiting** | Smart pacing to avoid platform detection |
| **Offline LLM Integration** | Ollama-based inference — no external API calls |

## Tech Stack

- Python
- Selenium / Browser Automation
- Ollama (local LLM inference)
- Multi-platform ATS integration
