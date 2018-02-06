# Brickblock Coding Challenge - Ethereum

## The Goal
Your task is to write a smart contract that creates your own [ERC20 token](https://en.wikipedia.org/wiki/ERC20) and build a small web wallet [Dapp](https://ethereum.stackexchange.com/questions/383/what-is-a-dapp) for it, using [React](https://reactjs.org).

## The Process

1. Fork this repo
1. In your forked repo, write a smart contract that implements the [ERC20 standard](https://theethereum.wiki/w/index.php/ERC20_Token_Standard)
1. Deploy your smart contract to a testnet of your choice
1. In your forked repo, create a new React app
1. Create a pull request from your fork into this original repository.
1. In your pull request description, please add a section on how to test the features you have built. Feel free to add additional thoughts, e.g. why you chose certain libraries or why you implemented a feature in a certain way etc.
1. Mention @chapati23 or @mattgstevens in the pull request description to let us know you're ready for review. Alternatively, send us an email to dev@brickblock.io

## Acceptance Criteria
* Your smart contract has been deployed to either the Ropsten, Kovan or Rinkeby testnet
* Your smart contract implements the [ERC20 standard](https://theethereum.wiki/w/index.php/ERC20_Token_Standard)
* Your Dapp should be easy to install and run locally (e.g. [create-react-app](https://github.com/facebook/create-react-app))
* Your Dapp should be able to display the token balance of your ERC20 token for a given Ethereum address

## Bonus Round (not required but nice-to-have)
* Your Dapp could work together with MetaMask and display the token balance of the currently active MetaMask account
* Your Dapp could have a button that can transfer tokens from the currently active MetaMask account to another address
* Anything else you could think of that would be cool for a web wallet to do. Surprise us…

## Rules
There are not many rules, really. It's all about the result. However, here are a few clarifications:

* Feel free to use as many 3rd party libraries or contracts as you'd like. For example, it's fine to use truffle boxes or [zeppelin-solidity](https://github.com/OpenZeppelin/zeppelin-solidity). However, if you just drop in an empty ERC20 contract from OpenZeppelin: We won't be impressed.
* It’s ok and even encouraged to look for inspiration elsewhere but if you're taking the lazy way of just copy-and-pasting CodePen snippets: We won't be impressed.

## How we're evaluating the result
Prioritised from most important to least important, here are our evaluation criteria:

1. Feature Completeness: Does your Dapp fulfil all acceptance criteria?
1. UX: Is the Dapp working well?
1. Code Quality: Is the code clean, well-structured and easy to understand?
1. The extra mile: Did you write tests? Are code quality tools such as eslint, flow, prettier or solium in place? Is there documentation on how to get the app running?

You do not need to hit all points, but obviously, the more the better :)