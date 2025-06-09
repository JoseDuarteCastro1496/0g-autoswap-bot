# 0gLabs Testnet Auto Swap BOT

![alt text](<images.png>)
Effortlessly automate your token swaps on the 0g Gallieo Testnet with this script—no more manual transactions needed! Leveraging the power of Zer0DEX, all swaps are executed seamlessly and efficiently, giving you a hassle-free experience while maximizing your testnet activities.

## Features

- 24/7 Non-stop automated token swaps
- Automatic faucet claiming for testnet tokens
- Automatic transaction pushing to 0glab testnet
- Multi-wallet support (multiple private keys separated by comma)
- Asset recovery system for insufficient swap balances
- Integration with Zer0 DEX router for token swaps
- Supports multiple tokens
- More features coming soon!

## Installation

1. Clone the repository:
```bash
git clone https://github.com/lokie99/0g-autoswap-bot.git
cd 0g-autoswap-bot
```

2. Install dependencies:
```bash
npm install
```

3. Configure environment variables:
   - Create a `.env` file in the root directory
   - Add your wallet private key:
```bash
PRIVATE_KEY=YOUR_PRIVATE_KEY_HERE
```

4. Run the script:
```bash
node index.js
```

## Security Notice

- Never share your private key with anyone
- Keep your `.env` file secure and never commit it to version control
- Always verify transaction details before executing swaps

## Disclaimer

This is an unofficial tool. Use at your own risk. Always verify transactions before confirming them.
