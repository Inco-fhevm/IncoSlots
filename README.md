# IncoSlots
![IncoSlots](./public/telegram_banner.jpg)

A simple slot machine game running on Telegram. It demonstrates Inco's on-chain randomness and utilizes Privy for embedded wallet creation.
You can test your luck by playing the demo version of the game here:
https://t.me/inco_slots_demo_bot?game=slots

Written with React + Svelte.

# Dependencies
The project uses the following dependencies:

- @privy-io/react-auth for the Privy overlay
- @twa-dev/sdk for Telegram Web API

# How it works
The game is written using two frameworks:
- React for the Privy overlay.
- Svelte for the game UI.

App.tsx is managing state, using Privy hooks, connects to Inco and sends transactions, makes calls to faucet, etc.
SlotMachine.svelte is rendering the game graphics and animations.

# How to run locally
To run the project locally, run the following commands:
```bash
npm install
npm start
```

# How to deploy
This project is deployed on GitHub Pages. To deploy, install github CLI
```bash
npm install -g gh
```
Then run

```bash
npm run deploy
```
