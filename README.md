# VOLCY Pool Metadata

Official extended metadata for VOLCY Cardano stake pool.

## Pool Information

- **Pool ID**: `e3f8a83cefed03fe4ebdc4f50f3cdd880a7c2fd0b2ce7ff9da9cdce2`
- **Ticker**: VOLCY
- **ITN Veteran**: ✅ Participated in Cardano's historic Incentivized Testnet (Dec 2019 - Aug 2020)

## Extended Metadata

This repository hosts the extended metadata JSON file for the VOLCY stake pool, including:

- Detailed pool information
- Social media links
- Multi-chain infrastructure details
- ITN verification credentials (CIP-6 compliant)

### Files

- `extendedpoolmeta.json` - Extended pool metadata with ITN credentials

## ITN Badge Verification

The extended metadata includes CIP-6 compliant ITN verification:

- **Owner Key**: `ed25519_pk1w30svwtq083dxvtk8ypz29jyer6h9jyrsajtwqr62shcaj55x5uqpyn8tk`
- **Witness Signature**: Cryptographically signed proof of ITN participation

## Multi-Chain Infrastructure

VOLCY operates across 10+ blockchain networks:

- **Cardano Mainnet/Testnet** - 279+ validated blocks
- **Midnight Validator** (testnet) - Zero-knowledge smart contract network
- **Mithril Signer** - Blockchain snapshots
- **NuNet Computing** - Decentralized AI/computing
- **Xerberus** - Risk management blockchain
- **Blockfrost IceBreakers** - API infrastructure
- **ApexFusion** - Multi-chain Ethereum-Cardano bridge
- **Âtrium Staking Baskets** - Multi-pool delegation protocol

## Usage

The extended metadata is accessible via:

```
https://raw.githubusercontent.com/gvolcy/volcy-pool-metadata/main/extendedpoolmeta.json
```

Reference this URL in your main pool metadata `poolmeta.json`:

```json
{
  "name": "VOLCY",
  "description": "...",
  "ticker": "VOLCY",
  "homepage": "https://www.volcyada.com/",
  "extended": "https://raw.githubusercontent.com/gvolcy/volcy-pool-metadata/main/extendedpoolmeta.json"
}
```

## Verification

Verify the JSON is valid:

```bash
curl -sL "https://raw.githubusercontent.com/gvolcy/volcy-pool-metadata/main/extendedpoolmeta.json" | jq '.'
```

Check ITN credentials:

```bash
curl -sL "https://raw.githubusercontent.com/gvolcy/volcy-pool-metadata/main/extendedpoolmeta.json" | jq '.itn'
```

## Links

- **Pool Website**: https://www.volcyada.com/
- **Twitter**: [@gvolcy](https://twitter.com/gvolcy)
- **Telegram**: https://t.me/volcyhttp
- **GitHub**: [@gvolcy](https://github.com/gvolcy)

---

🦁 **VOLCY - Elite Multi-Chain Infrastructure Provider**

*ITN Veteran since 2019 | 6+ years blockchain experience | 279+ blocks validated*
