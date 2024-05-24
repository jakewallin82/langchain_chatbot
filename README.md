## Server

Create a .env file and add the following:

```bash
PORT=5002
OPENAI_API_KEY=YOUR_KEY_HERE

```

Then start the server:

```bash
npm install

npm run dev
```

## Client

Create a .env file and add the following:

```bash
REACT_APP_API_URL=http://localhost:5002/
REACT_APP_BASE_URL=http://localhost:3000/
```

Install dependencies and then start the client:

```bash
npm install

npm run start
```
