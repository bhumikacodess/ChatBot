# Chatbot Project

A simple chatbot built with React. It can only answer a small set of pre-programmed
questions, using the `supersimpledev` Chatbot API to simulate responses — it's not
connected to a real AI model.

I built this while following supersimpledev's React course. Through this project
I learned the fundamentals of React, including useState, useRef, useEffect, and
how async functions work.

## Features
- Send messages and get a response from the chatbot
- Custom responses added on top of the default set (e.g. "goodbye")
- Chat history persisted with localStorage — messages survive a page refresh
- Loading indicator while waiting for a response
- Clear chat history
- Timestamps on messages

## Tech stack
- React
- Vite
- dayjs (for timestamps)
- supersimpledev (chatbot response simulation)

## Live Demo

https://bhumikacodess.github.io/ChatBot/

## Running locally
\`\`\`bash
npm install
npm run dev
\`\`\`
