# OandaV20RestApi C++ API

## Types

- <code><a href="./reference.md">Account</a></code>
- <code><a href="./reference.md">AccountChanges</a></code>
- <code><a href="./reference.md">AccountChangesState</a></code>
- <code><a href="./reference.md">AccountProperties</a></code>
- <code><a href="./reference.md">AccountSummary</a></code>
- <code><a href="./reference.md">CalculatedPositionState</a></code>
- <code><a href="./reference.md">CalculatedTradeState</a></code>
- <code><a href="./reference.md">Candlestick</a></code>
- <code><a href="./reference.md">CandlestickData</a></code>
- <code><a href="./reference.md">ClientConfigureRejectTransaction</a></code>
- <code><a href="./reference.md">ClientConfigureTransaction</a></code>
- <code><a href="./reference.md">ClientExtensions</a></code>
- <code><a href="./reference.md">ClientPrice</a></code>
- <code><a href="./reference.md">DynamicOrderState</a></code>
- <code><a href="./reference.md">HomeConversions</a></code>
- <code><a href="./reference.md">Instrument</a></code>
- <code><a href="./reference.md">InstrumentCommission</a></code>
- <code><a href="./reference.md">MarketOrderDelayedTradeClose</a></code>
- <code><a href="./reference.md">MarketOrderMarginCloseout</a></code>
- <code><a href="./reference.md">MarketOrderPositionCloseout</a></code>
- <code><a href="./reference.md">MarketOrderRejectTransaction</a></code>
- <code><a href="./reference.md">MarketOrderTradeClose</a></code>
- <code><a href="./reference.md">MarketOrderTransaction</a></code>
- <code><a href="./reference.md">Order</a></code>
- <code><a href="./reference.md">OrderBook</a></code>
- <code><a href="./reference.md">OrderBookBucket</a></code>
- <code><a href="./reference.md">OrderCancelRejectTransaction</a></code>
- <code><a href="./reference.md">OrderCancelTransaction</a></code>
- <code><a href="./reference.md">OrderClientExtensionsModifyRejectTransaction</a></code>
- <code><a href="./reference.md">OrderClientExtensionsModifyTransaction</a></code>
- <code><a href="./reference.md">OrderFillTransaction</a></code>
- <code><a href="./reference.md">OrderRequest</a></code>
- <code><a href="./reference.md">Position</a></code>
- <code><a href="./reference.md">PositionBook</a></code>
- <code><a href="./reference.md">PositionBookBucket</a></code>
- <code><a href="./reference.md">PositionSide</a></code>
- <code><a href="./reference.md">Price</a></code>
- <code><a href="./reference.md">PriceBucket</a></code>
- <code><a href="./reference.md">PricingHeartbeat</a></code>
- <code><a href="./reference.md">QuoteHomeConversionFactors</a></code>
- <code><a href="./reference.md">StopLossDetails</a></code>
- <code><a href="./reference.md">StopLossOrder</a></code>
- <code><a href="./reference.md">StopLossOrderRejectTransaction</a></code>
- <code><a href="./reference.md">StopLossOrderTransaction</a></code>
- <code><a href="./reference.md">TakeProfitDetails</a></code>
- <code><a href="./reference.md">TakeProfitOrder</a></code>
- <code><a href="./reference.md">TakeProfitOrderRejectTransaction</a></code>
- <code><a href="./reference.md">TakeProfitOrderTransaction</a></code>
- <code><a href="./reference.md">Trade</a></code>
- <code><a href="./reference.md">TradeClientExtensionsModifyRejectTransaction</a></code>
- <code><a href="./reference.md">TradeClientExtensionsModifyTransaction</a></code>
- <code><a href="./reference.md">TradeOpen</a></code>
- <code><a href="./reference.md">TradeReduce</a></code>
- <code><a href="./reference.md">TradeSummary</a></code>
- <code><a href="./reference.md">TrailingStopLossDetails</a></code>
- <code><a href="./reference.md">TrailingStopLossOrder</a></code>
- <code><a href="./reference.md">TrailingStopLossOrderRejectTransaction</a></code>
- <code><a href="./reference.md">TrailingStopLossOrderTransaction</a></code>
- <code><a href="./reference.md">Transaction</a></code>
- <code><a href="./reference.md">TransactionHeartbeat</a></code>
- <code><a href="./reference.md">UnitsAvailable</a></code>
- <code><a href="./reference.md">UnitsAvailableDetails</a></code>
- <code><a href="./reference.md">UserInfo</a></code>
- <code><a href="./reference.md">UserInfoExternal</a></code>

