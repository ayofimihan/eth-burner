# eth-burner

Watches each block for a balance update, and if one is detected, burns all that ETH by transferring ETH with the highest possible transaction fee, effectively burning it from the account.

## wanna burn?

```sh
# only do this once
yarn install

# burn eth in account corresponding to given prvkey

yarn start -k <your private key> -u https://sepolia.infura.io/v3/<key> -b <your public key>




```

_If you want to test this out without burning real ETH, use a testnet provider or a hardhat fork with url `http://localhost:8545`._
