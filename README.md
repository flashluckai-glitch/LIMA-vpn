# LIMA VPN

Aggregated VLESS / v2ray subscription, auto-rebuilt every 12 hours. Top tiers are filtered by real HTTP test through each proxy (xray-knife → `https://www.google.com/generate_204`), so every entry is verified to actually carry traffic.

**Last update (UTC):** 2026-05-28 19:45:02

**Configs:** 500 top500 / 2000 top2000 / 42328 TCP-live / 78116 total

**Real HTTP latency (working pool):** median 430 ms · p95 904 ms

**Top 2000 cutoff:** 992 ms

## Subscribe — Top 500 (lowest latency, recommended)

```
https://vpn.lima-xdt.art/top500_base64.txt
```

## Subscribe — Top 2000 (extended pool, good for client-side ping testing)

```
https://vpn.lima-xdt.art/top2000_base64.txt
```

## Subscribe — TCP-live intermediate (42328)

_Open ports — not necessarily working proxies. Backup tier._

```
https://vpn.lima-xdt.art/sub_base64.txt
```

## Subscribe — Unfiltered raw (78116)

```
https://vpn.lima-xdt.art/sub_all_base64.txt
```

## Protocols (in top 2000)

- `vless`: 1377
- `vmess`: 447
- `ss`: 163
- `trojan`: 13
