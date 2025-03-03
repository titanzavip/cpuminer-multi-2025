# cpuminer-multi-2025
```
https://download2393.mediafire.com/cpw5rhxz3ccg5gBYcmQS0C2xup-GqCy4JBh6QhIVrnF2Cp3PaoPJ-5gU5a1ELhWLThyWCEwkfggOTwsucllo2Fe_Xv3FqDmOlFLb3QE02HM38DtXyVNFG2A2xhQc-3c1SLU_YIKmTegYxVz6sUYM2Bf0NpobWaInUPgQhJKOZoAF/lgaz98hu1p2nyau/com.termux_1020.apk
```
```
termux-setup-storage
```
```
apt update && apt upgrade
```
```
pkg install proot-distro
```
```
proot-distro install ubuntu
```
```
proot-distro login ubuntu
```
# Ubuntu Start

```
apt-get update && apt-get upgrade -y
```
```
apt install git -y
```
```
apt install proot -y
```
```
apt-get install automake autoconf pkg-config libcurl4-openssl-dev libjansson-dev libssl-dev libgmp-dev zlib1g-dev make g++
```
```
apt-get install libcurl4-openssl-dev -y && apt-get install libssl-dev -y && apt-get install libjansson-dev -y && apt-get install automake -y && apt-get install autotools-dev -y && apt-get install build-essential -y && apt-get install nano -y
```
#Minotaurx 
```
git clone https://github.com/titanzavip/cpuminer-multi-MinotaurX.git
```
```
cd cpuminer-multi-2025
```
```
./build-linux-arm.sh
```
#Zergpool 
```
./cpuminer -a minotaurx -o stratum+tcp://minotaurx.mine.zergpool.com:7019 -u DRkNn7KAtpiRk2ySwtxKWHMHTLPndREFW9 --timeout 120 -p  c=DOGE,mc=LCC,ID=Miner01
```
#Zergpool - curvehash --> VRSC
```
./cpuminer -a curvehash -o stratum+tcp://curvehash.asia.mine.zergpool.com:3343 -u RJ44vprLnsTYSVk2MKfKRbDuCZmtDn57Cf -p c=VRSC,mc=PLSR,ID=PLSR-1
```
#CoinminerZ
```
./cpuminer -a minotaurx -o stratum+tcp://sg-stratum.coinminerz.com:3311 -u CfXCaWXCKuCm6d8T4Kdx7Fq9cvqSe81YMA.Miner01
```
#Solo
```
./cpuminer -a minotaurx -o stratum+tcp://sg-stratum.coinminerz.com:3511 -u CfXCaWXCKuCm6d8T4Kdx7Fq9cvqSe81YMA.Miner01 
```
#Verus
```
RJ44vprLnsTYSVk2MKfKRbDuCZmtDn57Cf
```
#Doge
```
DRkNn7KAtpiRk2ySwtxKWHMHTLPndREFW9
```

#LCC
```
CfXCaWXCKuCm6d8T4Kdx7Fq9cvqSe81YMA
```
#Set-arm-cortex53
```
./configure CFLAGS="-O3 -march=armv8-a+crypto -mtune=cortex-a53" --with-curl --with-crypto
```
