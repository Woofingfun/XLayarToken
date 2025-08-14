### Introduction to Meme Coin Launchpad on X Layer

The **Meme Coin Launchpad** is a user-friendly platform built on the **X Layer mainnet** (Chain ID: 196), powered by OKX’s blockchain infrastructure. It enables anyone to create and manage their own ERC20 meme coins with ease, leveraging the low fees and high performance of X Layer. With a sleek, modern interface inspired by OKX.com, this decentralized application (dApp) allows users to connect their MetaMask wallet, create custom tokens with a specified supply, and view their created tokens or the latest tokens on the platform. The platform is secure, transparent, and optimized for both desktop and mobile devices, making meme coin creation accessible to all.

### How to Use the Meme Coin Launchpad

Follow these steps to create and manage your meme coins on the X Layer network:

1. **Set Up Your Wallet**:
   - Install **MetaMask** (available as a browser extension or mobile app) if you haven’t already. Visit [metamask.io](https://metamask.io) to download.
   - Ensure you have **OKB** tokens in your wallet to cover gas fees on the X Layer network.

2. **Access the Launchpad**:
   - Open the Meme Coin Launchpad website via a local server (e.g., run `npx serve` in the directory containing the HTML file) to enable MetaMask interaction. Direct file access (`file://`) won’t work due to browser security restrictions.
   - Alternatively, host the website on a server or use a hosted version if available.

3. **Connect to X Layer**:
   - Click the **"Connect Wallet"** button on the homepage.
   - MetaMask will prompt you to connect your wallet. Approve the connection.
   - If X Layer (Chain ID: 196) isn’t in your MetaMask, the dApp will automatically prompt you to add or switch to it. The network details are:
     - **Network Name**: X Layer mainnet
     - **RPC URL**: https://rpc.xlayer.tech
     - **Chain ID**: 196
     - **Token Symbol**: OKB
     - **Block Explorer URL**: https://www.okx.com/web3/explorer/xlayer
   - Once connected, your wallet address will display (e.g., `0x1234...5678`).

4. **Create a Meme Coin**:
   - Navigate to the **"Create Meme Coin"** section.
   - Enter the following details:
     - **Token Name**: The name of your token (e.g., “XCoin”).
     - **Token Symbol**: A short ticker symbol (e.g., “XCN”).
     - **Total Supply**: The total number of tokens (e.g., `1000000` for 1 million tokens). The supply will be minted with 18 decimals (e.g., 1M tokens = 1,000,000 * 10^18 units).
   - Click **"Create Meme Coin"**.
   - MetaMask will prompt you to confirm the transaction. Ensure you have enough OKB for gas fees.
   - After confirmation, the platform will display the new token’s address, linked to the X Layer block explorer (e.g., `0x5c00...2D5b`).

5. **View Your Meme Coins**:
   - In the **"My Created Meme Coins"** section, click **"Fetch My Meme Coins"**.
   - The platform will display up to the latest 100 tokens you’ve created, showing each token’s address, name, and symbol.
   - Click the **"Copy"** button next to a token’s address to copy it to your clipboard for use in wallets or exchanges.

6. **Explore Latest Meme Coins**:
   - In the **"Latest Meme Coins"** section, click **"Fetch Latest Meme Coins"**.
   - The platform will show up to the latest 100 tokens created by all users, including their addresses, names, and symbols.
   - Copy token addresses as needed to interact with them on X Layer.

7. **Interact with Your Tokens**:
   - Use the token address in MetaMask or other X Layer-compatible wallets to add your token for trading, transferring, or other operations.
   - Visit the X Layer block explorer (https://www.okx.com/web3/explorer/xlayer) to view transaction details or token information.

8. **Troubleshooting**:
   - **Wallet Not Connecting**: Ensure MetaMask is installed and unlocked. Check that you’re on the X Layer network (Chain ID: 196).
   - **Insufficient Funds**: Make sure you have OKB tokens for gas fees. You can acquire OKB via OKX or other supported exchanges.
   - **Creation Fails**: Verify that the token name, symbol, and supply are valid (supply must be greater than 0). Check for sufficient gas and network connectivity.
   - **No Tokens Displayed**: If no tokens appear, you may not have created any yet, or the platform couldn’t fetch them due to a network issue. Try clicking “Fetch” again.

### Additional Notes:
- **Security**: The platform uses a secure smart contract deployed at `0x5c005d074E25b89db97A32087C06D154D8CB2D5b`. Only the creator can mint tokens, and ownership can be transferred or renounced.
- **Mobile-Friendly**: The interface is fully responsive, stacking elements vertically on smaller screens for easy navigation.
- **Cost**: Creating a token requires OKB for gas fees, which are low on X Layer. No additional fees are charged by the platform.
- **Support**: For issues, refer to the X Layer documentation or OKX support at [https://www.okx.com/help](https://www.okx.com/help).

Get started now and launch your meme coin on X Layer with the Meme Coin Launchpad! 🚀
