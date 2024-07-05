# Functions and Errors - ETH + AVAX

A simple Ethereum smart contract for implementing the require(), assert() and revert() statements.

## Description

This project showcases the use of `require`, `assert`, and `revert` statements in a Solidity smart contract. The contract allows an owner to set a greeting message, checks ownership status, and performs a mathematical operation with error handling.

## Executing program

1. **Access Remix IDE**:
   - Visit [Remix](https://remix.ethereum.org/) in your web browser.

2. **Create a New File**:
   - Click on the "+" icon in the left sidebar to create a new file.

3. **Paste the Solidity Code**:
   - Copy and paste the Solidity code from this repository into the new file.

4. **Compile the Contract**:
   - Go to the "Solidity Compiler" tab in Remix.
   - Select the appropriate compiler version (`^0.8.0`) from the dropdown.
   - Click on "Compile m3.sol" to compile the contract.

5. **Deploy the Contract**:
   - Go to the "Deploy & Run Transactions" tab in Remix.
   - Choose the environment (e.g., JavaScript VM, Injected Web3 for testnets).
   - Click on "Deploy" to deploy the contract.

6. **Interact with the Contract**:
   - Once deployed, you can interact with the contract using the provided functions:
     - `setGreeting(string memory _greeting)`: Set a new greeting message.
     - `isOwner()`: Check if the caller is the owner.
     - `mathOp(uint256 a, uint256 b)`: Perform a mathematical operation with an assertion.

## Authors
Metacrafter Chris  
Twitter: [@metacraftersio](https://twitter.com/metacraftersio)

## License
This project is licensed under the MIT License - see the LICENSE.md file for details.
