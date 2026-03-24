# Onyedikachi Ibeakolam – Portfolio

Web3 Product Lead portfolio site, built as a Node.js/Express app for deployment on dAppling or any Node host.

## Quick Start

```bash
npm install
npm start
```

Then open [http://localhost:3000](http://localhost:3000).

## Deploy to dAppling

1. Push this repo to GitHub.
2. Connect your GitHub repo on [dappling.network](https://dappling.network).
3. Set **Framework** to `Node.js`, **Build command** to `npm install`, **Start command** to `node server.js`, **Output/Port** to `3000`.
4. Deploy — dAppling will handle the rest, including IPFS pinning if you choose decentralized hosting.

## Project Structure

```
portfolio/
├── server.js          # Express server
├── package.json
├── .gitignore
└── public/
    ├── index.html     # Main portfolio page
    └── images/
        └── hero.jpg   # Profile photo
```

## Tech

- **Server**: Node.js + Express
- **Frontend**: Vanilla HTML/CSS/JS (no build step needed)
- **Fonts**: Google Fonts (Syne, DM Sans, DM Mono)
