forgottenserver
===============
This project is a downgrade created from the main [The Forgotten Server](https://github.com/otland/forgottenserver) project and was made to emulate version [7.72](https://github.com/nekiro/TFS-1.5-Downgrades/tree/7.72). This one is maintained and financed by [Diego Ligieri](https://github.com/diegoligieri).

### How to install
Works on versions higher than Ubuntu 18.04. Strictly recommended Ubuntu 20.04 or higher.
```bash
sudo apt install cmake build-essential libluajit-5.1-dev libmysqlclient-dev libboost-system-dev libboost-iostreams-dev libboost-filesystem-dev libpugixml-dev libcrypto++-dev libfmt-dev libboost-date-time-dev
```

### Compiling
```bash
cd elfen80
mkdir build && cd build
cmake ..
make -j 2
```
