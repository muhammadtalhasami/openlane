# INTRO
![logo](https://github.com/muhammadtalhasami/openlane/blob/main/designs/ram_8x72/src/klayout_8x72.png)

This is my OpenLane repository in which i perform the synthesis of different design modules.

**SYNTHESIS:** synthesis is the process of converting RTL(synthesizable verilog code)to technology specific gate level netlist.

**NETLIST:** It is basically a combination of sequential elements and their logical connectivity

# OPENLANE_INSTALLATION 

The short version is, to install the OpenLane environment...

1. [Get Docker](https://docs.docker.com/get-docker/)
2. Get Python 3.6 or higher[Ubuntu](https://packages.ubuntu.com/focal/python3))
    * On Ubuntu, you may also need to install venv: `apt-get install python3-venv`
  
Run the following commands in your terminal:

```sh
1): cd $HOME
2): git clone https://github.com/The-OpenROAD-Project/OpenLane
3): cd OpenLane
4): make
5): make test
```

After the installation is completed :

now simply run this on your terminal:-

```sh
1): cd OpenLane
2): make mount
```

now you can use it

**NOTE:** you might face some problem while installing docker please follow the above giving link for that carefully. 

# GUI_OF_DESIGN

for this you can used klayout 

follow this command on your terminal:-

```sh
1): sudo apt-get install klayout
```


