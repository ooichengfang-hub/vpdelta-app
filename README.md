# VP Delta

Live order-flow chart for Binance USDT-M futures, as a single-page web app (iPhone: Safari → Share → Add to Home Screen).

- Volume, delta and liquidation profiles; candle countdown.
- WICK: volume traded at each candle's top/bottom 10% tip, from public aggTrades (older higher-timeframe candles estimated from 1m candles).
- BOOK: order book depth on the price axis (public depth REST + stream).
- ZONE: draw/delete zones, saved per symbol on the device.
- PAPER trading only: simulated long/short with draggable SL/TP and PnL. Never sends orders.

Public Binance market data only. No account, no API keys. Not financial advice.
