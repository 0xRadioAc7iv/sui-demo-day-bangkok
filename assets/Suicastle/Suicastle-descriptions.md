<div align="center">
  <img src="logo.png" alt="SuiCastle Logo" width="200"/>
  
  [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
  [![Sui](https://img.shields.io/badge/Sui-Network-blue)](https://sui.io/)
  [![Next.js](https://img.shields.io/badge/Next.js-14-black)](https://nextjs.org/)
</div>

## 📝 Overview

The initial concept for Suicastle is to leverage zklogin, with sponsorship from Enoki, and build on the Sui network. Our goal is to address the challenges of Web3 game adoption. The game is hosted on Telegram, making it as user-friendly as a typical Web2 game. This approach encourages more people to try out the game without needing complicated setups.

The in-game assets are diverse, allowing users to own various items, such as knights, heroes with special abilities, and unique characters. These items make the game more engaging and offer players different strategies to explore. Players can develop a strong attachment to their game characters. All digital assets are securely recorded using blockchain technology, ensuring true ownership and providing opportunities for players to trade or upgrade their items in the future.

## 🚀 Technologies Used

### Frontend

- **Next.js 14**
- **TypeScript** - Typed JavaScript
- **Tailwind CSS** - Utility-first CSS framework
- **@mysten/dapp-kit** - Sui wallet integration
- **@tanstack/react-query** - Powerful asynchronous state management

### Blockchain

- **Sui Network** - Layer 1 blockchain
- **Sui Move** - Smart contract moveVM on Sui
- **Enoki** - Sui SDK
- **zkLogin** - Social login for web2 users

### Game Engine

- **Unity** - Game engine
- **React Unity WebGL** - Unity integration with React

## 🛠 Installation

1. Clone repository:

```bash
git clone https://github.com/phapdev/Suicastle.git
cd suicastle
```

2. Install dependencies:

```bash
npm install
```

3. Create environment file:

```bash
cp .env.local.template .env.local
```

4. Run development server:

```bash
npm run dev
```

## 🏗 Project Structure

```
├── app/                    # Next.js app router
├── components/             # React components
├── contexts/               # React contexts
├── lib/                    # Utility functions
├── types/                  # TypeScript types
└── public/                 # Static assets
```

## 🔐 Smart Contracts

The project uses Move Language to write smart contracts on the Sui Network. Contracts are located in the [Suicastle-Contract](https://github.com/phapdev/Suicastle-Contract) repository.

## 🌐 Environments

The project supports:

- Devnet

## 🎮 Game

The game is built with Unity and React Unity WebGL. The project is located in the [Suicastle-Game](https://github.com/orp1205/Sui-CastleUnity) repository.

## 📁 Github Repositories

- [Suicastle](https://github.com/phapdev/Suicastle)
- [Suicastle-Contract](https://github.com/phapdev/Suicastle-Contract)
- [Suicastle-Game](https://github.com/orp1205/Sui-CastleUnity)

## 📄 License

This project is distributed under the MIT License. See `LICENSE` file for more information.

## 🤖 Telegram bot

- Telegram bot: [@suicastle_bot](http://t.me/SuiCastle_bot)

## 🧑‍💻 Team Members:

- Project Manager: [@phapdev](https://github.com/phapdev)
- Game Developer: [@orp1205](https://github.com/orp1205)
- Blockchain Developer: [@0xboji](https://github.com/0xboji)
- Full Stack Developer: [@tranvanhai0504](https://github.com/0xboji)

---
<div align="center">
Made with ❤️ by
<a href="https://t.me/+ecU5JlgcojxkOWQ1">SuiCastle Team</a>
</div>
