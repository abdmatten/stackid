# StackID Smart Contract

A Clarity smart contract built on the Stacks blockchain.

## Development Setup

### Prerequisites

- [Clarinet](https://github.com/hirosystems/clarinet) - The Clarity development tool
- Node.js & NPM

### Installation

1. Clone the repository
2. Install dependencies:
```sh
npm install
```

### Testing

Run the test suite:
```sh
npm test
```

For detailed test reports including coverage and cost analysis:
```sh
npm run test:report
```

Watch mode for development:
```sh
npm run test:watch
```

### Project Structure

- `/contracts` - Smart contract source code
  - `stackid.clar` - Main contract
- `/tests` - Test files
- `/settings` - Network configuration files
