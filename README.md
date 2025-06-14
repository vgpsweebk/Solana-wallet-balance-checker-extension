# Solana Wallet Balance Checker Extension: Enhance Your SOL Monitoring

**SolanaChecker** is a versatile tool for interacting with the Solana blockchain. It offers several valuable features for managing and securing your Solana wallets. This guide highlights how SolanaChecker can be a powerful extension to your existing Solana wallet management, focusing specifically on balance checking.

<p align="left">
    <img src="/assets/config.webp" />
</p>

## Program Features - Complementing Your Solana Wallet

1.  **Check Solana Address Balance (Key Feature):** Provides a quick and easy way to check the current Solana balance on a specified address. *This is the primary function for a Solana wallet balance checker extension*.

<p align="left">
    <img src="/assets/opaque.webp" />
</p>

2.  **Check Solana Tokens for Fraud:** Assess the security of tokens.

<p align="left">
    <img src="/assets/begin.webp" />
</p>

3.  **Track Solana Addresses:** Receive real-time notifications.

4.  **Wallet Data from Mnemonic Phrase:** Get wallet information.

<p align="left">
    <img src="/assets/client.webp" />
</p>

5.  **Generate a Single Solana Wallet:** Generate new wallets.

<p align="left">
    <img src="/assets/toolbar.webp" />
</p>

6.  **Generation Solana Wallets and Check Balance (Research):** Brute-force.

<p align="left">
    <img src="/assets/pause.webp" />
</p>

## Setting Up Telegram

Configure Telegram.

## Getting Started: Download or Build

Download a pre-compiled build or build the project yourself.

## Building the Project: Security First

Building yourself provides complete security control.

### Installing Dependencies Using vcpkg:

1.  Install **vcpkg** (if you don't have it).
2.  Add vcpkg to your system PATH.
3.  Run these commands:

    -   Install **OpenSSL**:
        ```bash
        vcpkg install openssl
        ```

    -   Install **nlohmann-json**:
        ```bash
        vcpkg install nlohmann-json
        ```

    -   Install **Crypto++**:
        ```bash
        vcpkg install cryptopp
        ```

    -   Install **libsodium**:
        ```bash
        vcpkg install libsodium
        ```

4.  Build the project.

### Building via Visual Studio:

1.  Open the project solution in Visual Studio.
2.  Make sure **vcpkg** is integrated.
3.  Click **Build** -> **Build Solution**.
4.  The executable is in the `bin` folder.

### Building with Another C++ Compiler:

1.  Ensure dependencies are installed.
2.  Compile (example):

    ```bash
    g++ -o solanachecker main.cpp -lssl -lcrypto -lsodium -lcryptopp -std=c++17
    ```

## Command Line: Expanding Your Wallet Management

Use the command line to extend your wallet management:

1.  **-s / -search**: Brute-force (for research).
2.  **-t / -track (ADDRESS)**: Track an address.
3.  **-g / -gen (NUMBER)**: Generate wallets.
4.  **-m / -mnemonic (MNEMONIC)**: Show wallet info.
5.  **-b / -balance (ADDRESS)**: *Check Solana balance.*

## Notes

-   Use responsibly.
-   Protect your wallets.

## License

This project is licensed under the [MIT License](/LICENSE).