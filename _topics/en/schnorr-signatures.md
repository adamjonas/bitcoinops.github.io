---
title: Schnorr signatures

## Required.  At least one category to which this topic belongs.  See
## schema for options
categories:
  - Soft Forks
  - Scripts and Addresses

## Required.  Use Markdown formatting.  Only one paragraph.  No links allowed.
excerpt: >
  **Schnorr signatures** are digital signatures that provide similar
  security to the ECDSA scheme used since Bitcoin's original
  implementation and which can use Bitcoin's same elliptic curve
  parameters, but which can provide other benefits.

## Optional.  Use Markdown formatting.  Multiple paragraphs.  Links allowed.
extended_summary: |
  Schnorr is secure under the same cryptographic assumptions as
  [ECDSA][] and it is easier and faster to create secure multiparty
  signatures using schnorr with protocols such as [MuSig][].  A new
  signature type also provides an opportunity to change the signature
  serialization format from [BER/DER][] to something that's more compact
  and simpler to implement.

  [ECDSA]: https://en.wikipedia.org/wiki/Elliptic_Curve_Digital_Signature_Algorithm
  [BER/DER]: https://en.wikipedia.org/wiki/Basic_Encoding_Rules

## Optional.  Produces a Markdown link with either "[title][]" or
## "[title](link)"
primary_sources:
    - title: bip-schnorr

## Optional.  Each entry requires "title", "url", and "date".  May also use "feature:
## true" to bold entry
optech_mentions:
  - title: "Executive briefing: the next soft fork"
    url: /en/2019-exec-briefing/#the-next-softfork
    date: 2019-07-14
    feature: true

  - title: Proposed schnorr BIP
    url: /en/newsletters/2018/07/10/#featured-news-schnorr-signature-proposed-bip
    date: 2018-07-10

  - title: Continued bip-schnorr discussion
    url: /en/newsletters/2018/07/17/#continuing-discussion-about-schnorr-signatures
    date: 2018-07-17

  - title: Proposed change to schnorr pubkeys
    url: /en/newsletters/2019/08/14/#proposed-change-to-schnorr-pubkeys
    date: 2019-08-14

  - title: Update on changes to schnorr, taproot, and tapscript
    url: /en/newsletters/2019/10/16/#taproot-update
    date: 2019-10-16

  - title: "Talk summary: the quest for practical threshold Schnorr signatures"
    url: /en/newsletters/2019/10/16/#the-quest-for-practical-threshold-schnorr-signatures
    date: 2019-10-16

  - title: Announcement of structured taproot review (including schnorr)
    url: /en/newsletters/2019/10/23/#taproot-review
    date: 2019-10-23

  - title: Bitcoin Optech schnorr/taproot workshop
    url: /en/schorr-taproot-workshop/
    date: 2019-10-29
    feature: true

  - title: Blog post about x-only pubkeys for use in schnorr signature schemes
    url: /en/newsletters/2019/11/13/#x-only-pubkeys
    date: 2019-11-13

  - title: Safety of precomputed public keys used with schnorr signatures
    url: /en/newsletters/2020/02/05/#safety-concerns-related-to-precomputed-public-keys-used-with-schnorr-signatures
    date: 2020-02-05

  - title: "BIP340 alternative x-only pubkey tiebreaker and tagged hash"
    url: /en/newsletters/2020/02/05/#alternative-x-only-pubkey-tiebreaker
    date: 2020-02-05

  - title: Discussion about taproot versus other schnorr-enabling proposals
    url: /en/newsletters/2020/02/19/#discussion-about-taproot-versus-alternatives
    date: 2020-02-19

  - title: Proposed update to schnorr key selection and signature generation
    url: /en/newsletters/2020/03/04/#updates-to-bip340-schnorr-keys-and-signatures
    date: 2020-03-04

  - title: BIP340 schnorr signature recommendations updated for improved security
    url: /en/newsletters/2020/03/04/#bips-886
    date: 2020-03-04

  - title: Implementing statechains without schnorr signatures
    url: /en/newsletters/2020/04/01/#implementing-statechains-without-schnorr-or-eltoo
    date: 2020-04-01

  - title: Mitigating differential power analysis in schnorr signatures
    url: /en/newsletters/2020/04/01/#mitigating-differential-power-analysis-in-schnorr-signatures
    date: 2020-04-01

  - title: "BIP340 schnorr updated with alternative tiebreaker & nonce recommendation"
    url: /en/newsletters/2020/05/06/#bips-893
    date: 2020-05-06

  - title: RFC6979 nonce generation versus BIP340's recommended procedure
    url: /en/newsletters/2020/05/27/#why-isn-t-rfc6979-used-for-schnorr-signature-nonce-generation
    date: 2020-05-27

  - title: Presentations and discussions about schnorr signatures
    url: /en/newsletters/2020/07/01/#schnorr-signatures-and-multisignatures
    date: 2020-07-01

## Optional.  Same format as "primary_sources" above
see_also:
  - title: Will a schnorr soft fork introduce a new address format?
    link: https://bitcoin.stackexchange.com/questions/82952/will-a-schnorr-soft-fork-introduce-a-new-address-format-i-e-not-bech32
  - title: Taproot
    link: topic taproot
---
