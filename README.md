# Testnet-proposals

Proposals for things deployed to the vega testnets

# How to propose it?

1. Get the correct version of the wallet
2. Propose an object
3. Vote on the proposed object


## Proposal shell command

```shell
vega wallet transaction send \
    --network fairground \
    --passphrase-file ~/passphrase.txt \
    --wallet proposer \
    --pubkey 69464e35bcb8e8a2900ca0f87acaf252d50cf2ab2fc73694845a16b7c8a0dc6f \
    "$(cat <some_file>.json)"
```
