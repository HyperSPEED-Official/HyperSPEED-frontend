# HyperSPEED-frontend 🚘💨

Welcome to the driver’s seat of **HyperSPEED**, the slickest token launchpad DApp on Hyperliquid EVM. This repo powers the front-end where users race to launch tokens, snag pre-sale allocations, and dive into SPEED-fueled liquidity pools. Built for thrill-seekers and traders, it’s time to shift into high gear!

## What’s HyperSPEED?
HyperSPEED is the go-to platform for token launches on HyperEVM. Powered by the SPEED token, it offers pre-sales, instant liquidity, and a seamless ride—all wrapped in a UI that’s fast, bold, and car-obsessed. This frontend brings the action to life.

## Repo Structure
- `/src/`: The engine bay.
  - `/components/`: Reusable UI parts (e.g., `LaunchButton`, `TokenCard`).
  - `/hooks/`: Custom logic for wallets and contracts (e.g., `useSpeedBalance`).
  - `/pages/`: Key views like Home, Launch, and Token List.
- `/public/`: Static assets (logos, car-themed visuals).
- `/tests/`: Unit tests to keep the ride smooth.
- `package.json`: Dependencies and scripts.

## Getting Started
### Prerequisites
- Node.js (v16+)
- Yarn or npm
- A wallet like MetaMask connected to HyperEVM testnet

### Setup
1. **Clone the repo**:
   ```bash
   git clone https://github.com/0xHyperSPEED/HyperSPEED-frontend.git
   cd HyperSPEED-frontend
   ```
2. **Install dependencies**:
   ```bash
   npm install
   # or
   yarn install
   ```
3. **Configure environment**:
   Copy `.env.example` to `.env` and add:
   ```env
   REACT_APP_HYPEREVM_RPC=<your-testnet-rpc>
   REACT_APP_CONTRACT_ADDRESS=<deployed-launchpad-address>
   ```
4. **Start the DApp**:
   ```bash
   npm start
   # or
   yarn start
   ```
   Opens at `http://localhost:3000`.

### Connecting to Contracts
This frontend talks to `HyperSPEED-contracts`. Deploy those contracts first (see [HyperSPEED-contracts](https://github.com/0xHyperSPEED/HyperSPEED-contracts)), then plug in the addresses to `.env`.

## Contributing
Want to polish the chassis? PRs are welcome! Here’s the track:
1. Fork the repo.
2. Branch out (`git checkout -b feat/turbo-ui`).
3. Commit your upgrades (`git commit -m "Added turbo-charged UI"`).
4. Push it (`git push origin feat/turbo-ui`).
5. Open a PR and show off your horsepower.

Ideas to rev up:
- Sleeker car-themed designs.
- Real-time pool stats.
- Mobile responsiveness.

## Roadmap
- **Q1 2025**: Testnet UI with basic launch/pre-sale flows.
- **Q1 2025**: Mainnet polish—animations, analytics dash.
- **Q1 2025**: Extra gears (e.g., user profiles, leaderboards).

## Need a Tow?
Ping the crew: [@McQueenHL](https://twitter.com/McQueenHL), [@0xSallyHL](https://twitter.com/0xSallyHL), or [@MaterHL](https://twitter.com/MaterHL). Follow [@0xHyperSPEED](https://twitter.com/0xHyperSPEED) for updates. Let’s make this the slickest DApp on HyperEVM!

