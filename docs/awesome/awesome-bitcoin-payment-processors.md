<div class="github-widget" data-repo="alexk111/awesome-bitcoin-payment-processors"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
<div align="center">
<img width="500" src="https://raw.githubusercontent.com/alexk111/awesome-bitcoin-payment-processors/master/media/logo.svg?sanitize=true" alt="Awesome Bitcoin Payment Processors"/>
</div>

## Awesome Bitcoin Payment Processors [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

A curated list of awesome Bitcoin payment processors enabling merchants, businesses and nonprofits to accept Bitcoin payments.

Why are they awesome?

1. They are either immune to financial censorship or they don't practice it.
2. They accept Bitcoin via native Bitcoin addresses and don't require wallets to use the [controversial payment protocol](https://blog.samouraiwallet.com/post/169222582782/bitpay-qr-codes-are-no-longer-valid-important).
3. They don't [block payments by IPs/locations](https://twitter.com/alex_kaul/status/1090211252331208705).



## Self-Hosted Bitcoin Payment Processors

Self-Hosted payment processors run on your server and provide you with a full control over the entire payment process and funds. There's no third-party involvement - that significantly increases the censorship-resistance, privacy, and security for you and your customers. 

| Processor | Fees | Lightning | Directly to Your Wallet | Conversion to Fiat | Requirements |
| --------- |:----:|:---------:|:-----------------------:|:------------------:| ------------ |
| [BTCPay Server](https://btcpayserver.org/) | No fees | Yes | Yes | Via [Payment Forwarding](https://www.blockonomics.co/views/payment_forwarding.html) and [Exchange Integration](https://redbtc.org/flows/integrations/kraken-exchange/) | 2 GB RAM, 80 GB Storage, Docker |
| [One Time Address](https://github.com/alexk111/One-Time-Address) | No fees | No | Yes | No | NodeJS |
| [CryptoWoo](https://www.cryptowoo.com/) | $34 - $99 per year | No | Yes | No | PHP 5.6+, Wordpress 4.3+, WooCommerce 3.0+ |
| [BitcartCC](https://bitcartcc.com) | No fees | Yes | Yes | No | 1 GB RAM, 10 GB Storage, Docker |
| [LnMe](https://github.com/bumi/lnme) | No fees | Yes | Yes | No | LND node |
| [BTCPyment](https://github.com/nickfarrow/BTCPyment) | No fees | Yes | Yes | No | Python & a Bitcoin node. Lightning node & Woocommerce optional |

## Hosted Bitcoin Payment Processors

Hosted payment processors run on someone else's server. This simplifies the initial setup process, but reduces the amount of control you have over the payment process.

### Non-Custodial

| Processor | Fees | Lightning | Directly to Your Wallet | Conversion to Fiat | Requirements |
| --------- |:----:|:---------:|:-----------------------:|:------------------:| ------------ |
| [Blockonomics](https://www.blockonomics.co/merchants) | 1% | No | Yes | Via [Payment Forwarding](https://www.blockonomics.co/views/payment_forwarding.html) | No |
| [Bittery.io](https://bittery.io/) | No fees | Yes | Yes | Via [Payment Forwarding](https://www.blockonomics.co/views/payment_forwarding.html) and [Exchange Integration](https://redbtc.org/flows/integrations/kraken-exchange/) | No |
| [Payscrypt](https://payscrypt.com/) | No fees | No | Yes | No | No |

### Custodial

⚠ The following processors use their own wallets for receiving payments. They not only collect data about payments, they have full control over the funds.

| Processor | Fees | Lightning | Directly to Your Wallet | Conversion to Fiat | Requirements |
| --------- |:----:|:---------:|:-----------------------:|:------------------:| ------------ |
| [Confirmo](https://confirmo.net/) | 0.8% | No | No | Yes | Information about business / website. May require certain documents. |
| [CoinGate](https://coingate.com/accept-bitcoin) | 1% (merchant) + some [variable service fee](https://support.coingate.com/en/109/why-does-coingate-charge-service-fee) (customer) | Yes | No | Yes | Requires [a lot of information and business documents](https://blog.coingate.com/2019/05/verify-merchant-account-faq), officially translated in english. |
| [CoinPayments](https://www.coinpayments.net/) | 0.5% | Yes | No | No | On withdrawal may require a number of forms of identification and will require settlement of any outstanding amounts. |
| [GloBee](https://globee.com/) | 1% ($10 min. invoice) | Yes | No | Via [Luno](https://www.luno.com) and [Uphold](https://uphold.com/) | Information about business / website. May require certain documents. |
| [OpenNode](https://www.opennode.co/) | 1% | Yes | No | Yes | Requires [KYC/KYB documents](https://help.opennode.com/en/articles/3654899-kyc-and-kyb-requirements) |
| [Strike](https://strike.acinq.co/) | 1% | Only | No | No | For companies, the name of a company and a physical address. |
| [Coinremitter](https://coinremitter.com/) | 0.23% + 0.0001 | No | No | No | No |
| [Utrust](https://utrust.com/) | 1% | No | No | Yes | Require certain documents. |
| [NOWPayments](https://nowpayments.io/) | ≤0.5% | No | No | No | KYC/AML procedure applied to certain clients, wallet addresses and select assets. |

## Backers 💝

[![Backer](https://mynode.alexkaul.com/gh-backer/top/0/avatar/60)](https://mynode.alexkaul.com/gh-backer/top/0/profile)
[![Backer](https://mynode.alexkaul.com/gh-backer/top/1/avatar/60)](https://mynode.alexkaul.com/gh-backer/top/1/profile)
[![Backer](https://mynode.alexkaul.com/gh-backer/top/2/avatar/60)](https://mynode.alexkaul.com/gh-backer/top/2/profile)
[![Backer](https://mynode.alexkaul.com/gh-backer/top/3/avatar/60)](https://mynode.alexkaul.com/gh-backer/top/3/profile)
[![Backer](https://mynode.alexkaul.com/gh-backer/top/4/avatar/60)](https://mynode.alexkaul.com/gh-backer/top/4/profile)
[![Backer](https://mynode.alexkaul.com/gh-backer/top/5/avatar/60)](https://mynode.alexkaul.com/gh-backer/top/5/profile)
[![Backer](https://mynode.alexkaul.com/gh-backer/top/6/avatar/60)](https://mynode.alexkaul.com/gh-backer/top/6/profile)
[![Backer](https://mynode.alexkaul.com/gh-backer/top/7/avatar/60)](https://mynode.alexkaul.com/gh-backer/top/7/profile)
[![Backer](https://mynode.alexkaul.com/gh-backer/top/8/avatar/60)](https://mynode.alexkaul.com/gh-backer/top/8/profile)
[![Backer](https://mynode.alexkaul.com/gh-backer/top/9/avatar/60)](https://mynode.alexkaul.com/gh-backer/top/9/profile)

[[Donate](https://mynode.alexkaul.com/gh-donate)] Thank you for your support! 🙌