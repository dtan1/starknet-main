# Starknet Main #
This is the main repo for describing / listing all the projects related to Starkness
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
    - CLI for interacting with starknet contracts
      - call (for view functions)
      - invoke (for external functions)
     
  <br></br>
  - starknet foundry
    - a comprehensive toolkit for developing, testing, and deploying Starknet contracts.
      - Forge - fast testing framework for Starknet contracts;
      - Cast - an all-in-one tool for interacting with Starknet smart contracts




  
  
  
  
  
  
  
  
  

