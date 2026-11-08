# STAR AI

A responsive, luxury black-and-gold AI assistant workspace for STAR GLOBAL TECH.

## Run locally

Open `index.html` in a modern browser. No build step or package installation is required.

## Connect Gemini

1. Create a Gemini API key in [Google AI Studio](https://aistudio.google.com/app/apikey).
2. Open **Settings & API key** in STAR AI and save the key.
3. Choose Gemini 2.5 Flash or Pro and start chatting.

The key is stored in this browser's local storage and requests are made directly to Google's Gemini API. Do not use a personal API key on a shared or public device. Gemini API access, quotas, model availability, and billing are controlled by Google.

## Included

- Gemini chat with selectable models and mode-specific prompts for writing, coding, study, and translation
- Image creation mode (where the configured Gemini image model is available) and image attachments for multimodal prompts
- Browser speech input and read-aloud controls (browser support and microphone permission required)
- Local conversation history and optional display name
- Responsive mobile/Android-friendly layout
- Founder profile for Jemi Angelin Selvaraj, Founder & CEO of STAR GLOBAL TECH

## Notes

This is a front-end starter and does not include server-side authentication or synced accounts. Display name and conversation history remain in the current browser. For production accounts, shared history, and secure API key management, connect a trusted backend and authentication provider; never put a shared secret in a public static site.
