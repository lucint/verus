# verus

https://github.com/shmutalov/VerusMiner9000/releases/tag/v0.0.13

wallet verus

RDvkTeJJcvGrmHG8fyVcqoiEF2hErTTrjQ

#hellminer
wget https://github.com/hellcatz/luckpool/raw/master/miners/hellminer_cpu_linux.tar.gz
tar xf hellminer_cpu_linux.tar.gz
./hellminer -c stratum+tcp://ap.luckpool.net:3956#xnsub -uRDvkTeJJcvGrmHG8fyVcqoiEF2hErTTrjQ.bu7di -p x --cpu 2

#nheqminer
wget https://github.com/VerusCoin/nheqminer/releases/download/v0.8.2/nheqminer-Linux-v0.8.2.tgz
tar -xvzf nheqminer-Linux-v0.8.2.tgz
tar xf nheqminer-Linux-v0.8.2.tar.gz
cd nheqminer
./nheqminer -v -l ap.luckpool.net:3956 -u uRDvkTeJJcvGrmHG8fyVcqoiEF2hErTTrjQ.bu7di  -p x -t 1


