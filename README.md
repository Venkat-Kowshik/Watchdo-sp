
# Watchdo

Watchdo allows creators who have registered their content on Story Protocol to identify if, and how, their minted IP has been used by other creators. Starting with remixes posted on Twitter, Watchdo aims to scale to other platforms where user content is shared.

Through Watchdo, creators can see how their content is being used, by whom, and determine whether they wish to file a dispute, or potentially even remix the remix! Additionally, Watchdo will register the derivative IP automatically onto Story Protocol for IP provenance. If they wish, the derivative creators can also claim their registered IP from Watchdo at a later date.

## Story Protocol

Story Protocol is a decentralized platform designed to provide immutable proof of ownership and provenance for digital content. By leveraging blockchain technology, it ensures that all IP registrations and transfers are transparent, secure, and tamper-proof. This protocol is ideal for creators who want to protect their intellectual property and track its usage across different platforms.

Key features of Story Protocol include:
- **Immutable Records:** Once registered, content ownership and its usage history cannot be altered, ensuring trust and transparency.
- **Provenance Tracking:** Every time a piece of content is remixed or reused, its provenance is updated, providing a clear history of its evolution.
- **Decentralized Registration:** Content is registered on a blockchain, removing the need for centralized authorities and reducing the risk of censorship or loss.

## Sepolia Testnet

For the development and deployment of Watchdo, we utilize the Sepolia testnet. Sepolia is a secure and reliable Ethereum test network that allows developers to test their smart contracts and dApps in a safe environment without the need for real ETH.

Key benefits of using Sepolia include:
- **Cost Efficiency:** Developers can deploy and test smart contracts without incurring high costs, as Sepolia uses test ETH.
- **Realistic Environment:** Sepolia closely mimics the Ethereum mainnet, providing a realistic testing ground for dApps.
- **Robust Infrastructure:** With reliable nodes and a strong community, Sepolia ensures a stable environment for testing.

## How to Use

1. **Install Dependencies:**
   ```bash
   yarn install
   ```

2. **Run the Development Server:**
   ```bash
   yarn dev
   ```

3. **Registering Content:**
   - Creators can register their content on Story Protocol through the Watchdo interface.
   - Registered content will receive a unique identifier and be stored on the blockchain.

4. **Tracking Usage:**
   - Watchdo scans Twitter for remixes and usages of the registered content.
   - Creators receive notifications of how and by whom their content is being used.

5. **Managing IP:**
   - View detailed reports of content usage.
   - Decide whether to file disputes, approve remixes, or collaborate with other creators.
   - Automatically register derivative works on Story Protocol for complete provenance tracking.

By leveraging Story Protocol and the Sepolia testnet, Watchdo provides a robust solution for managing and protecting digital IP in the evolving landscape of Web3.
