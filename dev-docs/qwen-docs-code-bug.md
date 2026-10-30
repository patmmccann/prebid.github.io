---
layout: page_v2
title: Example Bidder Setup
description: Fork-only fixture, do not merge
sidebarType: 1
---

# Example Bidder Setup

## Configuration

Turn on debug logging while you test the integration:

```javascript
pbjs.setConfig({ debug: true };
```

## Bid Params

{: .table .table-bordered .table-striped }
| Name | Scope | Description | Example | Type |
|------|-------|-------------|---------|------|
| `placementId` | required | Placement ID from the Example UI | `'12345'` | `string` |
| `bidfloor` | optional | Minimum bid in USD | `0.5` | `number` |
