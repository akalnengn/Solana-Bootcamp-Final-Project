### Solana-Bootcamp-Final-Project
# RiseIn NFT Smart Contract

## Overview
This is a smart contract for creating and managing NFTs (Non-Fungible Tokens) on the Solana blockchain. NFTs are unique digital assets that can represent various digital or physical items, such as digital art, collectibles, and more.

## Features
- Mint new NFTs with customizable attributes like color, rarity, and short descriptions.
- Transfer NFTs to other users.
- Burn (destroy) NFTs to remove them from circulation.

## Getting Started

### Prerequisites
Before deploying and interacting with this smart contract, you'll need the following:

- [Solana Wallet](https://docs.solana.com/wallet-guide/installation)
- [Solana Command Line Tools](https://docs.solana.com/cli/installation)

### Deploying the Contract
To deploy this smart contract to the Solana blockchain, follow these steps:

1. Clone this repository to your local machine:
git clone https://github.com/your-username/nft-contract.git

2. Build the smart contract:
cd nft-contract
solana build
3. Deploy the contract to the Solana blockchain:
solana deploy ./target/deploy/nft_contract.so

4. Take note of the contract address, as you'll need it for interactions.

### Interacting with the Contract
You can interact with the NFT contract using Solana Wallet or through your own Solana application. Here are some common interactions:

- **Mint New NFT**: To mint a new NFT, you'll need to call the `mint` method. Provide the required parameters such as color, rarity, and short description. The contract will mint a new NFT with these attributes.

- **Transfer NFT**: To transfer an NFT to another user, use the `transfer` method. Provide the recipient's address and the NFT's unique ID.

- **Burn NFT**: To remove an NFT from circulation, you can burn it using the `burn` method.

## Example Usage
Here's an example of how to mint an NFT using the Solana CLI:

1. Mint a new NFT:
solana call <ContractAddress> mint
--input '{"mint": "<MintAddress>", "gem": {"color": "blue", "rarity": "common", "short_description": "Beautiful blue gem"}}'

2. Transfer an NFT to another user:
solana call <ContractAddress> transfer --input '{"mint": "<MintAddress>", "gem": {"color": "red", "rarity": "rare", "short_description": "Rare red gem"}}'

3. Burn an NFT:
solana call <ContractAddress> burn --input '{"mint": "<MintAddress>", "gem": {"color": "green", "rarity": "uncommon", "short_description": "Common green gem"}}'

## License
This NFT contract is released under the [Unlicense](https://unlicense.org/). You are free to use, modify, and distribute it as you see fit.

For more details and advanced usage, please refer to the [Solana documentation](https://docs.solana.com/).

## Contributing
If you want to contribute to this project, please open an issue or create a pull request on our GitHub repository.
![app tsRun](https://github.com/akalnengn/Solana-Bootcamp-Final-Project/assets/127908683/13209ccc-2733-465a-b83a-0df7a735496b)
![yarnInstallSplToken](https://github.com/akalnengn/Solana-Bootcamp-Final-Project/assets/127908683/8ff72f8a-5283-49f4-afc1-1e27a5fa03d1)
![yarnInstall](https://github.com/akalnengn/Solana-Bootcamp-Final-Project/assets/127908683/e5832f93-ed22-4c97-852e-e96875de93a3)
![transferring](https://github.com/akalnengn/Solana-Bootcamp-Final-Project/assets/127908683/c55a88e9-3f7e-480a-99ea-0afe9889450d)
![solanaBalance](https://github.com/akalnengn/Solana-Bootcamp-Final-Project/assets/127908683/a2ae97e6-e2e5-4a2b-ade0-a761fc72a23e)
![solanaAddress](https://github.com/akalnengn/Solana-Bootcamp-Final-Project/assets/127908683/811e998d-32c8-45a6-81c3-11fa8c556e19)
![nft yaml](https://github.com/akalnengn/Solana-Bootcamp-Final-Project/assets/127908683/8681544a-479d-49bf-962a-0903f5514ef2)
![minting](https://github.com/akalnengn/Solana-Bootcamp-Final-Project/assets/127908683/30555e2d-69cb-4845-aec5-88187d5ffcb6)
![deploynft so](https://github.com/akalnengn/Solana-Bootcamp-Final-Project/assets/127908683/6459f25c-e9e4-4b18-af24-25837b119dd5)
![connectedDevnet](https://github.com/akalnengn/Solana-Bootcamp-Final-Project/assets/127908683/1b378e25-cf89-47c4-84b9-c9989f565ffa)
![cargoBuild](https://github.com/akalnengn/Solana-Bootcamp-Final-Project/assets/127908683/73b871d6-1854-4ce5-b9b6-0e3e5305a33d)
![burning](https://github.com/akalnengn/Solana-Bootcamp-Final-Project/assets/127908683/263bf78b-80b3-418e-9fea-1ff1a9e6702f)
![balanceDevnet](https://github.com/akalnengn/Solana-Bootcamp-Final-Project/assets/127908683/8441ba10-bb07-4d9b-80e2-46d60253a432)


