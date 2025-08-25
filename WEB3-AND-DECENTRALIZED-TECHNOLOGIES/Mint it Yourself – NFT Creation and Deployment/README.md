# Lab 7 – NFT Creation and Deployment using IPFS and Smart Contract

## Objective
Create and deploy an NFT using IPFS for storage and a smart contract on a blockchain test network.

## Steps
1. **Upload Image to IPFS (Pinata):**
   - Log in to Pinata and upload the NFT image/logo.
   - Copy the IPFS link of the image.

2. **Create Metadata JSON:**
   - Include the image IPFS link and other metadata.
   - Upload the JSON file to Pinata and copy its IPFS link.

3. **Write and Deploy Smart Contract:**
   - Use Remix IDE to write an NFT smart contract.
   - Connect MetaMask to Sepolia Testnet and deploy the contract.

4. **Mint NFT:**
   - Call the `mint` function with:
     - Your wallet address.
     - The metadata IPFS URI.

5. **Verify NFT:**
   - Check MetaMask under the NFTs section to confirm the minted NFT.

## Tools Used
- **Pinata** (IPFS Storage)
- **Remix IDE**
- **MetaMask**
- **Ethereum Sepolia Test Network**

## Observations
- The NFT image and metadata were successfully uploaded to IPFS using Pinata.
- The smart contract was deployed on Sepolia via Remix and MetaMask.
- Minting linked the NFT to the wallet using the IPFS metadata URI.
- NFT appeared in MetaMask under the NFTs tab after minting.

## Final Output
NFT successfully created and visible in MetaMask with decentralized storage via IPFS.
