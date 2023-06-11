## Introduction

Solidity, the primary language for smart contract development on blockchain platforms like Celo, provides several features for error handling, such as require, revert, and assert. These constructs are vital for writing safe and secure contracts. In this challenge, you'll be required to use these constructs to create a contract that exemplifies best practices for error handling in Solidity.

## Problem Statement

Design a smart contract that simulates a basic banking system with the following requirements:

1. The contract should allow users to deposit and withdraw Celo.
2. The contract should prevent users from withdrawing more Celo than they have deposited.
3. The contract should stop execution and revert any transaction that would result in an error, such as a withdrawal that exceeds the user's balance.

## Hints

- Use `msg.sender` and `msg.value` to handle deposits and to keep track of each user's balance with a mapping.
- Use `require` statements to enforce the rules of your banking system, such as preventing overdrafts.
- The `transfer` function can be used to send Celo for withdrawals.

## Evaluation Criteria

- **Correctness**: The contract should compile without errors and meet all the requirements.
- **Readability**: The contract should be well-documented, with comments explaining the code.
- **Testability**: You should also provide examples of how to test each function of the contract.

Remember, handling real assets on a blockchain requires extreme care and extensive testing. Error handling plays a crucial role in avoiding vulnerabilities and ensuring the contract behaves as expected.

For a comprehensive understanding of Celo smart contracts, Solidity, and its error handling features, please refer to the Celo and Solidity tutorials.

## Submission

Please reply with a link to your PR on GitHub, including your banking contract. Also, include any notes or comments you think are necessary to understand your design and choices. Lastly, provide a brief explanation about how each function of the contract should be tested.
