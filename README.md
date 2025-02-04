# straumr
WebSocket subscription manager - Exchange data streaming - Using CCXT as it's backbone

# TODO
> - [] Containerize pub/sub clients
> - [] Write logic for segregating publishers (and consumers?) based on market criteria
> - [] Benchmark I/O and memory consumption at full throttle on 4 separate exchanges, play around with a single db and segregating by exchange or segregating by exchange:symbol, and splitting into separate databases per exchange.
> - [] Integrate Kafka?
> - [] Integrate Kinesis?
> - [] Final destination: RedShift
> - [] Integrate CCXT CLI charting to monitor prices in real time
