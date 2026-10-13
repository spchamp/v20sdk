# OandaV20RestApi C++ SDK Reference

## Operations

### instruments.listCandles

Get Candlesticks

- HTTP: `GET /instruments/{instrument}/candles`
- Response body: `application/json`
- Errors: `400, 401, 404, 405`

### instruments.listOrderBook

Get Order Book

- HTTP: `GET /instruments/{instrument}/orderBook`
- Response body: `application/json`
- Errors: `400, 401, 404, 405`

### instruments.listPositionBook

Get Position Book

- HTTP: `GET /instruments/{instrument}/positionBook`
- Response body: `application/json`
- Errors: `400, 401, 404, 405`

### instruments.price.list

Price

- HTTP: `GET /instruments/{instrument}/price`
- Response body: `application/json`
- Errors: `400, 401, 404, 405`

### instruments.price.listRange

Get Prices

- HTTP: `GET /instruments/{instrument}/price/range`
- Response body: `application/json`
- Errors: `400, 401, 404, 405`

### accounts.listOpenPositions

Open Positions

- HTTP: `GET /accounts/{accountID}/openPositions`
- Response body: `application/json`
- Errors: `401, 404, 405`

### accounts.listOpenTrades

List Open Trades

- HTTP: `GET /accounts/{accountID}/openTrades`
- Response body: `application/json`
- Errors: `401, 404, 405`

### accounts.list

List Accounts

- HTTP: `GET /accounts`
- Response body: `application/json`
- Errors: `401, 405`

### accounts.retrieve

Account Details

- HTTP: `GET /accounts/{accountID}`
- Response body: `application/json`
- Errors: `400, 401, 405`

### accounts.listSummary

Account Summary

- HTTP: `GET /accounts/{accountID}/summary`
- Response body: `application/json`
- Errors: `400, 401, 405`

### accounts.configure

Configure Account

- HTTP: `PATCH /accounts/{accountID}/configuration`
- Request body: `application/json`
- Response body: `application/json`
- Errors: `400, 401, 403, 404, 405`

### accounts.listChanges

Poll Account Updates

- HTTP: `GET /accounts/{accountID}/changes`
- Response body: `application/json`
- Errors: `401, 404, 405, 416`

### accounts.listPendingOrders

Pending Orders

- HTTP: `GET /accounts/{accountID}/pendingOrders`
- Response body: `application/json`
- Errors: `401, 404, 405`

### accounts.positions.list

List Positions

- HTTP: `GET /accounts/{accountID}/positions`
- Response body: `application/json`
- Errors: `401, 404, 405`

### accounts.positions.retrieve

Instrument Position

- HTTP: `GET /accounts/{accountID}/positions/{instrument}`
- Response body: `application/json`
- Errors: `401, 404, 405`

### accounts.positions.close

Close Position

- HTTP: `PUT /accounts/{accountID}/positions/{instrument}/close`
- Request body: `application/json`
- Response body: `application/json`
- Errors: `400, 401, 404, 405`

### accounts.trades.list

List Trades

- HTTP: `GET /accounts/{accountID}/trades`
- Response body: `application/json`
- Errors: `401, 404, 405`

### accounts.trades.retrieve

Trade Details

- HTTP: `GET /accounts/{accountID}/trades/{tradeSpecifier}`
- Response body: `application/json`
- Errors: `401, 404, 405`

### accounts.trades.close

Close Trade

- HTTP: `PUT /accounts/{accountID}/trades/{tradeSpecifier}/close`
- Request body: `application/json`
- Response body: `application/json`
- Errors: `400, 401, 404, 405`

### accounts.trades.setClientExtensions

Set Trade Client Extensions

- HTTP: `PUT /accounts/{accountID}/trades/{tradeSpecifier}/clientExtensions`
- Request body: `application/json`
- Response body: `application/json`
- Errors: `400, 401, 404, 405`

### accounts.trades.setDependentOrders

Set Dependent Orders

- HTTP: `PUT /accounts/{accountID}/trades/{tradeSpecifier}/orders`
- Request body: `application/json`
- Response body: `application/json`
- Errors: `400, 401, 404, 405`

### accounts.instruments.list

Account Instruments

- HTTP: `GET /accounts/{accountID}/instruments`
- Response body: `application/json`
- Errors: `400, 401, 405`

### accounts.instruments.listCandlesUnits

Get Candlesticks

- HTTP: `GET /accounts/{accountID}/instruments/{instrument}/candles`
- Response body: `application/json`
- Errors: `400, 401, 404, 405`

### accounts.transactions.list

List Transactions

- HTTP: `GET /accounts/{accountID}/transactions`
- Response body: `application/json`
- Errors: `400, 401, 403, 404, 405, 416`

### accounts.transactions.retrieve

Transaction Details

- HTTP: `GET /accounts/{accountID}/transactions/{transactionID}`
- Response body: `application/json`
- Errors: `401, 404, 405`

### accounts.transactions.listRange

Transaction ID Range

