---
layout: page
key: apps-use-cases
title: Use cases
---

# Social Commerce

Build an application that show cases products on social media platforms like Facebook, integrates products on a blogging platform or on any given site with a widget.

Suggested calls: [`GET` products](page:apps-api-get-shops-shopid-products-information), [`GET` categories](page:apps-api-get-shops-shopid-categories-information)

Optional calls: [`POST` carts](page:apps-api-post-shops-shopid-carts-information), [`PUT` carts/line-items](page:apps-api-put-shops-shopid-carts-cartid-line-items-lineitemid-information), [`GET` legal](page:apps-api-get-shops-shopid-legal-information)

Availability: <i class="fa fa-check"></i>

# Portal Engines

Build an application that adds products to price comparison or shopping portals.

Suggested calls: [`GET` products](page:apps-api-get-shops-shopid-products-information) (batch)

Optional calls: [`GET` categories](page:apps-api-get-shops-shopid-categories-information)

Availability: <i class="fa fa-check"></i>

# Shipping

Build an application that allows you to print shipping labels and to control the status of an order.

Suggested calls: [`GET` orders](page:apps-api-get-shops-shopid-orders-information), [`PUT` orders](page:apps-api-put-shops-shopid-orders-orderid-information)

Optional calls: [`GET` products](page:apps-api-get-shops-shopid-products-information)

Availability: <i class="fa fa-check"></i>

# Accounting

Build an application that allows you to manage and process orders.

Suggested calls: [`GET` orders](page:apps-api-get-shops-shopid-orders-information), [`PUT` orders](page:apps-api-put-shops-shopid-orders-orderid-information)

Optional calls: [`GET` products](page:apps-api-get-shops-shopid-products-information)

Availability: <i class="fa fa-check"></i>

# Content Optimisation and Marketing

Build an application that optimises or enhances the content of product or category descriptions for Search Engine Optimisation (SEO), for general marketing purposes or to add translations to all descriptive content.

Suggested calls: [`GET` products](page:apps-api-get-shops-shopid-products-information), [`PUT` products/stocklevel](page:apps-api-put-shops-shopid-products-productid-stock-level-information), [`GET` categories](page:apps-api-get-shops-shopid-categories-information), [`PUT` categories](page:apps-api-put-shops-shopid-categories-categoryid-information)

Availability: <i class="fa fa-check"></i>

# Legal Service

Build an application that provides up-to-date legal information (imprint, terms and conditions, etc.) automatically.

Suggested calls: [`GET` legal](page:apps-api-get-shops-shopid-legal-information), [`PUT` legal/contact-information](page:apps-api-put-shops-shopid-legal-contact-information-information), [`PUT` legal/privacy-policy](page:apps-api-put-shops-shopid-legal-privacy-policy-information), [`PUT` legal/terms-and-conditions](page:apps-api-put-shops-shopid-legal-terms-and-conditions-information), [`PUT` legal/rights-of-withdrawal](page:apps-api-put-shops-shopid-legal-rights-of-withdrawal-information), [`PUT` legal/shipping-information](page:apps-api-put-shops-shopid-legal-shipping-information-information)

Availability: <i class="fa fa-check"></i>

# Basic Point of Sale (POS)/Marketplace

Build an application that automatically updates the stock level of a product upon a POS/Marketplace sale.

Suggested calls: [`GET` products](page:apps-api-get-shops-shopid-products-information), [`PUT` products/stocklevel](page:apps-api-put-shops-shopid-products-productid-stock-level-information)

Optional calls: [`GET` categories](page:apps-api-get-shops-shopid-categories-information)

Availability: <i class="fa fa-check"></i>

# Sales Analytics

Build an application that allows to determine top selling products, top customers, top regions or optimise cross-selling products by evaluating orders.

Suggested calls: [`GET` products](page:apps-api-get-shops-shopid-products-information), [`GET` orders](page:apps-api-get-shops-shopid-orders-information), [`GET` categories](page:apps-api-get-shops-shopid-categories-information)

Availability: <i class="fa fa-check"></i>

# Advanced Point of Sale (POS)/Marketplace

Build an application that automatically updates the stock level of a product upon a POS/Marketplace sale and allows to create and manage customers and orders.

Suggested calls: [`GET` products](page:apps-api-get-shops-shopid-products-information), [`PUT` products/stocklevel](page:apps-api-put-shops-shopid-products-productid-stock-level-information), `PUT` products, `GET` customers, `PUT` customers, `POST` customers, [`GET` orders](page:apps-api-get-shops-shopid-orders-information), [`PUT` orders](page:apps-api-put-shops-shopid-orders-orderid-information), `POST` orders

Optional calls: [`GET` categories](page:apps-api-get-shops-shopid-categories-information)

Availability planned: **06/2016**

# Customer Relationship Management (CRM) and Newsletters

Build an application that analyses and groups/targets customers by ordered products and/or newsletter preferences and generates personalised newsletters accordingly.

Suggested calls: `GET` customers, `PUT` customers, `POST` customers, [`GET` orders](page:apps-api-get-shops-shopid-orders-information), [`GET` products](page:apps-api-get-shops-shopid-products-information)

Availability planned: **06/2016**

# Enterprise Management Systems (EMS)

Build an application that manages products, customers and orders as well as handles fulfillment, accounting and customer support.

Suggested calls: [`GET` products](page:apps-api-get-shops-shopid-products-information), `PUT` products, `POST` products, [`DELETE` products](page:apps-api-delete-shops-shopid-products-productid-information), `GET` customers, `PUT` customers, `POST` customers, [`GET` orders](page:apps-api-get-shops-shopid-orders-information), [`PUT` orders](page:apps-api-put-shops-shopid-orders-orderid-information), `POST` orders

Optional calls: ([`GET` categories](page:apps-api-get-shops-shopid-categories-information))

Availability planned: **06/2016**
