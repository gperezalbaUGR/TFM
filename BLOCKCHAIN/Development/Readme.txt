//TO START A PRIVATE TESTNET FROM GENESIS.JSON
cd C:\Users\Guillermo\Documents\Master\TFM\BLOCKCHAIN\Development\Geth\geth-windows-amd64-1.8.13-225171a4
geth --datadir C:\Users\Guillermo\Documents\Master\TFM\BLOCKCHAIN\Development\PrivateNet init C:\Users\Guillermo\Documents\Master\TFM\BLOCKCHAIN\Development\PrivateNet\genesis.json

//TO INIT GETH
geth --datadir C:\Users\Guillermo\Documents\Master\TFM\BLOCKCHAIN\Development\PrivateNet
//TO ATTACH
geth attach ipc:\\.\pipe\geth.ipc

//TO START MINING
miner.start(2)
eth.getBalance(eth.coinbase)
miner.stop()

//INSTALL TRUFFLE
npm install -g truffle
truffle init

//INSTALL ETH TEST RPC
npm install -g ethereumjs-test

//TESTRPC NETWORK
testrpc

//ALTERNATIVA A TESTRPC ES GANACHE
ganache-cli 
o
Iniciar Ganache-1.2.1.appx que tiene interfaz

//PROJECT FROM TRUFFLE BOX
truffle unbox pet-shop
truffle unbox Quintor/angular-truffle-box

o elegir cualquier otro de: https://truffleframework.com/boxes

truffle migrate

truffle serve

