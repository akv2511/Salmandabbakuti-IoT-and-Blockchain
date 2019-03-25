# IoT-and-Blockchain

# Pre-Requisites
## Npm packages
Truffle

```npm install -g truffle```

Pip

```curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py```

```python get-pip.py```

ganache-cli

```npm install -g ganache-cli```

web3.py

```pip install web3```

## Pip packages
Flask
GPIO Emulator

```pip install requirements.txt```

## Desktop App

Python
https://www.python.org/downloads/

# STEPS
*** Make Sure prerequisites are installed***

1.clone the repository into desktop

2. install required PiP dependencies

```pip install requirements.txt```

3.instantiate Ganache-cli Private Network.

```ganache-cli```

4.run app

```py app.py```

wait a moment. this will take a minute or two.

after deployment of contract in private network, you will see status of each pin in your command line and Emulator on Screen.

5.head into browser and type ```<Your computer ip>/``` and control through UI.

<img align=center src="https://github.com/Salmandabbakuti/IoT-and-Blockchain/blob/master/Screenshot%20(81).png">

basically, it will write particular pin status on blockchain and retrieve it from the chain. and then activate pin confiuaration accordingly.

boom.
