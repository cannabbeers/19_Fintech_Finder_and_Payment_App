
# under construction, working out errors running to ST

# 19_Fintech_Finder_and_Payment_App
Module 19 Challenge


# Module 19 Environment
module 19 setup instructions called for specific versions of `web3`, `eth-tester`, and will also require `mnemonic` and `bip44` packages.

## Two Choices
1) Build a new environment to run code *(you may remove `--strict-channel-priority` segment of code below if desired)*
2) Verify your package versions match details below and/or use `pip install <package_name>` to match below

  ### (Option #1) create "blockchain" environment for this module to ensure code runs properly (or simply skip and move to next step): 
      $ conda create -n blockchain -y -v -c conda-forge --strict-channel-priority python=3.9 web3=5.17 mnemonic ipykernel jupyterlab numpy pandas pip python-dotenv requests streamlit watermark
      
      $ pip install eth-tester==0.5.0b3

      $ pip install bip44

  ### (Option #2) update your current `dev` environment with following instructions: 

To install the Web3.py library, check that your dev environment is active, and then run the following:
      
          pip install web3==5.17
      
To install the ethereum-tester library, check that your dev environment is active, and then run the following:
      
          pip install eth-tester==0.5.0b3
      
To install the mnemonic package, check that your dev environment is active, and then run the following:
      
          pip install mnemonic
          
To install the bip44 package, check that your dev environment is active, and then run the following:
      
          pip install bip44

      
## Next, Install Ganache
download the latest version of Ganache and then create a Ganache workspace

  ### Install Ganache
Download the Latest Version of Ganache - https://trufflesuite.com/ganache/
Follow the instructions on the Ganache download to download and install this tool on your local machine.

  ### Create a Workspace
When you open Ganache, you are presented with two options for creating a workspace: *Quickstart Ethereum* and *New Workspace Ethereum*. 

  **Next Choose and Click...** `Quickstart Ethereum`


