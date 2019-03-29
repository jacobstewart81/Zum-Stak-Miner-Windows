# Zum-Stak-Miner
XMR-Stak - Cryptonight All-in-One Mining Software

XMR-Stak is a universal Stratum pool miner. This miner supports CPUs, AMD and NVIDIA GPUs and can be used to mine the crypto currencies Monero, Aeon and many more Cryptonight coins.
HTML reports

Video setup guide on Windows

Video by Crypto Sewer
Overview

    Features
    Supported altcoins
    Download
    Usage
    HowTo Compile
    FAQ
    Developer Donation
    Developer PGP Key's

Features

    support all common backends (CPU/x86, AMD-GPU and NVIDIA-GPU)
    support all common OS (Linux, Windows and macOS)
    supports algorithm cryptonight for Monero (XMR) and cryptonight-light (AEON)
    easy to use
        guided start (no need to edit a config file for the first start)
        auto-configuration for each backend
    open source software (GPLv3)
    TLS support
    HTML statistics
    JSON API for monitoring

Supported altcoins

Besides Monero, following coins can be mined using this miner:

    Aeon
    BBSCoin
    BitTube
    Conceal
    Graft
    Haven
    Lethean
    Masari
    Plenteum
    QRL
    Ryo - Upcoming xmr-stak-gui is sponsored by Ryo
    Stellite
    TurtleCoin
    Zelerius
    X-CASH

Ryo currency is a way for us to implement the ideas that we were unable to in Monero. See here for details.

If your prefered coin is not listed, you can choose one of the following algorithms:

    256Kib scratchpad memory
        cryptonight_turtle
    1MiB scratchpad memory
        cryptonight_lite
        cryptonight_lite_v7
        cryptonight_lite_v7_xor (algorithm used by ipbc)
    2MiB scratchpad memory
        cryptonight
        cryptonight_gpu (for Ryo's 14th of Feb fork)
        cryptonight_masari (used in 2018)
        cryptonight_v7
        cryptonight_v7_stellite
        cryptonight_v8
        cryptonight_v8_double (used by X-CASH)
        cryptonight_v8_half (used by masari and stellite)
        cryptonight_v8_reversewaltz (used by graft)
        cryptonight_v8_zelerius
    4MiB scratchpad memory
        cryptonight_haven
        cryptonight_heavy

Please note, this list is not complete and is not an endorsement.
Download

You can find the latest releases and precompiled binaries on GitHub under Releases.
Default Developer Donation

By default, the miner will donate 2% of the hashpower (2 minutes in 100 minutes) to my pool. If you want to change that, edit donate-level.hpp before you build the binaries.

If you want to donate directly to support further development, here is my wallet

fireice-uk:

4581HhZkQHgZrZjKeCfCJxZff9E3xCgHGF25zABZz7oR71TnbbgiS7sK9jveE6Dx6uMs2LwszDuvQJgRZQotdpHt1fTdDhk

psychocrypt:

45tcqnJMgd3VqeTznNotiNj4G9PQoK67TGRiHyj6EYSZ31NUbAfs9XdiU5squmZb717iHJLxZv3KfEw8jCYGL5wa19yrVCn
