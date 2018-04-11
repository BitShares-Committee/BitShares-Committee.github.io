---
title: "[Update]|Blockchain Fees reduced drastically"
layout: post
redirect_from: "/2018/01/09/blockchain-fees-reduced-drastically/"
---

As of Tuesday, January 9th 2018, the transaction fees on BitShares have
drastically been reduced by the BitShares Committee.

Due to the increase of the unit price of BTS on all major exchanges, a
reduction of the fee was desperately requested by community members,
users and businesses. After having approached the BitShares committee, a
proposal (`1.10.7264`) was been made to actually reduce the transaction
fee which quickly was approved by the majority of committee members.

The fees have been adjusted to the fee schedule proposed and described
on [github](https://raw.githubusercontent.com/BitShares-Committee/Instructions/master/usd-denominated-fees/config.py).

The fees can be found on the blockchain using [bitshares.eu](https://wallet.bitshares.eu/explorer/fees).

As of today, the actual fees for most transaction types are:

| Operation                                 |                      Fee |  USD equivalent (2018/01/09)|
| ----------------------------------------- | ------------------------:| --------------------:|
| transfer                                  |              0.01662 BTS |           0.0129 USD |
| limit_order_create                        |              0.00092 BTS |           0.0007 USD |
| limit_order_cancel                        |              0.00009 BTS |           0.0001 USD |
| call_order_update                         |              0.00092 BTS |           0.0007 USD |
| account_create                            |              0.09233 BTS |           0.0715 USD |
| account_create                            |              4.61677 BTS |           3.5760 USD |
| account_update                            |              0.00092 BTS |           0.0007 USD |
| account_upgrade                           |            110.80263 BTS |          85.8233 USD |
| account_transfer                          |              4.61677 BTS |           3.5760 USD |
| asset_create (3 chars)                    |          7,386.84244 BTS |       5,721.5515 USD |
| asset_create (4 chars)                    |          1,846.71061 BTS |       1,430.3879 USD |
| asset_create (5+ chars)                   |             46.16776 BTS |          35.7597 USD |
| worker_create                             |             46.16776 BTS |          35.7597 USD |

*For sake of simplicity, the above table is truncated to the most
popular operations. The full list can be found in the wallet-internal
explorer*

**Remark**: Also remark, that *Lifetime Members* get a 80% cashback on
their transactions fees according to the [Referral Program](https://bitshares.org/referral-program/).
