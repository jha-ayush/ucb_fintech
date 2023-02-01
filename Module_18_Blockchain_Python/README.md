# PyChain Ledger

Create a blockchain-based ledger system, with a user-friendly web interface. The ledger allows partner banks to conduct financial transactions (that is, to transfer money between senders and receivers) and to verify the integrity of the data in the ledger by using blockchain technology.

This project leverages `Python version: 3.9.16` along with the [streamlit](https://streamlit.io/) package to deploy Web Apps UIs



## Libraries

<sub>pandas   : 1.5.3</sub>

<sub>streamlit: 1.17.0</sub>

Create new `blockchain` environment:

```python
conda create -n blockchain python=3.9

conda activate blockchain
    
pip install pandas numpy streamlit watchdog watermark web3==5.17 eth-tester==0.5.0b3 mnemonic bip44
```

`cd` into main folder

Run `streamlit run pychain.py`



## Visualization
[Sreamlit app video demo](https://www.loom.com/share/cf67034167154a5a8f3cce9faea13026)



- App allows exact amount of money transfer between senders and receivers
- Highlights the `record` info, creator_id, previous hash id, timestamp and `nonce` (number used once) values