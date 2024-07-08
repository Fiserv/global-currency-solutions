## Multicurrency-Pricing

Multi currency Pricing (MCP) is a Card Not Present (CNP) offering that allows merchants to offer pricing in multiple currencies. The currency for MCP is determined by the cardholder upon entering the website or by using Geo IP. This service is offered for Visa, Mastercard and Amex credit transactions and cardholders can pay in more than 140 presentment currencies.

## Cardholder Experience
Provides cardholders with pricing in their currency of choice throughout the shopping experience but does not guarantee their final cost in their local currency.

## Merchant Experience

Depending on how MCP is implemented, the currency can be chosen by the cardholder, using a drop down for example, or determined by Geo IP. MCP is designed for card not present environments such as ecommerce. Merchants can display their prices in different currencies offering the cardholder the opportunity to transact in their currency of choice while the merchant is settled in their home currency.

Some merchant best practices, include:

- Fully disclose on your website payments page, the country or region in which you are currently operating. Merchants should also inform the customer of the transaction currency used for the purchase. This is particularly important for currencies that are not unique. For example, a dollar may be an Australian, New Zealand, Hong Kong, or U.S. Dollar.
- Merchants must disclose their payment location to consumers as part of the merchant website requirements.
- Allow the cardholder an easy and quick way to toggle between currencies, or shift back into merchant’s local currency.
- Price goods in your local currency by default and require that your customer opt to see prices in their local currency, only through conscious choice.

## Features
- Supports more than 130 global currencies (V,MC,AMEX)
- Merchant sets all pricing in foreign currency
- Merchant does not need to do incremental integration work
- Merchant settlement uses a different FX rate than authorization
- Enables easy cross-border expansion into markets where merchant may not be domiciled

## APIs Used
<!-- type: row -->
<!-- type: card 
title: Get All Rates
description: This API provides the set of exchange rate based on merchant hierarchy setup on OpenFX 2.0 platform. It uses Source currency, Target currency, Client Cross Reference ID and Merchant Cross Reference ID to determine the exchange rate.Target currency is an optional attribute and used as a filter criteria while determining the rate.
link: ../api/?type=post&path=/fx/v1/pricing/request/allrates
-->

<!-- type: row-end -->