## Instruments

Types:

- <code><a href="./reference.md">Candlestick</a></code>
- <code><a href="./reference.md">CandlestickData</a></code>
- <code><a href="./reference.md">OrderBook</a></code>
- <code><a href="./reference.md">OrderBookBucket</a></code>
- <code><a href="./reference.md">PositionBook</a></code>
- <code><a href="./reference.md">PositionBookBucket</a></code>

Methods:

- <code title="GET /instruments/{instrument}/candles">client.instruments.<a href="./reference.md">listCandles</a>(...)</code>
- <code title="GET /instruments/{instrument}/orderBook">client.instruments.<a href="./reference.md">listOrderBook</a>(...)</code>
- <code title="GET /instruments/{instrument}/positionBook">client.instruments.<a href="./reference.md">listPositionBook</a>(...)</code>

### Price

Types:

- <code><a href="./reference.md">Price</a></code>
- <code><a href="./reference.md">PriceBucket</a></code>

Methods:

- <code title="GET /instruments/{instrument}/price">client.instruments.price.<a href="./reference.md">list</a>(...)</code>
- <code title="GET /instruments/{instrument}/price/range">client.instruments.price.<a href="./reference.md">listRange</a>(...)</code>

## Accounts

Types:

- <code><a href="./reference.md">Account</a></code>
- <code><a href="./reference.md">AccountChanges</a></code>
- <code><a href="./reference.md">AccountChangesState</a></code>
- <code><a href="./reference.md">AccountProperties</a></code>
- <code><a href="./reference.md">AccountSummary</a></code>
- <code><a href="./reference.md">CalculatedPositionState</a></code>
- <code><a href="./reference.md">CalculatedTradeState</a></code>
- <code><a href="./reference.md">ClientConfigureRejectTransaction</a></code>
- <code><a href="./reference.md">ClientConfigureTransaction</a></code>
- <code><a href="./reference.md">ClientExtensions</a></code>
- <code><a href="./reference.md">DynamicOrderState</a></code>
- <code><a href="./reference.md">Order</a></code>
- <code><a href="./reference.md">Position</a></code>
- <code><a href="./reference.md">PositionSide</a></code>
- <code><a href="./reference.md">StopLossOrder</a></code>
- <code><a href="./reference.md">TakeProfitOrder</a></code>
- <code><a href="./reference.md">Trade</a></code>
- <code><a href="./reference.md">TradeSummary</a></code>
- <code><a href="./reference.md">TrailingStopLossOrder</a></code>

Methods:

- <code title="GET /accounts/{accountID}/openPositions">client.accounts.<a href="./reference.md">listOpenPositions</a>(...)</code>
- <code title="GET /accounts/{accountID}/openTrades">client.accounts.<a href="./reference.md">listOpenTrades</a>(...)</code>
- <code title="GET /accounts">client.accounts.<a href="./reference.md">list</a>(...)</code>
- <code title="GET /accounts/{accountID}">client.accounts.<a href="./reference.md">retrieve</a>(...)</code>
- <code title="GET /accounts/{accountID}/summary">client.accounts.<a href="./reference.md">listSummary</a>(...)</code>
- <code title="PATCH /accounts/{accountID}/configuration">client.accounts.<a href="./reference.md">configure</a>(...)</code>
- <code title="GET /accounts/{accountID}/changes">client.accounts.<a href="./reference.md">listChanges</a>(...)</code>
- <code title="GET /accounts/{accountID}/pendingOrders">client.accounts.<a href="./reference.md">listPendingOrders</a>(...)</code>

### Positions

Types:

