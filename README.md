# eth
eth contracts
// Specify the version of Solidity
pragma solidity ^0.8.0;

// Define a contract named Counter
contract Counter {
  // Declare a state variable named count of type uint (unsigned integer)
  uint public count;

  // Define a constructor that sets the initial value of count to zero
  constructor() {
    count = 0;
  }

  // Define a function named increment that increases count by one
  function increment() public {
    count += 1;
  }

  // Define a function named decrement that decreases count by one
  function decrement() public {
    count -= 1;
  }

  // Define a function named reset that sets count to zero
  function reset() public {
    count = 0;
  }
}
