---
"@x402/fetch": patch
"@x402/axios": patch
---

Stop adding the response-only Access-Control-Expose-Headers header to payment retry requests, avoiding unnecessary CORS preflight failures in browsers. Servers remain responsible for exposing payment response headers.
