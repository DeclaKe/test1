# Deploying NFTs with Remix

## **1. Code Preparation**

In the Remix IDE, write your smart contract code within the 'contracts' directory. Make sure your code is well-structured and tested.

<figure><img src="../.gitbook/assets/image (3).png" alt=""><figcaption></figcaption></figure>

You may use [our project's contract code](https://github.com/xueyuanhuang/nft-workshop), but you need to slightly alter it.

## **2. Compile Smart Contract**

Compile the smart contract code to check for any errors and prepare it for deployment.

<figure><img src="../.gitbook/assets/image (4).png" alt=""><figcaption></figcaption></figure>

## **3. Deploy & Run Transactions**

Navigate to the 'Deploy & Run Transactions' plugin.

## **4. Select Environment**

Choose 'Injected Provider - MetaMask' as your environment to connect Remix with your MetaMask wallet.

<figure><img src="../.gitbook/assets/image (5).png" alt=""><figcaption></figcaption></figure>

## **5. Deployment Setup**

Under the 'Deploy' section, input 'initialOwner' with the wallet address that will own the contract.

<figure><img src="../.gitbook/assets/image (6).png" alt=""><figcaption></figcaption></figure>

## **6. Base URL Entry**

For '\_initBaseURL', input the base URL for your metadata, which should look like "[https://gateway.pinata.cloud/ipfs/](https://gateway.pinata.cloud/ipfs/)\<your-ipfs-hash>". Replace "\<your-ipfs-hash>" with the actual IPFS hash location of your metadata JSON. Ensure you can navigate to this URL in your browser to verify its correctness.

<figure><img src="../.gitbook/assets/image (7).png" alt=""><figcaption></figcaption></figure>

## **7. Initiate Deployment**

Click 'transact' to deploy your smart contract to the blockchain.

<figure><img src="../.gitbook/assets/image (8).png" alt=""><figcaption></figcaption></figure>
