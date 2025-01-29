# Solana Wallets Track

This project is a command-line tool that allows you to track the balances of multiple Solana wallets. It fetches the balance of each wallet address from the Solana blockchain and displays them in a table format.

## Installation

```bash
npm install -g solana-wallets-track
Usage
To use the tool, you need to provide a list of Solana wallet addresses. You can do this either by passing them as command-line arguments or by providing a file containing the addresses.

Command-line arguments
Bash

solana-wallets-track <address1> <address2> <address3> ...
File input
Create a file named wallets.txt with one wallet address per line:

<address1>
<address2>
<address3>
...
Then, run the tool with the -f or --file option:

Bash

solana-wallets-track -f wallets.txt
Options
-f, --file: Path to the file containing the list of wallet addresses.
-h, --help: Display help message.
-v, --version: Display version information.
Output
The tool will display a table with the following columns:

Address: The Solana wallet address.
Balance: The balance of the wallet in SOL.
