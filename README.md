# AI System Design Interviewer

Mock system design interviews powered by Gemini AI. Get grilled by a senior engineer, watch your architecture diagram auto-draw, and receive a scorecard at the end.
   
## Features

- Conversational AI interviewer that pushes back on vague answers
- Live whiteboard that auto-generates as you describe components
- Final scorecard across 5 dimensions: Requirements, Scalability, Reliability, Tech Choices, Communication
- 8 built-in topics + custom topic input 

## Topics

Design Twitter, YouTube, Uber, URL shortener, WhatsApp, Google Drive, rate limiter, Netflix CDN — or type your own.

## Stack

- React + Vite
- Gemini 1.5 Flash (free tier)
- SVG canvas for whiteboard
- No backend required

## Setup

```bash
git clone https://github.com/YOUR_USERNAME/ai-system-design-interviewer
cd ai-system-design-interviewer
npm install
npm run dev
```



Enter your Gemini API key in the app (stored in localStorage, never sent anywhere except Google).

Get a free key at [aistudio.google.com](https://aistudio.google.com/app/apikey).

## How it works

1. Pick a system design topic
2. The AI plays a senior engineer and interviews you
3. As you describe components, the whiteboard auto-updates
4. Say "done" or click "Request score" to get your scorecard

## License

MIT
