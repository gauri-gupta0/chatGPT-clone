# Simple GPT clone using OPENAI API KEYS and local storage interaction for chats

<img width="1907" height="912" alt="image" src="https://github.com/user-attachments/assets/eacba210-e4a6-4280-92d0-0762ba4a9de5" />

## LIVE DEMO: https://chatgpt-clone-local.onrender.com/

## Features

- **Chat Interface**: Clean, dark-mode UI, making it a complete clone. 
- **Message History**: Saves chat history to local storage.
- **Node.js Backend**: Uses Express to proxy requests to OpenAI, keeping your API key secure.

## Prerequisites

- [Node.js](https://nodejs.org/) installed.
- An [OpenAI API Key](https://platform.openai.com/).

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/gauri-gupta0/chatGPT-clone.git
   cd chatGPT-clone
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Configure Environment:
   - Create a `.env` file in the root directory.
   - Add your OpenAI API key:
     ```
     OPENAI_API_KEY=your_api_key_here
     PORT=3000
     ```

4. Run the Server:
   ```bash
   npm start
   ```

5. Open your browser and navigate to `http://localhost:3000`.

## License

MIT
