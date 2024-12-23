This repository contains a Solidity smart contract with an integer overflow bug and its solution. The bug occurs in the `add` function when adding large numbers that exceed the maximum value of the `uint256` data type. The solution involves using SafeMath library to prevent integer overflow.