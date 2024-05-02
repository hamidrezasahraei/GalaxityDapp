# Galaxity Collectibles DApp

Welcome to Galaxity Collectibles, a decentralized application (DApp) running on the Ethereum blockchain.

## Features
Deploy Contract, Create/Buy/Sell/Burn/Transfer/Search Planet, Realtime events


## Getting Started

1. **Clone the repository:**

2. **Install dependencies and run the project:**

   Running frontent:
   ```bash
   cd frontend/
   npm install
   npm start
   ```

   Running Backend(Blockchain):
   ```bash
   npm install
   npx hardhat compile
   npx hardhat run ./tasks/deploy.ts --network localhost
   npx hardhat node
   ```

3. **Access the DApp in your web browser at `http://localhost:3000`.**
   
## Contributing

Contributions to Galactic Collectibles are welcome! Please follow the [contribution guidelines](CONTRIBUTING.md).

## License

This project is licensed under the [MIT License](LICENSE). Feel free to use, modify, and distribute the code.

## Acknowledgments

Some parts of this project was inspired by the [GalacticCollectables](https://github.com/rezaiyan/galactic-collectibles-dapp) project.

🙏 Thank you!
