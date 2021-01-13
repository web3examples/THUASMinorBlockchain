


# Details for the course Programming DAPPs on THUAS 2020/2021

## Schedule

|Date   |Day |Time  |Goal                |  Subject1                | Subject 2
|---    |--- |----  | --                 | ---------                | -------------
|11 nov |Wed |13.00 | Kickoff            | PD-1 Introduction        |
|20 nov |Fri |13.00 | Online session     | PD-2 First smart contract  
|27 nov |Fri |13.00 | Online session     | PD-3 Remix               | PD-4 Nodes
|4 dec  |Fri |13.00 | Online session     | PD-5 Web3.js             | PD-6 Other browsers
|11 dec |Fri |13.00 | Online session     | PD-7 Truffle             | PD-8 Oracles
|18 dec |Fri |13.00 | Online session     | PD-9 Best practices      | PD-10 Tokens
|26 dec |Fri | -    | Christmas holidays | 
|1 jan  |Fri | -    | Christmas holidays | 
|8 jan  |Fri |13.00 | Online session     | PD-11 IPFS               | PD-12 Security
|15 jan |Fri |13.00 | Online session     | PD-13 Tests              | PD-14 ENS
|22 jan |Fri |13.00 | Online session     | PD-15 New developments   | PD-16 End assignment
|29 jan |Fri |13.00 | Online session     | PD-16 End assignment

## Assignments

For each subject: study the material and try out the examples to get experience with is.
Install all the mentioned software and experiment.
Also look around on internet and on the other supplied source the get more information.

The idea is that we start with a simple smart contract that we are building out during the classes.
So put some thought in your first smart contract.
This could be:
- a small game
- a mini registration (database)


Provide prove of what you have done by putting the source code and/or a screen shot on github:
[web3assignments]

## Subjects

| Subject                    | Preparations            | Assignments
| ----------------------     | ------------            | -----------------
| PD-1 Introduction          | -                       | Supply: github account 
| PD-2 First smart contract  | Follow cryptozombies    | Create a smart contract => capture source
|                            | Read mastering ethereum |
| PD-3 Remix                 |                         | Adapt or create a smart contract with error handling, mapping, events => capture source
| PD-4 Nodes                 |                         | Use play editor with Ganache => capture screen
|                            |                         | Install Geth, Protheus, Grafana + dashboard => capture screen
| PD-5 Web3.js               | Study javascript        | Generate vanity address with >= 5 lead characters => capture priv key & address
|                            |                         | Deploy your smartcontract on testchain<br>make html+js program to call your contract<br>runnable via github pages https://web3assignments.github.io/BC3_{name}/PD-05/...<br>(generate production version when using a framework)<br>+ show log events => store source & capture screen
| PD-6 Other browsers        |                         | Send a transaction, preferable your own site, or [send] on:<br>- metamask mobile<br>- opera desktop<br>- opera mobile<br>- brave
| PD-7 Truffle               | Get Infura key          | Adapt your contract for truffle & deploy on test chain => store source & contract addresses
| PD-8 Oracles               |                         | Integrate an oracle in your smart contract => capture screen & source
| PD-9 Best practices        |                         | Update your smart contract with 3 of the following: <br>- add a modifier; <br>- add a selfdestruct function; <br>- if you use send or transfer, replace it with call; <br>- add natspec comments<br>- add safemath
|                            |                         | Deploy your contract with openzeppelin truffle-upgrades & do an upgrade => store source & contract addresses
|                            |                         | Verify your contract on etherscan => capture screen & store address
| PD-10 Tokens               |                         | Create fungible token contract & send tokens to 0xEA9a7c7cD8d4Dc3acc6f0AaEc1506C8D6041a1c5 => capture address, screen, source
|                            |                         | Create non fungible token contract + image & show on opensea & send token to 0xEA9a7c7cD8d4Dc3acc6f0AaEc1506C8D6041a1c5 => capture address, screen, source
| PD-11 IPFS                 |                         | Create website to store & retrieve images on IPFS => capture source
|                            |                         | Store the website itself on IPFS => capture cid
| PD-12 Security             |                         | Adapt your smart contract with access control => capture source
| PD-13 Tests                |                         | Add (at least 5) unit tests to your smart contract => capture source and test results
| PD-14 ENS                  |                         | register ENS name (on testnetwork), connect it to your smart contract, use it in your website to address the contract => capture source
|                            |                         | register ENS name (on testnetwork), connect it to your IPFS site => capture screen of ENS application (https://app.ens.domains/) {on mainnet you can directly use this with metamask}
| PD-15 New developments     |                         | 
| PD-16 End assignment       |                         | Combine all you have learned into one app => capture source and screen

[send]: https://web3examples.com/ethereum/web3js_browser/sendtransaction.html

[web3assignments]:  https://github.com/web3assignments

[possiblequestion1]: Integrate metatransactions in your app => capture source and screen
[possiblequestion2]: Create mini app with layer 2 => capture source and screen
[possiblequestion3]: Install metamask snaps beta; adapt example to get address 0x00..01 in  your metamask => capture screen
[possiblequestion4]: Add a query from a graph to your app
[possiblequestion5]: Integrate 3box profile in your app => capture source







