# micro-proxy
> now, SuperXEROX v2 support any NFT tokens
It will convert NFT copy token's uri() to origin NFT tokenURI().

## URI example from Cryptokitties
```
https://api.cryptokitties.co/kitties/1231
```
## to use Memes NFT as example
```
the NFT Copy Token's URI will be http://mars.muzamint:3001/e4605d46Fd0B3f8329d936a8b258D69276cBa26400000000000000000000007b.json
```
> the Contract address is 0xe4605d46Fd0B3f8329d936a8b258D69276cBa264 for memes, and the NFT id is 123
> where the {id} is combined with the original NFT contract addresss and its token id (123) in hex.

# run
```
yarn start
```

