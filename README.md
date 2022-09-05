# DEX-Using-ERC20

For this smart contract, we’ll create a really dummy decentralized exchange where a user can trade Ethereum with our newly deployed ERC-20 token.

For this tutorial we’ll use the code we wrote in the previous tutorial as a base. Our DEX will instantiate an instance of the contract in its constructor and perform the operations of:

- exchanging tokens to ether
- exchanging ether to tokens

we now have our DEX and it has all the token reserve available. The contract has two functions:

- `buy`: The user can send ether and get tokens in exchange
- `sell`: The user can decide to send tokens to get ether back