# Keep Random Beacon Dappnode Package (Ropsten Testnet)
This dappnode package will allow you to participate in the keep ropsten testnet.
see: https://keep.network/

## Install
Access this link using your dappnode wifi:
http://my.dappnode/#/installer/%2Fipfs%2FQmZgGj5prKg29Uoke5A5pR7qdeTGKf8CaPCf2LJ9nm3m1t

current ipfs hash `QmZgGj5prKg29Uoke5A5pR7qdeTGKf8CaPCf2LJ9nm3m1t`

## Quick Start
1. Set `KEEP_ETHEREUM_PASSWORD` and `PEERS` environment variables in config.

Note, peers should be a comma-delimited string with no spaces or quotation marks, eg:
```
/dns4/bootstrap-2.core.keep.test.boar.network/tcp/3001/ipfs/16Uiu2HAmQirGruZBvtbLHr5SDebsYGcq6Djw7ijF3gnkqsdQs3wK,/dns4/bootstrap-3.test.keep.network/tcp/3919/ipfs/16Uiu2HAm8KJX32kr3eYUhDuzwTucSfAfspnjnXNf9veVhB12t6Vf,/dns4/bootstrap-2.test.keep.network/tcp/3919/ipfs/16Uiu2HAmNNuCp45z5bgB8KiTHv1vHTNAVbBgxxtTFGAndageo9Dp
```
2. Wait for ropsten to sync
3. Copy operator address from package logs
4. GOTO https://dashboard.test.keep.network/
5. Delegate your keep tokens to the operator address
6. Authorize the Random Beacon contract

## Extracting your operator account
The operator account is generated automatically for you when this package is initialized.
The operator account (ie private key) is stored in the data volume for this package,
so if you delete the dnp completely, including data, then you will lose your operator account.

It is a good idea to back up the account file / json someplace safe like a password manager.
The (encrypted) account is written to `/mnt/keystore/keep_wallet.json`.

To save this file, simply browse to the `File Manager` section of the DNP package and enter
this path into the `DOWNLOAD FILE FROM PACKAGE` input.
