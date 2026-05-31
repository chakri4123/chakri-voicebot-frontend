# Chakri Voice Bot Frontend

Frontend application for the Chakradhar AI Voice Bot built for the 100x AI Engineer Stage 1 Assessment.

## Live Demo

Voice Bot:

https://chakri-voicebot-frontend.vercel.app

Backend API:

https://chakri-voicebot-backend.onrender.com

## Overview

This project is a browser-based AI voice bot that represents Boda Chakradhar Goud and answers questions as he would.

The application supports:

- Voice Input (Speech Recognition)
- Voice Output (Speech Synthesis)
- Text Chat
- Animated AI Avatar
- Personalized AI Responses
- Responsive Web Interface

The frontend communicates with a FastAPI backend powered by Google's Gemini model.

## Features

- Conversational AI experience
- Speech-to-Text using Web Speech API
- Text-to-Speech using Browser Speech Synthesis
- Interactive animated avatar
- Personalized responses based on candidate profile
- Mobile and desktop compatible
- No API key required from users

## Technologies Used

- HTML5
- CSS3
- JavaScript
- Web Speech API
- Speech Synthesis API
- Gemini API (via backend)
- Vercel

## Project Structure

```text
frontend/
│
└── index.html
```

## How It Works

```text
User Voice/Input
        │
        ▼
Frontend (Vercel)
        │
        ▼
FastAPI Backend (Render)
        │
        ▼
Google Gemini
        │
        ▼
Frontend Response
        │
        ▼
Voice + Text Output
```

## Local Setup

Clone Repository:

```bash
git clone https://github.com/chakri4123/chakri-voicebot-frontend.git
```

Open:

```text
index.html
```

in a browser.

## Deployment

Frontend is deployed using Vercel.

Production URL:

https://chakri-voicebot-frontend.vercel.app

## Backend Repository

Backend GitHub:

https://github.com/chakri4123/chakri-voicebot-backend

Backend API:

https://chakri-voicebot-backend.onrender.com

## Assessment Objective

This project was developed as part of the 100x AI Engineer Stage 1 Assessment.

The goal was to create a voice-enabled AI chatbot capable of answering interview questions as the candidate would respond.

## Author

Boda Chakradhar Goud

- IIT ISM Dhanbad
- B.Tech Electronics and Communication Engineering
- AIR 8304, JEE Advanced

## Sample Questions

- What should we know about your life story?
- What's your #1 superpower?
- What are the top 3 areas you'd like to grow in?
- What misconception do your coworkers have about you?
- How do you push your boundaries and limits?
