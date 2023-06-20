---
_build:
  publishResources: false
  render: never
  list: never
---

Specific (non-wildcard) custom hostnames can use [HTTP based DCV](/cloudflare-for-platforms/cloudflare-for-saas/security/certificate-management/issue-and-validate/validate-certificates/http/) for certificate renewals, as long as:

- The hostname is pointing to the SaaS provider.
- The hostname's traffic is proxying through the Cloudflare network.

If your custom hostnames do not meet these requirements, use another validation method.