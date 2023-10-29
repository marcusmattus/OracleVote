# OracleVote

Our project is a DApp that aims to democratize access to superintelligent systems that may emerge in the near future. On our website, users can propose new prompts or vote on existing ones by staking FLR tokens. The prompts are then submitted to an LLM via Flock SDK at regular intervals. Users can also view the history of all prompts and their responses from the connected LLM and in the future a superintelligent AI. We believe that everyone should have a say in what questions are asked to the AI, rather than letting a few powerful entities control it. This way, we can reduce the risk of misuse and abuse of the AI, and foster a more inclusive and transparent dialogue with it.



- metamask
- hardhat
- reactjs
- tailwind css
- solidity
- ethersjs
- flare 
- flock

## running the demo

to run the demo follow these steps:

 clone the project with the code below.

   ```sh

   # make sure you have the above prerequisites installed already!
   git clone https://github.com/daltonic/oraclevoted
   cd dappyvote # navigate to the new folder.
   yarn install # installs all the dependencies.
   ```


   ```sh
   yarn install
   yarn hardhat node
   yarn hardhat run scripts/deploy.js
   ```
