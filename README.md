# docker_minerd

## Description:

This docker container will help you to quickly launch minerd instance.
It is based on [cpuminer-multi](https://github.com/wolf9466/cpuminer-multi) and support **cryptonight** algorithm (Bytecoin, Monero).  

## Build:

**To build docker image it's easy.**  
``$ git clone https://github.com/Amauche/docker_minerd.git``  
``$ cd docker_minerd``  
  

**Change this line in entrypoint.sh to fit your need.**  
``/opt/minerd/minerd -a cryptonight -o stratum+tcp://mine.moneropool.com:3333 -u 46svDDc2ZXTgv2vY1THHuu7CjVsNsFMXDfCyAgcxW5Zad8SJRLfXT6cZErScz7HicwD7SECJS9RQuW1wZAGd7NQrTfgCrtZ -p x``


``$ docker build -t minerd .``

## Run:
Easy:

``$ docker run -d --name minerd minerd``

## Donations:

If you don't know what to do with your coins:

**ETH:** 0x04aab93d7d1f4e313b4704339a9f42cbd54406f1  
**BTC:** 1MmeZw638nycmveMNKbCxLsryNEretspLk  
**XMR:** 46svDDc2ZXTgv2vY1THHuu7CjVsNsFMXDfCyAgcxW5Zad8SJRLfXT6cZErScz7HicwD7SECJS9RQuW1wZAGd7NQrTfgCrtZ  
