---
title: Hardware wallet interface (HWI)
shortname: hwi

## Required.  At least one category to which this topic belongs.  See
## schema for options
categories:
  - Wallet Collaboration Tools

## Required.  Use Markdown formatting.  Only one paragraph.  No links allowed.
excerpt: >
  **Hardware Wallet Interface (HWI)** is a Python library and command-line tool used
  to interface with hardware wallets using Partially-Signed Bitcoin
  Transactions (PSBTs) and output script descriptors.

## Optional.  Use Markdown formatting.  Multiple paragraphs.  Links allowed.
extended_summary: |
  Designed primary by Bitcoin Core developers to allow that software to
  use hardware wallets as external signers, HWI is now being used by
  other wallets as well.

## Optional.  Produces a Markdown link with either "[title][]" or
## "[title](link)"
primary_sources:
    - title: HWI repository
      link: https://github.com/bitcoin-core/HWI

## Optional.  Each entry requires "title", "url", and "date".  May also use "feature:
## true" to bold entry
optech_mentions:
  - title: Bitcoin Core preliminary hardware wallet support
    url: /en/newsletters/2019/02/19/#bitcoin-core-preliminary-hardware-wallet-support
    date: 2019-02-19

  - title: Bitcoin Core 0.18 with basic hardware signer support
    url: /en/newsletters/2019/05/07/#basic-hardware-signer-support-through-independent-tool
    date: 2019-05-07

  - title: "CoreDev.tech discussions: HWI integration into Bitcoin Core"
    url: /en/newsletters/2019/06/12/#hwi
    date: 2019-06-12

  - title: "2019 year-in-review: HWI"
    url: /en/newsletters/2019/12/28/#core-hwi
    date: 2019-12-18

  - title: BTCPay Vault using HWI for signing
    url: /en/newsletters/2020/02/19/#btcpay-vault-using-hwi-for-signing
    date: 2020-02-19

  - title: Fix for segwit fee overpayment attack affects HWI compatibility
    url: /en/newsletters/2020/06/10/#fee-overpayment-attack-on-multi-input-segwit-transactions
    date: 2020-06-10

  - title: Initial release of Lily Wallet supports HWI
    url: /en/newsletters/2020/07/22/#lily-wallet-initial-release
    date: 2020-07-22

## Optional.  Same format as "primary_sources" above
see_also:
  - title: Partially-Signed Bitcoin Transactions (PSBTs)
    link: topic psbt
---
