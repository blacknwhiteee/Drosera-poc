# Drosera POS Operator

This repo contains smart contract traps and scripts to run a Drosera Network POS operator.

## Prerequisites
- [Bun](https://bun.sh) runtime
- [Foundry](https://getfoundry.sh/) (`forge` build tool)
- [Drosera CLI](https://app.drosera.io/install)

## Setup
curl -L https://app.drosera.io/install | bash
bun install
Notes
For each workshop, you may need to update the trap path in the drosera.toml file to point to current workshop build files.
You will need to add the operator address to the whitelist in the drosera.toml file to opt in to the trap.
Build Commands
After making changes to the contracts, you will need to build the contracts before running the Drosera commands so the updated bytecode is used.

make build-workshop-1
make build-workshop-2
make build-workshop-3
Operator Commands
make register-operator
make optin
make run-operator
