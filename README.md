# Keep Random Beacon Dappnode Package
This dappnode package will allow you to participate in the keep ropsten testnet.
see: https://keep.network/

## Install
Access this link using your dappnode wifi:
http://my.dappnode/#/installer/%2Fipfs%2FQmRo1nauFXGeQA1fDXvmCL92k4tBRFkrvngCQzbagyPqVg

current ipfs hash `QmRo1nauFXGeQA1fDXvmCL92k4tBRFkrvngCQzbagyPqVg`

## Quick Start
1. Set `KEEP_ETHEREUM_PASSWORD` and `PEERS` environment variables in config.

Note, peers should be a comma-delimited string with no spaces or quotation marks, eg:
```
/dns4/bootstrap-0.test.keep.network/tcp/3919/ipfs/16Uiu2HAmCcfVpHwfBKNFbQuhvGuFXHVLQ65gB4sJm7HyrcZuLttH,/dns4/bootstrap-1.test.keep.network/tcp/3919/ipfs/16Uiu2HAm3eJtyFKAttzJ85NLMromHuRg4yyum3CREMf6CHBBV6KY,/dns4/testnet.keep-client.hashd.dev/tcp/3919/ipfs/16Uiu2HAmJsBiNVFNxsJ27NSQEByv39B1M7AKx5FrAc1htqYhHGhU,/dns4/testnet2.keep-client.hashd.dev/tcp/3919/ipfs/16Uiu2HAmAV3sNGXTpdZCguUEd5QqMmg13WZ5dBTtjbhYeQmTHwgM
```
2. Wait for ropsten to sync
3. Copy operator address from package logs
4. GOTO https://dashboard.keep.network/
5. Delegate your keep tokens to the operator address
6. Authorize the Random Beacon contract
