# EquiXswap-lib

Cloned from: [uniswap-lib](https://github.com/Uniswap/solidity-lib/commit/c01640b0f0f1d8a85cba8de378cc48469fcfd9a6).

[![Tests](https://github.com/equiXswap/EquiXswap-lib/workflows/Tests/badge.svg)](https://github.com/equiXswap/EquiXswap-lib/actions?query=workflow%3ATests)
[![Static Analysis](https://github.com/equiXswap/EquiXswap-lib/workflows/Static%20Analysis/badge.svg)](https://github.com/equiXswap/EquiXswap-lib/actions?query=workflow%3A%22Static+Analysis%22)
[![Lint](https://github.com/equiXswap/EquiXswap-lib/workflows/Lint/badge.svg)](https://github.com/equiXswap/EquiXswap-lib/actions?query=workflow%3ALint)
[![Fuzz Testing](https://github.com/equiXswap/EquiXswap-lib/workflows/Fuzz%20Testing/badge.svg)](https://github.com/equiXswap/EquiXswap-lib/actions?query=workflow%3A%22Fuzz+Testing%22)
[![npm](https://img.shields.io/npm/v/@equixswap/lib)](https://unpkg.com/@equixswap/lib@latest/)

Solidity libraries that are shared across EquiXswap contracts. This package focuses on safety and execution gas efficiency.

## Install

Run `yarn` to install dependencies.

## Test

Run `yarn test` to execute the test suite.

## Usage

Install this in another project via `yarn add @equixswap/lib`

Then import the contracts via:

```solidity
import '@equixswap/lib/contracts/libraries/Babylonian.sol';

```
