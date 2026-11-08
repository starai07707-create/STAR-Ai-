# STAR AI

A responsive, premium black-and-gold AI assistant interface for STAR GLOBAL TECH, built with plain HTML, CSS, and JavaScript.

## Run it

Open `index.html` in a modern browser, or publish the repository with GitHub Pages. No build tools or package installation are needed. A network connection is required to load the optional Google Fonts and contact Gemini.

## Enable Gemini chat

1. Create a Gemini API key in [Google AI Studio](https://aistudio.google.com/app/apikey).
2. Open **Settings & Gemini API** in STAR AI and paste your key.
3. Choose a Gemini model and send a message. The model must be enabled and available for your Google account; access and quotas depend on Google.

**Security:** This is a static front-end. The API key is stored in this browser's local storage and sent directly to Google's Gemini API. Do not use a personal key on a shared device or commit it to source control. For a public production app, move Gemini requests behind a secured backend, add authentication, rate limiting, and server-side secret storage.

## Included in this starter

- Responsive Android/mobile and desktop layouts, with STAR's black-and-gold crown-star identity
- Gemini chat with a model selector and clear API error messages
- AI writing, coding, and beginner-friendly study modes using task-specific instructions
- Local chat history, conversation search, new chat, and response copy/share/feedback actions
- Browser speech input and read-aloud controls where the browser supports them (microphone permission is requested by the browser)
- Settings for a local display name and Gemini API key
- Founder profile for Jemi Angelin Selvaraj, Founder & CEO of STAR GLOBAL TECH

## Scope and next production steps

This is a functional front-end starter, not a complete SaaS backend. Accounts, synchronized history, server-side key management, payments, admin access, image/video generation, and document storage are not implemented. Add those with a trusted backend and explicitly configured providers before advertising them as available. Never expose provider secrets in a public static site.
