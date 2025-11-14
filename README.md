# Polkadot Creative Identity

This repository contains the Web3 Foundation grant implementation for Cross-Chain Bridge & Soulbound Tokens.

## Project Overview

We propose developing a cross-chain identity system using Polkadot's interoperability features and soulbound tokens to create a unified creative identity across all blockchain ecosystems. This module will enable creators to maintain a persistent, non-transferable identity that represents their creative journey, achievements, and collaborations, while facilitating seamless asset and data transfer between different blockchain networks.

## Features

- **Soulbound Tokens**: Non-transferable tokens representing creative identity
- **Cross-Chain Bridge**: Transfer assets and identity between blockchains
- **Identity Verification**: Proof of creative work ownership and skills
- **Polkadot Integration**: Native Substrate pallets and Polkadot JS integration
- **Multi-Chain Compatibility**: Works with NEAR, Solana, and Filecoin ecosystems

## Getting Started

### Prerequisites

- Rust and Cargo
- Node.js and npm
- Polkadot CLI
- Substrate development environment

### Installation

```bash
# Install CLI tools
./scripts/install-cli-tools.sh

# Build the project
./build-polkadot-grant.sh
```

### Building

```bash
# Build Polkadot client
cd src/polkadot-client
cargo build --lib
```

### Testing

```bash
# Run unit tests
cargo test

# Run integration tests with Polkadot node
./scripts/test-polkadot.sh
```

## Directory Structure

```
├── src/
│   ├── polkadot-client/       # Polkadot client and pallets
│   └── rust-client/           # Core Rust library (shared dependency)
├── test-website/              # Browser-based frontend
├── scripts/                   # Utility scripts
├── build-polkadot-grant.sh    # Build script
└── README.md                 # This file
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

- **Website**: https://compiling-org.netlify.app
- **GitHub**: https://github.com/compiling-org
- **Email**: kapil.bambardekar@gmail.com, vdmo@gmail.com
