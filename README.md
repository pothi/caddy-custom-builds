# Custom Caddy Builds (Ubuntu 26.04 + WordPress)

This repo builds two custom **Caddy** binaries with popular modules using `xcaddy`.

### Binaries (with auto-detected Caddy version)

| Binary                                      | Architecture | Included Module                     |
|---------------------------------------------|--------------|-------------------------------------|
| `caddy-ratelimit-vX.Y.Z-linux-amd64`       | Linux amd64  | `github.com/mholt/caddy-ratelimit` |
| `caddy-cloudflare-vX.Y.Z-linux-arm64`      | Linux arm64  | `github.com/caddy-dns/cloudflare`  |

### How to Build
1. Go to **Actions** → **Build Custom Caddy Binaries**
2. Click **"Run workflow"**
3. Download binaries from the new Release.

Run this manually whenever you want the latest Caddy version.

**Server Stack**: Web Server: **Caddy** • Server OS: **Ubuntu 26.04 Server** • App: **WordPress**
