# Algorand Marketplace

A decentralized e-commerce marketplace built with PyTeal smart contracts on the Algorand blockchain, with a React frontend.

## Overview

A full-stack dApp marketplace where users can list and purchase products using ALGO tokens. The backend logic is handled entirely by PyTeal smart contracts deployed on Algorand.

## Features

- **Product Listing** — Sellers can list products with price and details
- **Purchase Flow** — Buyers can purchase products with ALGO
- **Decentralized** — All transactions handled on-chain via Algorand
- **Wallet Integration** — Connect Algorand wallet to interact
- **React Frontend** — Modern UI for browsing and purchasing

## Tech Stack

### Smart Contracts
- **PyTeal** — Python library for Algorand smart contracts
- **Algorand** — Layer 1 blockchain

### Frontend
- **React** — UI framework
- **Algorand SDK** — Blockchain interaction
- **CSS** — Styling

## Getting Started

### Smart Contract

```bash
cd Backend
pip install pyteal py-algorand-sdk
python marketplace.py
```

### Frontend

```bash
cd Frontend/algorand-marketplace
npm install
npm start
```

## Project Structure

```
├── Backend/
│   └── marketplace.py         # PyTeal marketplace contract
├── Frontend/
│   └── algorand-marketplace/
│       ├── src/
│       │   ├── App.js                    # Main app
│       │   └── components/
│       │       └── marketplace/
│       │           ├── Products.jsx      # Product listing
│       │           ├── Product.jsx       # Single product
│       │           └── AddProduct.jsx    # Add product form
│       └── package.json
```

## License

MIT
