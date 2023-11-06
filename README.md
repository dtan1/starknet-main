# Starknet Main #
This is the main repo for describing the Starknet Contract and its related framework and toolings, as well as listing a series of projects for Starknet Contracts.
<br></br>

## Motivation ##
To create a series of Starknet contracts using Cairo V1. It covers the basic codes in various areas of Starknet projects such as :
- simple-bank
- basic Defi contract (lending and borrowing)
- back NFT
- etc

<br>

## Starknet Contract ##
- contract boilder plate / template
  (code block, and basic description)
  
<br></br>
### Starknet toolings ###
  - scarb
    - build toolchain and package manager for Cairo and Starknet ecosystems.
    - used to write, compile, and deploy Cairo and Starknet smart contracts.
    - steps (code block / table ....)
      - scarb new <project_name> :
        - sets up a new project -
          - generating a Scarb.toml configuration file and
          - an initial src/lib.cairo contract file.
      - scarb build :
        - compiles your contract into Sierra code, an intermediate layer between high-level Cairo and compilation targets such as Cairo Assembly (CASM) 

<br></br>
## Starknet Testing ##
- unit testing
- local testing
- testnet 

<br></br>
### local testing ###
- testing environment
  - Katana
  - starnet-dev

<br></br>
- testing toolings :

  - starkli
    - CLI for
      - creating and managing accounts
        - creates a JSON file that can be used to sign transactions
      - declaring and deploying Starknet contracts
        - class-hash
          - creates a unique identifer for the a contract class.
          - input : accepts a path to a JSON file containing the contract’s compiled code
          - computed based on :
            - contract's compiled Sierra code,
            - the contract's ABI (Application Binary Interface), and
            - the contract's version. 
        - declare
          - declaring new contract classes on StarkNet.
            - i.e. registering the contract's compiled code on the StarkNet network
              - reason : to separate the contract's code from its execution, which makes the network more scalable and efficient
            - also involves signing a transaction with the contract owner's private key
          - input : accepts a path to a JSON file containing the contract’s compiled code
        - deploy
          - deployed using the Universal Deployer Contract (UDC).
          - The UDC is a special contract on StarkNet that allows any user to deploy new contracts to the network
      - interacting with starknet contracts
        - call (for view functions)
        - invoke (for external functions)
     
  <br></br>
  - starknet foundry
    - a comprehensive toolkit for developing, testing, and deploying Starknet contracts.
      - Forge :
        - fast testing framework for Starknet contracts
          - write tests directly in Cairo and run them using Rust, similar to Ethereum's Foundry.
          - enhance testing :
            - simulate different conditions through cheat codes (allow developers to modify parameters or conditions to examine contract behavior in specific scenarios)
      - Cast :
        - CLI for interacting with Starknet smart contracts




  
  
  
  
  
  
  
  
  

