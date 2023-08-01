# CIRCUIT USING CIRCOM
In this project I've made a circuit using circom and deployed it on Mumbai testnet on Polygon chain.
## Description
1.In this I'm submitting the project of  Polygon [Advanced] course which has been given by Metacrafters. 

2.In this project I've created a circuit using gates and the requirements given on the project using circom language.
 
3.Then I've to verify that circuit on custom inputs.

4.Then Generate a proof using inputs A=0 B=1

5.Then deploy the verifier on Mumbai Testnet.

6.Call the verifyProof() method on the verifier contract and the assert output should be true
## Installation
1.Clone the repository given by metacrafters,or You can Clone my Repo,by using the git clone <link> command.

2.Then run the command npm i to install all the dependencies.

3.Create an .env file and store your private key there.
## Compilation and Deploy
1.For compilation of circom file, run this command
 npx hardhat circom
 
2.For deployment run this command
npx hardhat run scripts/deploy.ts --network mumbai

3.Then Deploy on Mumbai Testnet by running this command
npx hardhat run scripts/depoly.ts --network mumbai
## Author
Nisha- nishaneha924@gmail.com


 
