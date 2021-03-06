![academy_logo](https://github.com/cyberacademia/cyberevents/blob/kovan/img/academy_logo.png)

# Cyberevents

We’re going to realize an automated event organization blockchain platform. Our solution is a DApp, where participants can sign up, get their tickets and easily check in on the event. All these operations occur in the network of smart contracts and the entrance tickets are ERC721 tokens

# Test

If you want to run tests you need next dependencies

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org)
- [npm](https://www.npmjs.com/get-npm)
- [Truffle](https://truffleframework.com/)
- [Ganache](https://truffleframework.com/ganache) or [ganache-cli](https://github.com/trufflesuite/ganache-cli) (Ganache recommended)

Clone this repository

```sh
git clone https://github.com/cyberacademia/cyberevents
```

> _Make sure that you run all next commands in the repository root_

Install project node dependencies

```sh
npm install
```

To run all tests with npm

```sh
npm test
```

To run all tests with truffle

```sh
# <testrpc> : testrpc you're running (eg --network-ganache, in the truffle-config.js you can find all networks names)
truffle test --network-<testrpc>
```

To run the specified test

```sh
# <path-to-test> : path to the test file you're going to run (eg test/TestTicket.test.js)
truffle test <path-to-test> --network-ganache
```

# License

Licensed under the [MIT license](https://github.com/cyberevents/cyber-academy-dapp/edit/master/LICENSE), copyright © 2018 [Cyber Academy](https://github.com/cyberevents)
