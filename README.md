# challenge6sol
// SPDX-License-Identifier: MIT
pragma solidity 0.8.7;

contract con1 {
    //sum of first 1000 integers
    function sumOF1000() public pure returns (uint){
    uint i = 0;
    uint sum = 0;
    while (i < 1000){
    sum += i ;
    }
 return sum;
}

    //odd numbers till 100
    function sumof100() public pure returns (uint){
        uint j = 0;
    uint summation = 0;
    while (j < 1000){
    summation += j ;
    }
 return summation;
    }
}
