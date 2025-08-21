
🗳️ VoteChain – Blockchain-Based Election Voting System

VoteChain is a simple and secure voting system built using Blockchain technology in Python.
It ensures transparency, prevents duplicate voting, and records votes in a tamper-proof ledger using the concept of blocks and hashing.

🚀 Features

✅ Secure voting with Blockchain

✅ Age validation (18+ required to vote)

✅ Prevents duplicate voting (unique voter IDs)

✅ Proof-of-Work mining for block confirmation

✅ Transparent vote counting

✅ Final election results with winner declaration

✅ Blockchain integrity validation


⚙️ How It Works

1. Voters enter their ID and Age.


2. If eligible, they select a candidate to vote for.


3. Votes are stored as pending transactions until mined.


4. Mining creates a new block, securing the votes in the blockchain.


5. At the end, results are calculated and the winner is declared.



🛠️ Tech Stack

Python 3

hashlib (SHA-256 hashing)

JSON (data storage)

Proof-of-Work for block mining


📊 Example Output

✅ You voted successfully for Alice!
✅ Block mined: 000a9f3c7...
📊 Final Election Results
===============================
Alice: 3 votes
Bob: 2 votes
===============================
🏆 Winner: Alice with 3 votes
🗳️ Total voters: 5
