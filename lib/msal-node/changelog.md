# Change Log - @azure/msal-node

This log was last generated on Mon, 26 Oct 2020 21:00:29 GMT and should not be manually modified.

<!-- Start content -->

## 1.0.0-alpha.13

Mon, 26 Oct 2020 21:00:29 GMT

### Changes

- msal-browser and msal-node cache Interfaces to msal-common updated (#2415) (sameera.gajjarapu@microsoft.com)
- Export Node Cache Serializer for use in end-to-end testing framework (#2414) (hemoral@microsoft.com)

## 1.0.0-alpha.12

Tue, 20 Oct 2020 23:47:28 GMT

### Changes

- Adds support for any OIDC-compliant authority (#2389). (jamckenn@microsoft.com)

## 1.0.0-alpha.11

Thu, 15 Oct 2020 00:49:18 GMT

### Changes

- Export all "Request" types in msal-node (sameera.gajjarapu@microsoft.com)

## 1.0.0-alpha.10

Wed, 14 Oct 2020 23:45:07 GMT

### Changes

- Docs update for msal-node release (sameera.gajjarapu@microsoft.com)
- Export error types for msal-node (sameera.gajjarapu@microsoft.com)
- Add uuid as dependency in msal-node package.json so it is installed with the library (hectormgdev@gmail.com)
- Update TokenCache interface (#2348) (sameera.gajjarapu@microsoft.com)

## 1.0.0-alpha.9

Fri, 02 Oct 2020 17:42:35 GMT

### Changes

- Dummy implementation of access token proof-of-possession (prkanher@microsoft.com)

## 1.0.0-alpha.7

Wed, 23 Sep 2020 21:13:48 GMT

### Changes
- Make network interface public (#2335) (sameera.gajjarapu@microsoft.com)
- Rename TokenCache.cacheHasChanged to TokenCache.hasChanged (#2332) (sagonzal@microsoft.com)
- FOCI - Family of Client IDs feature (#2201) (sameera.gajjarapu@microsoft.com)
- Fix issue with token cache not removing old cache entities (#2304) (sagonzal@microsoft.com)

## 1.0.0-alpha.6

Thu, 17 Sep 2020 23:16:22 GMT

### Changes

- Address tsdx warnings (#2202) (thomas.norling@microsoft.com)
- Implement Telemetry in msal-node (#1921) (thomas.norling@microsoft.com)
- Changes node storage: getItem(), setItem() and removeItem() simplified and no longer need a 'type' (sameera.gajjarapu@microsoft.com)
- Add support for on-behalf-of flow (sagonzal@microsoft.com)

## 1.0.0-alpha.5

Tue, 25 Aug 2020 00:40:45 GMT

### Changes

- update APP_META_DATA to APP_METADATA (sameera.gajjarapu@microsoft.com)
- Client Capabilities Support (#2169) (thomas.norling@microsoft.com)
- Remove log statement (email not defined)
- undefined (sagonzal@microsoft.com)

# 1.0.0-alpha.4
- Add confidential client support (#2023)

# 1.0.0-alpha.3
- Fix an issue where the types were not defined correctly in the package.json (#2014)

# 1.0.0-alpha.2
- Fix an issue where the `dist` folder was not published (#2013)

# 1.0.0-alpha.1

- Add `response` to device code in `msal-node` (#1947)
- `msal-node` docs update (#1948)
- Export `AccountInfo` in `msal-node (#2005)

# 1.0.0-alpha.0

- scaffolding (#1328)
- Configuration and Client (#1325)
- Account and Authority (#1330)
- initial compatibility with other libs (#1342)
- `msal-node` crypto module (#1368)
- `msal-node` network module (#1371)
- `msal-node` lerna support (#1383)
- `msal-common` and `msal-node` Client applications, authorization code and device code flow (#1409)
- `msal-node` add DEBUG logging (#1423)
- `msal-common` authority changes (#1424)
- `msal-node` and `msal-common` unit tests for changes in #1409 (#1449)
- `msal-node` switch `strictNullChecks:true` for msal-node (#1478)
- `msal-node` and `msal-common` Update generation of client info headers (#1482)
- `msal-node` and `msal-common` Support for acquiring a token with refresh token (#1496)
- `msal-node` and `msal-common` Move authority generation from common to node (#1537)
- `msal-node` fix casing issue (#1630)
- `msal-node` Cache implementation (#1444, #1471, #1519, #1520, #1522, #1622, #1655, #1680)
- `msal-node` Silent Flow support (#1711)
- merge cache logic for all platforms (#1762)
- Utilize ScopeSet across the library (#1770)
- Update UnifiedCacheManager.ts (#1771)
- Node cache interface (#1801)
- SilentFlow node interface (#1809)
- Update TokenCache name (#1901)
