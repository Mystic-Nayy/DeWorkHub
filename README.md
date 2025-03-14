# DeWorkHub
 A decentralized hub for work opportunities.

## **Overview**
DeWorkHub is a Web3-powered platform that connects developers, designers, and writers with job opportunities in a fully decentralized manner.It leverages smart contracts to handle job postings, applications, hiring decisions, and payments transparently without intermediaries.

## **Features**
- 🏗 **Smart Contracts on StarkNet (Cairo)**
  - Job Listings: Companies can post and manage job openings.
  - User Profiles: Job seekers create on-chain profiles with reputation scores.
  - Applications & Hiring: Applications and hiring decisions are recorded on-chain.
  - Escrow Payments: Secure, trustless payments using stablecoins or custom tokens.

- 🌐 **Frontend (React + StarkNet.js)**
  - Job board UI with search and filters.
  - Wallet-based authentication (ArgentX, Braavos, WalletConnect).
  - Dashboard for job seekers and companies.

- 📦 **Decentralized Storage**
  - IPFS/Arweave for resumes, job descriptions, and portfolios.
  - Hashes stored on-chain for verification.

- ⭐ **Reputation System**
  - Soulbound NFTs to verify past work.
  - On-chain endorsements and rating system.

## **Tech Stack**
- **Blockchain:** StarkNet (L2 scaling solution)
- **Smart Contracts:** Cairo (for job listings, applications, and payments)
- **Frontend:** React + StarkNet.js
- **Storage:** IPFS, Arweave
- **Authentication:** Wallet-based login

## **Installation & Setup**
### Prerequisites
Ensure you have the following installed:
- [Node.js](https://nodejs.org/) (>= v18)
- [Yarn](https://yarnpkg.com/) (or npm)
- [ArgentX](https://www.argent.xyz/) or [Braavos](https://braavos.app/) wallet
- StarkNet development tools: [Starkli](https://github.com/Software-Mansion/starkli), [Scarb](https://github.com/software-mansion/scarb)

### Clone the Repository
```sh
 git clone https://github.com/your-username/starknet-job-board.git
 cd starknet-job-board
```

### Install Dependencies
```sh
yarn install  # or npm install
```

### Run the Development Server
```sh
yarn dev  # or npm run dev
```

### Deploy Contracts
```sh
scarb build  # Compile the Cairo smart contracts
starkli deploy <compiled_contract_path>
```

## **Project Structure**
```
/starknet-job-board
│── /contracts       # StarkNet Cairo smart contracts
│── /frontend        # React-based frontend
│── /scripts         # Deployment & automation scripts
│── /storage         # IPFS/Arweave integration
│── README.md        # Project documentation
```

