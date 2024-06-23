# AnonHealth: Secure, Anonymous Healthcare Records on Blockchain



## Project Overview

AnonHealth, powered by blockchain technology, revolutionizes healthcare record management by ensuring secure, anonymous storage and easy access to medical records globally. This decentralized application (dapp) addresses critical issues in healthcare, such as data security, patient anonymity, and transparent fund allocation.

### Vision

AnonHealth aims to create a seamless and secure ecosystem where patients' medical records are stored anonymously on the blockchain. By leveraging decentralized technologies, AnonHealth ensures data integrity, eliminates vulnerabilities associated with traditional record-keeping, and facilitates global access to medical data for research and healthcare purposes.

### Key Features

- **Decentralized Storage**: Utilizes IPFS for storing medical records securely on a decentralized network, preventing tampering and unauthorized access.
  
- **Anonymity**: Patient records are linked to Ethereum public addresses, ensuring patient anonymity and confidentiality.
  
- **Research Accessibility**: Facilitates access to anonymized medical records for researchers to conduct health services, epidemiologic, and clinical studies.
  
- **Decentralized Autonomous Organization (DAO)**: Implements DAO principles to allocate funds transparently through decentralized voting, ensuring community participation and oversight.




## Challenges Faced

### 1. Verification

Verifying doctors and labs without involving third parties posed a challenge. We integrated Chainlink to verify credentials seamlessly.

### Solution:
- Integrated Chainlink to verify doctors and labs using their registration IDs against an external API directly in our smart contract.

### 2. Network Compatibility

During development, Chainlink's Rinkeby network was undergoing maintenance, prompting us to deploy on Kovan temporarily, which posed challenges with our subgraph deployment.

### Solution:
- Deployed dual instances: Rinkeby for smart contracts and Kovan for testing verification functionalities, maintaining compatibility and functionality.

**Note:** The dapp currently operates on the Rinkeby network.


## Technologies Used

- **Solidity**: Smart contract development for Ethereum blockchain.
- **IPFS**: Decentralized storage solution for medical records.
- **GraphQL API**: Integrated with TheGraph for efficient data querying and indexing.
- **Chainlink**: Oracle integration for verifying credentials securely.
- **React**: Frontend development framework for dynamic user interface.
- **Web3**: JavaScript library for interaction with Ethereum blockchain.

## Test AnonHealth Live

Explore AnonHealth and experience the future of decentralized healthcare records management: [AnonHealth Live](https://docthereum.web.app/).


By combining blockchain's security and decentralization with advanced technologies like IPFS and Chainlink, AnonHealth sets a new standard for healthcare data management, promoting transparency, privacy, and accessibility worldwide.