- <code><a href="./reference.md">ClientExtensions</a></code>
- <code><a href="./reference.md">MarketOrderDelayedTradeClose</a></code>
- <code><a href="./reference.md">MarketOrderMarginCloseout</a></code>
- <code><a href="./reference.md">MarketOrderPositionCloseout</a></code>
- <code><a href="./reference.md">MarketOrderRejectTransaction</a></code>
- <code><a href="./reference.md">MarketOrderTradeClose</a></code>
- <code><a href="./reference.md">MarketOrderTransaction</a></code>
- <code><a href="./reference.md">OrderCancelTransaction</a></code>
- <code><a href="./reference.md">OrderFillTransaction</a></code>
- <code><a href="./reference.md">Position</a></code>
- <code><a href="./reference.md">QuoteHomeConversionFactors</a></code>
- <code><a href="./reference.md">StopLossDetails</a></code>
- <code><a href="./reference.md">TakeProfitDetails</a></code>
- <code><a href="./reference.md">TradeOpen</a></code>
- <code><a href="./reference.md">TradeReduce</a></code>
- <code><a href="./reference.md">TrailingStopLossDetails</a></code>
- <code><a href="./reference.md">UnitsAvailable</a></code>
- <code><a href="./reference.md">UnitsAvailableDetails</a></code>

Methods:

- <code title="GET /accounts/{accountID}/positions">client.accounts.positions.<a href="./reference.md">list</a>(...)</code>
- <code title="GET /accounts/{accountID}/positions/{instrument}">client.accounts.positions.<a href="./reference.md">retrieve</a>(...)</code>
- <code title="PUT /accounts/{accountID}/positions/{instrument}/close">client.accounts.positions.<a href="./reference.md">close</a>(...)</code>

### Trades

Types:

- <code><a href="./reference.md">ClientExtensions</a></code>
- <code><a href="./reference.md">MarketOrderRejectTransaction</a></code>
- <code><a href="./reference.md">MarketOrderTransaction</a></code>
- <code><a href="./reference.md">OrderCancelRejectTransaction</a></code>
- <code><a href="./reference.md">OrderCancelTransaction</a></code>
- <code><a href="./reference.md">OrderFillTransaction</a></code>
- <code><a href="./reference.md">StopLossDetails</a></code>
- <code><a href="./reference.md">StopLossOrderRejectTransaction</a></code>
- <code><a href="./reference.md">StopLossOrderTransaction</a></code>
- <code><a href="./reference.md">TakeProfitDetails</a></code>
- <code><a href="./reference.md">TakeProfitOrderRejectTransaction</a></code>
- <code><a href="./reference.md">TakeProfitOrderTransaction</a></code>
- <code><a href="./reference.md">Trade</a></code>
- <code><a href="./reference.md">TradeClientExtensionsModifyRejectTransaction</a></code>
- <code><a href="./reference.md">TradeClientExtensionsModifyTransaction</a></code>
- <code><a href="./reference.md">TrailingStopLossDetails</a></code>
- <code><a href="./reference.md">TrailingStopLossOrderRejectTransaction</a></code>
- <code><a href="./reference.md">TrailingStopLossOrderTransaction</a></code>

Methods:

- <code title="GET /accounts/{accountID}/trades">client.accounts.trades.<a href="./reference.md">list</a>(...)</code>
- <code title="GET /accounts/{accountID}/trades/{tradeSpecifier}">client.accounts.trades.<a href="./reference.md">retrieve</a>(...)</code>
- <code title="PUT /accounts/{accountID}/trades/{tradeSpecifier}/close">client.accounts.trades.<a href="./reference.md">close</a>(...)</code>
- <code title="PUT /accounts/{accountID}/trades/{tradeSpecifier}/clientExtensions">client.accounts.trades.<a href="./reference.md">setClientExtensions</a>(...)</code>
- <code title="PUT /accounts/{accountID}/trades/{tradeSpecifier}/orders">client.accounts.trades.<a href="./reference.md">setDependentOrders</a>(...)</code>

### Instruments

Types:

- <code><a href="./reference.md">Candlestick</a></code>
- <code><a href="./reference.md">Instrument</a></code>
- <code><a href="./reference.md">InstrumentCommission</a></code>

