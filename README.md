# rescue-fatfinger

This repo is about rescuing a fatfinger transaction generator who made a catastrophic mistake when setting the gas and gas-price.


## 1. Reasoning of rescue

- fees/gas/gas-price is a very confusing concept for normal users.
- gaiacli is not well-documented for normal users.
- Cosmos team suggested delegators to use gaiacli although there was no perfect documentation of it.
- There was no easy & secure way to generate and broadcast a transaction in early cosmoshub-1


## 2. Victim Address

- cosmos10whs4lsz6yjc90nzs6t4re5jv6lj59qr6zuxf8


## 3. Transactions

- block height : 98182,98201,98211,98222,98227
- tx_hash : 

  4EEB9B1A1202634A193B0365F54A84869ADFBBAAA94F30F01DB599725F1ED034
  72686AD3A78775B1371937C900FBA02915A799E3763ADB35013F7A614E6596B4
  8E76A09D379F7A9052AF0FE8A511DB5197A397DA0D4FF53C9982B4A51B6E40DB
  428304148802195AC6C983B6F721B0C59B2AD3C99B7E03410510601D2A6F716B
  6397D0A7F4B087BECEEE63E06ADB9121A013C1D3B0F8F361D52F515798F024D4


## 4. Transaction Contents

- [txs.json](https://github.com/b-harvest/rescue-fatfinger/blob/master/txs.json)


## 5. Total used atom from 5 mistaken transactions

- 14,578.6 + 2,697.152 + 2,697.152 + 2,697.152 + 7,289.6 = **29,959.656** ATOM

## 6. Distribution of mistaken transaction fees

Markdown | Less | Pretty
--- | --- | ---
aaa | bbb | ccc
1 | 2 | 3
