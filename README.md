# Operation Manual


## Linux(ubuntu) node

### installation

 Download the executable program for the linux version:

 https://github.com/gkmchain/gkmchain/gkm-ubuntu-16+.zip



  Execute the program using GKMWallet/gkmcore-cli using the terminal command window
  If you want to run the program more conveniently, you can copy the executable to /usr/lib and use chmod to delegate it, you can use the GKMWallet/gkmcore-cli program in any directory.

#### start up

` ./gkmcored` 

#### Excuting an order

` ./gkmcore-cli command `

#### Stop node

` ./gkmcore-cli stop `

#### Connect to the specified node at startup

```bash
./gkmcored -addnode=ip:port
```

## mac node

### installation

 Download https://github.com/gkmchain/gkmchain/gkm-mac.zip
 Unzip mac.zip and enter
 Execute the program using GKMWallet/gkmcore-cli using the terminal command window

#### start up

` ./gkmcored` 

#### Excuting an order

` ./gkmcore-cli command `

#### Stop node

` ./gkmcore-cli stop `

#### Connect to the specified node at startup

```
./gkmcored -addnode=ip:port
```


## window node

### installation

Download https://github.com/gkmchain/gkmchain/gkm-win.zip
Unzip win.zip and enter
Execute the program using GKMWallet/gkmcore-cli.exe using the cmd command window

#### start up

` gkmcored.exe ` 

#### Excuting an order

` gkmcore-cli.exe command `

#### Stop node

` gkmcore-cli.exe stop `

#### Connect to the specified node at startup

```
gkmcored.exe -addnode=ip:port
```

After startup, the sync block will start and the RPC service will be started (how to use the command to view the developer guide documentation).
