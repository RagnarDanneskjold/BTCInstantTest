BTCInstantTest
==============

A test repository for an automated bitcoin reputation engine that can be used for instant confirmations

BIP 70 is currently getting an extension for instant transactions. The concept is that the buyer can give the merchant an instant transaction signature on the message which the merchant can use to decide whether or not to accept an instant transaction.

The current implementation is a short list of accepted instant signatures probably based on agreements between wallet makers and merchant processors. I believe the trust network could be automated so that it wouldn't need to be just based on a small network of trusted parties.

This repository is meant to test theories on how this automated reputation system would work. The results will then be used for a more formal proposal that I am currently in the process of writing.