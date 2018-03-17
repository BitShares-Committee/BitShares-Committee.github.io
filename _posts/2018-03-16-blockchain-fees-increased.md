---
layout: post
title: "[Update]|Blockchain fees increased"
--- 

As of Friday, March 16th 2018, the transaction fees on BitShares have
been increased by the BitShares Committee.

Due to the decrease of the unit price of BTS on all major exchanges, an increase 
of the fees was required to align with the agreed upon USD values.
After discussions, the BitShares committee created a
proposal (`1.10.8736`) to actually increase the transaction
fees which was quickly approved by the majority of committee members.

The fees have been adjusted to the fee schedule proposed and described
on [github](https://raw.githubusercontent.com/BitShares-Committee/Instructions/master/usd-denominated-fees/config.py).

The fees can be found on the blockchain using [bitshares.eu](https://wallet.bitshares.eu/explorer/fees).

As of today, the actual fees for most transaction types are:

| Operation                                 |                      Fee |  USD equivalent (2018/03/15)|
| ----------------------------------------- | ------------------------:| --------------------:|
| transfer                                  |              0.10420 BTS |           0.0180 USD |
| limit_order_create                        |              0.00578 BTS |           0.0010 USD |
| limit_order_cancel                        |              0.00057 BTS |           0.0001 USD |
| call_order_update                         |              0.00578 BTS |           0.0010 USD |
| account_create                            |              0.57900 BTS |           0.1000 USD |
| account_create                            |             28.95000 BTS |           5.0000 USD |
| account_update                            |              0.00578 BTS |           0.0010 USD |
| account_upgrade                           |            695.00000 BTS |         120.0000 USD |
| account_transfer                          |             28.95000 BTS |           5.0000 USD |
| asset_create (3 chars)                    |         46,313.00000 BTS |       8,000.0000 USD |
| asset_create (4 chars)                    |         11,578.00000 BTS |       2,000.0000 USD |
| asset_create (5+ chars)                   |            289.50000 BTS |          50.0000 USD |
| worker_create                             |            289.50000 BTS |          50.0000 USD |

*For sake of simplicity, the above table is truncated to the most popular operations. The full list can be found in the wallet-internal explorer*

**Remark**: Also remark, that *Lifetime Members* get a 80% cashback on
their transactions fees according to the [Referral Program](https://bitshares.org/referral-program/).
