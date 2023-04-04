# Chat Application with ChatEngine and OpenAI Integration

This is a tutorial for building a chat application with ChatEngine and OpenAI integration. The frontend will consist of ChatEngine for our chat application, Redux Toolkit for our state management, Redux Toolkit Query for making api calls, Hero icons for our Icons and React Router for Navigation. For the backend we will be using Node Js as our runtime, Express Js as our backend framework, and OpenAI for Ai integration with our chat. We will be able to talk through our chat application like with ChatGPT.

## Installation

To install the necessary dependencies, follow these steps:

1. Install [Node.js](https://nodejs.org/en/download/) if you haven't already.
2. Install [VS Code](https://code.visualstudio.com/download) or your preferred code editor.
3. Install [npx](https://www.npmjs.com/package/npx) by running the command `npm install -g npx` in your terminal.
4. Install [nodemon](https://github.com/remy/nodemon) by running the command `npm install -g nodemon` in your terminal.
5. Install [Vite](https://vitejs.dev/guide/) by running the command `npm install -g vite` in your terminal.
6. Clone or download the [Chat Application repository](https://github.com/ed-roh/chat-app) and navigate to the project folder in your terminal.
7. Run the command `npm install` to install the dependencies.

## Usage

To run the application, follow these steps:

1. Create a ChatEngine account and create a new project. If you want your project to be hosted free forever, in the Promo Code type 'edward'. You can also upgrade to get more features, but it is not necessary to purchase for it to be hosted forever.
2. Create an OpenAI account and obtain an API key.
3. Create a `.env` file in the root directory of the project and add the following environment variables:

```makefile
CHAT_ENGINE_PROJECT_ID=<your-project-id>
CHAT_ENGINE_PRIVATE_KEY=<your-private-key>
OPENAI_API_KEY=<your-api-key>
```


Replace `your_project_id`, `your_user_name`, `your_user_secret`, and `your_api_key` with your actual values.
4. Run the command `npm run dev` to start the development server. This will start both the backend and frontend servers.

## Resources

- [Node.js](https://nodejs.org/en/download/)
- [VS Code](https://code.visualstudio.com/download)
- [npx](https://www.npmjs.com/package/npx)
- [nodemon](https://github.com/remy/nodemon)
- [Vite](https://vitejs.dev/guide/)
- [React Router](https://reactrouter.com/en/v6.3.0/getting-started)
- [React Dropzone](https://github.com/react-dropzone/react-dropzone)
- [Redux Toolkit](https://redux-toolkit.js.org/introduction/quick-start)
- [Redux Toolkit Query](https://redux-toolkit.js.org/rtk-query/overview)
- [Hero Icons](https://heroicons.com/)
- [dotenv](https://github.com/motdotla/dotenv)
- [ChatEngine Docs](https://chatengine.io/docs/react/v2)
- [ChatEngine Storybook](https://chatengine-io.github.io/react-chat-engine/)
- [ChatEngine API](https://rest.chatengine.io/)