Methods:

- <code title="GET /accounts/{accountID}/instruments">client.accounts.instruments.<a href="./reference.md">list</a>(...)</code>
- <code title="GET /accounts/{accountID}/instruments/{instrument}/candles">client.accounts.instruments.<a href="./reference.md">listCandlesUnits</a>(...)</code>

### Transactions

Types:

- <code><a href="./reference.md">Transaction</a></code>
- <code><a href="./reference.md">TransactionHeartbeat</a></code>

Methods:

- <code title="GET /accounts/{accountID}/transactions">client.accounts.transactions.<a href="./reference.md">list</a>(...)</code>
- <code title="GET /accounts/{accountID}/transactions/{transactionID}">client.accounts.transactions.<a href="./reference.md">retrieve</a>(...)</code>
- <code title="GET /accounts/{accountID}/transactions/idrange">client.accounts.transactions.<a href="./reference.md">listRange</a>(...)</code>
- <code title="GET /accounts/{accountID}/transactions/sinceid">client.accounts.transactions.<a href="./reference.md">listSince</a>(...)</code>
- <code title="GET /accounts/{accountID}/transactions/stream">client.accounts.transactions.<a href="./reference.md">stream</a>(...)</code>

### Pricing

Types:

- <code><a href="./reference.md">ClientPrice</a></code>
- <code><a href="./reference.md">HomeConversions</a></code>
- <code><a href="./reference.md">PricingHeartbeat</a></code>

Methods:

- <code title="GET /accounts/{accountID}/pricing">client.accounts.pricing.<a href="./reference.md">list</a>(...)</code>
- <code title="GET /accounts/{accountID}/pricing/stream">client.accounts.pricing.<a href="./reference.md">stream</a>(...)</code>

### Orders

Types:

- <code><a href="./reference.md">ClientExtensions</a></code>
- <code><a href="./reference.md">Order</a></code>
- <code><a href="./reference.md">OrderCancelRejectTransaction</a></code>
- <code><a href="./reference.md">OrderCancelTransaction</a></code>
- <code><a href="./reference.md">OrderClientExtensionsModifyRejectTransaction</a></code>
- <code><a href="./reference.md">OrderClientExtensionsModifyTransaction</a></code>
- <code><a href="./reference.md">OrderFillTransaction</a></code>
- <code><a href="./reference.md">OrderRequest</a></code>
- <code><a href="./reference.md">Transaction</a></code>

Methods:

- <code title="POST /accounts/{accountID}/orders">client.accounts.orders.<a href="./reference.md">create</a>(...)</code>
- <code title="GET /accounts/{accountID}/orders">client.accounts.orders.<a href="./reference.md">list</a>(...)</code>
- <code title="GET /accounts/{accountID}/orders/{orderSpecifier}">client.accounts.orders.<a href="./reference.md">retrieve</a>(...)</code>
- <code title="PUT /accounts/{accountID}/orders/{orderSpecifier}">client.accounts.orders.<a href="./reference.md">replace</a>(...)</code>
- <code title="PUT /accounts/{accountID}/orders/{orderSpecifier}/cancel">client.accounts.orders.<a href="./reference.md">cancel</a>(...)</code>
- <code title="PUT /accounts/{accountID}/orders/{orderSpecifier}/clientExtensions">client.accounts.orders.<a href="./reference.md">setClientExtensions</a>(...)</code>

## Users

Types:

- <code><a href="./reference.md">UserInfo</a></code>
- <code><a href="./reference.md">UserInfoExternal</a></code>

Methods:

- <code title="GET /users/{userSpecifier}">client.users.<a href="./reference.md">retrieve</a>(...)</code>
- <code title="GET /users/{userSpecifier}/externalInfo">client.users.<a href="./reference.md">listExternalInfo</a>(...)</code>

## Pricing

Types:

- <code><a href="./reference.md">Price</a></code>

Methods:

- <code title="GET /pricing">client.pricing.<a href="./reference.md">list</a>(...)</code>
- <code title="GET /pricing/range">client.pricing.<a href="./reference.md">listPriceRange</a>(...)</code>
