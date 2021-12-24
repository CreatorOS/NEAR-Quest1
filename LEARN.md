# Create your NEAR MainNet and TestNet Wallets

In this quest, let us learn how to create our own NEAR MainNet and TestNet Wallets. 
**MainNet** is for production ready smart contracts and live token transfers. Contracts ready for mainnet should have gone through rigorous testing and independent security reviews if necessary. mainnet is the only network where state is guaranteed to persist over time (subject to the typical security guarantees of the network's validation process).

**TestNet** is a public network and the final testing network for nearcore changes before deployment to mainnet. testnet is intended for testing all aspects of the NEAR platform prior to mainnet deployment. From account creation, mock token transfers, development tooling, and smart contract development, the testnet environment closely resembles mainnet behavior. 
All nearcore changes are deployed as release candidates on first testnet, before the changes are released on mainnet. A number of testnet validators validate transactions and create new blocks. dApp developers deploy their applications on testnet before deploying on mainnet. It is important to note that testnet has its own transactions and states.

## Create your first NEAR MainNet Wallet
Here are the simple steps to create your first NEAR Mainnet Wallet:
1. Go to https://wallet.near.org/

2. Click on the **Create Account** button and set a name for your account. Once you type in a name, you would be notified if your requested account name is available. You can click on **Reserve my Account ID** button and proceed to the next page.

3. Choose a method to secure your account. **Secure Passphrase** or **Ledger Hardware Wallet** are highly recommended choices.

4. As the nexts step, in order to create an account, you would require to fund the wallet with NEAR using an initial deposit or provide an email ID/Phone number to recieve an OTP.

5. If you choose to go the OTP route, you can input the OTP once received and wait for your account to get created.

6. If you choose the funding option, you can fund the account with purchased NEAR from other exchanges and transferring to the newly created wallet's temporary address.

Viola! Now you have a functioning NEAR Wallet. You can use this wallet to store your NEAR tokens or any other tokens supported by the NEAR blockchain.

However, in order to test your application on TestNet, we will also show you how to create a TestNet wallet.

## Create your first NEAR TestNet Wallet
Here are the simple steps to create your NEAR TestNet Wallet:
1. Go to the following link and click on "Create Account":
https://wallet.testnet.near.org/

2. You can use a name that would be easy to remember to create your testnet account. Once you choose a name for your account and input in the box on this page, you will be able to get an account named **account_name**.testnet 
![Create An Account](/learn_src/learn_assets/Screenshot%202021-11-09%20at%2011.12.08%20PM.png)

3. In the next page, you would be required to secure your account using one of the 4 options available. "Secure Passphrase" is one of the most secure and recommended way of securing an account. We highly recommend that.
![Secure Account](/learn_src/learn_assets/Screenshot%202021-11-09%20at%2011.14.32%20PM.png)

4. Post securing your account using a secure 12-word phrase, you would need to verify the secure phrase requested on the screen and viola, you now have a NEAR TestNet account which can be used to test your Dapps. Your account would automatically be populated with ~200 NEAR for testing purposes.
