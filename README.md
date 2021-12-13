Specify the Truffle version Truffle v5.4.17

OpenZeppelin version used in the project. v4.4.0

Your ERC-721 newstar

Your ERC-721 ns

Your “Token Address” on the Rinkeby Network

contract address:    0xc500130DB92EF25326a53f87d7C7a6e39d37c97F

New Star Owner is 0x5669273Ec9eeFb6f559217f2c6064c0109100438


Compiling your contracts...
===========================
> Compiling ./contracts/StarNotary.sol
> Artifacts written to /Users/1vim/Desktop/newstar/build/contracts
> Compiled successfully using:
   - solc: 0.5.16+commit.9c3226ce.Emscripten.clang

Unknown network "rinkeby". See your Truffle configuration file for available networks.
Truffle v5.4.17 (core: 5.4.17)
Node v14.18.0
1vim@Saads-MacBook-Air newstar % truffle deploy --network rinkeby
Warning: Both truffle-config.js and truffle.js were found. Using truffle-config.js.

Compiling your contracts...
===========================
> Everything is up to date, there is nothing to compile.

Warning: Both truffle-config.js and truffle.js were found. Using truffle-config.js.
Warning: Both truffle-config.js and truffle.js were found. Using truffle-config.js.


Migrations dry-run (simulation)
===============================
> Network name:    'rinkeby-fork'
> Network id:      4
> Block gas limit: 30000000 (0x1c9c380)


1_initial_migration.js
======================

   Deploying 'Migrations'
   ----------------------
   > block number:        9808285
   > block timestamp:     1639409146
   > account:             0xefa409f8db2dCa2D0d8838ab72CBA15Ffc4e4026
   > balance:             1.6203864185
   > gas used:            210237 (0x3353d)
   > gas price:           10 gwei
   > value sent:          0 ETH
   > total cost:          0.00210237 ETH

   -------------------------------------
   > Total cost:          0.00210237 ETH


2_deploy_contracts.js
=====================

   Deploying 'StarNotary'
   ----------------------
   > block number:        9808287
   > block timestamp:     1639409148
   > account:             0xefa409f8db2dCa2D0d8838ab72CBA15Ffc4e4026
   > balance:             1.5989509285
   > gas used:            2116186 (0x204a5a)
   > gas price:           10 gwei
   > value sent:          0 ETH
   > total cost:          0.02116186 ETH

   -------------------------------------
   > Total cost:          0.02116186 ETH


Summary
=======
> Total deployments:   2
> Final cost:          0.02326423 ETH


Warning: Both truffle-config.js and truffle.js were found. Using truffle-config.js.
Warning: Both truffle-config.js and truffle.js were found. Using truffle-config.js.
Warning: Both truffle-config.js and truffle.js were found. Using truffle-config.js.



Starting migrations...
======================
> Network name:    'rinkeby'
> Network id:      4
> Block gas limit: 30000000 (0x1c9c380)


1_initial_migration.js
======================

   Deploying 'Migrations'
   ----------------------
   > transaction hash:    0x836b936f9df48e376231dcbe4991d6043ace0d937cbbd7fadf78fa43a6787c74
   > Blocks: 0            Seconds: 8
   > contract address:    0x915B22BF6Fddd497ECd98991065a30A860b18aA4
   > block number:        9808285
   > block timestamp:     1639409160
   > account:             0xefa409f8db2dCa2D0d8838ab72CBA15Ffc4e4026
   > balance:             1.6202234185
   > gas used:            226537 (0x374e9)
   > gas price:           10 gwei
   > value sent:          0 ETH
   > total cost:          0.00226537 ETH


   > Saving migration to chain.
   > Saving artifacts
   -------------------------------------
   > Total cost:          0.00226537 ETH


2_deploy_contracts.js
=====================

   Deploying 'StarNotary'
   ----------------------
   > transaction hash:    0x55c5d19555bd9a7891aa4832ca79032c2b99f34fcefa6ad1ccd91108bbf96991
   > Blocks: 0            Seconds: 12
   > contract address:    0xc500130DB92EF25326a53f87d7C7a6e39d37c97F
   > block number:        9808287
   > block timestamp:     1639409190
   > account:             0xefa409f8db2dCa2D0d8838ab72CBA15Ffc4e4026
   > balance:             1.5982779285
   > gas used:            2148786 (0x20c9b2)
   > gas price:           10 gwei
   > value sent:          0 ETH
   > total cost:          0.02148786 ETH


   > Saving migration to chain.
   > Saving artifacts
   -------------------------------------
   > Total cost:          0.02148786 ETH


Summary
=======
> Total deployments:   2
> Final cost:          0.02375323 ETH