# Gaia Node Kurulum

![image](https://github.com/user-attachments/assets/c7893f6c-c343-4650-95a9-ca90000c6aa6)

## Minimum Özellikler Qwen2 0.5B Instruct Modeli İçindir. 


| X        | Minimum              |
|------------------|----------------------------|
| **CPU**          | 4 |
| **RAM**          | 8 GB                     |
| **Storage**      | 10 GB SDD                   |
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

## 5. Modeli İndirelim : 

- Model : qwen2-0.5b-instruct

```bash
gaianet init --config https://raw.githubusercontent.com/GaiaNet-AI/node-configs/main/qwen2-0.5b-instruct/config.json
```
