# rescue-fatfinger

This repo is about rescuing a fatfinger transaction generator who made a catastrophic mistake when setting the gas and gas-price.
<br />
<br />

## 1. Reasoning of rescue

- fees/gas/gas-price is a very confusing concept for normal users.
- Cosmos team suggested delegators to use gaiacli
- there was no easy-to-understand fees/gas/gas-price documentation on gaiacli.
- There was no easy & secure way to generate and broadcast a transaction by client-apps in early cosmoshub-1
- Those 5 transactions are the only transactions with above 1,000ATOM fees in cosmoshub-1

**We respectfully ask generosity of validators to donate 50% of mistakenly payed fees to the generator for the behalf of their delegators(It is still very thankful if validators donate more than 50% of mistakenly payed fees.)**
<br />
<br />


## 2. Transactions with above 10ATOM fees

height | tx_fee | tx_hash | tx_generator
--- | --- | --- | ---
<sub>**98182**</sub> | <sub>**14,578.6**</sub> | <sub>4EEB9B1A1202634A193B0365F54A84869ADFBBAAA94F30F01DB599725F1ED034</sub> | <sub>cosmos10whs4lsz6yjc90nzs6t4re5jv6lj59qr6zuxf8</sub>
<sub>**98201**</sub> | <sub>**2,697.152**</sub> | <sub>72686AD3A78775B1371937C900FBA02915A799E3763ADB35013F7A614E6596B4</sub> | <sub>cosmos10whs4lsz6yjc90nzs6t4re5jv6lj59qr6zuxf8</sub>
<sub>**98211**</sub> | <sub>**2,697.152**</sub> | <sub>8E76A09D379F7A9052AF0FE8A511DB5197A397DA0D4FF53C9982B4A51B6E40DB</sub> | <sub>cosmos10whs4lsz6yjc90nzs6t4re5jv6lj59qr6zuxf8</sub> 
<sub>**98222**</sub> | <sub>**2,697.152**</sub> | <sub>428304148802195AC6C983B6F721B0C59B2AD3C99B7E03410510601D2A6F716B</sub> | <sub>cosmos10whs4lsz6yjc90nzs6t4re5jv6lj59qr6zuxf8</sub> 
<sub>**98227**</sub> | <sub>**7,289.6**</sub> | <sub>6397D0A7F4B087BECEEE63E06ADB9121A013C1D3B0F8F361D52F515798F024D4</sub> | <sub>cosmos10whs4lsz6yjc90nzs6t4re5jv6lj59qr6zuxf8</sub>
<sub>287779</sub> | <sub>351.792</sub> | <sub>913ABBE761846669499A2CA75F8DD613B55A16B9522CCB703F76D08DDEA9413D</sub> | <sub>cosmos1eh6l0lzaw29rvkwt5wcazhddhfuq4qt8jyq8q6</sub>
<sub>287807</sub> | <sub>370.353</sub> | <sub>D4498125C3BCA98CF5DC280874AA24A4F2FC19314E46E784258935039D2A6942</sub> | <sub>cosmos1eh6l0lzaw29rvkwt5wcazhddhfuq4qt8jyq8q6</sub>


<br />


## 3. Transaction generator with above 1,000ATOM fees

- cosmos10whs4lsz6yjc90nzs6t4re5jv6lj59qr6zuxf8
<br />



## 4. Transaction contents

- [txs.json](https://github.com/b-harvest/rescue-fatfinger/blob/master/txs.json)
<br />

## 5. Total used atom from 5 mistaken transactions

- 14,578.6 + 2,697.152 + 2,697.152 + 2,697.152 + 7,289.6 = **29,959.656** ATOM
<br />

## 6. Distribution of mistaken transaction fees by each validator

- [Distributions.md](https://github.com/b-harvest/rescue-fatfinger/blob/master/Distribution.md)
