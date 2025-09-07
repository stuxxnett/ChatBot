# ChatBot
# ChatBot with Gemini API

A simple Node.js + Express chatbot that integrates with Google Gemini API. The project serves a frontend (`public/index.html`) and connects to the Gemini model for AI responses.

---

## Features

* Chat with AI (Gemini) from a web interface
* Node.js + Express backend
* Environment variables for API key security
* Easy to set up and run locally

---

## Prerequisites

* [Node.js](https://nodejs.org/) installed (v16+)
* A [Gemini API key](https://ai.google.dev/)

---

## Installation

1. Clone this repo

```bash
git clone https://github.com/stuxxnett/ChatBot.git
cd ChatBot
```

2. Install dependencies

```bash
npm install
```

3. Create a `.env` file in the root folder and add your Gemini key:

```
GEMINI_API_KEY=your_api_key_here
```

4. Create a `.gitignore` file (if you don't have one) and add:

```
node_modules/
.env
```

5. Run the server

```bash
node server.js
```

Server will start on [http://localhost:3000](http://localhost:3000).

---

## Project Structure

```
ChatBot/
├── public/           # Frontend files (index.html, CSS, JS)
├── server.js         # Express server
├── package.json      # Dependencies
├── .gitignore        # Ignored files
└── README.md         # Project docs
```

---

## Usage

* Open [http://localhost:3000](http://localhost:3000) in browser
* Type a message in the chat box
* Get AI-powered responses from Gemini

---

## Notes

* Never commit your `.env` file (it contains your API key)
* `node_modules/` is excluded via `.gitignore`, run `npm install` to install dependencies
