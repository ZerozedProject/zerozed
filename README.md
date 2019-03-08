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

One of the greatest ethical and logistical challenges humanity has been forced
to face is one that has not changed since the dawn of society itself. The fair
and even distribution of wealth and power.

Using a Diffusion of Innovations based inflation model along with an industry
tried-and-true mining algorithm, Zerozed incorporates cross-chain transactions,
such as the Atomic Swap network on the Komodo (KMD) platform, in order to solve
a long time debated issue surrounding not just volatility but also how to achieve
successful diffusion of a currency whilst maintaining the normal distribution and
a standard score of 0z.

In other words, how do we create a stable Cryptocurrency that is, relatively speaking,
evenly dispersed between everyone alive once new coins cease production.

Social Media
------------

Twitter: https://twitter.com/zerozed_x0z  
Exchange: https://meanxtrade.com/trade/btc/x0z  
Anncouncement: https://bitcointalk.org/index.php?topic=4096286  
Discord: https://discord.gg/8GcFtUX  
Telegram: https://t.me/zerozed_x0z  
IRC: #zerozed https://webchat.freenode.net/  
Pool: https://x0z.magnificentpool.com/   
Explorer: https://chainz.cryptoid.info/x0z/


Addnodes
--------

addnode 104.248.147.25 add

addnode 104.248.157.179 add

Secondary nodes
---------------

66.42.55.163:2601
52.15.220.131:2601
139.180.209.176:2601
3.8.75.233:2601

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
