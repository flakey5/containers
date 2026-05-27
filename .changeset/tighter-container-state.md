---
'@cloudflare/containers': patch
---

Reset container state after failed startup or terminal monitor errors, avoid stale monitor callbacks updating newer instances, and apply configured constructor startup options.
