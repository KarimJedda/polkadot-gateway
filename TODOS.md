# TODO.md for Polkadot Gateway API

## Setup and Configuration
- [x] Set up project structure for Polkadot gateway
- [ ] Create an auto configuration method similar to `Gateway.configure()`
- [ ] Implement JSON configuration option like `Gateway.configure_from_json()`
- [ ] Add support for different networks or abstract those completely (e.g., Polkadot, Kusama, system chains, parachains)

## Wallet Management
- [ ] Implement `Wallet.create()` method for creating new wallets
- [ ] Add support for accessing default address of a wallet
- [x] Implement method to retrieve wallet balance

## Fund Management
- [ ] Create a faucet method for testnet DOT 
- [ ] Implement `transfer()` method for sending funds between wallets
- [ ] Add support for transferring different assets (DOT, KSM, parachain tokens)

## Transaction Handling
- [ ] Implement transaction submission and waiting mechanism
- [ ] Add simplified contract calling functionality
- [ ] Add method to list transfers for an address (incoming and outgoing, link to sentry / DotLake with an API key)

## Webhook Integration
- [ ] Implement webhook creation functionality
- [ ] Add support for different event types relevant to Polkadot
- [ ] Create method to attach webhooks to wallets

## Documentation
- [ ] Write API documentation
- [ ] Create usage examples for each main feature

## Testing
- [ ] Write more tests

## Advanced Features
- [ ] Research and implement Polkadot-specific features (e.g., staking, governance)
- [ ] Add support for custom extrinsics
- [ ] Add support for XCM

## Release Management
- [ ] Set up versioning system
- [ ] Create release process and documentation

## Community and Support
- [ ] Create CONTRIBUTING.md file
- [ ] Set up issue templates for GitHub
- [ ] Establish support channels for developers