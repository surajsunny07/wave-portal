# Basic Sample Hardhat Project

This project demonstrates a basic Hardhat use case. It comes with a sample contract, a test for that contract, a sample script that deploys that contract, and an example of a task implementation, which simply lists the available accounts.

PROJECT SUMMARY
* What exactly we are doing here is 
- We have enabled the user to connect to the meta mask wallet from our application
- Once the user is connected to the meta mask wallet we are asking the user to wave and enter some message (ex : "HI")
- Here for us a wave is nothing but just a count
- Every time the user hits the wave we are updating the count increment and message in storage
- As we know to update the storage in the blockchain it needs some gas cost and that will be done by the user who is waving at us.

Try running some of the following tasks:

```shell
npx hardhat accounts
npx hardhat compile
npx hardhat clean
npx hardhat test
npx hardhat node
node scripts/sample-script.js
npx hardhat help
```
