# Farcaster Frame Engine (v2)

In 2026, decentralized social media platforms like Farcaster are primary layers for user interaction. Frames v2 transforms social feeds into rich, canvas-based mini-dApps that render inside mobile applications like Warpcast. 

This repository provides an production-ready, flat-structured backend engine to build dynamic, interactive Farcaster Frames that validate user inputs and securely interact with the on-chain data ecosystem.

## Core Architecture
- **Ed25519 Message Validation:** Cryptographically verifies incoming payloads using Farcaster Hub RPC nodes to prevent spoofing.
- **Dynamic Meta Tags:** Automatically renders state-dependent UI elements via standard OpenGraph tags conforming to the Frame v2 spec.
- **Gasless Interaction Layer:** Integrates natively with gas abstraction tools for instant on-frame NFT claims or token distributions.
- **Flat Layout:** All routing logic, validation middleware, and asset-handling processes live in the root directory.

## Setup Instructions
1. Install dependencies: `npm install`
2. Configure your Farcaster Hub RPC endpoint in your `.env` file.
3. Start the Frame server: `node frameServer.js`
