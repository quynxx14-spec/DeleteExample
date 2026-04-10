# DeleteExample
DeleteExample.sol
pragma solidity ^0.8.20;
contract DeleteExample {
    uint public num;

    function set(uint _num) public {
        num = _num;
    }

    function reset() public {
        delete num;
    }
}
