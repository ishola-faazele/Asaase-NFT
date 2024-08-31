# ASAASE NFT
## Link
- Smart Contract: https://github.com/ishola-faazele/asaase-smart-contract
- Subgraph: https://github.com/ishola-faazele/asaase-subgraph
- FrontEnd: https://github.com/ishola-faazele/asaase-frontend
- Contract On Celo: https://alfajores.celoscan.io/address/0xfb36c13360122ac1985d476a60d991905525d24a
  
### Project Description: Solving Land Acquisition and Registration Issues with Blockchain Technology

**Problem Statement:**
The land acquisition and registration process faces significant challenges, including:

1. **Lack of Transparency in Land Transactions:** The absence of a clear, transparent record of land transactions leads to mistrust and potential fraud.
2. **Multiple Allocations of the Same Land:** The same piece of land can be allocated to multiple parties, resulting in ownership disputes.
3. **Difficulty Verifying Rightful Owners:** Verifying the true owner of a land parcel is often complex and time-consuming, leading to delays and legal issues.
4. **Disputes Over Boundaries:** Uncertainty and conflict over land boundaries frequently result in long-standing disputes.

**Solution:**
The project harnesses the power of blockchain technology to overcome these challenges:

- **Blockchain for Transparency:** By recording all land transactions on a blockchain, we ensure an immutable, transparent history for each land parcel that is accessible to all stakeholders.
- **NFTs for Unique Land Ownership:** Each land parcel is represented as a non-fungible token (NFT), ensuring uniqueness and preventing multiple allocations.
- **Verifiable Ownership on the Blockchain:** Ownership data is securely stored on the blockchain, making it easily verifiable and reducing the risk of fraud.
- **Boundary Verification:** Blockchain-backed records help verify land boundaries, reducing disputes and enhancing trust.

**Data Querying with The Graph:**
To effectively manage and access the data stored on the blockchain, we utilize The Graph. This decentralized indexing and querying protocol allows us to efficiently query the blockchain for relevant data, such as ownership details, transaction history, and land boundaries. By integrating The Graph into our solution, we can provide real-time access to critical information, enhancing the transparency and reliability of land transactions.

**Tech Stack:**
- **Blockchain & NFTs:** Secure land transactions and ownership verification.
- **The Graph:** Efficient querying of blockchain data.
- **Web Technologies:** 
  - **React** for building a responsive user interface.
  - **Web3** and **ethers** for interacting with the blockchain.
  - **Leaflet** and **React-Leaflet** for mapping and visualizing land boundaries.
  - **GraphQL-Request** for querying data from The Graph.
  - **Recharts** for data visualization.
  - **Tailwind CSS** for styling.
- **Other Tools:**
  - **@metamask/detect-provider** for wallet connection.
  - **@tanstack/react-query** for data fetching and caching.
  - **React-Router-Dom** for client-side routing.
