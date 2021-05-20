# RNZ contracts

## Test locally

1. Install [NodeJS](https://nodejs.org) v10.

2. Install the node dependencies:

```sh
npm install
```

3. Install truffle and ganache-cli (`sudo` permission might be needed):

```sh
npm install -g truffle ganache-cli
```

4. Run ganache-cli:

```sh
ganache-cli --gasLimit 8000000 --accounts 20
```

5. Use truffle to run tests:

```sh
truffle test
```

## Prepare artifact JSON files for sgn-explorer

1. Compile the contracts:

```sh
npx truffle migrate
```
