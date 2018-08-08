

**Summary**

This repo needs organization. For now it's just a place to keep all the notes. Wiki format preferred.


**Smart Contract Storage**

For optimizing GAS usage, Storage.Put will be the most expensive thing you do, at a minimum of 1 GAS per Put. So if you have a lot of variables you need to store, it's best to use Serialize/Deserialize and store them together in a single Put call if possible.


**ONT / Ontology**

Neon doesn't work with MainNet ONT. You have to use the ONTO mobile wallet for now but you should be able to use the same key that you use with Neon so your ONT will be there when you log in.


**Neon Wallet Installation**

Nothing happens after installer runs on Windows 10.

1. Try uninstalling any previous version of Neon Wallet.
2. Backup neon wallet data file c:\users\yourusername\Appdata\Roaming\ then delete that folder.
3. Install new version.


**Thanks**

Thanks to Hal0x2328 for a majority of these answers as they are mostly his exact wording.
