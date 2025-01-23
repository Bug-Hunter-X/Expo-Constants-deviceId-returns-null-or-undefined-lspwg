# Expo Constants.deviceId returns null or undefined

This repository demonstrates a common issue encountered when using `Constants.deviceId` in Expo applications: receiving `null` or `undefined` when attempting to retrieve the device ID. The issue is often due to timing or platform inconsistencies.

The `bug.js` file showcases the problematic code, while `bugSolution.js` provides a robust solution to handle cases where the ID is unavailable.  This example focuses on asynchronous handling to ensure the device ID is ready before use.

## Setup

1. Clone this repository.
2. Navigate to the project directory.
3. Run `npm install` or `yarn install`.
4. Start the development server using `expo start`.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request if you find any improvements or have alternative solutions.
