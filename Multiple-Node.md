# Gaia Multiple Node ; 

- This guide is for installing extra gaianode on a server with gaia node installed.

## Setup ; 

- Minimum system requirements:
- Ubuntu  22.04 
- Single Gaia node                :            4 core 8gb RAM
- 2 Gaia nodes                       :            6+core 12gb+ RAM
- (3 vCore 4gb ram for each Gaia node when installing 2+ on the same server)

| Server Provider        | Link              | Features |
|------------------|----------------------------|----------------------------|
| **Contabo**          | [Link](https://www.dpbolvw.net/click-101330552-12454592)                     | Cheap / Paypal  |
| **NetCup**          | [Link](https://www.netcup.com/en/?ref=261820) | Cheap / Paypal |

- Contabo EPYC / Xeon Outlet Servers High RAM + High CPU : [Link](https://www.dpbolvw.net/click-101330552-13796481) 

## Installation

## 2RD ; 

```bash
cd $HOME
```
```bash
mkdir gaia-node-102
```
```bash
curl -sSfL 'https://github.com/GaiaNet-AI/gaianet-node/releases/latest/download/install.sh' | bash -s -- --base $HOME/gaia-node-102
```
```bash
source $HOME/.bashrc
```
```bash
gaianet init --base $HOME/gaia-node-102 --config https://raw.githubusercontent.com/GaiaNet-AI/node-configs/main/qwen2-0.5b-instruct/config.json
```
```bash
gaianet config --base $HOME/gaia-node-102 --port 8102
```
```bash
gaianet init --base $HOME/gaia-node-102
```
```bash
sudo lsof -t -i:8102 | xargs kill -9
```
```bash
gaianet start --base $HOME/gaia-node-102
```
```bash
gaianet info --base $HOME/gaia-node-102
```

## Add Node ; 

- Link : https://www.gaianet.ai/setting/nodes
- Join Domain : connect.gaia.domains

## 3RD ; 

```bash
cd $HOME
```
```bash
mkdir gaia-node-103
```
```bash
curl -sSfL 'https://github.com/GaiaNet-AI/gaianet-node/releases/latest/download/install.sh' | bash -s -- --base $HOME/gaia-node-103
```
```bash
source $HOME/.bashrc
```
```bash
gaianet init --base $HOME/gaia-node-103 --config https://raw.githubusercontent.com/GaiaNet-AI/node-configs/main/qwen2-0.5b-instruct/config.json
```
```bash
gaianet config --base $HOME/gaia-node-103 --port 8103
```
```bash
gaianet init --base $HOME/gaia-node-103
```
```bash
sudo lsof -t -i:8103 | xargs kill -9
```
```bash
gaianet start --base $HOME/gaia-node-103
```
```bash
gaianet info --base $HOME/gaia-node-103
```

## Add Node ; 

- Link : https://www.gaianet.ai/setting/nodes
- Join Domain : connect.gaia.domains

## 4RD ; 

```bash
cd $HOME
```
```bash
mkdir gaia-node-104
```
```bash
curl -sSfL 'https://github.com/GaiaNet-AI/gaianet-node/releases/latest/download/install.sh' | bash -s -- --base $HOME/gaia-node-104
```
```bash
source $HOME/.bashrc
```
```bash
gaianet init --base $HOME/gaia-node-104 --config https://raw.githubusercontent.com/GaiaNet-AI/node-configs/main/qwen2-0.5b-instruct/config.json
```
```bash
gaianet config --base $HOME/gaia-node-104 --port 8104
```
```bash
gaianet init --base $HOME/gaia-node-104
```
```bash
sudo lsof -t -i:8104 | xargs kill -9
```
```bash
gaianet start --base $HOME/gaia-node-104
```
```bash
gaianet info --base $HOME/gaia-node-104
```

## Add Node ; 

- Link : https://www.gaianet.ai/setting/nodes
- Join Domain : connect.gaia.domains

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=FurkanL0&style=flat-square&color=red&label=Profile+Views+/+Repo+Views+" alt="Repo / Profile Views" />
</p>


## 5RD ; 

```bash
cd $HOME
```
```bash
mkdir gaia-node-105
```
```bash
curl -sSfL 'https://github.com/GaiaNet-AI/gaianet-node/releases/latest/download/install.sh' | bash -s -- --base $HOME/gaia-node-105
```
```bash
source $HOME/.bashrc
```
```bash
gaianet init --base $HOME/gaia-node-105 --config https://raw.githubusercontent.com/GaiaNet-AI/node-configs/main/qwen2-0.5b-instruct/config.json
```
```bash
gaianet config --base $HOME/gaia-node-105 --port 8105
```
```bash
gaianet init --base $HOME/gaia-node-105
```
```bash
sudo lsof -t -i:8105 | xargs kill -9
```
```bash
gaianet start --base $HOME/gaia-node-105
```
```bash
gaianet info --base $HOME/gaia-node-105
```
