# Solana Freeze Bundler

Solana Freeze Bundler is a script that deploys a token on the Solana blockchain. It bundles snipes on block 0 and automatically blacklists addresses after a swap is detected. 

It will only allow the initial snipes to sell, while any other address will be frozen.


This can be useful for managing token security and preventing malicious activities.

**TELEGRAM** for contact & **POC**(Proof of Concept): [@benoriz0](https://t.me/benoriz0)


**Other tools**
- [Solana Volume Bot](https://github.com/bigmovers/solana-volume-bot)
- [Solana JITO Bundler](https://github.com/bigmovers/solana-bundle)
- [Pump.Fun Bundler(25 buys)](https://github.com/bigmovers/pumpfun-bundler)
- [Buyers/Holders Maker](https://github.com/bigmovers/solana-maker)
- [Sniper for New Pairs with Filters](https://github.com/bigmovers/solana-sniper-bot)
- Non-JITO Bundler(3 buys)
- LP Manager
- Telegram Cloner




## Features

- Deploy a token on Solana.
- Bundle snipes on block 0.
- Automatically blacklist addresses after a swap is detected.

## Prerequisites

- RPC
- Node.js and npm installed.


## Installation

1. **Get the script from https://t.me/benoriz0**


5. **Install Node.js and npm:**

    Follow the instructions from the [Node.js website](https://nodejs.org/) to install Node.js and npm.

## Configuration

1. **Edit `config.ts`:**

    Open the `config.ts` file and configure deployer & funder wallet + RPC


## Usage

1. **Deploy the token:**

    ```bash
    npm run start
    ```

    The script will deploy the token on the Solana blockchain with the preconfigured options, bundle snipes on block 0, and monitor for swaps to blacklist addresses automatically.

## Disclaimer

This script is intended for educational purposes only. Deploying tokens and managing blacklists can have legal and ethical implications. Use this script responsibly and at your own risk.


## Contact

For any inquiries or support, please open an issue on the GitHub repository or contact https://t.me/benoriz0
