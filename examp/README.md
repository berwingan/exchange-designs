npx hardhat init
    -Create an empty hardhat.config.js
    -add require("@nomicfoundation/hardhat-toolbox"); to top of config.js


contracts/
    Token.sol

npx hardhat compile 

test/
    -fixture tests

npx hardhat test
    
Debug
    -import "hardhat/console.sol"; in .sol code
    
[BoilerPlate]
cd hardhat-boilerplate
npm install
npx hardhat node
npx hardhat --network localhost run scripts/deploy.js
cd frontend
npm install
npm run start