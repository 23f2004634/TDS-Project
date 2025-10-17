---
title: TDS LLM Code Deployment
emoji: 🚀
colorFrom: blue
colorTo: purple
sdk: docker
pinned: false
---

# TDS LLM Code Deployment API

This is a FastAPI application that automatically builds and deploys code using LLMs.

## Features
- Accepts task requests via POST `/api-endpoint`
- Generates code using Google Gemini AI
- Creates GitHub repositories automatically
- Deploys to GitHub Pages
- Notifies evaluation servers

## API Endpoint

POST `/api-endpoint`

Send JSON with: email, secret, task, round, nonce, brief, checks, evaluation_url, attachments

## Setup
Environment variables are configured in Hugging Face Spaces Settings.
