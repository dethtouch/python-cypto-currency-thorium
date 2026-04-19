Thorium 2.0 - Zero-Fee P2P Cryptocurrency

https://img.shields.io/badge/License-MIT-yellow.svg
https://img.shields.io/badge/python-3.8+-blue.svg

Thorium is a live, peer-to-peer cryptocurrency with zero transaction fees. One file. No installation. Just download and run.
What You Need

    A computer (Windows, Mac, or Linux, rasberry pi is what im on :) )

    Python 3.8 or newer installed

Quick Start

Open a terminal and run these commands:
bash

mkdir thorium
cd thorium
curl -O https://raw.githubusercontent.com/dethtouch/python-crypto-currency-thorium/main/thorium2.0
mv thorium2.0 thorium.py
python3 thorium.py

No curl? Use wget:
bash

wget https://raw.githubusercontent.com/dethtouch/python-crypto-currency-thorium/main/thorium2.0
mv thorium2.0 thorium.py
python3 thorium.py

On Windows? Download the raw file from GitHub in your browser, save as thorium.py, then run python thorium.py in Command Prompt.
First Run

When you run Thorium for the first time, these folders are created:

    wallets/ - Your encrypted wallet files

    logs/ - Activity logs

    thorium.db - Blockchain database

You will see a menu:
text

======================================================================
💰 THORIUM 2.0 - ENHANCED P2P CRYPTOCURRENCY
======================================================================
📊 BLOCKCHAIN STATUS:
   Height: 0
   Difficulty: 4 zeros (Easy mode)

📋 MAIN MENU:
1. Wallet Management
2. Send Thorium (Zero Fee)
3. Mining Operations
4. Blockchain Explorer
5. Network Management
6. Settings & Tools
7. Exit

Creating a Wallet

    Type 1 (Wallet Management)

    Type 1 (Create new wallet)

    Enter a name (example: mywallet)

    Enter a password (8+ characters)

    Confirm password

    SAVE YOUR PRIVATE KEY - This is the ONLY way to recover your coins

Your address starts with TH... - share this to receive Thorium.
Unlocking Your Wallet

Before sending or mining:

    Type 1 (Wallet Management)

    Type 2 (Unlock existing wallet)

    Select your wallet

    Enter your password

Mining Thorium

    Unlock your wallet

    Type 3 (Mining Operations)

    Type 1 (Start mining)

    Press Ctrl+C to stop

Mining details:

    First 100,000 blocks: 4 zeros difficulty (easy for home miners)

    After block 100,000: 6 zeros difficulty (harder)

    Block reward: 50 TH, halves every 210,000 blocks

    Minimum reward: 1 TH per block (permanent)

Sending Thorium

    Unlock your wallet

    Type 2 (Send Thorium)

    Enter amount (example: 1.5)

    Enter recipient address

    Confirm

Zero fees - Send 1 TH, recipient gets 1 TH.
Connecting to the Network

The default peer is 192.168.0.26 on port 9333

To connect:

    Type 5 (Network Management)

    Type 2 (Add peer manually)

    Enter 192.168.0.26:9333

To see connected peers:

    Type 5 (Network Management)

    Type 1 (List connected peers)

Checking Your Balance

    Your balance shows on the main screen when wallet is unlocked

    Or type 4 (Blockchain Explorer) → 5 (Check address balance)

What Files Are Created
text

thorium/
├── thorium.py          # The program
├── wallets/            # Encrypted wallets (JSON files)
├── logs/               # Activity logs
└── thorium.db          # Blockchain database (SQLite)

Common Problems

"python3: command not found" - Python is not installed. Download from python.org

"Address already in use" - Port 9333 is busy. Close other Thorium instances.

Mining finds no blocks - Normal. Let it run for 10-15 minutes.

Forgot password - Coins are lost forever. No recovery possible.

Can't connect to peer - Ensure peer is online and port 9333 is open.
Stopping Thorium

Type 7 (Exit) or press Ctrl+C
License

MIT License

Thorium is live. One file. No fees. No gates. Just run it. have fun!
