# AI Product Feed Specification

Official specification for the Brands Seekers AI Product Feed.

---

## Overview

The Brands Seekers AI Product Feed is a machine-readable JSON feed that provides structured information for products published in the live Brands Seekers catalogue of authentic designer fashion.

The feed is designed for AI assistants, large language models (LLMs), search engines, commerce platforms, research projects, and integration partners that require high-quality structured product data.

---

# Purpose

The AI Product Feed exists to:

- Publish structured product information.
- Improve machine understanding of products.
- Support AI-powered product discovery.
- Improve semantic search.
- Provide consistent product metadata.
- Enable future integrations with AI platforms and partners.

---

# Feed Information

| Property | Value |
|----------|-------|
| Format | JSON |
| Encoding | UTF-8 |
| Availability | Public |
| Update Frequency | Automatically updated |
| Source | Live Brands Seekers catalogue |

---

# Feed URL

```
https://brandsseekers.com/ai-product-feed.json
```

---

# Coverage

The feed represents products currently published on Brands Seekers.

Depending on catalogue updates, the feed may include:

- Products
- Brands
- Categories
- Product Images
- Pricing
- Availability
- Product Metadata
- Structured Attributes
- AI Metadata

---

# Product Object

Each product is represented as a structured JSON object.

Typical properties include:

- Product ID
- Title
- Description
- Brand
- Product URL
- Images
- Price
- Currency
- Availability
- Category
- GTIN
- Color
- Gender
- Size
- Product Highlights
- Product Details
- Related Products
- Size Guide
- Style Keywords
- Occasion Keywords
- Search Intent

The exact structure may evolve over time while maintaining backwards compatibility whenever possible.

---

# Intended Consumers

The AI Product Feed is intended for:

- AI Assistants
- Large Language Models (LLMs)
- Search Engines
- Commerce Platforms
- Product Discovery Systems
- Research Projects
- Integration Partners

---

# Best Practices

Consumers should:

- Always use the latest published feed.
- Respect update frequency.
- Preserve field names when parsing.
- Treat optional fields as nullable.
- Avoid assumptions about field ordering.

---

# Versioning

Brands Seekers may expand the AI Product Feed over time.

Whenever practical, new information will be introduced through additive changes to preserve compatibility with existing integrations.

---

# Related Documentation

- Merchant Product Feed Specification
- Pinterest Product Feed Specification
- Product Schema Specification
- Brand Schema Specification
- Size Guide Schema Specification

---

© Brands Seekers Documentation
