## Dynamic Currency Conversion

Dynamic Currency Conversion (DCC) is a Card Present (CP) and Card Not Present (CNP) offering that allows merchants to offer international credit cardholders the choice to pay in either their own currency or the merchant’s base currency. Merchants benefit by offering their foreign customers the choice, convenience, and transparency to pay in their card billing. This service is offered for Visa and Mastercard credit transactions and supports more than 70 global currencies. 
![Dynamic Currency Conversion](../assets/images/Clover-pos.png)

## Cardholder Experience
Provides cardholders with choice to pay in cardholder currency or merchant's local currency at the time of purchase. Cardholder is presented with all of the important information needed to make an informed decision, including the local amount, foreign amount, exchange rate, and any markup added ot the transaction. 

## Merchant Experience
Merchants provide their customers with a simple and transparent currency choice at the point-of-sale (POS). DCC enables merchants to deliver an enhanced checkout experience to their customers while earning additional revenue on DCC transactions. 

The DCC choice is determined by interrogating the BIN of the card to determine whether the card is foreign issued and eligible for conversion. If determined to be eligible, disclosures must be presented to the cardholder to allow them to make an active choice to pay in their card billing currency or the merchant’s local currency (for US merchant, USD).

The card associations mandate rules for offering DCC to protect the cardholder and merchants. The fundamental principles of DCC are:

1. <b>Cardholder Choice:</b> The DCC merchant must offer the cardholder a choice to transact in the merchant’s local currency or in their card billing currency
2. <b>Transparency & Disclosure:</b> Merchants must disclose all relevant details to allow the cardholder to make an informed currency choice. These disclosures must occur at the time the DCC offer is made and before the cardholder is asked to choose their preferred transaction currency.
3. <b>Steering:</b> The merchant must not use any language or procedures that may cause the cardholder to choose DCC by default.

The card scheme-mandated disclosures, include:

- Amount of the goods or services (including taxes) shown in the merchant’s local currency
- Currency symbol or code (e.g., AUD or SGD) of the merchant’s local currency
- Exchange rate used to determine the DCC transaction amount
- Any additional exchange rate mark-up over the wholesale or government-mandated rate
- Total transaction amount in the DCC currency
- Currency symbol or code (e.g., AUD or SGD) of the offered DCC transaction amount in cardholder currency

## Features
- Supports Visa and Mastercard transactions 
- Easy to configure DCC margins by scheme or currency
- Multiple rate provider options
- No disruption to funding timelines


## APIs Used
<!-- type: row -->
<!-- type: card 
title: Get Rate
description: This API provides the exchange rate based on merchant hierarchy setup on OpenFX 2.0 platform. The request uses source currency, client cross reference ID ("client"),  merchant cross reference ID ("xref") and BIN to determine the exchange rate.
link: ../api/?type=post&path=/fx/v1/pricing/request
-->

<!-- type: card 
title: Get BINs by Currency
description: This API will provide the list of available BINs in OpenFX for the given currency code.
link: ../api/?type=get&path=/fx/v1/pricing/bin/{currency_code}
-->

<!-- type: row-end -->