# Decentralized Authentication System

This repository contains a DApp project that demonstrates how to set up and interact with a decentralized application using Truffle, Ganache, and a simple client interface.

## Getting Started

Follow these step-by-step instructions to set up and run the project on your local machine.

### Prerequisites

Ensure you have the following installed on your system:
- Node.js
- npm (Node Package Manager)
- Truffle
- Ganache

### Installation and Setup

1. **Install Client Dependencies**
    ```
    cd client
    npm install
    ```

2. **Start Ganache**
    - Open Ganache and start a new workspace or use the default Quickstart workspace.

3. **Compile the Smart Contracts**
    ```
    cd ../
    truffle compile
    ```

4. **Migrate the Smart Contracts to the Blockchain**
    ```
    truffle migrate
    ```

5. **Start the Client Application**
    ```
    cd client
    npm start
    ```

Your DApp should now be running and accessible in your browser. By default, it will be available at `http://localhost:3000`.

### Troubleshooting

- **Ganache not starting**: Ensure that Ganache is properly installed and running before executing the Truffle commands.
- **Compilation errors**: Check the Solidity code in the `contracts/` directory for syntax errors.

## Contributors

Thanks to the following people who have contributed to this project:

- [@Pemarathna I.R.C](https://github.com/IT21170416)
- [@Ariyarathna H.C.K](https://github.com/IT21176388)

Happy coding! 🚀
