# Zuperscripts

A general collection of web3 scripts

## Installation (Nuyul Lava Network Usage)

first, you download the repository and move to right directory using the following command:

```bash
git clone https://github.com/nmluthfi/web3-scripts.git && cd web3-scripts/zuperscripts
````

then, you need to install the required packages using the following command:

```bash
sudo apt install -y libgmp3-dev && pip install starknet-py
````

after that, you can run the script using the following command:

```bash
python main.py 
--ethereum_rpc_endpoint <your rpc> 
--ethereum_wallet_address <your address> 
--near_mainnet_rpc_endpoint <your rpc> 
--near_mainnet_account_id <your account id> 
--near_testnet_rpc_endpoint <your rpc> 
--near_testnet_account_id <your account id> 
--starknet_mainnet_rpc_endpoint <your rpc> 
--starknet_mainnet_wallet_address <your address>
--starknet_testnet_rpc_endpoint <your rpc>
--starknet_testnet_wallet_address <your address>

# alternatively you can use pyhton3 to run the script
```

## Installation (Package Usage)

```bash
pip install zuperscripts
```

## How To Use

### Transaction ERC
```python
import zuperscripts

zuperscripts.TransactionERC(wallet address, rpc endpoint).check_balance()
```
### Transaction NEAR
```python
import zuperscripts

zuperscripts.TransactionNear(wallet address, rpc endpoint).check_balance()
```

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

Developed by Zuperhunt Team (c) 2024
