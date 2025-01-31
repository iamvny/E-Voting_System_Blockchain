## ABOUT
A blockchain-based voting system that preserves voter privacy and increases accessibility, while keeping the voting system transparent, secure, and cost-effective. The system implements a voting framework that utilizes ethereum’s blockchain and smart contracts to achieve voter administration and auditable voting records. The implementation was deployed on ethereum’s test network to demonstrate usability, scalability, and efficiency.

Check out the detailed implementation at https://medium.com/@meshram.vinay2003/e-voting-system-based-on-blockchain-1a3facbe3e51

Pre requisites:
1. Node JS
2. Ganache
3. Metamask extension in the browser, preferably chrome.

## SET UP INSTRUCTIONS

Open ganache and select quick start ethereum.

Open your browser and configure metamask. Create a wallet and store your```Secret Recovery Phrase``` in a safe place.

#### Connecting metamask and ganache
1. In metamask, go to settings > networks > add network. You can also get to this by clicking the metamask extension pinned on your browser > clicking the profile picture > settings > networks > add network
2. Give your network any name of choice. 
3. For New RPC URL go to ganache where you'll copy the RPC server url and paste in Metamask. 
4. Chain ID for ganache is 1337. 
5. You can name currency symbol as "ETH" and save. 

#### Importing an account from ganache to metamask
1. Open ganache and select show keys on any account. The show keys button is the key icon.
2. Copy the private key and click done.
3. Open the metamask menu which can be accessed by clicking the profile picture and select import account.
4. Paste the private key copied from ganache and click import.

#### Cloning the project

```git clone https://github.com/iamvny/E-Voting_System_Blockchain```

```cd E-Voting_System_Blockchain```

```npm i```

```truffle compile```

```truffle migrate```or```truffle migrate --reset``` for subsequent runs

```npm start```

The project will open in the browser and metamask will ask you to select an account. Select the account we had imported earlier.


![Screenshot 2025-01-30 141753](https://github.com/user-attachments/assets/7f1b1afd-bd00-44fe-9cfe-cdd6c09d09ea)

![Screenshot 2025-01-30 151442](https://github.com/user-attachments/assets/64a72a2f-b4a2-48f0-abef-607fd7f5f8ec)

![Screenshot 2025-01-30 151748](https://github.com/user-attachments/assets/c704095b-201a-4f1f-911f-a2a74aa8ea32)

![Screenshot 2025-01-30 151801](https://github.com/user-attachments/assets/c0e7c9eb-b91e-4a6a-9852-7278dde3b26f)

![Screenshot 2025-01-30 145004](https://github.com/user-attachments/assets/ca2a1ab9-073a-4dcd-96c1-95842e4a5400)




