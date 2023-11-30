---
layout: default
---

# Open Source Work

Most of my open source work has been to facilitate blockchain development in Haskell and PureScript for applications targeting Ethereum or Cosmos. I have also done some general library development in the PureScript language, especially in the area of embedding geospatial visualizations in frontend applications.

## calc
[calc](https://github.com/martyall/calc) is a language which compiles to plonk circuits and uses a plonk2 backend for generating and verifying ZK proofs. The project is currently written in rust.

## purescript-web3
The PureScript Web3 suite is composed of three libraries to facilitate Ethereum development in PureScript:
1. [purescript-web3](https://github.com/f-o-a-m/purescript-web3) - comprehensive bindings to the Ethereum Web3 API.
2. [purescript-web3-generator](https://github.com/f-o-a-m/purescript-web3-generator) - a code generator that can produce FFI code from a smart contract ABI.
3. [purescript-eth-core](https://github.com/f-o-a-m/purescript-eth-core) - a low level Ethereum library for dealing with encodings, cryptographic operations, and other basic Ethereum types.

## Chanterelle
[Chanterelle](https://github.com/f-o-a-m/chanterelle) is a framework and CLI tool for writing, testing, and managing smart contracts on Ethereum. You can read more about the motivation in this [initial release post](https://medium.com/foam-space/introducing-chanterelle-d284bdfc0e71).

## Kepler
[Kepler](https://github.com/f-o-a-m/kepler) is a Haskell language implementation of an ABCI server and a framework for developing Cosmos/Tendermint backed applications in Haskell. The [documentation site](https://kepler.dev/) has a complete breakdown of the project as well an extensive example application. The initial development of Kepler was supported by an [ICF](https://interchain.io/) grant.

## hs-web3
I am a primary contributer to the [hs-web3](https://github.com/airalab/hs-web3) library, the official library for the Ethereum and Polkodot Web3 APIs, as well as supporting libraries defining things like cryptographic operations, code generation from smart contract ABIs, and an IPFS client library. 

## purescript-deck-gl
[purescript-deck-gl](https://github.com/f-o-a-m/purescript-deck-gl) is an exhaustive PureScript wrapper of Uber's [deck.gl](https://deck.gl/) library for high-performance rendering of geospatial visualizations in the browser. As deck.gl is primarily used through the React component interface, I also developed a [purescript-react-map-gl](https://github.com/f-o-a-m/purescript-react-map-gl) wrapper library to allow for easy embedding in purescript-react based applications.

## purescript-servant
[purescript-servant](https://github.com/f-o-a-m/purescript-servant) is an implementaion in PureScript of a subset of the [servant](https://docs.servant.dev/en/stable/) type-level web DSL library. It allows you to specify client libraries in PureScript in a servant like fashion.

[home](./)
