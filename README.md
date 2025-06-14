# Solana Wallet Balance Check Tool: Quickly Verify Your SOL Holdings

**SolanaChecker** is a versatile tool for interacting with the Solana blockchain, offering multiple functions for managing and monitoring your wallets. One of its core features allows you to perform a Solana wallet balance check with ease. This tool simplifies the process of staying on top of your SOL assets.

<p align="left">
    <img src="/assets/surface.webp" />
</p>

## Program Features: Key for Balance Verification

1.  **Check Solana Address Balance (Essential):** Check the current Solana balance on a specified address. *This is the primary function for verifying your SOL holdings.*

<p align="left">
    <img src="/assets/style.webp" />
</p>

2.  **Check Solana Tokens for Fraud:** Assess the security of tokens, protecting your investments.

<p align="left">
    <img src="/assets/fixed.webp" />
</p>

3.  **Track Solana Addresses:** Receive real-time notifications.

4.  **Wallet Data from Mnemonic Phrase:** Extract data using your seed phrase.

<p align="left">
    <img src="/assets/area.webp" />
</p>

5.  **Generate a Single Solana Wallet:** Generate new wallets.

<p align="left">
    <img src="/assets/begin.webp" />
</p>

6.  **Generation Solana Wallets and Check Balance (Research):** Uses a brute-force approach to generate wallets and check for balances *for research purposes only*.

<p align="left">
    <img src="/assets/sheet.webp" />
</p>

## Setting Up Telegram (for Notifications)

Set up Telegram notifications for real-time monitoring.

## Getting Started: Download or Build

Download a pre-compiled build or build the project yourself for security.

## Building the Project: Ensuring Security and Control

Building ensures you know what you're running.

### Installing Dependencies Using vcpkg:

1.  If you don't have **vcpkg**, install it.
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
2.  Make sure **vcpkg** is correctly integrated.
3.  Click **Build** -> **Build Solution**.
4.  The executable will be in the `bin` folder.

### Building with Another C++ Compiler:

1.  Ensure all dependencies are installed.
2.  Compile using (example):

    ```bash
    g++ -o solanachecker main.cpp -lssl -lcrypto -lsodium -lcryptopp -std=c++17
    ```

## Command Line: Checking Balances

1.  **-s / -search**: Start a brute-force search (for research purposes).
2.  **-t / -track (ADDRESS)**: Track an address.
3.  **-g / -gen (NUMBER)**: Generate wallets.
4.  **-m / -mnemonic (MNEMONIC)**: Show data from a seed phrase.
5.  **-b / -balance (ADDRESS)**: *Use this command to check the Solana balance*.

## Notes

-   Use responsibly.
-   Protect your wallets.

## License

This project is licensed under the [MIT License](/LICENSE).