
##### A while ago I tried entering a hackathon with a small team on this concept I had centered around the idea of mining cryptocurrency while riding a bike. We lost. I stumbled upon this project again, and since it is mostly open and the tutorials are available, I thought, "why not use this for Lonero?" Hence, this repurpose or rebranding of sorts was born. ...

### Installation
**Run the Lonero Daemon Locally:** \
``gh repo clone Lonero-Team/Lonero-Beta`` \
OR ``git clone https://github.com/Lonero-Team/Lonero-Beta.git`` \
``cd Lonero-Beta`` \
``./forknoted --config-file configs/lonero.conf`` \
**Run the GUI Wallet:**
```bash
$ apt-get update
$ apt-get upgrade
$ apt-get install qtbase5-dev libssl-dev cmake git libboost1.58-all-dev build-essential g++
$ git clone https://github.com/Lonero-Team/Lonero-Wallet-2.0
$ cd Lonero-Wallet-2.0/
$ cmake CMakeLists.txt
$ make -j 8
$ cd Lonero-Wallet-2.0/
$ make -j 8
```
OR \
**Create or Connect to a Pool:** I recommend that you follow the guide [here](https://github.com/Lonero-Team/LNR-Mining-Pool) or run a pool locally and connect to stratum. Ultimately, you can also connect to a remote node.

## Setup Hardware
**Flash Microcontroller:** For *Chip*, see documentation [here](http://www.chip-community.org/index.php/Documentation) \
**Node Connectivity:**
