FLUX Faucet — Token Faucet on Arc Testnet
A fully on-chain token faucet dApp built on the Arc Testnet. Claim 100 FLUX tokens every 8 hours directly from your browser. Built with vanilla JavaScript and ethers.js — no framework, no build step.
Live Demo · View on Arc Explorer
What It Does
Displays live faucet balance and your personal FLUX balance
Connects to MetaMask or Rabby wallet
Claims 100 FLUX tokens with a single transaction
Enforces an 8-hour cooldown between claims with a live countdown timer
Links every claim transaction to the Arc block explorer
Auto-switches wallet to Arc Testnet if needed
Smart Contracts
FLUX Token
ERC-20 token deployed on Arc Testnet.
Code
FLUX Faucet
Holds tokens and drips 100 FLUX per claim with an 8-hour cooldown.
Code
Solidity
Network Details
Parameter
Value
Network
Arc Testnet
Chain ID
5042002
RPC
https://rpc.testnet.arc.network
Gas token
USDC
Explorer
testnet.arcscan.app
Run Locally
Bash
Open via a local server or deploy to GitHub Pages — wallet connections require HTTPS and won't work from a local file.
Built With
Vanilla HTML, CSS, JavaScript
ethers.js v6 — wallet connection and contract interaction
Remix IDE — contract deployment
Arc Testnet — EVM-compatible L1 with USDC as gas token
Google Fonts — Space Mono + Syne
Made by @mfbololadeyy
