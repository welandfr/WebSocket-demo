# WebSocket-demo

A silly (but working) WebSocket demo by Fredrik Welander.

## Start server:
- clone the repo
- create `ws-node/.env` (see .env-example)
- `cd ws-node`
- `npm i`
- `npm run dev`

## Start client:
- Open `ws-frontend`in VSCode
- Run with Live Server extension
- Use the hard coded example token (`my-secret-token`) or set your own token in the Developer Console:    
    `localStorage.setItem('ws_token', 'my-very-secret-token')`

