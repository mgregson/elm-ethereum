# <img src="https://cdn.rawgit.com/cmditch/elm-web3/master/elm-web3-logo.svg" width="75"> elm-web3
###### Feed the tree some ether.

## Give it a try :smiley:    

First Install Geth    
https://geth.ethereum.org/downloads/

Second Install Elm things    
```
npm install -g elm
npm install -g elm-live
```
Then get elm-web3 and open test/example page   
```
git clone https://github.com/cmditch/elm-web3.git
cd elm-web3/
npm run test
```
Run the local Geth testnet in a new terminal window    
To allow for tests involving tx's and subscriptions mine a little.   
```
npm run testnet
miner.start(1)
```

open http://localhost:8000/test   
