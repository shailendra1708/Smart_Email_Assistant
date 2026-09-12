# Smart Email Assistant

A simple AI-powered email assistant that helps generate email replies based on the message and the tone you want.

I built this project to learn how to connect a React frontend with a Spring Boot backend and use the Gemini API to generate useful, context-aware email responses.

---

## What it does

You paste an email, select the tone you want, and the application generates a reply for you.

For example, you can use it when you need to write a:

- Professional reply
- Friendly response
- Formal email
- Quick follow-up

The goal is to keep the process simple — paste, choose a tone, generate.

---

## Preview

<p align="center">
  <img src="screenshots/email-assistant.png" alt="Smart Email Assistant" width="850">
</p>

---

## How it works

```text
You
 ↓
React Frontend
 ↓
Spring Boot REST API
 ↓
Gemini API
 ↓
Generated Email Reply
