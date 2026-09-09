**Shopify CRO Auditor**
Overview

Shopify CRO Auditor is a lightweight, browser-based tool for reviewing live Shopify product pages for potential conversion-rate optimisation (CRO) issues.

The tool runs directly on the storefront through a bookmarklet and requires no browser extension, account, API key or Google approval. The audit runs locally in the browser and does not send store data elsewhere.

It is designed to quickly identify potential friction within the product-purchase journey and provide evidence, recommendations and suggested validation methods.

**What It Checks**

The auditor performs a range of automated and manual-review checks covering areas including:

Product title, price and purchase clarity
Add-to-cart visibility and availability
Above-the-fold content
Product variants, colours and sizing
Product imagery and image quality
Delivery and returns information
Reviews and customer reassurance
Payment information
Product descriptions and decision-support content
Mobile usability
Accessibility
Product availability and structured product data
Product-specific information for categories such as apparel, drinkware, homeware, prints, books and collectibles

The auditor adapts some checks based on the type of product it detects, rather than applying every requirement to every PDP.

**Installation**
Open shopify-cro-auditor-v6.html in Chrome.
Make sure the bookmarks bar is visible:
Mac: ⌘ + Shift + B
Windows: Ctrl + Shift + B
Drag the Run CRO Audit button onto the bookmarks bar.
If an older version is installed, remove the existing bookmark before installing the new version.

**Usage**

Open a live Shopify product page and click Run CRO Audit from the bookmarks bar.

The auditor scans the currently rendered product page and displays an audit panel containing:

Improve — potential CRO issues that have been detected.

Working — checks that the product page currently passes.

Review — areas that cannot be reliably assessed automatically and require human judgement.

The results also include an overall score, grade, product profile, viewport information and category-level performance.

If product options are changed after an audit, use Rescan to analyse the new product state.

**Scoring**

Applicable checks contribute towards a weighted overall score. Higher-priority checks have a greater impact on the result, while checks that are not relevant to the detected product are excluded.

The resulting score is classified as:

Score	Rating
85–100	Strong
70–84	Promising
50–69	Needs work
Below 50	High friction

The auditor also calculates individual category scores to help identify the weakest areas of the PDP.

**Reports**

Audit results can be exported using:

Download report — generates a standalone HTML audit report containing findings, evidence, priorities, recommendations and validation suggestions.

Export data (JSON) — exports the audit data in a structured format for further analysis or storage.

**Important**

The Shopify CRO Auditor is intended as a diagnostic and hypothesis-generation tool, not a replacement for Shopify Analytics, customer research or A/B testing.

A failed check does not automatically mean that making the recommended change will increase conversion. Important recommendations should be validated against real customer behaviour and conversion data.

The tool is best used to:

Identify potential friction → investigate the evidence → make a CRO hypothesis → implement where appropriate → validate against real performance data.
