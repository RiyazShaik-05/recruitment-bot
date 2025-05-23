> **Recruitment** **Bot** **-** **README**

\# Recruitment Bot - README

An AI-powered recruitment assistant that conducts interviews, evaluates
candidates, and adapts

dynamically based on their responses. Built with React, Vite, Tailwind
CSS, Redux, Node.js, and the

OpenAI API.

\## Features

\### Frontend

\- React + Vite + Tailwind CSS for a fast, responsive UI

\- Google OAuth login

\- Redux for state management and authentication

\- Dynamic Interview Chat with AI-powered recruiter

\- Chat history & session storage support

\- Pages: Dashboard, Profile, Settings, Session History, Welcome

\### Backend

\- Express.js API with:

> \- Chat handling and system prompt logic
>
> \- Session persistence
>
> \- Job description management

\- OpenAI API integration for AI-driven Q&A

\- Google OAuth for user login

\- MongoDB for data persistence

\- JWT for secure authentication

\- Error handling for robust interactions

\## Getting Started

\### 1. Clone the Repository

\`\`\`bash

git clone https://github.com/RiyazShaik-05/recruitment-bot.git

cd recruitment-bot

\`\`\`

\### 2. Set Up Environment Variables

Create a \`.env\` file in the \`/backend\` directory and add the
following variables:

\#### \`.env\` in \`/backend\`:

\`\`\`

MONGODB_URI=your_mongodb_connection_string

PORT=your_desired_port_number

GEMINI_API_KEY=your_gemini_api_key

GOOGLE_CLIENT_ID=your_google_client_id

GOOGLE_CLIENT_SECRET=your_google_client_secret

GOOGLE_REDIRECT_URI=your_google_redirect_uri

CLIENT_URI=your_client_uri

JWT_SECRET=your_jwt_secret

\`\`\`


\### 3. Install Dependencies

\`\`\`bash

\# Frontend

cd frontend

npm install

\# Backend

cd ../backend

npm install

\`\`\`

\### 4. Run the Project

\`\`\`bash

\# Terminal 1 (Backend)

cd backend

npm run dev

\# Terminal 2 (Frontend)

cd frontend

npm run dev



\## License

MIT © \[Riyaz Shaik\](https://github.com/RiyazShaik-05)
