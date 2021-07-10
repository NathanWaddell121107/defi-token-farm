# defi-token-farm

## Get Started:

run `yarn`

make sure you have ganache for local ethereum network testing. https://www.trufflesuite.com/ganache

Open ganache using the quickstart button on the ethereum network

run `yarn truffle compile`

run `yarn truffle migrate`

Now the token contracts should be deployed to your test network

run the scripts below to see the farming / token balance / withdraw farm token working:

`yarn truffle exec .\scripts\get-my-token-balance.js`  
`yarn truffle exec .\scripts\transfer-to-farm-token.js`  
`yarn truffle exec .\scripts\withdraw-from-farm-token.js`
