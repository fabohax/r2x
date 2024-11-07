# REX: Peer-to-Peer (P2P) and Face-to-Face (F2F) Cryptocurrency Trading Platform

Welcome to the REX project repository! This repository contains the **web application** of REX, built with **Next.js**. REX is a decentralized, reputational exchange platform focused on peer-to-peer (P2P) and face-to-face (F2F) trading, allowing users to buy and sell cryptocurrency/fiat seamlessly with minimal barriers.

## Features

- **P2P Trading**: Connect directly with other users to buy or sell cryptocurrency without intermediaries.
- **F2F (Face-to-Face) Trading**: Arrange secure meetups to exchange fiat for crypto in person.
- **Reputational Exchange System**: Builds trust with a decentralized reputation model based on successful transactions and user feedback.
- **Tokenized Rewards**: Earn REX tokens as rewards for successful trades, boosting engagement and user loyalty.
- **Multi-Wallet Integration**: Supports popular wallets (MetaMask, Phantom, WalletConnect, etc.) for seamless connectivity and ease of use.
- **KYC-Free**: No KYC or signup required for users, ensuring a smooth and private onboarding experience.
- **Automated Trade Recommendations**: AI-driven system that suggests optimal trading opportunities based on market rates, location, and user preferences.
- **Governance via REXDAO**: Community-driven governance model using a DAO structure, allowing users to participate in platform decisions.

## Table of Contents

1. [Getting Started](#getting-started)
2. [Installation](#installation)
3. [Environment Variables](#environment-variables)
4. [Usage](#usage)
5. [Project Structure](#project-structure)
6. [Contributing](#contributing)
7. [License](#license)

## Getting Started

To get started with the REX web app, make sure you have **Node.js** and **npm** installed.

This application is built with **Next.js** for server-rendered React applications. It allows users to connect their wallets, arrange P2P/F2F transactions, view trade histories, and manage their profiles.

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/fabohax/r2x.git
   cd r2x
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Set up environment variables (see [Environment Variables](#environment-variables) section below).

4. Run the development server:
   ```bash
   npm run dev
   ```

5. Open [http://localhost:3000](http://localhost:3000) in your browser to view the app.

## Environment Variables

Create a `.env.local` file in the root directory and add the following environment variables:

```plaintext
NEXT_PUBLIC_API_URL=<Your API URL>
NEXT_PUBLIC_APP_NAME=REX
NEXT_PUBLIC_REX_TOKEN_ADDRESS=<Your REX Token Contract Address>
NEXT_PUBLIC_REXDAO_API=<REXDAO API URL>
NEXT_PUBLIC_MAPS_API_KEY=<API Key for map service (for F2F meetups)>
```

> **Note**: Ensure that the API keys and addresses are correctly configured to enable full functionality, including wallet connectivity and F2F trading location services.

## Usage

- **Wallet Connection**: Users can connect with MetaMask, WalletConnect, or other supported wallets to trade crypto directly.
- **P2P/F2F Trading**: Users can initiate P2P trades with other users online or agree to F2F meetups at a safe, agreed location.
- **Reputation and Rewards**: Each completed trade affects user reputation and rewards in REX tokens, enabling higher trust scores and rewards for active traders.
- **Governance**: Token holders can participate in the DAO for decisions on platform changes and improvements.

## Project Structure

- `/pages`: Contains the main pages of the application, like `index.js` for the homepage and other route pages.
- `/components`: Contains reusable components like trade listings, wallet connectors, and user profiles.
- `/lib`: Contains helper functions, API wrappers, and other utility functions.
- `/public`: Public assets, including images and icons.
- `/styles`: CSS and style modules for custom styling.

## Contributing

We welcome contributions from the community! To contribute:

1. Fork the repository and create a new branch.
2. Make your changes and submit a pull request with a detailed description of your modifications.
3. Ensure that your code follows the project's coding standards and passes all tests.

For major changes, please open an issue first to discuss your ideas.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Thank you for your interest in REX! Join us in building a revolutionary platform for secure, reputational-based, and decentralized crypto trading.
```
