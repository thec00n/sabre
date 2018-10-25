# Sabre

A quick-and-dirty CLI for [Mythril Platform](https://mythril.ai).

## Usage

```
$ export MYTHRIL_API_KEY=xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx
$ export MYTHRIL_API_URL=https://api.myhthril.ai/
$ node sabre.js mycontract.sol 

__mycontract.sol __
3     Low     State Variable Default Visibility    https://smartcontractsecurity.github.io/SWC-registry/docs/SWC-108
5     Low     Function Default Visibility          https://smartcontractsecurity.github.io/SWC-registry/docs/SWC-100
14    High    Reentrancy                           https://smartcontractsecurity.github.io/SWC-registry/docs/SWC-107
```
