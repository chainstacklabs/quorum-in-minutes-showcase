# quorum-in-minutes-showcase

Run a Quorum network, deploy a smart contract, and make transactions in minutes.

## Quorum showcase picture

![showcase image](./assets/showcase-01.png)

## Showcase slide deck

- [https://speakerdeck.com/hayorov/quorum-in-minutes-with-chainstack](https://speakerdeck.com/hayorov/quorum-in-minutes-with-chainstack)

## Step-by-step guide

1. Get a free account (with 14 days free usage) at [console.chainstack.com](https://console.chainstack.com).
2. Deploy a Quorum network on Chainstack with three nodes - Node A, Node B, and Node C.
3. Install Python 3, [web3 library](https://web3py.readthedocs.io/en/stable/quickstart.html#installation), [Solidity Compiler](https://solidity.readthedocs.io/en/latest/installing-solidity.html) with [Python wrapper](https://github.com/iamdefinitelyahuman/py-solc-x) and [Jupyter](https://jupyterlab.readthedocs.io/en/stable/getting_started/installation.html).

4. Run Jupyter Notebook:

    ```bash
    > jupyter notebook --no-browser
    ```

5. Follow the instructions inside the notebooks:

    - **(clickable on GitHub)** [01-quorum-meetup-writer.ipynb](./01-quorum-meetup-writer.ipynb)

    - **(clickable on GitHub)** [02-quorum-meetup-reader.ipynb](./02-quorum-meetup-reader.ipynb)
