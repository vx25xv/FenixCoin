FENIX

Algorithm 	Scrypt

Target spacing 	64 seconds

Type 	PoW/PoS

RPC port 	30902

P2P port 	30901

ubuntu node

cd /fenix/src/leveldb

chmod +x build_detect_platform

make clean

make libleveldb.a libmemenv.a

cd /fenix/src

make -f makefile.unix

strip fenixd

cp fenixd /usr/bin

fenixd

