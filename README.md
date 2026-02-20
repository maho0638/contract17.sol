# contract17.sol
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.0;

// Solidity mapping example for Web3
contract Contract17 {
    mapping(address => uint) public balances;

    function setBalance(uint amount) public {
        balances[msg.sender] = amount;
    }
}
