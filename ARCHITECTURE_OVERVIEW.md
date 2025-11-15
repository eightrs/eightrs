# Eight Rs — High-Level Architecture (Public Version)

This file provides a non-proprietary overview of the Eight Rs system
components on Stellar.

## Components

### 1. Stellar Asset: 8RS
- Created using Stellar's native asset issuance.
- Distributed to users for verified recycling actions.
- Traceable and transparent.

### 2. Soroban Contract Layer
Handles:
- reward distribution rules
- basic validation logic
- permitted actor roles
- issuance controls

(Actual proprietary logic is excluded.)

### 3. Verifier Module (Concept Only)
A separate service validates recycling actions.  
This public version does not describe proprietary mechanisms.

### 4. User & Merchant Dashboard
For:
- users claiming 8RS rewards
- merchants offering redemptions
- recyclers logging materials received

### 5. Marketplace / Redemption System
Allows 8RS holders to hold or redeem tokens for:

- digital currency 
- discounted services
- environmental credits

Fiat bridging is outside public documentation.

## Architecture Diagram

This diagram is intentionally basic to avoid revealing IP