- HTTP: `GET /accounts/{accountID}/transactions/idrange`
- Response body: `application/json`
- Errors: `400, 401, 404, 405, 416`

### accounts.transactions.listSince

Transactions Since ID

- HTTP: `GET /accounts/{accountID}/transactions/sinceid`
- Response body: `application/json`
- Errors: `400, 401, 404, 405, 416`

### accounts.transactions.stream

Transaction Stream

- HTTP: `GET /accounts/{accountID}/transactions/stream`
- Response body: `application/json`
- Errors: `400, 401, 404, 405`

### accounts.pricing.list

Current Account Prices

- HTTP: `GET /accounts/{accountID}/pricing`
- Response body: `application/json`
- Errors: `400, 401, 404, 405`

### accounts.pricing.stream

Price Stream

- HTTP: `GET /accounts/{accountID}/pricing/stream`
- Response body: `application/json`
- Errors: `400, 401, 404, 405`

### accounts.orders.create

Create Order

- HTTP: `POST /accounts/{accountID}/orders`
- Request body: `application/json`
- Response body: `application/json`
- Errors: `400, 401, 403, 404, 405`

### accounts.orders.list

List Orders

- HTTP: `GET /accounts/{accountID}/orders`
- Response body: `application/json`
- Errors: `400, 404, 405`

### accounts.orders.retrieve

Get Order

- HTTP: `GET /accounts/{accountID}/orders/{orderSpecifier}`
- Response body: `application/json`
- Errors: `401, 404, 405`

### accounts.orders.replace

Replace Order

- HTTP: `PUT /accounts/{accountID}/orders/{orderSpecifier}`
- Request body: `application/json`
- Response body: `application/json`
- Errors: `400, 401, 404, 405`

### accounts.orders.cancel

Cancel Order

- HTTP: `PUT /accounts/{accountID}/orders/{orderSpecifier}/cancel`
- Response body: `application/json`
- Errors: `401, 404, 405`

### accounts.orders.setClientExtensions

Set Order Extensions

- HTTP: `PUT /accounts/{accountID}/orders/{orderSpecifier}/clientExtensions`
- Request body: `application/json`
- Response body: `application/json`
- Errors: `400, 401, 404, 405`

### users.retrieve

User Info

- HTTP: `GET /users/{userSpecifier}`
- Response body: `application/json`
- Errors: `401, 403, 405`

### users.listExternalInfo

External User Info

- HTTP: `GET /users/{userSpecifier}/externalInfo`
- Response body: `application/json`
- Errors: `401, 403, 405`

### pricing.list

Get Base Prices

- HTTP: `GET /pricing`
- Response body: `application/json`
- Errors: `400, 401, 404, 405`

### pricing.listPriceRange

Get Price Range

- HTTP: `GET /pricing/range`
- Response body: `application/json`
- Errors: `400, 401, 404, 405`

## Models

- `Candlestick`
- `CandlestickData`
- `OrderBook`
- `OrderBookBucket`
- `PositionBook`
- `PositionBookBucket`
- `Position`
- `PositionSide`
- `CalculatedPositionState`
- `Trade`
- `TradeSummary`
- `CalculatedTradeState`
- `Instrument`
- `InstrumentCommission`
- `Account`
- `AccountChangesState`
- `AccountProperties`
- `AccountSummary`
- `AccountChanges`
- `Transaction`
- `ClientConfigureTransaction`
- `ClientConfigureRejectTransaction`
- `MarketOrderTransaction`
- `MarketOrderRejectTransaction`
- `TakeProfitOrderTransaction`
- `TakeProfitOrderRejectTransaction`
- `StopLossOrderTransaction`
- `StopLossOrderRejectTransaction`
- `TrailingStopLossOrderTransaction`
- `TrailingStopLossOrderRejectTransaction`
- `OrderFillTransaction`
- `OrderCancelTransaction`
- `OrderCancelRejectTransaction`
- `OrderClientExtensionsModifyTransaction`
- `OrderClientExtensionsModifyRejectTransaction`
- `TradeClientExtensionsModifyTransaction`
- `TradeClientExtensionsModifyRejectTransaction`
- `ClientExtensions`
- `TakeProfitDetails`
- `StopLossDetails`
- `TrailingStopLossDetails`
- `TradeOpen`
- `TradeReduce`
- `MarketOrderTradeClose`
- `MarketOrderMarginCloseout`
- `MarketOrderDelayedTradeClose`
- `MarketOrderPositionCloseout`
- `TransactionHeartbeat`
- `UserInfo`
- `UserInfoExternal`
- `ClientPrice`
- `QuoteHomeConversionFactors`
- `HomeConversions`
- `PricingHeartbeat`
- `DynamicOrderState`
- `Order`
- `TakeProfitOrder`
- `StopLossOrder`
- `TrailingStopLossOrder`
- `OrderRequest`
- `UnitsAvailableDetails`
- `UnitsAvailable`
- `PriceBucket`
- `Price`
