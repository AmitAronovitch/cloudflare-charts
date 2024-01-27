# Cloudflare Helm Charts

### About
A convenient location to publish Cloudflare helm charts

### Setup
```bash
helm repo add aa-cloudflare https://amitaronovitch.github.io/cloudflare-charts
helm repo update
```

### Discovery
```bash
helm search repo aa-cloudflare
```

### Contents

- `charts/cloudflare-tunnel`: Helm 3 chart using cloudflared best practices
- `charts/cloudflare-tunnel-remote`: Helm 3 chart for managing remotely-managed tunnel
