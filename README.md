## Qt Bitcoin Trader

This software helps you open and cancel orders very fast. Real time data monitoring.

Developed on pure Qt, uses OpenSSL, AES 256 key and secret protection.

I want to develop this Trader App so that it can be configured for any rule and strategy.

Next ToDo:
- Add realtime charts
- Make rules more advanced

## Official website

* https://centrabit.com/index.php?m0prm=6

## Download binaries

* https://sourceforge.net/projects/bitcointrader/  `Win32`,`Mac`
* http://www.softpedia.com/get/Others/Finances-Business/Bitcoin-Trader.shtml `Win32`
* http://mac.softpedia.com/get/Finance/Qt-Bitcoin-Trader.shtml `Mac`
* http://packages.gentoo.org/package/app-office/QtBitcoinTrader `Gentoo`
* http://packages.altlinux.org/en/Sisyphus/srpms/QtBitcoinTrader `Alt Linux`

## Compilation on Linux
```
sudo apt-get install g++ libssl-dev libglu1-mesa-dev qt5-qmake qtscript5-dev qtmultimedia5-dev
export QT_SELECT=5
qmake QtBitcoinTrader_Desktop.pro
make && make install && make clean
```

## Demos

* http://www.youtube.com/watch?v=C--P258DQkk

## Forums

* https://bitcointalk.org/index.php?topic=201062 `ENG`
* https://bitcointalk.org/index.php?topic=218044 `RUS`
* https://forum.btcsec.com/index.php?/topic/1496-qt-bitcoin-trader-klient-mtgox-pod-macwinlinux/ `RUS`

## Social

* http://www.facebook.com/QtBitcoinTrader
* http://twitter.com/QtBitcoinTrader
* http://vk.com/QtBitcoinTrader `RUS`

## Change Log

v1.40.09
- Fixed FeeCalculator crash
- Fixed account open orders filtering and calculations
- UI layout bugs fixed

v1.40.08
- Added WEX exchange, removed BTC-e
- Fixed crash on app closing
- Added confirmation message on script editor clear
- Minor fixes

v1.40.07
- Release builds for Win64
- Fix balance for OKCoin
- Fix script for Bitfinex
- Fix order type for Bitfinex
- JL Script logs now recognize endline and tabulation
- Fixed bug when silent auto update wont work

v1.40.06
- Fixed fee calculator issue
- Added new currencies
- Minor improvements and fixes

v1.40.03
- Bitfinex support fixes
- Secure auto update now works via Proxy
- YoBit support fixes
- Added button to force resync currencies

v1.4
- New Exchange YoBit.net
- Currency pair synchronization on startup!
- Fixed issue with functions getPriceByVolume and getVolumeByPrice in JL Script
- Add HiDPI enable or disable settings
- Now you can search for currency pairs by keyword
- Improved many elements of interface
- Fixed bug with certificate that caused error messages
- Many other small fixes

v1.30.04
- Add new pair for BitStamp
- Fixd fee calculations in Bitfinex
- Main window title now shows middle price instead of last trade price
- Fixed issue when app can't start

v1.30.03
- High screen resolution support for Windows
- Fixed fee for BTCChina and OKCoin
- Add new pairs for Bitfinex
- Fixed authorization for Bitfinex
- Completed the Norwegian translation
- Fixed bug on restoring Workspace from previous state
- Fixed account data and add new pairs for bitstamp
- Fixed minor bugs

v1.3
- macOS Sierra support
- JL Script file read/write support
- Syncronised currency pairs of Bitfinex, Bitstamp, BTC-e
- Fixed bugs of history and currency pair in Bitstamp
- Improved Proxy settings
- Fixed network stat information
- Fixed display of balance in bitfinex, bitstamp, btcchina
- Fix tonce in btcchina
- Add reducing interface elements spacing (optional in settings)
- Add inactive start script button
- Fixed JL Script groups bug
- Fixed open order/cancel bug in bitstamp
- Fixed time synchronization bug


v1.07.01
- Hotfix. High CPU load fix. Nonce error fix

v1.07
- Improved connection stability
- API engine rewrited
- Added balances triggers to rules
- Fixed RUR currency in BTC-e
- Fixed auto-scroll mode in last trades
- Fixed many minor bugs
- Now all binaries is digitally signed

v1.06
- Bugfix release
- Fixed critical bug in Mt.Gox engine
- Fixed Mac OS X "New window" bug
- Fixed minor bugs
- Improved buy/sell/cancel stability

v1.05
- Critical bugs fixed
- Calculations fixes
- Ui fixes
- Added PPC, FTC, RTC support
- Added proxy support

v1.04
- Fixed UI bugs
- Added NMC and NVC to BTC-e
- Now last price displays in title
- Stability improvements in BTC-e exchange
- Many small improvements
- Translation fixes

v1.03
- SSL security fix
- Fixed translations
- Small ui fix

v1.02
- BTC-E.com support added. Now you can trade with LTC
- Added trade history display
- Multi-monitor support (Detachable windows)
- Improved connection stability
- Added German translation
- Fixed UI bugs, translation bugs and some minor bugs

v1.01
- Fixed traffic heavy load.
- Added trades fetch to update last values faster.

v1.00
- Api engine rewrited. Now works faster.
- Api lag improvements.
- Fixed minor bugs.
- Added Norwegian translation.

v0.99
- Fixed minor bugs
- Added Spanish translation
- Translation engine updated
- Checking update engine rewrited. Secure autoinstall for Mac and Win feature added.
- Added portable mode for Windows (Just create folder QtBitcoinTrader near exe file)

v0.98
- Added translation engine. Now you can translate application to your native language
- Fixed ui bugs
- Enhanced rules. Now there is two modes, Sequential and Concurrent

v0.97
- Added profit calculation to main window
- Optimized ui

v0.96
- Fixed minor bugs
- Optimized ui
- Mac version released

v0.95
- Fixed fee calculator bug
- Now supports resolution down to 1024x700
- Enhanced rules feature
- Minor bugs fixed

v0.94
- Rules finally working!
- Fixed some minor bugs

v0.93
- Fixed critical ui bug where was wrong field in orders table

v0.92
- Fixed minor bugs in ui and currencies

v0.91
 - Added Profiles
 - Fixed Ui Bugs

v0.90
- Added all currencies supported by Mt.Gox
- Minor fixes

v0.89
- Fixed critical bug

v0.88
- Addes Mt.Gox key and secret encryption with AES 256
- Fixed some ui bugx
- Minor fixes

v0.87
- Match more faster engine
- Fixed some bugs
- Improved socket stability
- Tested on Linux, thanks to macman31

v0.86
- Fixed bug in Orders Log
- Fixed bug in fee calculation
- Fixed ui dialogs

v0.85
- Added SSL switcher
- Fixed some dialogs

v0.84
- Interlaced software lag performance

v0.83
- Added Fee Calculator

v0.82
- Improved socket stability

v0.81
- Minor bugs fixed
- Improved stability
- Added packet priority for buying and selling

v0.8
- First public release

Created by July IGHOR
Contact: `julyighor@gmail.com`
Donate: `1d6iMwjjNo8ZGYeJBZKXgcgVk9o7fXcjc`
