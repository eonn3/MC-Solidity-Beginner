# GLOOMY
Gloomy is a Solidity project surrounding a coin called GLOOMY ($GLM).

## Description
myToken.sol has a contract called MyToken, which has three variables: tokenName, tokenAbbrv, and totalSupply. This contract has two functions: mint for adding $GLM and burn for destroying $GLM.

## Creating $GLM Tokens
To mint $GLM, call the function ```mint(address, value)``` with the address of the target wallet and the amount you want to mint as the parameters. This adds the amount to the wallet and the total token supply.

## Burning $GLM Tokens
To burn $GLM, call the function ```burn(address, value)``` with the address of the target wallet and the amount you want to burn as the parameters. This function will check if the amount in the wallet is sufficient and will only push through with the burn if the amount passed to the burn() function is not less than the balance of the wallet provided. Once the burn pushes through, the total supply and the balance of the wallet will decrease.

## Author
Eonn Domingo

## License
This project is licensed under the MIT License.
