# Gaia Node Kurulum

![image](https://github.com/user-attachments/assets/c7893f6c-c343-4650-95a9-ca90000c6aa6)

## Minimum Özellikler Qwen2 0.5B Instruct Modeli İçindir. 


| X        | Minimum              |
|------------------|----------------------------|
| **CPU**          | 4 |
| **RAM**          | 8 GB                     |
| **Storage**      | 256 GB SDD                   |
| **Network**      | 100 Mbps (1 Gbps+ recommended) |

| Server Sağlayıcıları        | Link              | Özellikler |
|------------------|----------------------------|----------------------------|
| **NetCup**          | [Link](https://www.netcup.com/en/?ref=261820) | Ucuz / Kredi Kartı / Paypal |
| **Contabo**          | [Link](https://www.dpbolvw.net/click-101330552-12454592)                     | Ucuz / Kredi Kartı / Paypal  |
| **PQ**      | [Link](https://pq.hosting/?from=627713)                  | Ucuz / Kredi Kartı / Kripto İle Ödeme |

## Kayıt ; 

- Kod : RB92j9 Link : https://gaianet.ai/reward?invite_code=RB92j9
- Start Earning'e basın Cüzdan bağlayın ve kayıt işlemini gerçekleştirin.
- Dasboard'da sosyal medya etkinlikleri var etkinliklere katılım sağlamayı unutmayın. https://www.gaianet.ai/reward-summary
- Sosyal medya görevlerini yapın - dönüştürülebilir kredi sağlayacak.

## Gaia Node Kurulum 

- Nodumuzu kuracağız.
- Sunucumuz aktif olarak çalışacak.
- Sunucumuzu bir domaine bağlayacağız.
- Ai ile sohbet edeceğiz.


## 1. Sunucuyu Güncelleyelim : 

```bash
sudo apt update -y && sudo apt upgrade -y
```
## 2. Gerekli paketleri kurun:

```bash
sudo apt install htop ca-certificates zlib1g-dev libncurses5-dev libgdbm-dev libnss3-dev tmux iptables curl nvme-cli git wget make jq libleveldb-dev build-essential pkg-config ncdu tar clang bsdmainutils lsb-release libssl-dev libreadline-dev libffi-dev jq gcc screen unzip lz4 -y
```

## 3. Pyhton 

```bash
sudo apt install -y python3-pip
sudo apt install pip
sudo apt install -y build-essential libssl-dev libffi-dev python3-dev
```
## 4. Gaia Node CLI İndirelim 

```bash
curl -sSfL 'https://github.com/GaiaNet-AI/gaianet-node/releases/latest/download/install.sh' | bash
```

```bash
source /root/.bashrc
```

![image](https://github.com/user-attachments/assets/2053663d-960d-49ef-945d-3dea6ca14696)


## 5. Modeli İndirelim : 

- Model : qwen2-0.5b-instruct

```bash
gaianet init --config https://raw.githubusercontent.com/GaiaNet-AI/node-configs/main/qwen2-0.5b-instruct/config.json
```

![image](https://github.com/user-attachments/assets/f2117332-5a02-41f9-bdd0-1d7877041218)


## 6. Startı Verelim : 
```bash
gaianet start
```

![image](https://github.com/user-attachments/assets/25397317-5733-442a-81cc-ff593bcb4c02)


- Durdurmak İsterseniz : gaianet stop

## 7. Nodemizi Kayıt Edelim : 

- Nodemizin bilgilerini alalım - Node ID ve Device ID vericek - bunu kimseyle paylaşmayın.

```bash
gaianet info
```
![image](https://github.com/user-attachments/assets/219b8bb4-167c-40d6-85a0-6321661d3f7c)


- Link : https://www.gaianet.ai/setting/nodes

![image](https://github.com/user-attachments/assets/5c561fbd-832d-4219-8731-73423b92d618)

![image](https://github.com/user-attachments/assets/4de464c6-444b-41b1-a8bb-8c808e41576b)

![image](https://github.com/user-attachments/assets/8a9e9782-db5d-487c-b193-b979e3472043)


## 8. Domaine Bağlayalım : 
```bash
gaianet stop
gaianet config --domain gaia.domains
gaianet init
gaianet start
```

- Link : https://www.gaianet.ai/setting/nodes
- 3 Noktaya basın - Join domaine tıklayın. 
- Arama kısmında Domain arayın - bizimki connect.gaia.domains
- Üstüne tıklayıp onaylayın - diğer aşamaları tamamlayın.

![image](https://github.com/user-attachments/assets/0ee113d6-c334-4604-aa08-7a063089e0ff)

![image](https://github.com/user-attachments/assets/ad3e1336-82e7-4c11-9864-af3d8e13d1d3)

![image](https://github.com/user-attachments/assets/6f8a6f68-21db-4d3f-b616-082da717c935)


## 9. Node İle Sohbet Edin : 

Sohbet edip XP Kazanmak için AI Sohbete bağlanmanız gerekiyor : 
- Link : https://connect.gaia.domains
- Sohbet edebilmek için "Credit Balance"ınızın olması gerekiyor. Olmazsa - yazıyor :D

![image](https://github.com/user-attachments/assets/5c53e057-9d36-4970-8de6-a74e956946bc)

## 10. Otomatik Sohbet Bot ; 

- Gaia Üzerinden Api Key Alıyoruz - güzelce kayıt edin tek seferlik gözükecektir. : https://www.gaianet.ai/setting/gaia-api-keys

#### Kurulum : 

- .py'i İndirelim : 

```bash
curl -L -o gaiabot.py https://github.com/FurkanL0/Gaia-Node/raw/main/gaiabot.py
```

- Screen Açalım
```bash
screen -S gaiabot
```

- Çalıştıralım

```bash
python3 gaiabot.py
```

- Api keyinizi girin.
- CTRL A + D ile screenden çıkabilirsiniz.
- screen -r gaiabot ile geri screene girebilirsiniz.
- Durdurmak ve silmek isterseniz screen içinden CTRL C sonrasında screen -XS gaiabot quit komutunu kullanabilirsiniz.

![image](https://github.com/user-attachments/assets/44fb8fe3-d6c1-42c2-8b45-0d98d0ad1515)



<p align="center">
  <img src="https://komarev.com/ghpvc/?username=FurkanL0&style=flat-square&color=red&label=Profile+Views+/+Repo+Views+" alt="Repo / Profile Views" />
</p>
