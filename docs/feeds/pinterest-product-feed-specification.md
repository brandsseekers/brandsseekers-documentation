# Pinterest Product Feed Specification

Official specification for the Brands Seekers Pinterest Product Feed.

---

## Overview

The Brands Seekers Pinterest Product Feed is the authoritative XML feed used for Pinterest Catalogs and Shopping integrations.

It provides structured product information from the live Brands Seekers catalogue of authentic designer fashion in a format optimized for Pinterest's commerce ecosystem.

---

# Purpose

The Pinterest Product Feed is designed to:

- Publish structured product information for Pinterest.
- Support Pinterest Catalog synchronization.
- Maintain accurate product metadata.
- Enable reliable shopping experiences.
- Keep Pinterest product listings aligned with the live Brands Seekers catalogue.

---

# Specification Information

| Property | Value |
|----------|-------|
| Specification Version | 1.0 |
| Status | Production |
| Format | XML |
| Encoding | UTF-8 |
| Availability | Public |
| Source | Live Brands Seekers catalogue |
| Update Frequency | Automatically updated |

---

# Feed URL

```
https://brandsseekers.com/pinterest-feed.xml
```

---

# Data Coverage

The Pinterest Product Feed represents products currently published in the live Brands Seekers catalogue and includes the structured commerce information required for Pinterest Shopping integrations.

---

# Product Object

Each product entry contains structured commerce information including:

- Product Identifier
- Product Title
- Description
- Brand
- Product URL
- Images
- Availability
- Price
- Sale Price
- Currency
- GTIN
- Product Category
- Color
- Size
- Gender
- Age Group
- Shipping Information

---

# Intended Consumers

The Pinterest Product Feed is intended for:

- Pinterest Catalogs
- Pinterest Shopping
- Commerce Integrations
- Retail Technology Partners

---

# Best Practices

Consumers should:

- Retrieve the latest published feed.
- Respect update frequency.
- Validate XML before processing.
- Preserve field names and values.
- Support optional fields where applicable.

---

# Versioning

Brands Seekers maintains backwards compatibility whenever practical while continuing to improve the specification over time.

---

# Related Specifications

- AI Product Feed Specification
- Merchant Product Feed Specification
- Product Schema Specification
- Brand Schema Specification
- Size Guide Schema Specification

---

© Brands Seekers Documentation
