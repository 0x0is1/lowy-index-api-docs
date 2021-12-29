# Lowy Institute Asia Power Index API Documentation (Unofficial)

[![Say Thanks!](https://img.shields.io/badge/Say%20Thanks-!-1EAEDB.svg)](https://saythanks.io/to/0x0is1) ![Deprecation](https://img.shields.io/badge/Deprecation-No-orange)

### Institute Introduction
The [Lowy Institute](https://lowyinstitute.org) is an independent think tank founded in April 2003 by Frank Lowy to conduct original, policy-relevant research about international political, strategic and economic issues from an Australian perspective. It is based in Sydney, New South Wales, Australia.
___

### API Overview

The annual [Asia Power Index](https://power.lowyinstitute.org/about/) — launched by the Lowy Institute in 2018 — measures resources and influence to rank the relative power of states in Asia. The project maps out the existing distribution of power as it stands today, and tracks shifts in the balance of power over time.

**This api is a back-traced of official website so it will be removed if Lowy Institute asked for. We respect copyright.**

* API BASE URL: `https://power.lowyinstitute.org`

#### API Reference

| References            | Args Required | Request Type |  Info                         |
| ----------------------| ------------- | ------------ | ----------------------------- |
| `/world.json`         |   None        | `http-get`   | World topology data           |
| `/countries.json`     |   None        | `http-get`   | Get List of all countries with `power` and various `score` including **Country's slug** |
| `{country_slug}.json` | Country Slug  | `http-get`   | Get `score`, `influence`, `lat-long` and other additional data. |
| `/data/{Year}.json`   |   Year        | `http-get`   | Get `score`, `rank` and `country code` of Countries by Year (2018+) |
| `/network-power.json` |   None        | `http-get`   | Get `Economic`, `Cultural`, `Defence` and `Diplomatic` networks of countries |
___

### Planned Future Developments
An API wrapper is planned to be made for this project soon in multiple python.

### Licence
This documentation is [licenced](./LICENCE) under GNU GPLv3 for fair use of API.

## Special thanks to our Countributors
+ [Surya](https://github.com/0x0is1)
+ [Matheus Felipe](https://github.com/matheusfelipeog) (Special thanks)

## Message for Countributors
Please consider submitting issue or providing further details of API or adding new figured out api references through the pull request. All kind of contributios are welcomed.

## Message for Lowy Institute
Please let us know if this documentation is violating any kind of your terms or policies through our [email](mailto://0x0is1@protonmail.com). 
