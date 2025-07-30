# Crynux Token

Multi-chain deployment of Crynux Token

## Hyperlane Cross Chain Infra

1. Place `chains` into `~/.hyperlane`

1. Set HYP_KEY to the private key in env vars

```bash
export HYP_KEY='<YOUR_PRIVATE_KEY>'
```
2. Generate config file if not present

```bash
hyperlane core init
```

3. Deploy the Hyperlane core contracts

```bash
hyperlane core deploy
```
