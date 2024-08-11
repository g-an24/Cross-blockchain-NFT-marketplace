# Cross-blockchain NFT Marketplace

This repository contains the code for a capstone project focused on implementing cross-blockchain functionality for an NFT marketplace. The project allows users to buy, sell, and trade NFTs across different blockchain networks.

## Features

- **Cross-Blockchain Compatibility:** Enables transactions across multiple blockchain networks.
- **Smart Contracts:** Utilizes Solidity for creating and managing NFT smart contracts.
- **Frontend:** Built with Next.js and styled using Tailwind CSS for a responsive UI.
- **Testing:** Comprehensive testing suite included.

## Installation

1. **Clone the repository:**
    ```bash
    git clone https://github.com/g-an24/Cross-blockchain-NFT-marketplace.git
    cd Cross-blockchain-NFT-marketplace
    ```

2. **Install dependencies:**
    ```bash
    npm install
    ```

3. **Compile smart contracts:**
    ```bash
    npx hardhat compile
    ```

4. **Start the development server:**
    ```bash
    npm run dev
    ```

## Usage

- Visit the marketplace at `http://localhost:3000` after running the development server.
- Deploy and interact with NFTs across different blockchain networks.

## Testing

- Run the test suite to ensure all contracts and functionalities are working correctly:
    ```bash
    npx hardhat test
    ```

## Project Structure

- **contracts/** - Contains Solidity smart contracts.
- **pages/** - Next.js pages for the frontend.
- **scripts/** - Deployment scripts.
- **styles/** - Tailwind CSS styles.
- **test/** - Test cases for smart contracts.

## Contributing

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Create a Pull Request.

## License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.
