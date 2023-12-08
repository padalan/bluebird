# Bluebird
Automating Ethereum Wallet Creation, Funding, and Token Purchases for Airdrops

Title: **Python Script for Automating Ethereum Wallet Creation, Funding, and Token Purchases for Airdrops**

### Overview:
The project involves developing two Python scripts for managing Ethereum wallets and transactions to maximize the potential for receiving airdrops. The first script creates 100 Ethereum wallets (airdrop wallets), and the second script distributes funds from a principal wallet to these airdrop wallets. Additionally, each airdrop wallet will purchase a set amount of a specified token.

### Script 1: Create Ethereum Wallets

**Purpose**:
- To generate 100 Ethereum wallets (addresses and private keys).

**Key Features**:
1. Utilize a library like `web3.py` for Ethereum interactions.
2. Generate 100 Ethereum wallets.
3. Save the wallet addresses and their corresponding private keys securely.
4. Ensure the storage method for keys is encrypted and secure.

### Script 2: Distribute Funds and Purchase Tokens

**Purpose**:
- To distribute Ether from a principal wallet to the 100 airdrop wallets.
- To execute token purchase transactions from each airdrop wallet.

**Key Features**:
1. Load the principal wallet using its private key.
2. Send Ether to each of the 100 airdrop wallets. The amount should be specified and enough to cover token purchase and transaction fees.
3. For each airdrop wallet, initiate a transaction to purchase a specified amount of the given token. The token contract address should be configurable.
4. Handle transaction confirmations and error checks.

### Additional Considerations:

- **Security**: Managing multiple wallets and private keys requires careful consideration of security practices.
- **Rate Limiting and Gas Fees**: Manage transaction rate limiting and optimize for gas fees, considering the Ethereum network's congestion and fee variability.
- **Testing**: Initially, run the scripts in a testnet environment to avoid loss of funds due to errors.
- **Compliance and Ethics**: Ensure that the scripts and their intended use comply with legal and ethical standards concerning cryptocurrency transactions and airdrops.

### Technologies and Libraries:
- `Python 3.x`: For scripting.
- `web3.py`: Python library for Ethereum.
- `Cryptography`: For secure storage of private keys.
- Ethereum Test Networks (Ropsten, Rinkeby): For testing the scripts.

### Execution Flow:
1. **Run Wallet Creation Script**:
   - Generates 100 wallets and stores their credentials securely.
2. **Run Distribution and Purchase Script**:
   - Loads principal wallet.
   - Distributes Ether to airdrop wallets.
   - Executes token purchases for each wallet.

### Output:
- Two Python scripts: one for wallet creation and another for fund distribution and token purchasing.
- Log files recording transactions and any errors.

---

**Note**: This project should be undertaken with a clear understanding of the risks involved in handling cryptocurrency wallets and transactions, including security risks and the volatile nature of cryptocurrency markets. Additionally, the ethical implications and legal compliance of the intended use should be thoroughly considered. 

ONLY FOR EDUCATIONAL PURPOSES.
