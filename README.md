# Polishcoin [POL] Integration/Staging Tree
http://www.polish-coin.org/

![PolishCoin](http://www.polish-coin.org/media/logo_big_polishcoin_350.png)


## What is PolishCoin?
Polishcoin is like Bitcoin, but based on Litecoin.

## License
PolishCoin is released under the terms of the MIT license. See [COPYING](COPYING)
for more information or see http://opensource.org/licenses/MIT.

## Development and contributions
Developers work in their own trees, then submit pull requests when they think
their feature or bug fix is ready.

### How much POL can exist?
Total of 100,000,000,000 coins

1 Minute Block Targets, 4 Hour Diff Readjustments

Special reward system: Random block rewards

1-100,000: 0-1,000,000 Polishcoin Reward

100,001 — 200,000: 0-500,000 Polishcoin Reward

200,001 — 300,000: 0-250,000 Polishcoin Reward

300,001 — 400,000: 0-125,000 Polishcoin Reward

400,001 — 500,000: 0-62,500 Polishcoin Reward

500,001 - 600,000: 0-31,250 Polishcoin Reward

600,000+ — 10,000 Reward (flat)

### Wow plz make polishcoind

    sudo apt-get install build-essential \
                         libssl-dev \
                         libdb5.1++-dev \
                         libboost-all-dev \
                         libqrencode-dev \
                         libminiupnpc-dev

    cd src/
    make -f makefile.unix USE_UPNP=1 USE_IPV6=1 USE_QRCODE=1

### Ports
RPC 4822
P2P 4823

(http://www.polish-coin.org/media/logo_big_polishcoin_350.png)
