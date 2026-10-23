# AgentPay AI 🤖💸

> **Autonomous Financial Agent & Cross-Chain Intent Executor on NEAR Protocol**

### 🌐 [👉 Click Here to Launch Live Interactive Dashboard Demo](https://karen10kazemi.github.io/agentpay-ai/)

---

## Overview
**AgentPay AI** is an autonomous financial agent designed for the agent economy on NEAR. It enables users and DAOs to define strict human constraints (daily spending caps, slippage limits, and whitelisted chains) inside a Confidential Execution Environment (TEE), allowing AI agents to securely handle recurring expenses, team payroll, and 1-Click cross-chain swaps without manual intervention.

## Key Architecture & NEAR Tools Used
1. **Human-Defined Constraints (TEE Guard):** Users set financial limits (e.g., `$15,000/day` autonomous cap) verified inside **NEAR AI Cloud**'s Trusted Execution Environment before any signature is generated.
2. **Autonomous Intent Execution:** Converts natural language financial commands (e.g., *"Swap 4.3 ETH to USDC with <0.3% slippage"*) into structured **NEAR Intents** payloads.
3. **Cross-Chain Settlement:** Powered by **Chain Signatures (MPC)** and the **1-Click Swap SDK** for instant, optimal routing across NEAR, Ethereum, and Base.

## Repository Structure
- `index.html` — Interactive Command Center & Live TEE Execution Terminal UI
- `src/agent.js` — Core `AgentPayAI` class implementing TEE constraint verification and NEAR Intent broadcasting
- `package.json` — NEAR JS SDK dependencies and agent runtime scripts

## How to Test / Run
1. **Live Web Prototype:** Open the [Live Dashboard Demo](https://karen10kazemi.github.io/agentpay-ai/) directly in your browser.
2. **Local CLI Execution:**
   ```bash
   git clone [https://github.com/karen10kazemi/agentpay-ai.git](https://github.com/karen10kazemi/agentpay-ai.git)
   cd agentpay-ai
   npm install
   npm run start-agent
