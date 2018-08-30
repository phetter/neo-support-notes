

**Summary**

This repo needs organization. For now it's just a place to keep all the notes. Wiki format preferred.


**Smart Contract Storage**

For optimizing GAS usage, Storage.Put will be the most expensive thing you do, at a minimum of 1 GAS per Put. So if you have a lot of variables you need to store, it's best to use Serialize/Deserialize and store them together in a single Put call if possible.


**ONT / Ontology**

Neon doesn't work with MainNet ONT. You have to use the ONTO mobile wallet for now but you should be able to use the same key that you use with Neon so your ONT will be there when you log in.

**Ontology Discord**

https://discord.gg/YdaXAy7

**ONTO and ONT Token Swap**

https://medium.com/ontologynetwork/mainnet-ont-token-swap-notice-%E5%85%B3%E4%BA%8Eont%E4%B8%BB%E7%BD%91%E5%88%87%E6%8D%A2%E7%9A%84%E8%AF%B4%E6%98%8E-4cd38c2fc55b

**Neon Wallet Installation**

Nothing happens after installer runs on Windows 10.

1. Try uninstalling any previous version of Neon Wallet.
2. Backup neon wallet data file c:\users\yourusername\Appdata\Roaming\ then delete that folder.
3. Install new version.


**Neon Wallet Data Files**

c:\users\yourusername\Appdata\Roaming\Neon\storage\userWallet.json


**Aphelion Wallet**

Can be used for decrypting and encrypted neo key


**Data Types Reference**

Neo Network Protocol

http://docs.neo.org/en-us/network/network-protocol.html#data-type

neo-python

https://neo-python.readthedocs.io/en/latest/data-types.html?highlight=hex


**Development Environments**
  - dApps

    https://github.com/CityOfZion/neo-local

**Thanks**
