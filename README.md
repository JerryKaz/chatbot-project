# Hello Chatbot 🤖

A simple chatbot built with React that responds to basic user commands such as getting today’s date, flipping a coin, and rolling a dice.

<img width="1324" height="943" alt="image" src="https://github.com/user-attachments/assets/fb753ba1-0c61-4f08-a3d2-e79f315b492a" />

## Features 

* Get today’s date
* Flip a coin
* Roll a dice
* Interactive chat interface
* Beginner-friendly React project
* Simple and responsive UI

## Example Conversation 

```txt
hello chatbot

Hello! How can I help you?

can you get me todays date?

Today is September 27

hi

Sorry, I didn't quite understand that. Currently, I only know how to flip a coin, roll a dice, or get today's date. Let me know how I can help!
```

## Built With 

* React
* JavaScript
* CSS

## How It Works 

The chatbot checks user messages for specific keywords and responds accordingly:

* `"today's date"` → returns the current date
* `"flip a coin"` → returns Heads or Tails
* `"roll a dice"` → returns a random number from 1–6

If the chatbot does not recognize the message, it responds with a fallback reply.

## Getting Started 

### 1. Clone the Repository

```bash
git clone <your-repository-link>
```

### 2. Navigate to the Project Folder

```bash
cd chatbot-project
```

### 3. Install Dependencies

```bash
npm install
```

### 4. Start the Development Server

```bash
npm start
```

The app will run locally at:

```txt
http://localhost:3000
```

## Project Structure 📁

```txt
src/
├── components/
├── App.js
├── index.js
├── styles.css
```

## Future Improvements 

* Add AI-powered responses
* Improve chatbot understanding
* Add dark mode
* Add voice support
* Store chat history
* Deploy online

