# StepCounter.sol
StepCounter.sol3
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract StepCounter {
    uint public count;

    function increment() public {
        count++;
    }

    function decrement() public {
        count--;
    }
}
Add 20 simple contracts for practice
Improve gas efficiency
