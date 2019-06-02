# quorum-in-minutes-showcase

Run a Quorum network, deploy smart contract and make transactions in minutes

## A Quorum showcase picture

![showcase image](./assets/showcase-01.png)

## Showcase slide deck

- [https://speakerdeck.com/hayorov/quorum-in-minutes-with-chainstack](https://speakerdeck.com/hayorov/quorum-in-minutes-with-chainstack)

## Step by step guide

1. Get a free account (with 14 days trial) at [console.chainstack.com](https://console.chainstack.com)
2. Deploy a Quorum network at chainstack portal with three nodes - Node A, B and C
3. Install Python 3, web3 library, solidity compiler and Jupyter

   ```bash
    # macos installer https://brew.sh/
    > brew brew tap ethereum/ethereum
    > brew install python ethereum/ethereum/solidity@4
    > pip install py-solc web3 jupyter
    ```

4. Run jupyter notebook

    ```bash
    > jupyter notebook --no-browser
    ```

5. Follow the instructions inside notebooks

    - **(clickable on GitHub)** [01-quorum-meetup-writer.ipynb](./01-quorum-meetup-writer.ipynb)

    - **(clickable on GitHub)** [02-quorum-meetup-reader.ipynb](./02-quorum-meetup-reader.ipynb)
