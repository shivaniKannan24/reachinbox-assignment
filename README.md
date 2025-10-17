# ReachInBox Assignment

The assignment is to build a tool that will parse and check the emails in a Google and Outlook email ID, and
respond to the e-mails based on the context using AI. Use BullMQ as the tasks scheduler
This is a server-based application built with Node.js and Express. It uses various packages such as  `openai` 
for AI functionalities, `googleapis` for Google APIs, and `axios` for HTTP requests and `bullMQ` to process queues.

# technologies used:
- Node.js
- Express.js
- OpenAI
- Google APIs
- Microsoft Graph API
# npm packages used
- dotenv
- Axios
- bullMQ
- google-auth-library
- ioredis
- @microsoft/microsoft-graph-client
- @azure/msal-node

<br>

## Installation setup

1. Navigate to the root directory of the project directory :
```bash 
cd server
```
2. Run `npm install` to install all the dependencies
3. Create a `.env` file in the root directory with the same IDs as specified in the documentation.

## Running the server
1. To start the server, run the following command in your terminal
```bash
npm start
```
*This will start the server at localhost:5000 (or whatever port you have specified).*
or we can use backend deployed link also.

2. To start the worker.js file, run the following command in your terminal
```bash
npm run server
```


## Sample .env sample:
```
PORT = ***
GOOGLE_CLIENT_ID = ***
GOOGLE_CLIENT_SECRET = ***
GOOGLE_REDIRECT_URI = ***
GOOGLE_REFRESH_TOKEN = ***
OPENAI_SECRECT_KEY = ***
redis_port = ***
redis_host = ***
redis_pass = ***
AZURE_CLIENT_ID = ***
AZURE_CLIENT_SECRET = *** 
AZURE_TENANT_ID = ***
```
