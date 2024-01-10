# Running Competition 

## Overview

This Solidity smart contract facilitates a running competition on the Ethereum blockchain. Participants can record their running speeds, and the contract includes criteria for participation.

## Features

 **Runner Speed Recording:** Participants can use `recordRunnerSpeed` to log their running speed. The recorded speeds are associated with participants' Ethereum addresses.

 **Winner Event Logging:** The contract emits a `Winner` event to log the winner's address based on recorded speeds.

 **Participation Criteria Check:** The `checkParticipationCriteria` function ensures participants meet criteria: weight > 60kg and past record speed > 7 meters per second.

## Usage

 **Recording Speed:** Call `recordRunnerSpeed` with your speed (must be >= 10 m/s).

 **Participation Criteria:** Ensure your weight is > 60kg, and past record speed is > 7 m/s before participating.

 **Winner Determination:** The highest recorded speed determines the winner.

## License

This contract made is under the MIT License. See [LICENSE](LICENSE) for details.

## Author

Madhumati

mvmati99@gmail.com
