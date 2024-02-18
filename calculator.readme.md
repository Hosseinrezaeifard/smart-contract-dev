### Visit contract on etherscan
https://sepolia.etherscan.io/tx/0x10b8fb50ff0f3e1365599bdd5fb523605760f1ab75fb73566f152a445cd6b415

### Function Visibility 
`public` keyword means the function could be used both externally and internally, for example Metamask or any other contract could use it

`private` keyword means the function could be used within the contract only

`internal` keyword means only the contract and inherited contracts are allowed to use this function, for example Metamask could not use it, but any other inherited contract or other functions of the contract will be using it like a piece of cake 

`external` keyword means function can be accessed from external contracts or accounts

