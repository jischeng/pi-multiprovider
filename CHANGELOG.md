# Changelog

## 0.11.0

- Merge upstream 0.10.2: in-place pooled account reauthentication and Pi 1.0 compatibility validation.
- Retain model-scoped cooldowns for entitlement rejections.
- Published as `@jischeng/pi-multiprovider`.

## 0.10.2

- Validate Pi 1.0.0 with exact development pins and wildcard host peers.
- Extend offline real-host probes through session startup and repeated shutdown; retain native provider delegation and failover behavior.

## 0.10.1

- Validate against Pi 0.99.0, including an offline real-host package-loading probe.
- Declare imported host packages as wildcard peers and pin development dependencies to Pi 0.99.0.
