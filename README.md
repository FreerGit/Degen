# Tasks

## smol

Feeds should not render as chunks of list but rather singles, maybe stagger? - has to be smoother
colors based on difference from min - tresholds or only min size

## Large

These are all @not done@ - just temp

- [x] Starting state - JSON local storage
  - [x] remove dexie
  - [x] use local storage
- [ ] Options for trades feed
  - [ ] delete
  - [ ] search
    - To finish search multiple things need to happen.
    1. If markets are not in localstorage then go to point 2. ELSE go to point 3.
    2. All markets across linear, perp and spot needs to be fetched for each exchange. SAMPLE DONE
    3. display all exchanges in modal and search bar for markets, this should be 5-10k pairs.
    4. After all pairs are chosen, save it.
    5. Reinstate the websocket subscription for the updated pairs.
  - [x] settings
- [ ] liq feed
- [ ] options for liq feed
- [ ] trades delta over time
- [ ] make both feeds removeable (only bybit)
- [ ] make both feeds addable (only bybit)
- [ ] make order books addable (only bybit)
- [ ] make order books removable (only bybit)
- [ ] polish feeds
- [ ] polish order book
- [ ] add coinbase order books
- [ ] add coinbase liq feed
- [ ] add coinbase trade feed
- [ ] make settings savable - local storage

## Issues

Who handles subscriptions?

## Layout

Maybe resizable windows later for OB and feeds but for now just have sized windows with layout config

## EOD - NEXT UP

be able to add trade feeds
be able to remove trade feeds

also should be able to remove chosen markets.
search modal shouldn't look like shit
