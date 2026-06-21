<div align="center">

# ImKKingshuk Scoop Bucket

Scoop manifests for tools by [@ImKKingshuk](https://github.com/ImKKingshuk).

</div>

## Setup

```powershell
scoop bucket add imkkingshuk https://github.com/ImKKingshuk/scoop-bucket
```

## Available Manifests

| Manifest | Description | Install |
|----------|-------------|---------|
| **LockKnife** | The Ultimate Android Security Research Tool | `scoop install imkkingshuk/lockknife` |
| **BloatwareHatao** | The Ultimate Android Bloatware Removal Tool | `scoop install imkkingshuk/bloatwarehatao` |

BloatwareHatao becomes installable after its first GitHub release is published and the `Update Bucket` workflow generates `bucket/bloatwarehatao.json`.

## Usage

```powershell
# Add this bucket (one-time)
scoop bucket add imkkingshuk https://github.com/ImKKingshuk/scoop-bucket

# Install a manifest
scoop install imkkingshuk/lockknife
scoop install imkkingshuk/bloatwarehatao

# Update
scoop update && scoop update lockknife
scoop update && scoop update bloatwarehatao
```

## Requirements

- Windows 10/11
- Scoop 1.0+

## License

Each manifest references its respective project's license. See individual project repositories for details.
