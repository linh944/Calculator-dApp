
# Calculator dApp on Aptos using Move

## Introduction

This project is a beginner-friendly demonstration of how to build a decentralized application (dApp) on the Aptos blockchain using Move. The dApp is a simple calculator that allows users to perform basic arithmetic operations.

## Features

-   Perform basic arithmetic operations: addition, subtraction, multiplication, and division.
    
-   Smart contract implementation using Move.
    
-   Deployment on the Aptos blockchain.
    

## Prerequisites

Before getting started, ensure you have the following installed:

-   Aptos CLI
    
-   [Move CLI](https://github.com/move-language/move)
    
-   Rust
    
-   [Node.js](https://nodejs.org/) and npm (for frontend development, if applicable)
    

## Getting Started

### 1. Clone the Repository

```
 git clone https://github.com/linh944/Calculator-dApp.git
 cd calculator-dapp-aptos
```

### 2. Set Up Aptos Account

Create an Aptos account and configure your CLI:

```
aptos init
```

### 3. Build and Test the Move Module

Compile the Move contract:

```
move build
```

Run tests to ensure everything is working:

```
move test
```

### 4. Deploy the Contract to Devnet

```
aptos move publish --profile devnet
```

### 5. Interact with the Contract

You can interact with the smart contract using Aptos CLI or a frontend interface.


## Contributing

Contributions are welcome! Feel free to open issues and pull requests.

## License

This project is licensed under the MIT License.

## Resources

-   [Aptos Docs](https://aptos.dev/)
    
-   Move Language
    
-   [Aptos GitHub](https://github.com/aptos-labs)
