## Constructing a RESTful API Request
FX Solutions RESTful API allows a merchant or bank partner to get FX Rates used for MCP or DCC within their own website, software, or terminal. Each request consists of the Header followed by the Request Body.

## Environments

FX Solutions has different environments, that allow the consumption of our RESTful APIs for client development and customer testing. For ease of use, only the testing environment will be available.

## Sandbox
https://int.api.fiservapps.com

- Uses Sandbox credentials
- Test APIs before certifying for production
- View the response format of a specific API
  = Experiment, develop code and fix bugs
- Send and cancel "test" transactions
------------------

## API Overview
The FX Solutions APIs use API keys to authenticate requests. You can request your TEST API keys by creating a user account on Developer Studio.

Please keep the TEST API keys secure, these belong to you. Do not share your secret API keys in publicly accessible websites such as GitHub, client-side code, and so forth. All API requests must be made over HTTPS. Calls made using HTTP will fail.

## Authentication
All visitors to the Developer Studio can access the API Documentation to integrate you'll need a TEST API key and secret. You'll need to register for an account to get an API key and secret.

### Access FX Solution APIs

Follow the below steps to get an access to the Developer Studio and use the FX Solutions APIs.

1. Request and create a developer account in the Developer Studio. To create an account, you will need account information and a valid business email address.

2. Receive TEST API Key and Secret. After registration,  the developer will have instant access to the shared sandbox Merchant ID (MID) and FX Solutions Exchange Rate APIs. The developer will also receive a test API Key and Secret via encrypted email. This API Key and Secret will be used for authentication.

3. Construct an API Request to use the FX Solutions APIs in TEST environment. For DCC, use 1) Get RATE call and 2)Get BINS BY CURRENCY. For MCP, recommend Get ALL RATES. 