# elliptic (mapped fork)

Temporary fork of [indutny/elliptic](https://github.com/indutny/elliptic) with the fix for [CVE-2025-14505](https://github.com/advisories/GHSA-848j-6mx2-7j84) from [PR #345](https://github.com/indutny/elliptic/pull/345).

**This fork will be retired once the upstream PR is merged.** Use the official package when available.

## What's different

Fixes a bug where k values with leading zeros were incorrectly truncated during ECDSA signature generation (RFC 6979 violation).

## Install

```
npm install @mapped/elliptic
```
