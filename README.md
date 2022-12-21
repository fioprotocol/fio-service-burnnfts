# fio-burn-expired
Service to burn expired domains

## Environment variables

Include a .env file with:

```
server=          # FIO API node (e.g., https://fio.blockpane.com)
privateKey=      # FIO private key
publicKey=       # FIO public key
account=         # FIO account associated with public key
```

## Usage

npm run burn-nfts     # Burn NFTs that have been removed by users