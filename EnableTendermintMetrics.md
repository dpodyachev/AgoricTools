# Enable tendermint metrics

To enable the exporting of Tendermint metrics, you need to set the flag for prometheus to true in the *[instrumentation]* section inside of your *~/.ag-chain-cosmos/config/config.toml* file:

[instrumentation]  
prometheus = true  
prometheus_listen_addr = ":26660"  