## Security

### Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | The Intrinio ID for the Security | [optional] 
**company_id** | **str** | The Intrinio ID for the company for which the Security is issued | [optional] 
**name** | **str** | The name of the Security | [optional] 
**type** | **str** | The Security&#39;s type | [optional] 
**code** | **str** | A 2-3 digit code classifying the Security | [optional] 
**share_class** | **str** | The Security&#39;s share class (if applicable) | [optional] 
**currency** | **str** | The currency in which the Security is traded on the exchange | [optional] 
**round_lot_size** | **float** | The normal unit of trading | [optional] 
**ticker** | **str** | The common ticker | [optional] 
**exchange_ticker** | **str** | The exchange-level ticker | [optional] 
**composite_ticker** | **str** | The country-composite ticker | [optional] 
**alternate_tickers** | **list[str]** | Alternate formats of the common ticker | [optional] 
**figi** | **str** | The exchange-level OpenFIGI identifier | [optional] 
**cik** | **str** | Central Index Key issued by the SEC, which is the unique identifier for all owner filings | [optional] 
**composite_figi** | **str** | The country-composite OpenFIGI identifier | [optional] 
**share_class_figi** | **str** | The global-composite OpenFIGI identifier | [optional] 
**figi_uniqueid** | **str** | The OpenFIGI unique ID | [optional] 
**active** | **bool** | If true, the Security is active and has been recently traded | [optional] 
**etf** | **bool** | If true, this Security is an ETF | [optional] 
**delisted** | **bool** | If true, the Security is no longer traded on the exchange | [optional] 
**primary_listing** | **bool** | If true, the Security is the primary issue for the company, otherwise it is a secondary issue on a secondary stock exchange | [optional] 
**primary_security** | **bool** | If true, the Security is considered by Intrinio to be the primary Security for its company | [optional] 
**first_stock_price** | **date** | The date of the first recorded stock price | [optional] 
**last_stock_price** | **date** | The date of the last recorded stock price (or the most recent trading day) | [optional] 
**last_stock_price_adjustment** | **date** | The date of the last stock price adjustment (dividend, split, etc) | [optional] 
**last_corporate_action** | **date** | The date of the last corporate action | [optional] 
**previous_tickers** | **list[str]** | Previous tickers used by this security | [optional] 
**listing_exchange_mic** | **str** | The MIC code of the exchange on which this security primarily trades | [optional] 



