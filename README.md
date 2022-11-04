# Smart Contracts Template

> A smart contracts development demplate by Commmon Prefix.

## Installation 

```bash
yarn install 
```

## Testing
 
```bash
# forge tests
yarn test

# hardhat tests
yarn test:hardhat
```

## Development Notes

Whenever you install new libraries using Foundry, make sure to update your `remappings.txt` file by running `forge remappings > remappings.txt`. This is required because we use `hardhat-preprocessor` and the `remappings.txt` file to allow Hardhat to resolve libraries you install with Foundry.
