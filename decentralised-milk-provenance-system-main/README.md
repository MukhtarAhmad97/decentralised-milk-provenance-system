# decentralised-milk-provenance-system

A blockchain-based system to ensure trust, transparency, and traceability in the dairy supply chain. This project records and verifies the journey of milk from farm to consumer, reducing fraud and enhancing consumer confidence.

---

## Features
- Blockchain-backed provenance with tamper-proof records.
- IoT sensor integration for real-time data (temperature, storage conditions, transport logs).
- Smart contracts to automate verification, payments, and compliance checks.
- Role-based access for farmers, distributors, retailers, and consumers.
- QR code scanning for consumers to verify milk batch history.

---

## Technology Stack
- **Blockchain**: Ethereum / Hyperledger Fabric
- **Smart Contracts**: Solidity / Chaincode
- **Backend**: Node.js, Express
- **Database**: PostgreSQL (indexing) and IPFS (immutable storage)
- **Frontend**: React.js / Next.js dashboard
- **IoT Integration**: MQTT, Arduino/Raspberry Pi
- **QR Code API**: For consumer-facing verification

---

## Installation

### Prerequisites
- Node.js (v18 or later)
- Docker and Docker Compose
- PostgreSQL
- Truffle / Hardhat (for Ethereum deployment)

### Steps
```bash
# Clone repository
git clone https://github.com/your-username/decentralised-milk-provenance-system.git
cd decentralised-milk-provenance-system

# Install dependencies
npm install

# Compile and deploy smart contracts (Ethereum example)
npx hardhat compile
npx hardhat run scripts/deploy.js --network localhost

# Start backend server
npm run server

# Start frontend application
npm run client
