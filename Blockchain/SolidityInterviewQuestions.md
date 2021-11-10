# Solidity Interview Questions

In this article you will find a lot of questions to prepare your Solidity job interview. Questions are grouped into easy, intermediate and difficult categories.

- [Easy](#Easy)
- [Intermediate](#Intermediate)
- [Difficult](#Difficult)

### Easy <span id="Easy"><span>

> ##### What is an Ethereum smart contract?
> It's a small program that runs on the EVM/Ethereum blockchain.

> ##### What makes an Ethereum smart contract so special compared to other programs?
> Once an Ethereum smart contract has been deployed to the blockchain it cannot be stoped, hacked (if no bugs was found), or modified. Even if you are a creator of the smart contract. Data of the smart contract can be modified.

> ##### Can a smart contract interact with other smart contracts?
> Yes. It's what makes smart contracts so powerful. 

> ##### Can a Solidity smart contract call an API on the web?
> No. A smart contract can execute only its code and interact with other smart contracts on the Ethereum blockchain. If you need your smart contract to interact with an API the pattern you use is the Oracle pattern where an external API calls a function on the smart contract and fills it with some data. And after that smart contract can make use of this external data.

> ##### Can a Solidity smart contract store a lot of data?
> No. Storing data in the smart contract cost gas. Gas consumption is capped in each Ethereum block. So indirectly storage is limited.

> ##### Can a smart contract be written in another language than Solidity?
> Yes. Vyper, LLL but Solidity is more popular.

> ##### Is Solidity is dynamically or statically typed language?
> Statically typed which means that variable types need to be defined.

> ##### Is Solidity compiled or interpreted?
> Compiled. That means that before we are able to run a smart contract we need to first compile it.

> ##### Can a single Solidity file have several smart contracts?
> Yes. I just have to use the contract keyword several times.

> ##### What is the typical layout of a Solidity smart contract?
> First, we need to put a pragma statement to indicate to the Solidity compiler which version of solidity we want to use. This is for avoiding mistakes where you write a smart contract for one version of solidity but accidentally use another version when you compile.

### Intermediate <span id="Intermediate"><span>
### Difficult <span id="Difficult"><span>
