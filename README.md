# fio-service-burnnfts

Service for burning NFTs that have been removed by a user on the FIO Chain.

## Environment variables

Include a .env file with:

```
server=          # FIO API node (e.g., https://fio.blockpane.com)
privateKey=      # FIO private key
publicKey=       # FIO public key
account=         # FIO account associated with public key
```

## Usage

```
npm run burn-nfts

```