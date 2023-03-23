# Solidity Test

This repository contains a solidity/hardhat project in Typescript. It is a simple application for learning solidity and the funamentals of smart-contracts and Ethereum Blockchain.

# How to setup a hardhat environment?

1. Create a node project with npm start.
2. npm install hardhat.
3. npx hardhat.

# Contracts

The solidity smart-contracts are present in the contracts directory.

# Tests

The test cases for the smart-contracts are available in the test direcotry.

# Scripts

Scripts are available in the scripts directory. They contain the scripts for deploying the contract.
Scripts can be executed using the npx hardhat run command followed by the path to the script file.

# Commands

## Create hardhat project. Get details of hardhat once the project has been setup

> npx hardhat

## Compile the project

> npx hardhat compile

## Run the tests

> npx hardhat test

## Run scripts

> npx hardhat run path/to/script.ts

## Make network available locally.

> npx hardhat node
