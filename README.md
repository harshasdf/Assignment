
## Project Structure

```
micronotes/
├── client/                
│   └── src/
│       └── App.jsx     
├── server/                
│   ├── server.js           
│   └── package.json
├── warmup.js              
├── .gitignore
└── README.md
```

## How to run it

You need **Node.js** installed. Then open two terminals.

### 1. Start the backend (server)

```bash
cd server
npm install
npm run dev
```

The server runs on `http://localhost:5000`.

### 2. Start the frontend (client)

```bash
cd client
npm in  stall
npm run dev
```

Open the URL Vite prints (usually `http://localhost:5173`) in your browser.

## Built with

- [React](https://react.dev/) + [Vite](https://vitejs.dev/)
- [Express](https://expressjs.com/)
- [cors](https://www.npmjs.com/package/cors)

