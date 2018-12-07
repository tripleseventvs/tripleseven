Compile Daemon:

apt-get update && apt-get upgrade
apt-get install ntp git build-essential libssl-dev libdb-dev libdb++-dev libboost-all-dev libqrencode-dev

wget http://miniupnp.free.fr/files/download.php?file=miniupnpc-1.8.tar.gz && tar -zxf download.php\?file\=miniupnpc-1.8.tar.gz && cd miniupnpc-1.8/
make && make install && cd .. && rm -rf miniupnpc-1.8 download.php\?file\=miniupnpc-1.8.tar.gz

git clone https://github.com/tripleseventvs/tripleseven
cd tripleseven
cd src
mkdir obj
cd leveldb
make clean
cd tripleseven
cd src
make -f makefile.unix USE_UPNP=- USE_QRCODE=- USE_IPV6=-
strip triplesevend



TRIPLESEVEN - TVS

Tripleseven "TVS"
7 Years Mining 
Algo: X13 PoW/PoS 
TVS POW SUPPLY: 2325760000
Algorithm: X13 POW/POS
Pos: 8% Annually
Maturity: 30 Blocks
Max Pow Blocks: 7257600
Blocksize: 1000000
Airdrop + Mining
rpcport: 62092
port: 62093

Tripleseven has already been launched with CHECKPOINTS included, to allow a very secure network
Every month, new checkpoint will be added





