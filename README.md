# Custom Caddy Builds

This repository builds two custom **Caddy** binaries using `xcaddy`:

### Binaries
| Binary                        | Architecture | Module Included                          |
|-------------------------------|--------------|------------------------------------------|
| `caddy-ratelimit-linux-amd64` | Linux amd64  | `github.com/mholt/caddy-ratelimit`      |
| `caddy-cloudflare-linux-arm64`| Linux arm64  | `github.com/caddy-dns/cloudflare`       |

### How to Use
1. Go to **Actions** → "Build Custom Caddy Binaries"
2. Click **"Run workflow"**
3. Download the binaries from the created Release.

**Note**: Run this workflow manually whenever a new version of Caddy is released.

---

**Server Info** (as per your preference):
- Web Server: **Caddy**
- Server OS: **Ubuntu 26.04 Server**
- App: **WordPress**
