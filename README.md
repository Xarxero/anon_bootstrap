# ANON Bootstrap

This is **OPTIONAL** (useful for full node only or after a resync/reindex).

If you want to sync faster, you can download a significant portion of the blockchain.
This zipped file contains raw blocks (up to block 46,000).

[Download (updated 01.04.19)](https://uce34a600f740abaeabcb39a2ab1.dl.dropboxusercontent.com/cd/0/get/AeMgSfGnOYqkb9RhLhehWODwsUH9oRcS1I4G6fHDS3FxxuZB-9EQ4daaxO5g5muVwLLt8_n8FjDiP0f0-AatCObpVeb7Idq7BwmMb3dJSlmiog/file?dl=1#)

Raw link: https://www.dropbox.com/s/u9kx808t2lkywiw/anon_bootstrap.zip?dl=0

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
