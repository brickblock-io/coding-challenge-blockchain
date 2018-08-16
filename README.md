# Brickblock Coding Challenge - Ethereum

## The Goal
Your task is to write a smart contract that creates your own [ERC20-based token](https://en.wikipedia.org/wiki/ERC20) and build a small [Dapp](https://ethereum.stackexchange.com/questions/383/what-is-a-dapp) for it, using [React](https://reactjs.org).

## The Process
1. Create a new repo wherever you like. Can be GitHub/GitLab/Bitbucket, doesn't matter.
1. In your repo, write a smart contract that implements the [ERC20 standard](https://theethereum.wiki/w/index.php/ERC20_Token_Standard) plus some custom functionality. Being a security token company, this could be anything around dividend payouts, a whitelist to restrict trades to a certain set of users, burning and minting new tokens (think ETF shares) or something we can't even imagine. Surprise us :)
1. Deploy your smart contract to a testnet of your choice
1. In your repo, create a new React app that interacts with your smart contract(s) in a useful way.
1. Create a README.md explaining how to test the features you have built. Feel free to add additional thoughts, e.g. why you chose certain libraries or why you implemented a feature in a certain way etc.
1. Send us an email to dev@brickblock.io when you're ready to have it reviewed

## Acceptance Criteria
* Your smart contract has been deployed to either the Ropsten, Kovan or Rinkeby testnet
* Your smart contract implements the [ERC20 standard](https://theethereum.wiki/w/index.php/ERC20_Token_Standard)
* Your Dapp should be easy to install and run locally
* Your Dapp should at least be able to display the token balance of your ERC20 token for a given Ethereum address

## Bonus Round (not required but nice-to-have)
* Display the token balance of the currently active MetaMask account
* Add a button to transfer tokens from the currently active MetaMask account to another address
* Dockerize the app
* Deploy the app somewhere
* Anything else you could think of that would be cool for a web wallet to do. Surprise us…

## Rules
There are not many rules, really. It's all about the result. However, here are a few clarifications:

* Feel free to use as many 3rd party libraries or contracts as you'd like. For example, it's fine to use truffle boxes or [zeppelin-solidity](https://github.com/OpenZeppelin/zeppelin-solidity). However, if you just drop in an empty ERC20 contract from OpenZeppelin: We won't be impressed.
* It’s ok and even encouraged to look for inspiration elsewhere but if you're taking the lazy way of just copy-and-pasting CodePen snippets: We won't be impressed.

## How we're evaluating the result
Prioritised from most important to least important, here are our evaluation criteria:

1. Feature Completeness: Does your Dapp fulfil all acceptance criteria?
1. UX: Is the Dapp easy to understand and use?
1. Code Quality: Is the code clean, well-structured and easy to understand?
1. The extra mile: Did you write tests? Are code quality tools such as eslint, flow, prettier or solium in place? Is there documentation on how to get the app running?

You do not need to hit all points, but obviously, the more the better :)
