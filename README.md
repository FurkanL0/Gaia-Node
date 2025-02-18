# Gaia AI Node Setup

![image](https://github.com/user-attachments/assets/c7893f6c-c343-4650-95a9-ca90000c6aa6)

## Minimum Specifications are for Qwen2 0.5B Instruct Model.


| X        | Minimum              |
|------------------|----------------------------|
| **CPU**          | 4 |
| **RAM**          | 8 GB                     |
| **Storage**      | 256 GB SDD                   |
| **Network**      | 100 Mbps (1 Gbps+ recommended) |

| Server Provider        | Link              | Features |
|------------------|----------------------------|----------------------------|
| **Contabo**          | [Link](https://www.dpbolvw.net/click-101330552-12454592)                     | Cheap / Paypal  |
| **PQ**      | [Link](https://pq.hosting/?from=627713)                  | Cheap / Crypto Payment |
| **NetCup**          | [Link](https://www.netcup.com/en/?ref=261820) | Cheap / Paypal |

## Kayıt ; 

- Code : RB92j9 Link : https://gaianet.ai/reward?invite_code=RB92j9
- Click "Start Earning" Connect Wallet and complete the registration process.
- Dasboard has social media quest and don't forget to participate in them. https://www.gaianet.ai/reward-summary
- Do social media tasks - it will provide convertible credit.

## Gaia Node Setup 

- Install Node
- Our server will work actively.
- We will connect our server to a domain.
- Chat with ai


## 1. Server Update : 

```bash
sudo apt update -y && sudo apt upgrade -y
```
## 2. Install Packages:

```bash
sudo apt install htop ca-certificates zlib1g-dev libncurses5-dev libgdbm-dev libnss3-dev tmux iptables curl nvme-cli git wget make jq libleveldb-dev build-essential pkg-config ncdu tar clang bsdmainutils lsb-release libssl-dev libreadline-dev libffi-dev jq gcc screen unzip lz4 -y
```

## 3. Install Pyhton 

```bash
sudo apt install -y python3-pip
sudo apt install pip
sudo apt install -y build-essential libssl-dev libffi-dev python3-dev
```

```bash
pip install requests
```
## 4. Install Gaia Node CLI

```bash
curl -sSfL 'https://github.com/GaiaNet-AI/gaianet-node/releases/latest/download/install.sh' | bash
```

```bash
source /root/.bashrc
```

![image](https://github.com/user-attachments/assets/2053663d-960d-49ef-945d-3dea6ca14696)


## 5. Install Model : 

- Model : qwen2-0.5b-instruct

```bash
gaianet init --config https://raw.githubusercontent.com/GaiaNet-AI/node-configs/main/qwen2-0.5b-instruct/config.json
```

![image](https://github.com/user-attachments/assets/f2117332-5a02-41f9-bdd0-1d7877041218)


## 6. Run Node : 
```bash
gaianet start
```

![image](https://github.com/user-attachments/assets/25397317-5733-442a-81cc-ff593bcb4c02)


- If you want to stop : 'gaianet stop'

## 7. Register Our Node : 

- Get the information of our node - Node ID - Device ID - don't share this with anyone.

```bash
gaianet info
```
![image](https://github.com/user-attachments/assets/219b8bb4-167c-40d6-85a0-6321661d3f7c)


- Link : https://www.gaianet.ai/setting/nodes

![image](https://github.com/user-attachments/assets/5c561fbd-832d-4219-8731-73423b92d618)

![image](https://github.com/user-attachments/assets/4de464c6-444b-41b1-a8bb-8c808e41576b)

![image](https://github.com/user-attachments/assets/8a9e9782-db5d-487c-b193-b979e3472043)


## 8. Connect Domain : 
```bash
gaianet stop
gaianet config --domain gaia.domains
gaianet init
gaianet start
```

- Link : https://www.gaianet.ai/setting/nodes
- Press 3 dots - click on Join domain. 
- Search for Domain in Search - ours connect.gaia.domains
- Click on it and confirm - complete the other steps.

![image](https://github.com/user-attachments/assets/0ee113d6-c334-4604-aa08-7a063089e0ff)

![image](https://github.com/user-attachments/assets/ad3e1336-82e7-4c11-9864-af3d8e13d1d3)

![image](https://github.com/user-attachments/assets/6f8a6f68-21db-4d3f-b616-082da717c935)


## 9. Chat with Ai : 

You need to connect to AI Chat to chat and earn XP: 
- Link : https://connect.gaia.domains
- You need to have a "Credit Balance" to chat.

![image](https://github.com/user-attachments/assets/5c53e057-9d36-4970-8de6-a74e956946bc)

## 10. Ai Auto Chat  Bot ; 

- We get Api Key via Gaia - register it and it will appear only once. : https://www.gaianet.ai/setting/gaia-api-keys

#### Setup : 

- Install .py : 

```bash
curl -L -o gaiabot.py https://github.com/FurkanL0/Gaia-Node/raw/main/gaiabot.py
```

- Screen : 
```bash
screen -S gaiabot
```

- Run Bot

```bash
python3 gaiabot.py
```

- Enter your API key.
- You can exit the screen with CTRL A + D.
- screen -r gaiabot you can enter the back screen.
- If you want to stop and delete it, you can use CTRL C then screen -XS gaiabot quit command from screen.

![image](https://github.com/user-attachments/assets/44fb8fe3-d6c1-42c2-8b45-0d98d0ad1515)



<p align="center">
  <img src="https://komarev.com/ghpvc/?username=FurkanL0&style=flat-square&color=red&label=Profile+Views+/+Repo+Views+" alt="Repo / Profile Views" />
</p>
