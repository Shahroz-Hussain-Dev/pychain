PyChain – Fully Functional Python Blockchain Prototype 


Key Features

🪙 Wallet functionality – Key generation & management

🔐 Elliptic Curve Cryptography (ECC) – Implemented from scratch for public/private keys & transaction signing

📜 Transaction validation – Memory pool management for pending transactions

⛏️ Mining & Consensus – Proof-of-work mining with conflict resolution between miners

🔄 Peer-to-peer networking – Node communication & block propagation

⚡ Multiprocessing support – Utilizes all CPU cores for mining and validation

⚠️ Note: ECC involves advanced math — you can skip it if you’re exploring basic blockchain concepts



Getting Started

Prerequisites: Python 3.10.12 or higher

Steps to Clone and Run Locally

Clone the repository:

git clone https://github.com/Shahroz-Hussain-Dev/pychain/
cd PyChain


Install dependencies:

pip install -r requirements.txt


Update system paths:

Windows: Replace all instances of sys.path.append("/Users/Shahroz/Desktop/Bitcoin") with your local PyChain path

Linux: Make sure the full path matches your system, e.g., /home/username/Desktop/PyChain

Open Visual Studio Code and run blockchain.py inside the core directory.

If you encounter errors with config.ini, run in debug mode:
Run -> Start Debugging (no need to set breakpoints)

Open your browser at http://127.0.0.1:5900/
 to access your local PyChain node.

Notes

This project is primarily for educational purposes to explore blockchain technology.

ECC implementation is included but optional for beginners.

Designed in 2025, PyChain includes modern Python practices and optimized multiprocessing for mining.

License

MIT License © 2025 Shahroz
