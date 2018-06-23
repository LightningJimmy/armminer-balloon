## cpuminer-balloon
_cpuminer supporting balloon128/4_

Optimized for better performance on ARM.

### credits
cpuminer-multi, authored by tpruvot

modified for balloon 128/4, authored by barrystyle

optimized balloon, authored by Belgarion ( accepting donations at: (deft) dJP7aS2GVbmSKbHrS9aRFycdab5UNd4zxa )

modified so that ARM compiles without errors by LightningJimmy

### installation
 * sudo apt update
 * sudo apt install build-essential autoconf automake libssl-dev libcurl4-openssl-dev libjansson-dev zlib1g-dev screen git
 * git clone https://github.com/LightningJimmy/cpuminer-balloon
 * cd cpuminer-balloon
 * ./build.sh
 
 Note: ./build.sh will take quite a few minutes, don't do anything until it actually finishes. If it ends with an error, try running this instead:
  * ./pibuild.sh

### mine
 * ./cpuminer -a balloon -o stratum+tcp://mine-deft.leafpool.com:6611 -u dPWarUhyPbo6C3ijoPgziUzHjvjma2k6vA -p x
