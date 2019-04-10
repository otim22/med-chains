# Med chains

This is a medicines blockchian supply chain implementation in a distributed application (DAPP) using solidity programming langauge to truck the supply and distribution of drugs.


## Getting Started

Get started by Cloning this repository into your local machine.

```
git clone https://github.com/otim22/med-chains.git
```

Then...

```
cd med-chains
```

While in the directory after implementations start your development blockchain by running the command below from your terminal. 

```
$ truffle develop 
```

From the truffle console, compile and migrate the contracts by running 

```
compile 
```

and 

```
migrate
```

Run prewritten tests
```
test
```

Ensure that you have ganache is running in the background, either ganache-cli or the ganache app 
If not start the ganache app or by running 

```
ganache-cli
```

So, to start our application in the frontend run

```
cd client && npm run start
```

### Prerequisites

In order to get started with DAPP development you need the following environments setup

First you need to have things installed

* NodeJS

* Node Package Manager (NPM)


### Installing

A step by step series of examples that tell you how to get a development env running

Say what the step will be

Remix IDE - A web browser based IDE

```
sudo npm install -g truffle

sudo npm install -g ganache-cli
```

Truffle development suite
[Truffle frame](https://truffleframework.com/ "Truffle + Ganache") 

A familiar IDE probaly with solidity extensions available, prefebly Visual studio

[Visual Studio](https://code.visualstudio.com/ "Download it here") 

[Intergrated terminal](https://code.visualstudio.com/docs/editor/integrated-terminal "Download it here") 

[Solditiy support for VS Code](https://marketplace.visualstudio.com/itemdetails?itemName=JuanBlanco.solidity "Download it here") 

[Live share: for real time collaborative coding](https://marketplace.visualstudio.com/itemdetails?itemName=MS-vsliveshare.vsliveshare "Download it here") 


## Running the tests

Run this if you not yet in the console
```
$ truffle develop 
```

compile the contract 

```
compile 
```

and migrate it

```
migrate
```

Then test 
```
test
```

To test the frontend
```
cd client && npm run test
```

To build the frontend

```
cd client && npm run build
```

If after all those tests fails fix the issues and iteract the steps above till its all passes


## Deployment

```
Truffle deploy
```

## Built With

* [Truffle](https://truffleframework.com/) - Truffle suite framework
* [Solidity](https://solidity.readthedocs.io/en/develop/index.html#) - Programming Langauge


## Versioning

We use [git](http://github.cm/) for versioning. 


## Authors

* **Otim Fredrick** - *Team lead* - [otim22](https://github.com/otim22)

* Arishain Abraham

* Mpimbaza Christian

See also the list of [contributors](https://github.com/otim22/med-chains/contributors) who participated in this project.


## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details


## Acknowledgments

* [Consensys Academy](https://consensys.net/academy/) 
* [Africa Blockchain Alliance](https://afriblockchain.org/)
* [Cryptosavanna](https://cryptosavannah.com/)