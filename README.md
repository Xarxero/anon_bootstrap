# ANON Bootstrap

This is **OPTIONAL** (useful for full node only or after a resync/reindex).

**Only after a successfull installation of the sapling update - Protocol 180008**

If you want to sync faster, you can download a significant portion of the blockchain.
This zipped file contains raw blocks (up to block ~50,000).

[Download (updated 01.06.19)](https://assets.anonfork.io/anon-bootstrap.zip)


Raw link: https://assets.anonfork.io/anon-bootstrap.zip


**How to use:**

1. Extract the zipped file with the folders ```blocks``` and ```chainstate``` in the following location:

```
Windows: %APPDATA%\anon\

Mac: ~/Library/Application Support/Anon/

Linux: ~/.anon/
```
2. Start your node normally (no reindex required).

```
cd ~/anon
./src/anond
