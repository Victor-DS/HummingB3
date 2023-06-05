# HummingB3

----

[![License](https://img.shields.io/badge/License-Apache%202.0-informational.svg)](https://github.com/hummingbot/hummingbot/blob/master/LICENSE)

The idea of this project is to build a simple trading bot on top of the original HummingBot that works on the B3 stock exchange. The goal is to remove the crypto-specific code, and have a more generic platform that is easy to connect to B3 and implement new strategies, we will keep *some* the already implemented ones where it makes sense.

For now, the original HummingBot documentation is valid for building and understanding the overall project, will build a new doc when it diverges enough to justify it.

This code is free and publicly available under the Apache 2.0 open source license!

## Quick Links

* [Docs](https://docs.hummingbot.org): The original Hummingbot documentation
* [Installation](https://hummingbot.org/installation/): Original installation instructions for HummingBot, still valid.


## Strategies and Scripts

We provide customizable strategy templates for core trading strategies that users can configure, extend, and run. Hummingbot Foundation maintains three **CORE** strategies:

* [Pure Market Making](https://docs.hummingbot.org/strategies/pure-market-making/): Our original single-pair market making strategy

**CORE** strategies are selected via HBOT voting through quarterly [Polls](https://hummingbot.org/maintenance/certification/). In addition, the codebase includes **COMMUNITY** strategies that are maintained by individuals or firms in the community. See the [Hummingbot documentation](https://docs.hummingbot.org/strategies) for all strategies supported.

### Scripts

Scripts are a newer, lighter way to build Hummingbot strategies in Python, which let you modify the script's code and re-run it to apply the changes without exiting the Hummingbot interface or re-compiling the code.

See the [Scripts](https://docs.hummingbot.org/scripts/) section in the documentation for more info, or check out the [/scripts](https://github.com/hummingbot/hummingbot/tree/master/scripts) folder for all Script examples included in the codebase.
