# Fired Guys NFT Collection

This project consists of a Solidity smart contract for creating NFTs (Non-Fungible Tokens) and a React application for interacting with the contract and displaying the NFT collection.

## Solidity Smart Contract

### Contract Address
- The smart contract address: `0x5FbDB2315678afecb367f032d93F642f64180aa3`

### Contract Features
- This smart contract allows you to create and manage NFTs.
- NFTs are created with metadata stored on IPFS.
- Users can mint NFTs by paying a fee of 0.05 Ether.
- The contract tracks the total number of minted NFTs.

### Contract Functions
- `safeMint(address to, string memory uri)`: Allows the owner to safely mint NFTs with specified URIs.
- `isContentOwned(string memory uri)`: Checks if a specific NFT with URI is already owned.
- `count()`: Returns the total number of minted NFTs.

## React Application

### Features
- The React application interacts with the smart contract to display the NFT collection.
- Users can view minted NFTs and mint new ones.
- Each NFT is associated with an image URI.
- Minted NFTs display their images, and users can view the URI of the minted NFTs.

### Prerequisites
- MetaMask or another Ethereum wallet extension is required for using this application.

### Getting Started
1. Clone this repository.
2. Run `npm install` to install dependencies.
3. Run `npm start` to start the development server.
4. Connect your Ethereum wallet to interact with the smart contract.

## Usage
1. Visit the web application.
2. Connect your Ethereum wallet.
3. Mint new NFTs by clicking the "Mint" button.
4. View minted NFTs and click "Show URI" to view their metadata URI.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
- This project uses OpenZeppelin contracts for ERC721 tokens.

## Author
- Your Name

For any questions or issues, please contact [Your Email Address].

Feel free to contribute to the project by forking and creating pull requests.
