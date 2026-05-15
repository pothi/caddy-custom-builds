# Custom Caddy Builds 🚀

Custom builds of Caddy web server with rate-limit & Cloudflare DNS modules. Built for Linux amd64 & arm64. Extend if you wish.

![Caddy](https://img.shields.io/badge/Caddy-2.x-1f88c2?style=for-the-badge&logo=caddy)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)
![Build](https://img.shields.io/badge/Build-Manual%20Trigger-blue?style=for-the-badge)

### Available Binaries

| Binary                                      | Architecture | Included Module                     |
|---------------------------------------------|--------------|-------------------------------------|
| `caddy-ratelimit-vX.Y.Z-linux-amd64`       | Linux amd64  | `github.com/mholt/caddy-ratelimit` |
| `caddy-cloudflare-vX.Y.Z-linux-arm64`      | Linux arm64  | `github.com/caddy-dns/cloudflare`  |

### How to Build

1. Go to **Actions** → **Build Custom Caddy Binaries**
2. Click **"Run workflow"**
3. Download binaries + checksums from the latest Release

Run this workflow manually whenever a new Caddy version is released.

---

### How to Verify Binaries (Security Recommended)

**⚠️ Security Disclaimer**: These binaries are built automatically in GitHub Actions. While the workflow is transparent and open-source, **always verify the SHA256 checksums** before using them on any production server. This helps protect against supply-chain attacks or tampering.

```bash
# Verify using the provided checksums.txt from the release
sha256sum -c <<< "$(grep amd64 checksums.txt)"

# Or check manually
sha256sum caddy-ratelimit-v2.11.3-linux-amd64
```

The checksums are included in every GitHub Release.

## Credits

Powered by xcaddy
Built with ❤️ using Grok by xAI

### License: MIT
