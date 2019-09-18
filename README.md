Zerozed Core integration/staging tree
=====================================

https://zero-zed.com

What is Zerozed?
----------------

Zerozed is an experimental digital currency that enables instant payments to
anyone, anywhere in the world. Zerozed uses peer-to-peer technology to operate
with no central authority: managing transactions and issuing money are carried
out collectively by the network. Zerozed Core is the name of open source
software which enables the use of this currency.

For more information, as well as an immediately useable, binary version of
the Zerozed Core software, see http://github.com/ZerozedProject/releases.

What is Zerozed Trying to Achieve?
----------------------------------

One of the greatest ethical and logistical challenges humanity has been forced to face is one that has not changed since the dawn of society itself. The fair and even distribution of wealth and power.

Using a Diffusion of Innovations based inflation model, along with an industry tried-and-true mining algorithm we seek to solve a long time debated issue surrounding not just volatility but also how to achieve successful diffusion of a currency, global adoption, whilst maintaining the normal distribution and a standard score of 0z.

In other words, how do we create a stable Cryptocurrency that is, relatively speaking, evenly dispersed between everyone alive once new coins cease production.

We believe by utilising the Diffusion of Innovations we can establish the Normal Distribution within a socioeconomic system. We have proposed an inflation algorithm for Cryptocurrencies yet to launch, as well as coins existing today, to set or retarget blockrewards and follow a more sustainable and diffusion-viable incentive model.

In replacement to the standard halving-mechanism employed by Bitcoin and the greater majority of Cryptocurrencies to-date, we demonstrate the modeling of an inflation schedule guided by the theory, Diffusion of Innovations.


Resources
-----------

Explorer: https://chainz.cryptoid.info/x0z/
Pool: https://x0z.magnificentpool.com/
Pool: https://luckyaltcoin.com/
Pool: https://coins4u.cc/
Pool: http://www.masters-pool.com/
Mining Calculator: https://cointomine.today/calculator/coin/X0Z
Exchange: https://altmarkets.io/trading/x0zbtc
Decentralised Exchange: https://deex.exchange/market/ZEROZED_BTC
In-House Exchange: https://meanxtrade.com/trade/btc/x0z
Trello: https://trello.com/b/TGOym8Po/zerozed-roadmap

CoinLib: https://coinlib.io/coin/X0Z/Zerozed
CoinGecko: https://coingecko.com/en/coins/zerozed
Coinpaprika: https://coinpaprika.com/coin/x0z-zerozed/
Delta: https://delta.app/en/crypto/x0z/zerozed
Blockfolio: https://blockfolio.com/#get-app

Social Media
-------------

Twitter: https://twitter.com/zerozed_x0z
Discord: https://discord.gg/8GcFtUX
Telegram: https://t.me/zerozed_x0z
Facebook: https://www.facebook.com/zerozed.x0z/
Reddit: https://www.reddit.com/r/zerozed_x0z
IRC: #zerozed https://webchat.freenode.net/
Matrix - https://matrix.to/#/#zerozed_x0z:matrix.allmende.io


Addnodes
--------

addnode 104.248.147.25 add

addnode 104.248.157.179 add


Building Depends
----------------

// Clean repo

git clean -fdx

cd depends

make HOST=x86_64-pc-linux-gnu

// Go to bed now, it takes hours!

cd ..

./autogen.sh

./configure --prefix=`pwd`/depends/x86_64-pc-linux-gnu

make


License
-------

Zerozed Core is released under the terms of the MIT license. See [COPYING](COPYING) for more
information or see https://opensource.org/licenses/MIT.

Development Process
-------------------

The `master` branch is regularly built and tested, but is not guaranteed to be
completely stable. [Tags](https://github.com/ZerozedProject/zerozed/tags) are created
regularly to indicate new official, stable release versions of Zerozed Core.

The contribution workflow is described in [CONTRIBUTING.md](CONTRIBUTING.md).


Mission Statement
-----------------

Create an easily replicable software & hardware ecosystem along with a decentralised autonomous
organisational structure of which can be used to empower and advance emerging nations seamlessly 
into the present and beyond into a future without a centralised State run governance system 
required to sustain it.


Protect the free exchange of ideas, the freedom to criticise, and the liberty to experiment.

Support social orders that foster freedom of communication, action, experimentation, innovation, questioning and learning.

Avoid unnecessary hierarchy whilst favoring the rule of math and decentralisation of power and responsibility.

Support social order characterised by voluntary relationships and exchanges.
