# Core Architecture

Here’s how Middlemint is structured under the hood:

1\. Middlemint Token (SPL Standard) &#x20;

* Deployed as an SPL token for seamless integration with Solana wallets, DEXs, and apps. &#x20;
* Fully compatible with token swaps, staking contracts, and bridges across the Solana ecosystem.

2\. Payment Engine

* Lightweight smart contracts manage task-based payments, split payments, and automated bounties. &#x20;
* Optional escrow modules allow clients and jobbers to securely lock and release funds based on predefined rules or verified completions.

3\. Payout Dashboard (Coming Soon)

* Web-based interface for DAOs, platforms, and clients to:
* Create and track payments
* Onboard contributors
* Automate milestone-based or recurring payouts

4\. Contributor Identity & Trust Layer (Roadmap Feature)

* Integration with Solana's identity protocols (e.g., Dialect, Civic) &#x20;
* Badging system that rewards reliable contributors with on-chain reputation &#x20;
* Helps clients make trust-based decisions without needing centralized profiles
