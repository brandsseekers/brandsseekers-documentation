# Merchant Product Feed Specification

Official specification for the Brands Seekers Merchant Product Feed.

---

## Overview

The Brands Seekers Merchant Product Feed is the authoritative XML representation of products published in the live Brands Seekers catalogue of authentic designer fashion.

The feed is designed for merchant platforms, shopping engines, marketplaces, comparison shopping services, and commerce integrations that require structured product data.

---

## Purpose

The Merchant Product Feed provides standardized product information to support product discovery, shopping integrations, and catalog synchronization across merchant platforms.

---

## Specification Information

| Property | Value |
|----------|-------|
| Specification Version | 1.0 |
| Status | Production |
| Format | XML |
| Encoding | UTF-8 |
| Availability | Public |
| Update Frequency | Automatically updated |
| Source | Live Brands Seekers catalogue |

---

## Public Endpoint

```
https://brandsseekers.com/merchant-feed.xml
```

---

## Data Coverage

The Merchant Product Feed represents products currently published in the live Brands Seekers catalogue and includes structured commerce information such as:

- Product Identity
- Brand
- Pricing
- Availability
- Images
- Categories
- Product URLs
- GTIN
- Product Attributes
- Shipping Information

---

## Product Object

Each product is represented as an XML item containing standardized commerce attributes suitable for merchant platforms and shopping engines.

The complete field specification is documented separately.

---

## Intended Consumers

The Merchant Product Feed is intended for:

- Merchant Platforms
- Shopping Engines
- Marketplace Integrations
- Product Catalog Services
- Commerce Partners
- Product Aggregators

---

## Best Practices

Consumers should:

- Always consume the latest published feed.
- Respect update frequency.
- Preserve XML field names.
- Treat optional elements as nullable.
- Validate XML before processing.

---

## Versioning

The Merchant Product Feed follows a stable specification.

Whenever practical, future enhancements will be introduced through additive changes to preserve backwards compatibility.

---

## Related Specifications

- AI Product Feed Specification
- Pinterest Product Feed Specification
- Product Schema Specification
- Brand Schema Specification
- Size Guide Schema Specification

---

© Brands Seekers Documentation
