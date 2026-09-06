---
title: "Edge CDN Gateway"
description: "Global low-latency Cloudflare Edge CDN providing caching, font delivery, and static binary asset hosting."
---

# Edge CDN Gateway (`cdn.iamrp.dev`)

**`cdn.iamrp.dev`** provides distributed, low-latency edge caching and immutable asset hosting across the entire RPDev ecosystem.

- **Edge Gateway URL**: **[`https://cdn.iamrp.dev/`](https://cdn.iamrp.dev/)**
- **Core Role**: Air-gapped typography (`JetBrains Mono`), PDF resumes, security policy archives, and high-frequency cached manifests.
- **Cache Policy**: Strict `immutable, max-age=31536000` caching with SHA-256 digest validation on all static payloads.
