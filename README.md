# Sample Hardhat Project

This project demonstrates a basic Hardhat use case. It comes with a sample contract, a test for that contract, and a script that deploys that contract.

Try running some of the following tasks:

```shell
npx hardhat help
npx hardhat test
REPORT_GAS=true npx hardhat test
npx hardhat node
npx hardhat run scripts/deploy.js
```



# Loading environment variables
The configuration in ```hardhat.config.ts``` uses dotenv to load the ```PRIVATE_KEY``` environment variable from a ```.env``` file to     ```process.env.PRIVATE_KEY```. You should use a similar method to avoid hardcoding your private keys within your source code.

To install dotenv, run:

```npm install --save-dev dotenv```

Once you have dotenv installed, you can create a .env file with the following content:

```PRIVATE_KEY="<YOUR_PRIVATE_KEY>"```

Substituting ```<YOUR_PRIVATE_KEY>``` with the private key for your wallet.
