# Decentralized Token Exchange DApp

This dApp is made to perform fully functional Web3 Decentralized Exchange, from start to finish. It will allow users to swap erc20 tokens to other erc20 tokens on a selected EVM Chain.

We have build the project using ReactJS, NodeJS, Moralis, Wagmi.

To run this dApp, follow the below steps:

1. First, clone the repository.
2. Then, go to the dex folder which contains all the frontend files of the project and install the dependencies using ```$ npm i```.
3. Then, do the same for the dexBack folder which contains the backend files of the project and install the dependencies.
4. Go to the [Moralis](https://moralis.io/) website and take your API key and paste it in the ```.env``` file of the 'dexBack' folder.
5. Then move back to the frontend folder and run the following command:

    ```shell
    $ npm run start
    ```
6. Go to the backend folder and run the following command:
   
   ```shell
   $ node index.js
   ```