---
layout: bidder
title: Aardvark
description: Prebid Aardvark Bidder Adaptor
top_nav_section: dev_docs
nav_section: reference
hide: true
biddercode: aardvark
biddercode_longer_than_12: false
gdpr_supported: true
prebid_1_0_supported: true
---

### bid params

{: .table .table-bordered .table-striped }
| Name | Scope    | Description        | Example  | Type     |
|------|----------|--------------------|----------|----------|
| `ai` | required | The rtk auction ID | `'XBC1'` | `string` |
| `sc` | required | The rtk shortcode  | `'AF2g'` | `string` |
| `categories` | optional | Deal ID Categories  | `['news','sports']` | `array` |
