# ANON Bootstrap

This is **OPTIONAL** (useful for full node only or after a resync/reindex).

**Only after a successfull installation of the sapling update - Protocol 180008**

If you want to sync faster, you can download a significant portion of the blockchain.
This zipped file contains raw blocks (up to block ~46,000).

[Download (updated 03.04.19)](https://uc1ef31583995d106768bcab1f0d.dl.dropboxusercontent.com/cd/0/get/AeSlR9RAbotrVCLFD5n5e-0AxbmZ1dbewjhoXIJcuAA9gtz08WB_Ngydabj0dzRHvZzc7r7CPaxPark1g-A-U8-ii1_WX7joxWhNvXhFsKNOuw/file?dl=1#)


Raw link: https://www.dropbox.com/s/idub2rp6wk2boh4/anon_bootstrap.zip?dl=0


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
