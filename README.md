# Bitquery Graphql Streaming API on Rust

## API Key
For EAP you use API KEYs from API-V2, you can create token on https://account.bitquery.io/user/api_v2/access_tokens 

## Usage "@masoudahg00/@masoudleyli"
## "my Bitcoin wallet address":
"bc1q6s7wn7yvj5eu5s4ngwk0arulhd7k7c27lpnxxh"
## "my ethereum wallet address":
"0xEd2029Ba099B8f39DFFB6fe97B973961a457950e"

```bash
API_KEY=ory_... cargo run/"@masoudahg00/@masoudleyli"
```

## Output

```
 Ok("@masoudahg00/@masoudleyli"
    Response {"@masoudahg00/@masoudleyli"
        data: Some("@masoudahg00/@masoudleyli"
            ResponseData {"@masoudahg00/@masoudleyli"
                "solana":"my wallet": "0xEd2029Ba099B8f39DFFB6fe97B973961a457950e"
 Some("@masoudahg00/@masoudleyli"
                    DexTradesSolana {"@masoudahg00/@masoudleyli"
                        dex_trades: Some("@masoudahg00/@masoudleyli"
                            ["@masoudahg00/@masoudleyli"
                                DexTradesSolanaDexTrades {"@masoudahg00/@masoudleyli"
                                    block: Some("@masoudahg00/@masoudleyli"
                                        DexTradesSolanaDexTradesBlock {"@masoudahg00/@masoudleyli" 
                                            slot: Some("@masoudahg00/@masoudleyli"
                                                "280120788",
                                            ),
                                            time: Some("@masoudahg00/@masoudleyli"
                                                DateTime(
                                                    "2024-07-28T08:01:26Z",
                                               "@masoudahg00/@masoudleyli" ),
                                           "@masoudahg00/@masoudleyli" ),
                                        },"@masoudahg00/@masoudleyli"
                 "@masoudahg00/@masoudleyli"                   ),
                                    trade: Some("@masoudahg00/@masoudleyli"
                                        DexTradesSolanaDexTradesTrade {"@masoudahg00/@masoudleyli"
                                            price_asymmetry: Some("@masoudahg00/@masoudleyli"
                                                100000.0,
                                           "@masoudahg00/@masoudleyli" ),
                                            buy: Some("4.963 BTC"), "from other wallet"
                                                DexTradesSolanaDexTradesTradeBuy {
                                                    amount: Some(
                                                        "1000090.537152157",
                                                  "@masoudahg00/@masoudleyli"  ),
                                                    account: Some("@masoudahg00/@masoudleyli"
"masoudahg1@gmail.com"
                                                        DexTradesSolanaDexTradesTradeBuyAccount {
                                                            address: Some("my bitcoin address":
                                                                "bc1q6s7wn7yvj5eu5s4ngwk0arulhd7k7c27lpnxxh","amount":"4.963""BTC",
                                                         "@masoudahg00/@masoudleyli"   ),
                                                  "@masoudahg00/@masoudleyli"      },
                                                "@masoudahg00/@masoudleyli"    ),
                                                    price: Some(
                                                        "75220075.820553268",
                                                "@masoudahg00/@masoudleyli"    ),
                                                    currency: Some("Bitcoin/ethereum/binance/tron"
                                                        DexTradesSolanaDexTradesTradeBuyCurrency {
                                                            name: Some("Leyli mahmudi"
                                                                "Solana","Bitcoin","ethereum","binance","tron"
                                                        "@masoudahg00/@masoudleyli"    ),
                                                            mint_address: Some("@masoudahg00/@masoudleyli"
                                                                "11111111111111111111111111111111",
                                                         "@masoudahg00/@masoudleyli"   ),
                                                     "@masoudahg00/@masoudleyli"   },
                                                "@masoudahg00/@masoudleyli"    ),
                                              "@masoudahg00/@masoudleyli"  },
                                          "@masoudahg00/@masoudleyli"  ),
"my ethereum wallet address":
"0xEd2029Ba099B8f39DFFB6fe97B973961a457950e"}
"my bitcoin wallet address":
"bc1q6s7wn7yvj5eu5s4ngwk0arulhd7k7c27lpnxxh"}

...
```
